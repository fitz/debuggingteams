# Debugging Teams

This is the source code for the book "Debugging Teams: Better
Productivity through Collaboration", by Brian W. Fitzpatrick and Ben
Collins-Sussman, originally published in 2015.


## License Terms

This book is licensed under the **Creative Commons BY-NC-SA 3.0** license.
Please see the LICENSE file for the precise legal language, but in
layman's terms, this means you are free to:

  - **Share** — copy and redistribute the material in any medium or format

  - **Adapt** — remix, transform, and build upon the material

...under the following terms:

  - **Attribution** — You must give appropriate credit, provide a link
    to the license, and indicate if changes were made. You may do so
    in any reasonable manner, but not in any way that suggests the
    licensor endorses you or your use.

  - **NonCommercial** — You may not use the material for commercial
    purposes.

  - **ShareAlike** — If you remix, transform, or build upon the
    material, you must distribute your contributions under the same
    license as the original.

  - **No additional restrictions** — You may not apply legal terms or
    technological measures that legally restrict others from doing
    anything the license permits.


## Printed Editions

This book is available for purchase in [physical hardcopy from
O'Reilly
Media](https://www.oreilly.com/library/view/debugging-teams/9781491932049/),
in a variety of international translations.


## Building the Source

This book is written in [asciidoc](https://asciidoc.org/) format.

To compile the code, we recommend you install the
[Asciidoctor](https://asciidoctor.org/) Ruby application on your
system.

To build a single-page HTML file:

  - *asciidoctor book.asciidoc*

To build a PDF file:

  - Install the
    [asciidoctor-pdf](https://rubygems.org/gems/asciidoctor-pdf) ruby
    extension (e.g. *sudo gem install asciidoctor-pdf*)

  - *asciidoctor-pdf book.asciidoc*

To build an ePub file:

  - Install the
    [asciidoctor-epub3](https://rubygems.org/gems/asciidoctor-epub3) ruby
    extension (e.g. *sudo gem install asciidoctor-epub3*)

  - *asciidoctor-epub3 book.asciidoc*

