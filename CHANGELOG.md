# Change Log
All notable changes to this project will be documented in this file. This change log follows the conventions of [keepachangelog.com](http://keepachangelog.com/).

## 0.3.0 - 2018-09-20
### Changed
- Swapped argument order for unsign function to make partial application easier

## 0.2.1 - 2018-09-20
### Added
- Error logging for failing key resolve

## 0.2.0 - 2018-09-19
### Added
- Added specs for unsign and generator for ::jwt
- Added logging for retry in resolve-key function

## 0.1.0 - 2018-09-18
### Added
- Initial implementation of clj-jwt library.
- Function `resolve-key` that fetches jwks keys and returns a PublicKey given the kid in the jwt header.
- Function `unsign` which tries to validate a jwt given a jwks URL and a jwt.

[Unreleased]: https://gitlab.nsd.no/clojure/clj-jwt/compare/0.2.0...HEAD
[0.2.0]: https://gitlab.nsd.no/clojure/clj-jwt/compare/0.1.0...0.2.0