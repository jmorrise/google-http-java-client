# Changelog

## [1.34.0](https://www.github.com/googleapis/google-http-java-client/compare/v1.33.0...v1.34.0) (2019-12-10)


### Features

* add option to pass redirect Location: header value as-is without encoding, decoding, or escaping ([#871](https://www.github.com/googleapis/google-http-java-client/issues/871)) ([2c4f49e](https://www.github.com/googleapis/google-http-java-client/commit/2c4f49e0e5f9c6b8f21f35edae373eaada87119b))


### Bug Fixes

* redirect on 308 (Permanent Redirect) too ([#876](https://www.github.com/googleapis/google-http-java-client/issues/876)) ([501ede8](https://www.github.com/googleapis/google-http-java-client/commit/501ede83ef332207f0ed67c3d7120b20a1416cec))

## [1.32.2](https://www.github.com/googleapis/google-http-java-client/compare/v1.32.1...v1.32.2) (2019-10-29)


### Bug Fixes

* wrap GZIPInputStream for connection reuse ([#840](https://www.github.com/googleapis/google-http-java-client/issues/840)) ([087a428](https://www.github.com/googleapis/google-http-java-client/commit/087a428390a334bd761a8a3d66475aa4dde72ed1)), closes [#749](https://www.github.com/googleapis/google-http-java-client/issues/749) [#367](https://www.github.com/googleapis/google-http-java-client/issues/367)
* HttpResponse GZip content encoding equality change ([#843](https://www.github.com/googleapis/google-http-java-client/issues/843)) ([9c73e1d](https://www.github.com/googleapis/google-http-java-client/commit/9c73e1db7ab371c57ff6246fa39fa514051ef99c)), closes [#842](https://www.github.com/googleapis/google-http-java-client/issues/842) [#842](https://www.github.com/googleapis/google-http-java-client/issues/842) [#842](https://www.github.com/googleapis/google-http-java-client/issues/842) [#842](https://www.github.com/googleapis/google-http-java-client/issues/842) [#842](https://www.github.com/googleapis/google-http-java-client/issues/842)
* use platform default TCP buffer sizes ([#855](https://www.github.com/googleapis/google-http-java-client/issues/855)) ([238f4c5](https://www.github.com/googleapis/google-http-java-client/commit/238f4c52086defc5a055f2e8d91e7450454d5792))



### Documentation

* fix HttpResponseException Markup ([#829](https://www.github.com/googleapis/google-http-java-client/issues/829)) ([99d64e0](https://www.github.com/googleapis/google-http-java-client/commit/99d64e0d88bdcc3b00d54ee9370e052e5f949680))
* include HTTP Transport page in navigation, add support page ([#854](https://www.github.com/googleapis/google-http-java-client/issues/854)) ([57fd1d8](https://www.github.com/googleapis/google-http-java-client/commit/57fd1d859dad486b37b4b4c4ccda5c7f8fa1b356))
* remove theme details ([#859](https://www.github.com/googleapis/google-http-java-client/issues/859)) ([eee85cd](https://www.github.com/googleapis/google-http-java-client/commit/eee85cd8aaaacd6e38271841a6eafe27a0c9d6ec))
* update libraries-bom to 2.7.1 in setup ([#857](https://www.github.com/googleapis/google-http-java-client/issues/857)) ([cc2ea16](https://www.github.com/googleapis/google-http-java-client/commit/cc2ea1697aceb5d3693b02fa87b0f8379f5d7a2b))
* use libraries-bom 2.6.0 in setup instructions ([#847](https://www.github.com/googleapis/google-http-java-client/issues/847)) ([5253c6c](https://www.github.com/googleapis/google-http-java-client/commit/5253c6c5e2b2312206000fd887fe6f0d89a26570))


### Dependencies

* update dependency com.fasterxml.jackson.core:jackson-core to v2.10.0 ([#831](https://www.github.com/googleapis/google-http-java-client/issues/831)) ([ffb1a85](https://www.github.com/googleapis/google-http-java-client/commit/ffb1a857a31948472b2b62ff4f47905fa60fe1e2))
* update dependency com.fasterxml.jackson.core:jackson-core to v2.9.10 ([#828](https://www.github.com/googleapis/google-http-java-client/issues/828)) ([15ba3c3](https://www.github.com/googleapis/google-http-java-client/commit/15ba3c3f7cee9e2e5362d69c1278f45531e56581))
* update dependency com.google.code.gson:gson to v2.8.6 ([#833](https://www.github.com/googleapis/google-http-java-client/issues/833)) ([6c50997](https://www.github.com/googleapis/google-http-java-client/commit/6c50997361fee875d6b7e6db90e70d41622fc04c))
* update dependency mysql:mysql-connector-java to v8.0.18 ([#839](https://www.github.com/googleapis/google-http-java-client/issues/839)) ([1522eb5](https://www.github.com/googleapis/google-http-java-client/commit/1522eb5c011b4f20199e2ec8cb5ec58d10cc399a))

### [1.32.1](https://www.github.com/googleapis/google-http-java-client/compare/v1.32.0...v1.32.1) (2019-09-20)


### Dependencies

* update dependency com.google.protobuf:protobuf-java to v3.10.0 ([#824](https://www.github.com/googleapis/google-http-java-client/issues/824)) ([c51b62f](https://www.github.com/googleapis/google-http-java-client/commit/c51b62f))
* update guava to 28.1-android ([#817](https://www.github.com/googleapis/google-http-java-client/issues/817)) ([e05b6a8](https://www.github.com/googleapis/google-http-java-client/commit/e05b6a8))
