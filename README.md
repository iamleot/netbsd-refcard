# NetBSD reference card #
The NetBSD reference card is a leaflet with the primary aim to be a useful
resource in case of quick reference to both novice and experience NetBSD users.

It does not intend to substitute high-quality (and longer)
[documentation](http://www.netbsd.org/docs/), in
particular [The NetBSD guide](http://www.netbsd.org/docs/guide/en/netbsd.html),
[The pkgsrc guide](http://www.netbsd.org/docs/pkgsrc/index.html) and
[man pages](http://man.netbsd.org/) but it will be complementary to them.


## How can I build it? ##
`netbsd-refcard` uses [latex-mk](http://latex-mk.sourceforge.net/) to ease the
building of the PDF.

    $ make clean
    $ make pdf

You can find all needed dependencies in pkgsrc:
 * `print/latex-mk`
 * `print/tex-leaflet`
