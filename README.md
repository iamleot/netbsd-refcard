# NetBSD reference card #
The NetBSD reference card is a
[leaflet](http://en.wikipedia.org/wiki/Flyer_(pamphlet)) with the primary aim
to be a useful resource in case of quick reference to both novice and
experience [NetBSD](http://www.netbsd.org) users.

It does not intend to substitute high-quality and clear
[documentation](http://www.netbsd.org/docs/), in
particular [The NetBSD guide](http://www.netbsd.org/docs/guide/en/netbsd.html),
[The pkgsrc guide](http://www.netbsd.org/docs/pkgsrc/index.html) and
[man pages](http://man.netbsd.org/) but it will be complementary to them.


## How can I build it? ##
First of all you need to `clone` the [git](http://git-scm.com/) repository:

    $ git clone https://github.com/iamleot/netbsd-refcard.git

`netbsd-refcard` uses [latex-mk](http://latex-mk.sourceforge.net/) to ease the
building of the PDF:

    $ make clean
    $ make pdf

You can find all needed dependencies in [pkgsrc](http://www.pkgsrc.org):
 * `print/latex-mk`
 * `print/tex-leaflet`
 * `devel/git-base`


**DISCLAIMER**: the `netbsd-refcard` is in a phase of brainstorming and probably
its contents will be completed rewritten in the next weeks.
