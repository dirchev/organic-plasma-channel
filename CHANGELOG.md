# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [2.0.0] - [26.11.2017]

**The release contains breaking changes towards v1.x.x**
Upgrade path requires providing for `plasma` an instance of organic-plasma v2.x.x as
it has organic plasma feedback included

### Changed

- removed `organic-plasma-feedback` decoration

### Fixed

- chemicals through channel having `err` defined as `Error` type are now
transferred as expected having their `message` and `stack` properties included
- README content
