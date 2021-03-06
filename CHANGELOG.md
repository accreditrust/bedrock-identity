# bedrock-identity ChangeLog

## 4.2.2 - 2016-06-20

### Fixed
- Add existence checks before transforming roles.

## 4.2.1 - 2016-06-07

### Changed
- Update dependencies.

## 4.2.0 - 2016-05-23

### Added
- Use the config to model identity object updates.

## 4.1.0 - 2016-05-09

### Added
- New `postInsert` event.

## 4.0.2 - 2016-04-30

### Changed
- Remove plaintext passcode and password from new identities.

## 4.0.1 - 2016-04-26

## 4.0.0 - 2016-04-26

### Changed
- Transform the roles contained in identities to URLs.

## 3.0.2 - 2016-04-19

### Fixed
- Do not remove plaintext password and passcode.

## 3.0.1 - 2016-04-15

### Changed
- Update bedrock dependencies.

## 3.0.0 - 2016-03-02

### Changed
- Update package dependencies for npm v3 compatibility.

## 2.0.0 - 2016-01-31

### Changed
- **BREAKING**: Moved key functionality to `bedrock-key`.

## 1.0.2 - 2015-07-16

### Changed
- Catch `ursa` exceptions and return Bedrock errors.

## 1.0.1 - 2015-05-07

### Fixed
- Fix database result access.

## 1.0.0 - 2015-04-08

### Security
- Log identity **after** password hashing.

## 0.1.0 (up to early 2015)

- See git history for changes.
