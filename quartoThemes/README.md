# Catppuccin colorscheme for quarto documents

This is the Catppuccin styesheet set for the quarto documents that I personally
created. The scheme is not fully applied, but the files will be updated as the
new elements were applied with the colors.

The theme is usualy coupled with the existing themes of quarto. This is done
to take the things other than colors, like font and font-size, from the built-in
themes and just replace the colors.

## Procedure to apply the schemes

1. Copy and paste the \_extensions folder into the documents directory.

2. Open the main file (either yml or qmd file) where the themes are defined

3. Augment the colorscheme as shown in below snippet

```{.quarto}
format:
  html:
    theme:
      light: [comso,_extensions/catppuccin_latte.scss]
      dark: [comso,_extensions/catppuccin_mocha.scss]
```
