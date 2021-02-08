# NXYZ Beamer Theme

Just a simple and minimalistic beamer theme with a few custom elements created with the LaTeX packages PGFPlots and TikZ.

## Preview

### Black: `\usetheme[black]{NXYZ}`
![](preview/black_main.gif)

### Blue: `\usetheme[blue]{NXYZ}`
![](preview/blue_main.gif)

### Green: `\usetheme[green]{NXYZ}`
![](preview/green_main.gif)

### Red: `\usetheme[red]{NXYZ}`
![](preview/red_main.gif)

## Usage 

Simply download the `.sty` files contained in this repository and include them in the preamble of the LaTeX beamer by specifying the theme as follows:

```
% Include this in the preamble of the LaTeX beamer
\usetheme[red]{NXYZ}     % Red theme 
% \usetheme[black]{NXYZ} % Black theme
% \usetheme[blue]{NXYZ}  % Blue theme
% \usetheme[green]{NXYZ} % Blue theme
```

See the example document `main.tex` for reference and more details.

**Note**: The beamer document might have to be complied twice for the decorative mesh figure on the title page to be placed correctly.
