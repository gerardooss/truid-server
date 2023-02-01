# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.2.11](https://github.com/tru-ID/dev-server/compare/v0.2.10...v0.2.11) (2023-02-01)

- Fixed issue where `coverage` scope was not being correctly defined in the `/coverage-access-token` endpoint.
- Fixed a condition in `/examples/subscriber-check`, where if there was a slight latency is the result, it would show as failed even if it had passed.

### [0.2.10](https://github.com/tru-ID/dev-server/compare/v0.2.9...v0.2.10) (2023-01-24)

- Added `/coverage-access-token` endpoint, which allows applications to request an access token with just the `coverage` scope. This is used to request a reachability request through an authenticated method.
- Removed `/my-ip` endpoint, no longer neccessary
- Small changes/tidied up the landing page of the examples section

### [0.2.9](https://github.com/tru-ID/dev-server/compare/v0.2.8...v0.2.9) (2022-11-24)

- Included SubscriberCheck v0.1 and v0.2 demos within `/public/examples` directory

### [0.2.8](https://github.com/tru-ID/dev-server/compare/v0.2.1...v0.2.8) (2022-07-22)

- Updated mobile-web-v2 example to use PhoneCheck v0.2 functionality within web-sdk.

### [0.2.7](https://github.com/tru-ID/dev-server/compare/v0.2.1...v0.2.7) (2022-06-07)

- Updated README to contain instructions for PhoneCheck v0.2 functionality (redirect_url)

### [0.2.6](https://github.com/tru-ID/dev-server/compare/v0.2.1...v0.2.6) (2022-05-16)

- Added "mobile-web-v2" example code to demonstrate PhoneCheck v0.2 functionality

### [0.2.5](https://github.com/tru-ID/dev-server/compare/v0.2.4...v0.2.5) (2022-01-14)

- Updated error handling on mobile-web example
- Updated legacy URLs of GitHub Repository

### [0.2.4](https://github.com/tru-ID/dev-server/compare/v0.2.3...v0.2.4) (2021-12-03)

- Added deploying `dev-server` to cloud to improve getting started options.

### [0.2.2](https://github.com/tru-ID/dev-server/compare/v0.2.1...v0.2.2) (2021-06-01)

- Updated packages, added linting and formatting

### [0.1.9](https://github.com/tru-ID/dev-server/compare/v0.1.8...v0.1.9) (2021-04-26)

### Bug Fixes

- change required Node.js version from 15.x. to >=12.0.0
- remove req.form.phone_number in /sim-check ([73827b8](https://github.com/tru-ID/dev-server/commit/73827b85721ad7c1650e8a1ac2191b56a24ee36a))

### [0.1.8](https://github.com/tru-ID/dev-server/compare/v0.1.7...v0.1.8) (2021-03-11)

### Bug Fixes

- Adding SubscriberCheck endpoints back that were lost in the v0.1.7 release.

### Features

- adding SubscriberCheck endpoints ([545c6a6](https://github.com/tru-ID/dev-server/commit/545c6a670e4c4147b7c34f06c2ddbe0cf34bff1d))

### [0.1.7](https://github.com/tru-ID/dev-server/compare/v0.1.6...v0.1.7) (2021-03-11)

### Features

- add /my-ip to get the IP address of the device making the request to the endpoint ([e1d76b7](https://github.com/tru-ID/dev-server/commit/e1d76b761a5da6028777cc534363d57a0fa90d01))

### Bug Fixes

- **routes:** config.API_BASE_URL -> config.apiBaseUrl ([985e7fc](https://github.com/tru-ID/dev-server/commit/985e7fccd5fb99aed7e6cf4dcea87f9859912ef1))

### [0.1.6](https://github.com/tru-ID/dev-server/compare/v0.1.5...v0.1.6) (2021-02-27)

### Features

- adding SubscriberCheck endpoints ([1203584](https://github.com/tru-ID/dev-server/commit/1203584f836f48f53e36755aefb84abe665705fb))

### [0.1.5](https://github.com/tru-ID/dev-server/compare/v0.1.4...v0.1.5) (2021-02-26)

### Bug Fixes

- loading project configuration from file ([15f4fa3](https://github.com/tru-ID/dev-server/commit/15f4fa3d6da37ebc012b1227e88d6df2a751c499))
- pass configuration to the tru API module ([775dc85](https://github.com/tru-ID/dev-server/commit/775dc85e4f750cf1f0297e884bc988db03a58212))
- routes should set status before calling send ([51669b2](https://github.com/tru-ID/dev-server/commit/51669b21dc5c1eba089852c2dcb23d25e5d1e314))

### [0.1.4](https://github.com/tru-ID/dev-server/compare/v0.1.3...v0.1.4) (2021-02-05)

### Bug Fixes

- remove 'files' from package ([9438255](https://github.com/tru-ID/dev-server/commit/943825553a4a78d40bf4c78af4be2c052d3d1a14))

### [0.1.3](https://github.com/tru-ID/dev-server/compare/v0.1.2...v0.1.3) (2021-02-05)

### Bug Fixes

- include "public" in published build ([796d07a](https://github.com/tru-ID/dev-server/commit/796d07a379ecd35a1f4a134ad112bdd5d99c64a6))

### [0.1.2](https://github.com/tru-ID/dev-server/compare/v0.1.1...v0.1.2) (2021-02-05)

### Features

- improving config handling ([ceef120](https://github.com/tru-ID/dev-server/commit/ceef120652e31b8287d43de368bb7611677c4f3c))

### Bug Fixes

- ensure path to static folder is correct ([baffd35](https://github.com/tru-ID/dev-server/commit/baffd3515a235f9f103d2557af6e5fc115d50e20))

### 0.1.1 (2021-02-03)

### Features

- expose as `serve` module for reuse ([5399377](https://github.com/tru-ID/dev-server/commit/53993771092a379c478e0dea42bf40cd5902f593))
- add localtunnel.me support ([2edce2c](https://github.com/tru-ID/dev-server/commit/2edce2c5a77719c5ebb2c1184cdeb8f8aa2afc8b))

### 0.1.0

### Features

- add SIMCheck example ([dbdd64d](https://github.com/tru-ID/dev-server/commit/dbdd64d14d46ee1104df652769179ecf7c3bba27))
- add support for basic password protection ([a81d4dd](https://github.com/tru-ID/dev-server/commit/a81d4ddbc5fb42deb56ac2d23dd5abc26c22129a))
- add support for tru.ID project config in env vars ([a377288](https://github.com/tru-ID/dev-server/commit/a3772888b3ecbb1327d32abee287855be0b56579))
- adding Phone Check callback handling example ([b6e8dff](https://github.com/tru-ID/dev-server/commit/b6e8dffe91943d358425f9bbadde049222349cb0))
- coverage + PhoneCheck mobile web example ([924d392](https://github.com/tru-ID/dev-server/commit/924d39290225ce6f496d244a52c498d7948946c0))
- update to use truID SDK for the web from CDN ([bde96ec](https://github.com/tru-ID/dev-server/commit/bde96ec720583e92c8dc8c4a7f7239154e00bcac))
