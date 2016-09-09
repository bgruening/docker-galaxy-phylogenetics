# galaxy-phylogenetics
:whale::bar_chart::books: Docker Images for molecular phylogenetics

[![Build Status](https://travis-ci.org/bgruening/galaxy-phylogenetics.svg?branch=master)](https://travis-ci.org/bgruening/galaxy-phylogenetics)
[![Docker Repository on Quay](https://quay.io/repository/bgruening/galaxy-phylogenetics/status "Docker Repository on Quay")](https://quay.io/repository/bgruening/galaxy-phylogenetics)

Galaxy Image for Molecular Phylogenetics
================================

:whale: Galaxy Docker repository for molecular phylogenetics

# Installed tools

- Alignements:
    - [CLUSTALW](http://www.genome.jp/tools/clustalw/)
    - [MAFFT](http://mafft.cbrc.jp/alignment/software/)
    - [Muscle](http://www.drive5.com/muscle/)
- Phylogeny construction:
    - [PhyML](http://www.atgc-montpellier.fr/phyml/)
    - [RAxML](http://sco.h-its.org/exelixis/web/software/raxml/index.html)
    - [BEAST](http://beast.bio.ed.ac.uk/)
- Visualization:
    - [GraPhlAn](https://huttenhower.sph.harvard.edu/graphlan)
    - [export2graphlan](https://bitbucket.org/nsegata/graphlan/wiki/export2graphlan%20-%20tutorial)

# Requirements

- [Docker](https://docs.docker.com/installation/) for Linux / Windows / OSX
- [Kitematic](https://kitematic.com/) for Windows / OS-X (optinal)

# Usage

To launch:

```
docker run -i -t -p 8080:80 bgruening/galaxy-phylogenetics
```

For more details about this command line or specific usage, please consult the
[`README`](https://github.com/bgruening/docker-galaxy-stable/blob/master/README.md) of the main Galaxy Docker image, on which the current image is based.

# Contributers

- Bjoern Gruening
- Bérénice Batut

# Support & Bug Reports

You can file an [github issue](https://github.com/bgruening/galaxy-phylogenetics/issues) or ask us on the [Galaxy development list](http://lists.bx.psu.edu/listinfo/galaxy-dev).
