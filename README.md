# Maser's Thesis Report

[**Most of the part of the original readme is left unchanged for referencial purpose]

This is a copy of LaTeX template created according to the guidelines for TUM informatics theses in SS 2013. (It has been modified according to my requirements, even more modifications in formatting is expected) **Always check the [current formatting guidelines][thesis-guidelines] before you hand in.

Note: Because of copyright considerations, TUM logos are not included in this template and have to be downloaded separately (see instructions below).

Comments & contributions welcome!

## Quickstart

 * Download and extract the template. If you prefer to use Git, just clone/fork the repository.
 * Download the TUM logos in PDF format:
   * Log in to [MyTUM][mytum].
   * Download the TUM logo from [here][mytum-logo-tum] and save it to `logos/tum.pdf`.
   * Download your faculty's logo from [here][mytum-logo-faculty] and save it to `logos/faculty.pdf`.
   * Some logos might not be cropped; execute the `crop-logos` script to do that for you. The script requires the `pdfcrop` tool (included in TeX Live/MiKTeX), so make sure your `PATH` environment variable is set accordingly.
 * Configure your latex editor to use `pdflatex`, `biber` for bibliography, and `makeglossaries` for glossary generation. Set `main.tex` as the master document. Alternatively, you can use the provided makefile to create a PDF in the `build` directory (requires `latexmk`).
 * Look for `TODO` comments in the provided files. Start at `main.tex`.


## License

[![Creative Commons License][license-image]][license]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][license].

[thesis-guidelines]: http://www.in.tum.de/fuer-studierende/pruefungen-und-formalitaeten/abschlussarbeit.html
[mytum]: https://portal.mytum.de
[mytum-logo-tum]: https://portal.mytum.de/corporatedesign/download/TUM_Logo/index_html
[mytum-logo-faculty]: https://portal.mytum.de/corporatedesign/download/fakultaetslogos/index_html
[license]: https://creativecommons.org/licenses/by-sa/4.0/
[license-image]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
