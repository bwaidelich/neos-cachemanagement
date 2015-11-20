[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)
[![Latest Stable Version](https://poser.pugx.org/flownative/neos-cachemanagement/version)](https://packagist.org/packages/flownative/neos-cachemanagement)

# Neos Cache Management Backend Module

![Screenshot of the Cache Management Module](Documentation/BackendScreenshot.png)

This [Neos](https://www.neos.io) backend module provides cache management functions to Neos administrators. In this
early version, the backend module simply allows for flushing the content cache (TYPO3_TypoScript_Content).

Note that in general it is not necessary to flush content caches manually. This is rather a sign of a mis-configured
website. Before making it a habit to flush caches, please read and implement the advice mentioned in the respective
section of the [Neos Manual](http://neos.readthedocs.org/en/stable/CreatingASite/ContentCache.html).

# Installation

Simply install this package via Composer. The package key is `flownative/neos-cachemanagement`.
