## 0.3.0

* Refactor client behind a protocol
* Add memory client to facilitate testing
* Deprecate top-level ns to make emacs clojure-mode happy

## 0.2.1

* Add update! fn

## 0.2.0

* Relax salesforce types

## 0.1.7

* Use ex-info for exceptions to provide better data

## 0.1.6

* Fix bug in resolving field paths for custom relations
* Add :where clause support to query

## 0.1.5

* Fix bug in field description type
* Add url metadata to sails-forth.query/query

## 0.1.4

* Add type registry to allow custom objects to have nicer type names
* Add helper fn to resolve attrs by labels

## 0.1.3

* Convert date fields to joda local-date instances
* Convert some double and int fields to integral types

## 0.1.2

* Add count! fn
* Add sails-forth.query ns
* Configure cheshire to parse json numbers as bigdecimals
* Parse dates and datetimes as joda instances

## 0.1.1

* Move user to sails-forth.repl and remove dependency on test ns

## 0.1.0

* Initial release: uses core.typed predicates to validate responses
