# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.1.3] 2016-03-25

  * Changed: updated license data files.
  * Changed: dropped `test` namespace.
  * Changed: tedious small things.

## [1.1.2] 2015-10-05

  * Changed: new licenses added.

## [1.1.1] 2015-09-07

  * Changed: improved performance when looking up just one license.
  * Changed: new licenses added.

## [1.1.0] 2015-07-17

  * Changed: updater now sorts licenses and exceptions by key.
  * Changed: filenames now class constants of SpdxLicenses (`LICENSES_FILE` and `EXCEPTIONS_FILE`).
  * Changed: resources directory now available via static method `SpdxLicenses::getResourcesDir()`.
  * Changed: new licenses added.
  * Changed: removed json-schema requirement.

## [1.0.0] 2015-07-15

  * Break: the following classes and namespaces were renamed:
    - Namespace: `Composer\Util` -> `Composer\Spdx`
    - Classname: `SpdxLicense` -> `SpdxLicenses`
    - Classname: `SpdxLicenseTest` -> `SpdxLicensesTest`
    - Classname: `Updater` -> `SpdxLicensesUpdater`
  * Changed: validation via regex implementation instead of lexer.

[1.1.3]: https://github.com/composer/spdx-licenses/compare/1.1.2...1.1.3
[1.1.2]: https://github.com/composer/spdx-licenses/compare/1.1.1...1.1.2
[1.1.1]: https://github.com/composer/spdx-licenses/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/composer/spdx-licenses/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/composer/spdx-licenses/compare/0281a7fe7820c990db3058844e7d448d7b70e3ac...1.0.0
