# mlrMBO


Model-based optimization with mlr

[![Build Status](https://travis-ci.org/mlr-org/mlrMBO.png?branch=master)](https://travis-ci.org/mlr-org/mlrMBO)
[![Build status](https://ci.appveyor.com/api/projects/status/gvr607kqcl78qjq9/branch/master?svg=true)](https://ci.appveyor.com/project/jakob-r/mlrmbo/branch/master)


The package will be released soon, so some links below are not working.

* [Offical CRAN release site](http://cran.r-project.org/web/packages/mlrMBO/index.html)  (*not available yet*)
  
* [Tutorial on github](http://mlr-org.github.io/mlrMBO/devel/html/) (*work in progress*)

# Installation

The package has not been released on CRAN yet. Run the following command in R to install the current GitHub version. 

To install packages directly from github use the `install_github()` function from `devtools`.

```r
install.packages("devtools")
```

Before you can install `mlrMBO` you need the current github versions of both [mlr](https://github.com/mlr-org/mlr/) and [ParamHelpers](https://github.com/berndbischl/ParamHelpers).

```r
library(devtools)
install_github("berndbischl/ParamHelpers")
install_github("mlr-org/mlr")
```

Then you can easily install.  

```r
install_github("mlr-org/mlrMBO")
```

Àll other dependencies will be installed automatically from CRAN. 


[Further installation instructions](https://github.com/rdatsci/PackagesInfo/wiki/Installation-Information) are available at the site of tudo-r

# Mailinglist and Email-Service-Hook

Developers use this mailing list:

https://groups.google.com/forum/?hl=de#!forum/mlrmbo-devel

mlrmbo-devel@googlegroups.com

The github-service-hook will also send commit messages to this list. 
