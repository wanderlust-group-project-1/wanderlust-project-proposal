# wanderlust-project-proposal


## Arch Linux

### Install
```bash
yay -S texlive
```
### Complie 

```bash
pdflatex Wanderlust.tex 
```
If the table of contents, list of tables, and list of figures are not visible, then install **rubber** complie with **rubber**.

```bash
yay -S rubber
```
```bash
rubber -d Wanderlust.tex 
```

