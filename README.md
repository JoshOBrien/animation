# animation

[![Build Status](https://travis-ci.org/yihui/animation.svg)](https://travis-ci.org/yihui/animation)

## Introduction

This is an R package to create and export animations to a variety of formats
(HTML/JS, GIF, Video, PDF), and it also serves as a gallery of statistical
animations.

## Installation

To install the stable version on CRAN:

```s
install.packages('animation')
```

To install the GitHub version under development:

```s
install.packages('animation', repos = 'http://yihui.name/xran')
```

If you want to contribute, the documentation and NAMESPACE of this package
are generated by **roxygen2** and **Rd2roxygen**:

```s
if (!require('Rd2roxygen') install.packages('Rd2roxygen')
library(Rd2roxygen)
rab('animation', install = TRUE)
```

## Contact

Bugs and feature requests can be filed to
<https://github.com/yihui/animation/issues>. Pull requests are also welcome.

