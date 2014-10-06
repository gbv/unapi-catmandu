# unapi-catmandu

unAPI services based on the (Catmandu framework)[http://librecat.org].

## Services

* doi.psi - Get MODS, RDF, JSON via DOI
* ...

# Installation

Requires Perl and cpanmimus

    apt-get install cpanminus
    apt-get install libplack-perl
    apt-get install librdf-trine-perl
    apt-get install libxml-libxml-perl
    cpanm --installdeps .

    plackup doi.psgi

