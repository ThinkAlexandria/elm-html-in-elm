# Change Log

# [1.0.1] - 2018-09-20

## Fixed

* now properly handles Elm 0.19's internal virtual dom JSON structure.

## [1.0.0] - 2018-09-20

### Changed

* elm-html-in-elm now supports only Elm 0.19

* Errors when using elm-html-in-elm with custom elements or markdown are no
  longer reported to console because of Elm 0.19 restrictions on use of
`Debug.log`.
