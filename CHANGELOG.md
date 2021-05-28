# Changelog

## **unreleased**

- Fixed
  - `TOMLDecodeError` is now raised for duplicate key names in inline tables,
    as opposed to silently overriding the previous value

## 0.2.0

- Changed
  - Project name to Tomli
- Added
  - A performance boost

## 0.1.0

- Added
  - `tomli.loads` for parsing TOML strings
  - `tomli.TOMLDecodeError` that is raised for parse errors