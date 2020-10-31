# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 1.4.0 - TBD

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 1.3.2 - 2020-09-10


-----

### Release Notes for [1.3.2](https://github.com/laminas-api-tools/api-tools-documentation-swagger/milestone/1)



### 1.3.2

- Total issues resolved: **0**
- Total pull requests resolved: **1**
- Total contributors: **1**

#### Enhancement

 - [13: Fix tests](https://github.com/laminas-api-tools/api-tools-documentation-swagger/pull/13) thanks to @alexdenvir

## 1.3.1 - 2020-04-01

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Provides updates to address [security advisory LP-2020-02](https://getlaminas.org/security/advisory/LP-2020-02).

## 1.3.0 - 2018-05-07

### Added

- [zfcampus/zf-apigility-documentation-swagger#34](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/34) adds support for PHP 7.1 and 7.2.

### Changed

- [zfcampus/zf-apigility-documentation-swagger#28](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/28) updates the component to generate Swagger 2.2.6 / OpenAPI 2.0 documentation (instead of Swagger 1.3).

### Deprecated

- Nothing.

### Removed

- [zfcampus/zf-apigility-documentation-swagger#34](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/34) removes support for HHVM.

### Fixed

- [zfcampus/zf-apigility-documentation-swagger#29](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/29) fixes an issue that occurs when a field definition in an input filter
  is not a `Field` instance; these are now skipped when generating field documentation.

## 1.2.1 - 2016-10-11

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-documentation-swagger#27](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/27)
  fixes the `SwaggerUiControllerFactory` to properly use the `$container`
  variable, not the nonexistent `$services` variable, when pulling the
  `ApiFactory` to inject in the controller.

## 1.2.0 - 2016-07-14

### Added

- [zfcampus/zf-apigility-documentation-swagger#24](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/24)
  adds support for v3 releases of Laminas components, keeping
  compatibility for v2 releases.
- [zfcampus/zf-apigility-documentation-swagger#14](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/14) and
  [zfcampus/zf-apigility-documentation-swagger#19](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/19) add
  support for retrieving the field type as both the type and dataType.

### Deprecated

- Nothing.

### Removed

- [zfcampus/zf-apigility-documentation-swagger#24](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/24)
  removes support for PHP 5.5.
- [zfcampus/zf-apigility-documentation-swagger#21](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/21)
  removes the verbiage "Operation for {Api}" as a default service description
  from the swagger templates.

### Fixed

- [zfcampus/zf-apigility-documentation-swagger#23](https://github.com/zfcampus/zf-apigility-documentation-swagger/pull/23)
  updates the link to the Swagger website to point to the new swagger.io URL.
