Minutes of meetings
=========

The protocols are written in [Markdown](http://daringfireball.net/projects/markdown/).

Start each protocol with a title block. This is used when compiling to PDF.

Example

```
% Styrelsemöte - Python Sverige
% Sekreterare: Frej Connolly \
  Justerare: Tome Cvitan och Jyrki Pulliainen
% 2013-01-08
```

The order is title, authors and date. More info can be found in the Pandoc documention under [title block](http://johnmacfarlane.net/pandoc/README.html#title-block). Backslash following by a new line converts to a hard line break in the PDF.

How to export to PDF
--------------------
Install [Pandoc](http://johnmacfarlane.net/pandoc/installing.html) and the recommended LaTeX compiler for you OS given by the Pandoc instructions. Use option ```-N``` to add numbering to each section in the output.

```
pandoc -N input.md -o output.pdf
```
