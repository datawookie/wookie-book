# Wookie-book Format

Derived from [Nicole Rennie's extension](https://nrennie.rbind.io/blog/pdf-quarto/making-pretty-pdf-quarto/). Had to make some tweaks to work for books.

## Installing

This will install the extension and create an example qmd file that you can use as a starting place for your article.

```bash
quarto use template datawookie/wookie-book
```

To use the extension in an existing project without installing the template file:

``` bash
quarto install extension datawookie/wookie-book
```
Note that you will need to update the output format to `format: wookie-book-pdf` to enable use of the extension. For book projects, add:

```
project:
  type: wookie-book
```

to the `_quarto.yml` file.

## Adjusting LaTeX Styling

If you want to update the LaTeX version of this template to use a different colour or logo, open up the `_extensions/nrennie/PrettyPDF/PrettyPDF.tex` file after you have installed the extension.

## Example

Here is the source code for a minimal sample document: [example.qmd](example.qmd).
