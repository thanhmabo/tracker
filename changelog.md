# Changelog

## [Unreleased][unreleased]
### Added
- Referer parsing, to store marketing attribution data (medium, source and search term)
- Tracker::trackVisit()
- Tracker::trackEvent()
### Changed
- Move to UA-PHP instead of PragmaRX/UaParser
- Using a better bot detector 
### Fixed
- Correctly get the application url
- Migrations for MySQL
- Sessions now change when a different users logs in
### Changed
- Use ua-php instead of ua-parser directly
- No need to execute tracker:updateparser during install anymore

## [1.0.5] - 2015-03-10
### Added
- Middleware filter to routes

## [1.0.4] - 2015-03-10
### Fixed
- Console exception handler

## [1.0.3] - 2015-03-08
### Fixed
- Datatables bug

## [1.0.2] - 2015-03-07
### Fixed
- Migrations for MySQL

## [1.0.1] - 2015-03-06
### Changed
- Use a stable version of datatables

## [1.0.0] - 2015-02-21
### Changed
- Added support for Laravel 5

## [0.5.2] - 2014-07-06
### Fixed
- HTTP cache by removing PHP session_start

## [0.5.1] - 2014-07-03
###Added
- A 'Today' filter option on Stats Panel
- All stats tables are now Google Charts Tables (paginated)

## [0.5.0] - 2014-07-02
###Changed
- Moved pie charts from flot to Google Charts
 
