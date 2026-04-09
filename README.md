# sbuerk/typo3-gerrit-change-downloader - Composer plugin to manage TYPO3 Gerrit changes as composer patches

## Overview

It's planned that this get a series of real composer commands to handle patch files based on TYPO3 Gerrit Core changes,
but for the start only provides a simple download script `vendor/bin/download-patch-from-gerrit.phpsh` to create
`vaimo/composer-patches` files automatically splitting core changes for dedicated core composer packages and also
stripping out test related changes or any non-composer package changes related to the TYPO3 mono-repository.