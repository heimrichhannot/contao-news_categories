# Changelog
All notable changes to this project will be documented in this file.

## [2.2.1] - 2024-11-22
- Fixed: compatibility issue with fieldpalette 0.6

## [2.2.0] - 2024-01-30
- Added: php8 support

## [2.1.0] - 2023-01-10
- Changed: replace tree_picker with native picker

## [2.0.4] - 2022-09-27
- Fixed: invalid namespace

## [2.0.3] - 2018-12-06

### Fixed
- FieldpaletteModel instance call in CategoryHelper

## [2.0.2] - 2018-12-06

### Fixed
- FieldpaletteModel instance call in contao 4

## [2.0.1] - 2018-12-06

### Fixed
- replaced dependency `heimrichhannot/contao-fieldpalette` with `heimrichhannot/contao-fieldpalette-bundle` class errors

## [2.0.0] - 2018-12-06

### Changed
- contao 4 branch only
- replaced dependency `heimrichhannot/contao-fieldpalette` with `heimrichhannot/contao-fieldpalette-bundle`

## [1.0.0] - 2017-10-20

Fork from `https://github.com/codefog/contao-news_categories` 2.8.6

### Added
- primary category support (primary category can be set on news, otherwise first category in list is primary category)
- category jumpTo based on news_archive (can be set on each news category for each news archive)
- news url jumpTo based on news_archive and primary category (can be set on each news category for each news archive) -> news url will be linked to the primary category jumpTo page instead of archive jumpTo page
- news categories can now have a teaser (also based on news_archive, can be set on each news category for each news archive)
- several new inserttags

### Changed
- adjusted composer.json and dependencies
