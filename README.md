# 02-731: Modelling Evolution Final Project

To compile the presentation run
```
pandoc slides.md -t beamer -i -o slides.pdf
```

To compile the final report run
```
latexmk -pdf report.tex
```

To run the simulation run
```
python model.py
```
Dependencies
- `matplotlib`
- `numpy`
- `tqdm`
