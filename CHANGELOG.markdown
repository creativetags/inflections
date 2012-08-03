0.0.6 (current version)
=======================
* Support for British English

0.0.5
=======================
* Rails users no longer need to specify a locale to load; inflections are automagically loaded depending on `I18n.default_locale`

0.0.4
=====
* Support for Spanish (es)

0.0.3
=====
* Code reorganization. Inflections will now be located under `lib/inflections/` and will be named as according to their I18n abbreviation.
* Tests have also been reorganized. They live in the `test/` directory (big surprise) and, like the inflection files, should be named as according to their I18n abbreviation (`en_test.rb`, `es_test.rb`, `de_test.rb`, etc.)

0.0.2
=====
* Travis CI support

0.0.1
=====
* Initial version: support for English (en)
