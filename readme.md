# Intro to NN - netcom slides
You can check the NN slides under `nn-intro.pdf`.

## Check the implementation
A implementation example is present as a python notebook, so just open `zdm.ipynb`.

## Compile the slides
It is necessary to symlink the eps files of the beamer template.
```bash
ln -s beamer-uc3m/uc3m.eps uc3m.eps
ln -s beamer-uc3m/logo-uc3m.eps logo-uc3m.eps
```
Then just execute `latexmk -pdf -pvc nn-intro.tex`, and the `.latexmkrc` will include the beamer template in the compilation environment.
