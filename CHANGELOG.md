# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.3] - 2021-02-03
### Added
  * user configuration for setting cache on or off

### Changed
  * fix handle/renderer signature; missing `Doku_Handler`, etc. attributes

## [1.1.2] - 2020-06-08
### Changed
  * removed pass-by-reference on `handle` and `render` function calls; this is inline
    with changes to Dokuwiki starting with version "Hogfather" RC2

## [1.1.1] - 2019-10-10
### Fixed
  * added missing LaTeX tilde characters (thanks rrfeup!)

## [1.1.0] - 2019-10-08
### Added
  * extended sanitizer to include more 'tilda' characters

### Changed
  * updated dokuwiki meta file

## [1.0.0] - 2019-10-08
### Changed
  * changed version number and changelog format for project (the existing changelog
    details are potentially incomplete.
  * reformated README

_Versions beyond this point do not exist within the Git History!_

## [0.1.1] - 2013-03-22
### Added
  * minor bugfixes for
  * added a new optional parameter "authors", which allows linking to websites of
    co-authors by creating an additional file/wiki page with "URL Author Name"
    entries

## [0.1.0] - 2013-03-12
### Added
  * bib2tpl updated to v2 with additional modifications (see changelog in
    bib2tpl folder).
  * Included simple (optional) TeX to utf8 sanitiser in syntax.php.
  * Included Spanish (es) language file.
  * "handle" function (syntax.php) parser code corrections. "only" option
    not correctly parsed when using a single condition. E.g. "only:a=b" would
    yield 'only' => 'a=b' instead of 'only' => ['a' => 'b'].
  * Language option: set default from "translation" plugin (if installed &
    enabled) or global language configuration. "lang:xx" option is not needed
    now in most cases.
  * Added/updated administrative files: COPYING, etc.

[Unreleased]: https://github.com/SacBase/publistf/compare/1.1.2...HEAD
[1.1.2]: https://github.com/SacBase/publistf/compare/1.1.1..1.1.2
[1.1.1]: https://github.com/SacBase/publistf/compare/1.1.0..1.1.1
[1.1.0]: https://github.com/SacBase/publistf/compare/1.0.0..1.1.0
[1.0.0]: https://github.com/SacBase/publistf/releases/tag/1.0.0
[0.1.1]: #
[0.1.0]: #
