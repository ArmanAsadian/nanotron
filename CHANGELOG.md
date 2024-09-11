# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.0.0-alpha.0](https://github.com/Alwatr/nanotron/compare/v1.2.7...v4.0.0-alpha.0) (2024-09-10)

### ⚠ BREAKING CHANGES

* everything rewrite from scratch please check the documents

Co-authored-by: Mohammad Honarvar <honarvar.info@gmail.com>

### Features

* Add API routes for root and hello endpoints in api-server demo ([4692fbb](https://github.com/Alwatr/nanotron/commit/4692fbb1ee54d481f35583b17e51a9d9c875da30)) by @AliMD
* Add applyReplyHeaders_ method to NanotronApiConnection class ([2a0eb4a](https://github.com/Alwatr/nanotron/commit/2a0eb4a1cb02519ad4aea6ad5d4d45de058029c2)) by @AliMD
* Add close method to NanotronApiServer ([cbd2ed8](https://github.com/Alwatr/nanotron/commit/cbd2ed8bc43fc78027ec8a647659a8ab59e7606c)) by @AliMD
* Add constructor to NanotronApiConnection class ([71d7a3a](https://github.com/Alwatr/nanotron/commit/71d7a3a51009a53fa7a23e39a3780bbc755038fd)) by @AliMD
* Add constructor to NanotronApiServer ([fbb358c](https://github.com/Alwatr/nanotron/commit/fbb358c1f2867f3bece25e7cb3cc4b18760e4204)) by @AliMD
* Add constructor, default configuration, DefineRouteOption interface, and NanotronApiServerConfig interface to NanotronApiServer ([3af3d82](https://github.com/Alwatr/nanotron/commit/3af3d82db4fc7c8d18767d11254aff52691fe8db)) by @AliMD
* Add default configuration for NanotronApiServer ([19495d0](https://github.com/Alwatr/nanotron/commit/19495d07c0dfb6d5c400ebbbf5beac8aa9236452)) by @AliMD
* Add defineRoute method to NanotronApiServer ([e1448c9](https://github.com/Alwatr/nanotron/commit/e1448c991c8beae0b8f53a283b2439cc0a826603)) by @AliMD
* Add DefineRouteOption interface ([f481ecb](https://github.com/Alwatr/nanotron/commit/f481ecb0e71c2d6d04184394f2403fd4ad376113)) by @AliMD
* Add error handling and request handling to NanotronApiServer ([2fcc6f9](https://github.com/Alwatr/nanotron/commit/2fcc6f943e9f08cd3f83c8d19691b79dbb877ca0)) by @AliMD
* Add error handling for client errors in NanotronApiServer ([f7667d8](https://github.com/Alwatr/nanotron/commit/f7667d82cb7778943e83e041820d95868866de1b)) by @AliMD
* Add error handling for HTTP errors in NanotronApiServer ([2a8a87c](https://github.com/Alwatr/nanotron/commit/2a8a87cb0d1aa5d359daab49f3456b34c8ae7984)) by @AliMD
* Add error handling to handleServerError_ method in NanotronApiServer ([4273478](https://github.com/Alwatr/nanotron/commit/42734788c59dbcac264ea5b75d2a547cac2a33e1)) by @AliMD
* Add getRouteOption_ method to NanotronApiServer ([4eada32](https://github.com/Alwatr/nanotron/commit/4eada3237cbed77709389bf823d8ed8f5c9259d0)) by @AliMD
* Add HttpResponseHeaders interface and ErrorResponse type to type.ts ([03fe655](https://github.com/Alwatr/nanotron/commit/03fe655e5f9c8d965948b20ca0d2f5817f78e0f4)) by @AliMD
* Add HttpResponseHeaders interface to type.ts ([fe971fd](https://github.com/Alwatr/nanotron/commit/fe971fd13a61aee1ee49d3ac2039ca8c5d3cd2d7)) by @AliMD
* Add HttpStatusCode type to const.ts ([44888c3](https://github.com/Alwatr/nanotron/commit/44888c386fe4d943f2bf78b5ec0ad2f80a4269e8)) by @AliMD
* Add HttpStatusCodes object to const.ts ([76436bc](https://github.com/Alwatr/nanotron/commit/76436bcda5a64c249b232cae433eb5c93f32d9e4)) by @AliMD
* Add HttpStatusMessages object to const.ts ([4424261](https://github.com/Alwatr/nanotron/commit/442426170c1cc667a8ac834f4b6d87c28da602ad)) by @AliMD
* Add MatchType type to type.ts ([21fe834](https://github.com/Alwatr/nanotron/commit/21fe83479483e70ac4f52ca83a479732836dcd4e)) by @AliMD
* Add NanotronApiConnection class and import dependencies ([ee952a5](https://github.com/Alwatr/nanotron/commit/ee952a5024b40e8f361c791a60e06714f355a4c6)) by @AliMD
* Add NanotronApiConnectionConfig interface ([995fad1](https://github.com/Alwatr/nanotron/commit/995fad15f92909ee62fb4032e5ad797ac5a45b9f)) by @AliMD
* Add NanotronApiServerConfig interface ([fe94be3](https://github.com/Alwatr/nanotron/commit/fe94be388d7f97b84ee0878595731e6f85886e6e)) by @AliMD
* Add reply method to NanotronApiConnection class ([494173c](https://github.com/Alwatr/nanotron/commit/494173c270c645b244a6611947c3f6e7280b4444)) by @AliMD
* Add replyError method to NanotronApiConnection class ([1489c34](https://github.com/Alwatr/nanotron/commit/1489c3485253db3805ac59ede2ad332191fe45f6)) by @AliMD
* Add replyHeaders property to NanotronApiConnection ([166f308](https://github.com/Alwatr/nanotron/commit/166f3086d94901a37ae2c5326727aaab3c6236bc)) by @AliMD
* Add replyJson method to NanotronApiConnection class ([028e6ef](https://github.com/Alwatr/nanotron/commit/028e6eff04e346fd33e9ebeb65c639a8841dabfa)) by @AliMD
* Add replyJsonError method to NanotronApiConnection class ([5cbb0a7](https://github.com/Alwatr/nanotron/commit/5cbb0a7e444a46d4aec1da469d4b5fe22a81bf97)) by @AliMD
* Add replySent property to NanotronApiConnection class ([ad955c3](https://github.com/Alwatr/nanotron/commit/ad955c397463dad707b56506eeaaecd3fc350f31)) by @AliMD
* Add replyStatusCode property to NanotronApiConnection class ([e92d71c](https://github.com/Alwatr/nanotron/commit/e92d71c71d6485bca56784ae43211f11cbf4cdbf)) by @AliMD
* Add RouteHandler type to type.ts ([0050dc3](https://github.com/Alwatr/nanotron/commit/0050dc3bee94c0d8fc663581f7c801c4782b34ce)) by @AliMD
* Add setRouteOption_ method to NanotronApiServer ([755cb93](https://github.com/Alwatr/nanotron/commit/755cb934d0ddff81e33436c0f787285e7dd378c8)) by @AliMD
* Add standard HTTP methods to const.ts ([eb9cf06](https://github.com/Alwatr/nanotron/commit/eb9cf061e557eac88c5b3fcab4f82ea3fb82ee5b)) by @AliMD
* Add version pattern and logger to NanotronApiConnection ([798af10](https://github.com/Alwatr/nanotron/commit/798af1064cb5a81b819a19b68efbf0aea92d8994)) by @AliMD
* HttpMethod type ([520ac4f](https://github.com/Alwatr/nanotron/commit/520ac4f8965d67023fafdf8dfcc3fde901462fc0)) by @AliMD
* new package for export all nanotron packages ([1c065d2](https://github.com/Alwatr/nanotron/commit/1c065d2c9de1e0a1e4202783c42e42b78a191098)) by @AliMD

### Bug Fixes

* build issue after update package.json ([9df6a58](https://github.com/Alwatr/nanotron/commit/9df6a5866d2b5542e89788f1cf2a1bea5cc369d3)) by @njfamirm

### Code Refactoring

* cleanup old nano-server ([0656967](https://github.com/Alwatr/nanotron/commit/06569674be239cca025e7f48810324aed6c03ede)) by @AliMD
* Import necessary modules and types in api-server.ts ([bd4253f](https://github.com/Alwatr/nanotron/commit/bd4253f4d5f1e7237cbf3a1e4d07e44e628ba2d8)) by @AliMD
* Remove unused 'client-id' header from IncomingHttpHeaders ([43617d8](https://github.com/Alwatr/nanotron/commit/43617d86189055c41a6f326e101a3dff834c8d28)) by @AliMD
* Update import paths for duration parsing ([97dd8aa](https://github.com/Alwatr/nanotron/commit/97dd8aa68e050127e444ef268e48246b6b7318c6)) by @AliMD
* Update import paths for duration parsing and update typescript SDK version to 5.6.2 ([7d8ea97](https://github.com/Alwatr/nanotron/commit/7d8ea97ed8d7741e26d3a609b30e42992d9fb051)) by @AliMD
* Update package description in api-server ([acfda5c](https://github.com/Alwatr/nanotron/commit/acfda5cbab6b764392db07031ab5aae79e42171e)) by @AliMD
* Update package description in api-server ([df4df3f](https://github.com/Alwatr/nanotron/commit/df4df3f9e71dcdca4f9f0b53199bf15fcb41fa5a)) by @AliMD
* Update test script in package.json to pass with no tests ([d215777](https://github.com/Alwatr/nanotron/commit/d2157778829531bce27370fc1626023a3dc7fb13)) by @AliMD

### Miscellaneous Chores

* add required deps ([32b8ade](https://github.com/Alwatr/nanotron/commit/32b8adeba96dbd68879d004fe44f2f2c88b2b624)) by @njfamirm
* cleanup extra packages ([20733c7](https://github.com/Alwatr/nanotron/commit/20733c7bc5335f4110a40a6eb8d6a24a2d940a32)) by @njfamirm
* copy config from nanolib ([3068614](https://github.com/Alwatr/nanotron/commit/30686143c0a85b571a011b02f98f6f8cfe6710b7)) by @njfamirm
* fix upd script ([10f2540](https://github.com/Alwatr/nanotron/commit/10f2540487028f1428c598ae5f485aa6550a3973)) by @AliMD
* rename http-server to nanotron-api-server ([7dd983e](https://github.com/Alwatr/nanotron/commit/7dd983e41e174349549fcdcf02ee202e74aa4453)) by @AliMD
* update .vscode/settings.json ([5dbbd41](https://github.com/Alwatr/nanotron/commit/5dbbd41b023ed60c3440f3b220bc6c3884b154ef)) by @AliMD
* Update lerna.json version to 0.0.0 ([0973e25](https://github.com/Alwatr/nanotron/commit/0973e250264d90f78a546656077830c73b84160d)) by @AliMD
* update package.json ([b411ca5](https://github.com/Alwatr/nanotron/commit/b411ca5514401c5e1a656d988ee51d9243e44dbd)) by @AliMD
* update package.json of each package from nanolib ([b8a7c8a](https://github.com/Alwatr/nanotron/commit/b8a7c8af9f88d36ac3c1ab6324b78890dc2023b3)) by @njfamirm

### Dependencies update

* bump github/codeql-action ([a485ab3](https://github.com/Alwatr/nanotron/commit/a485ab374f281307ac2aa01cf455c7b2baccfdaf)) by @dependabot[bot]
* update ([9af3b8f](https://github.com/Alwatr/nanotron/commit/9af3b8f2b3bfb0a3476d574948895b96f10c2235)) by @AliMD
* update ([f95134f](https://github.com/Alwatr/nanotron/commit/f95134fe5a4b61ee01eb84450807efb9ef099010)) by @AliMD
* update all ([e5242dc](https://github.com/Alwatr/nanotron/commit/e5242dc87799d2c4e64568c3b220881620d114e2)) by @njfamirm
* Update typescript SDK version to 5.6.2 ([edbbf5e](https://github.com/Alwatr/nanotron/commit/edbbf5eb0062a004166e741c2dd2e23e5909e5df)) by @AliMD