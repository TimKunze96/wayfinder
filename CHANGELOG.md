# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased](https://github.com/laravel/wayfinder/compare/v0.1.5...main)

## [v0.1.5](https://github.com/laravel/wayfinder/compare/v0.1.4...v0.1.5) - 2025-05-07

### What's Changed

* Grammar Check of README.md by [@j3ns3n](https://github.com/j3ns3n) in https://github.com/laravel/wayfinder/pull/43
* php 8.2 support by [@emhashef](https://github.com/emhashef) in https://github.com/laravel/wayfinder/pull/42
* Update README.md to improve integration by [@nckrtl](https://github.com/nckrtl) in https://github.com/laravel/wayfinder/pull/35
* Improve docs by [@timacdonald](https://github.com/timacdonald) in https://github.com/laravel/wayfinder/pull/47
* Add support for generating route while routes are cached by [@timacdonald](https://github.com/timacdonald) in https://github.com/laravel/wayfinder/pull/45
* Test it can import storage routes by [@timacdonald](https://github.com/timacdonald) in https://github.com/laravel/wayfinder/pull/46
* Blade + TypeScript clean up by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/wayfinder/pull/52
* Handle namespaced routes correctly by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/wayfinder/pull/51
* Fix: Use forward slashes in docblock paths by [@istiak-tridip](https://github.com/istiak-tridip) in https://github.com/laravel/wayfinder/pull/56
* Fix for PostgreSQL ID typing by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/wayfinder/pull/58
* Don't escape forward slashes in URI by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/wayfinder/pull/60

### Potential Minor Breaking Change

The changes to how Wayfinder writes barrel files in v0.1.3 were largely reverted. Sorry for the back and forth there, still refining the DX.

### New Contributors

* [@j3ns3n](https://github.com/j3ns3n) made their first contribution in https://github.com/laravel/wayfinder/pull/43
* [@emhashef](https://github.com/emhashef) made their first contribution in https://github.com/laravel/wayfinder/pull/42
* [@nckrtl](https://github.com/nckrtl) made their first contribution in https://github.com/laravel/wayfinder/pull/35
* [@istiak-tridip](https://github.com/istiak-tridip) made their first contribution in https://github.com/laravel/wayfinder/pull/56

**Full Changelog**: https://github.com/laravel/wayfinder/compare/v0.1.4...v0.1.5

## [v0.1.4](https://github.com/laravel/wayfinder/compare/v0.1.3...v0.1.4) - 2025-04-07

### What's Changed

* Check possible undefined by [@hosmelq](https://github.com/hosmelq) in https://github.com/laravel/wayfinder/pull/30
* Add route prefix to reserved js keyword route names by [@aktasumut34](https://github.com/aktasumut34) in https://github.com/laravel/wayfinder/pull/32

### New Contributors

* [@aktasumut34](https://github.com/aktasumut34) made their first contribution in https://github.com/laravel/wayfinder/pull/32

**Full Changelog**: https://github.com/laravel/wayfinder/compare/v0.1.3...v0.1.4

## [v0.1.3](https://github.com/laravel/wayfinder/compare/v0.1.1...v0.1.3) - 2025-04-04

### What's Changed

* Check if routable is an Eloquent model ([#8](https://github.com/laravel/wayfinder/pull/8))
* Return literal HTTP methods, fixes Inertia TypeScript error ([14](https://github.com/laravel/wayfinder/pull/14))
* Strip additional whitespace ([#12](https://github.com/laravel/wayfinder/pull/12))
* Fix: Convert Hyphenated File Names to Camel Case ([#13](https://github.com/laravel/wayfinder/pull/13))
* Do not delete directories when skipping by [@hosmelq](https://github.com/hosmelq) in https://github.com/laravel/wayfinder/pull/16
* fix: URL constructor: // is not a valid URL. by [@ArthurYdalgo](https://github.com/ArthurYdalgo) in https://github.com/laravel/wayfinder/pull/20
* docs: update Vite watcher pattern to support nested routes by [@IlyasMohetna](https://github.com/IlyasMohetna) in https://github.com/laravel/wayfinder/pull/19
* Remove trim deadspace directive for function arguments by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/wayfinder/pull/24
* fix: build.ts on Windows by [@Niush](https://github.com/Niush) in https://github.com/laravel/wayfinder/pull/23
* Refactor contribution documentation and add support and security guidelines by [@michaelnabil230](https://github.com/michaelnabil230) in https://github.com/laravel/wayfinder/pull/17
* Expanded list of JavaScript reserved words by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/wayfinder/pull/25
* Fix barrel files by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/wayfinder/pull/26
* Allow chaining of reserved JavaScript words from controllers by [@joetannenbaum](https://github.com/joetannenbaum) in https://github.com/laravel/wayfinder/pull/28
* Fix typo in readme and change highlighting for notes by [@AndrewMast](https://github.com/AndrewMast) in https://github.com/laravel/wayfinder/pull/27

### Potential Minor Breaking Change

The changes to how Wayfinder writes barrel files in https://github.com/laravel/wayfinder/pull/26 might affect your codebase depending on how you are currently importing actions or routes.

### New Contributors

* [@hosmelq](https://github.com/hosmelq) made their first contribution in https://github.com/laravel/wayfinder/pull/16
* [@ArthurYdalgo](https://github.com/ArthurYdalgo) made their first contribution in https://github.com/laravel/wayfinder/pull/20
* [@IlyasMohetna](https://github.com/IlyasMohetna) made their first contribution in https://github.com/laravel/wayfinder/pull/19
* [@Niush](https://github.com/Niush) made their first contribution in https://github.com/laravel/wayfinder/pull/23
* [@AndrewMast](https://github.com/AndrewMast) made their first contribution in https://github.com/laravel/wayfinder/pull/27

**Full Changelog**: https://github.com/laravel/wayfinder/compare/v0.1.2...v0.1.3

## [v0.1.1](https://github.com/laravel/wayfinder/compare/v0.1.0...v0.1.1)

- Fix middleware closure crash ([#5](https://github.com/laravel/wayfinder/pull/5))

## v0.1.0

- Initial release!
