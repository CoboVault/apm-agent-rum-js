# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.1.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@cobo/apm-rum@0.1.0...@cobo/apm-rum@1.1.0) (2020-07-01)


### Features

* **dev:** update version number ([b11b607](https://github.com/CoboVault/apm-agent-rum-js/commit/b11b607fac660bb14c55ee6ec166793875113539))
* **dev:** update version number ([fb68760](https://github.com/CoboVault/apm-agent-rum-js/commit/fb68760cfbed2f8b0b38dd87f2c35d7e223a7255))





## [0.1.1](https://github.com/CoboVault/apm-agent-rum-js/compare/@cobo/apm-rum@0.1.0...@cobo/apm-rum@0.1.1) (2020-07-01)

**Note:** Version bump only for package @cobo/apm-rum





# 0.1.0 (2020-06-03)


* BREAKING CHANGE: move IE 10 and Android 4 to unsupported list (#196) ([16f4440](https://github.com/CoboVault/apm-agent-rum-js/commit/16f444062331d8f14e58cc4fa3ad72c9d0e1b35f)), closes [#196](https://github.com/CoboVault/apm-agent-rum-js/issues/196)


### Bug Fixes

* **rum:** add constructor types for ApmBase class ([#562](https://github.com/CoboVault/apm-agent-rum-js/issues/562)) ([273f63f](https://github.com/CoboVault/apm-agent-rum-js/commit/273f63fe3763c5566c45ce02755279ccc7faabb3))
* **rum:** do not polyfill the global Promise variable ([#366](https://github.com/CoboVault/apm-agent-rum-js/issues/366)) ([f5dc95c](https://github.com/CoboVault/apm-agent-rum-js/commit/f5dc95c4c0d69494d706b70af3782ff4b37e6081))
* **rum:** keep page load transaction until load ([#224](https://github.com/CoboVault/apm-agent-rum-js/issues/224)) ([29afb27](https://github.com/CoboVault/apm-agent-rum-js/commit/29afb2745e80007dec957919a9ae783b48eb6dd0))
* **rum:** log unsupported message only on browser environment ([#382](https://github.com/CoboVault/apm-agent-rum-js/issues/382)) ([ff759d1](https://github.com/CoboVault/apm-agent-rum-js/commit/ff759d10caccd82e2fa7d8794a7220d0c1f1293b))
* **rum:** noop for API when agent is inactive ([#569](https://github.com/CoboVault/apm-agent-rum-js/issues/569)) ([77d4f6d](https://github.com/CoboVault/apm-agent-rum-js/commit/77d4f6da20bf113bf803652fd01c8d785eea3722))
* **rum:** publish all packages as transpiled modules ([#432](https://github.com/CoboVault/apm-agent-rum-js/issues/432)) ([1f4ee87](https://github.com/CoboVault/apm-agent-rum-js/commit/1f4ee873429e678f39d23076bead1e6399c49525))
* **rum:** return noop agent when config is inactive ([#239](https://github.com/CoboVault/apm-agent-rum-js/issues/239)) ([7deef2d](https://github.com/CoboVault/apm-agent-rum-js/commit/7deef2d8a6b65c63fc1a268d878d8ba822a7b006))
* **rum:** sync version mumber with latest published version ([#362](https://github.com/CoboVault/apm-agent-rum-js/issues/362)) ([909f480](https://github.com/CoboVault/apm-agent-rum-js/commit/909f480aaae20ad6dfcc4f23108bed32ba33a297))
* **rum-core:** capture all spans as part of page-load transaction ([#273](https://github.com/CoboVault/apm-agent-rum-js/issues/273)) ([0122bf7](https://github.com/CoboVault/apm-agent-rum-js/commit/0122bf71b62e48481833fdae0e2abd0cd79d9c73))
* **rum-core:** export browser responsiveness interval correctly ([#658](https://github.com/CoboVault/apm-agent-rum-js/issues/658)) ([2ecf060](https://github.com/CoboVault/apm-agent-rum-js/commit/2ecf060a35dd1b64110149edc5bbdd4a4613caa9))
* **rum-core:** hardcode agent name and version in service metadata ([#236](https://github.com/CoboVault/apm-agent-rum-js/issues/236)) ([a90337d](https://github.com/CoboVault/apm-agent-rum-js/commit/a90337d949f4606a23b5095d36f7994665135c4d))
* **rum-core:** replace >> in click transaction name with '-' ([#690](https://github.com/CoboVault/apm-agent-rum-js/issues/690)) ([ca43a71](https://github.com/CoboVault/apm-agent-rum-js/commit/ca43a7104a4820b3d880282d32c0509e4190a9d0))
* **rum-core:** schedule xhr invoke task as a macro task ([#480](https://github.com/CoboVault/apm-agent-rum-js/issues/480)) ([d4f181f](https://github.com/CoboVault/apm-agent-rum-js/commit/d4f181fd6c521dd85ec4d5a8abc9b516a75fb269)), closes [#390](https://github.com/CoboVault/apm-agent-rum-js/issues/390)


### Features

* **dev:** changes ([3910f84](https://github.com/CoboVault/apm-agent-rum-js/commit/3910f847fb8f0c6c1d9dfd9c38f88124039e58c6))
* **dev:** modify dependencies ([40be9ae](https://github.com/CoboVault/apm-agent-rum-js/commit/40be9ae64495c6217f307ff8b8b6c1f0e6807bd0))
* **dev:** modify package.json ([e16a74c](https://github.com/CoboVault/apm-agent-rum-js/commit/e16a74cc6a683463ffe5ec3225ef7e19a52e2c95))
* **dev:** modify readme ([882e2b3](https://github.com/CoboVault/apm-agent-rum-js/commit/882e2b361a9786471c195b74871195dd185f1bef))
* **rum:** add typescript typings ([#537](https://github.com/CoboVault/apm-agent-rum-js/issues/537)) ([dc4f391](https://github.com/CoboVault/apm-agent-rum-js/commit/dc4f391fe228a01b7b8e640a73127257a52d5d52))
* **rum:** better log message on invalid configuration ([#216](https://github.com/CoboVault/apm-agent-rum-js/issues/216)) ([b65a806](https://github.com/CoboVault/apm-agent-rum-js/commit/b65a8067994b45100fef7d442c3bcce01d64d5a9))
* **rum:** deprecate addTags in favor of addLabels ([#270](https://github.com/CoboVault/apm-agent-rum-js/issues/270)) ([3e313d3](https://github.com/CoboVault/apm-agent-rum-js/commit/3e313d3adbce1508da5b2d738751fb4b97bfff57))
* **rum-core:** add event listeners for transactions ([#279](https://github.com/CoboVault/apm-agent-rum-js/issues/279)) ([d98f7c7](https://github.com/CoboVault/apm-agent-rum-js/commit/d98f7c7166b605c7fb4b4c97a4389461915672cb))
* **rum-core:** Add task API ([#194](https://github.com/CoboVault/apm-agent-rum-js/issues/194)) ([0153229](https://github.com/CoboVault/apm-agent-rum-js/commit/015322981c1c560420b8838fbb144d10b64c2eda))
* **rum-core:** capture unhandled promise rejection as errors ([#427](https://github.com/CoboVault/apm-agent-rum-js/issues/427)) ([ef34ccc](https://github.com/CoboVault/apm-agent-rum-js/commit/ef34ccc1f8d8784f31d7ee2e5fb9ba9aac3439d4))
* capture click user-interaction transactions ([#604](https://github.com/CoboVault/apm-agent-rum-js/issues/604)) ([30530c1](https://github.com/CoboVault/apm-agent-rum-js/commit/30530c11c4b4ae46ad5fe140f1a15c1f3d240199))
* **rum-core:** improve the debug logs with transaction details ([#469](https://github.com/CoboVault/apm-agent-rum-js/issues/469)) ([b9629b4](https://github.com/CoboVault/apm-agent-rum-js/commit/b9629b450b1eff9b0a53bcaff5a28c9926c61d49))
* **rum-core:** patch history API ([#259](https://github.com/CoboVault/apm-agent-rum-js/issues/259)) ([be58997](https://github.com/CoboVault/apm-agent-rum-js/commit/be58997e1efa212dd0eabdf427fbbff1b9662a43))
* **rum-core:** support rn ([439061b](https://github.com/CoboVault/apm-agent-rum-js/commit/439061b908a8cdc60df8f5b449adf20a0bc8d825))
* **rum-core:** use etag for fetching config ([#439](https://github.com/CoboVault/apm-agent-rum-js/issues/439)) ([bac0e15](https://github.com/CoboVault/apm-agent-rum-js/commit/bac0e15aeccfa84423e102b1b7ea3716ac7826f0))
* **rum-core:** use global promise when available and fallback ([#629](https://github.com/CoboVault/apm-agent-rum-js/issues/629)) ([65f08e0](https://github.com/CoboVault/apm-agent-rum-js/commit/65f08e06d2819a5ba76f476d9a4bc1dfd7fe788b))
* capture http-request transactions ([#517](https://github.com/CoboVault/apm-agent-rum-js/issues/517)) ([27ed994](https://github.com/CoboVault/apm-agent-rum-js/commit/27ed994ea9866e4493015eb3817ab12266f572a5))
* Initial react integration ([#265](https://github.com/CoboVault/apm-agent-rum-js/issues/265)) ([83cbebd](https://github.com/CoboVault/apm-agent-rum-js/commit/83cbebd7f8a0ae12f2b420e9095d4efff8d10d73))
* Introduce managed transaction option ([#440](https://github.com/CoboVault/apm-agent-rum-js/issues/440)) ([a08f210](https://github.com/CoboVault/apm-agent-rum-js/commit/a08f21093735abf578be1de46f03beb89368ef88))
* Support central config management ([#415](https://github.com/CoboVault/apm-agent-rum-js/issues/415)) ([1382cc9](https://github.com/CoboVault/apm-agent-rum-js/commit/1382cc972d6c1b215374b76fe1f965717b6c2fcd))


### Performance Improvements

* **rum:** move to ES6 modules to reduce bundle size ([#237](https://github.com/CoboVault/apm-agent-rum-js/issues/237)) ([7aa4351](https://github.com/CoboVault/apm-agent-rum-js/commit/7aa43513ad75736ae42410cc32ae1a44bc31280c))
* **rum:** remove debug logs on production build ([#245](https://github.com/CoboVault/apm-agent-rum-js/issues/245)) ([2565844](https://github.com/CoboVault/apm-agent-rum-js/commit/2565844febe9596eafe0f9fc07627bb23b0f097e))
* **rum-core:** random number generator using crypto.getRandomValues ([#705](https://github.com/CoboVault/apm-agent-rum-js/issues/705)) ([ce0db92](https://github.com/CoboVault/apm-agent-rum-js/commit/ce0db92d1ba057def0c81595340de4e9e59c4872))
* refactor ServiceFactory to use constant service names ([#764](https://github.com/CoboVault/apm-agent-rum-js/issues/764)) ([fdda235](https://github.com/CoboVault/apm-agent-rum-js/commit/fdda23555b418166727d85f143e84a16079d83e6)), closes [#238](https://github.com/CoboVault/apm-agent-rum-js/issues/238)


### BREAKING CHANGES

* Dropping the support for IE 10 and android 4* versions. Bundling condigurations and testing environments are changed to reflect the same

* parallelize the e2e tests and use single tunnel

* update contributing.md





# [5.4.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@elastic/apm-rum@5.2.0...@elastic/apm-rum@5.4.0) (2020-05-29)


### Features

* **dev:** modify repo config ([c89979e](https://github.com/CoboVault/apm-agent-rum-js/commit/c89979e78c2559d78319c7ecda84dcaef2126062))





# [5.3.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@elastic/apm-rum@5.2.0...@elastic/apm-rum@5.3.0) (2020-05-28)


### Features

* **dev:** modify repo config ([c89979e](https://github.com/CoboVault/apm-agent-rum-js/commit/c89979e78c2559d78319c7ecda84dcaef2126062))





# [5.2.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@5.1.1...@elastic/apm-rum@5.2.0) (2020-05-22)


### Features

* **rum-core:** support rn ([8b210aa](https://github.com/elastic/apm-agent-rum-js/commit/8b210aaa228b4115624b033a459b934ec191d6fc))


### Performance Improvements

* refactor ServiceFactory to use constant service names ([#764](https://github.com/elastic/apm-agent-rum-js/issues/764)) ([fdda235](https://github.com/elastic/apm-agent-rum-js/commit/fdda23555b418166727d85f143e84a16079d83e6)), closes [#238](https://github.com/elastic/apm-agent-rum-js/issues/238)





## [5.1.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@5.1.0...@elastic/apm-rum@5.1.1) (2020-04-15)

**Note:** Version bump only for package @elastic/apm-rum





## [5.1.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@5.0.0...@elastic/apm-rum@5.1.0) (2020-04-08)


### Features

* **rum-core:** end spa navigations after browser frame ([#730](https://github.com/elastic/apm-agent-rum-js/issues/730)) ([5397fa2](https://github.com/elastic/apm-agent-rum-js/commit/5397fa22eb88c080f7a6d07ef5b89dfefc572fb3))


### Performance Improvements

* **rum-core:** random number generator using crypto.getRandomValues ([#705](https://github.com/elastic/apm-agent-rum-js/issues/705)) ([ce0db92](https://github.com/elastic/apm-agent-rum-js/commit/ce0db92d1ba057def0c81595340de4e9e59c4872))





# [5.0.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.9.1...@elastic/apm-rum@5.0.0) (2020-03-18)

**Note:** Version bump only for package @elastic/apm-rum





## [4.9.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.9.0...@elastic/apm-rum@4.9.1) (2020-03-09)


### Bug Fixes

* **rum-core:** replace >> in click transaction name with '-' ([#690](https://github.com/elastic/apm-agent-rum-js/issues/690)) ([ca43a71](https://github.com/elastic/apm-agent-rum-js/commit/ca43a7104a4820b3d880282d32c0509e4190a9d0))





# [4.9.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.8.1...@elastic/apm-rum@4.9.0) (2020-03-03)


### Bug Fixes

* **rum-core:** export browser responsiveness interval correctly ([#658](https://github.com/elastic/apm-agent-rum-js/issues/658)) ([2ecf060](https://github.com/elastic/apm-agent-rum-js/commit/2ecf060a35dd1b64110149edc5bbdd4a4613caa9))


### Features

* **rum-core:** use global promise when available and fallback ([#629](https://github.com/elastic/apm-agent-rum-js/issues/629)) ([65f08e0](https://github.com/elastic/apm-agent-rum-js/commit/65f08e06d2819a5ba76f476d9a4bc1dfd7fe788b))





## [4.8.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.8.0...@elastic/apm-rum@4.8.1) (2020-02-14)

**Note:** Version bump only for package @elastic/apm-rum





# [4.8.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.7.1...@elastic/apm-rum@4.8.0) (2020-02-13)


### Features

* capture click user-interaction transactions ([#604](https://github.com/elastic/apm-agent-rum-js/issues/604)) ([30530c1](https://github.com/elastic/apm-agent-rum-js/commit/30530c11c4b4ae46ad5fe140f1a15c1f3d240199))





## [4.7.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.7.0...@elastic/apm-rum@4.7.1) (2020-01-30)

**Note:** Version bump only for package @elastic/apm-rum





# [4.7.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.6.0...@elastic/apm-rum@4.7.0) (2020-01-15)


### Bug Fixes

* **rum:** add constructor types for ApmBase class ([#562](https://github.com/elastic/apm-agent-rum-js/issues/562)) ([273f63f](https://github.com/elastic/apm-agent-rum-js/commit/273f63fe3763c5566c45ce02755279ccc7faabb3))
* **rum:** noop for API when agent is inactive ([#569](https://github.com/elastic/apm-agent-rum-js/issues/569)) ([77d4f6d](https://github.com/elastic/apm-agent-rum-js/commit/77d4f6da20bf113bf803652fd01c8d785eea3722))


### Features

* **rum:** add typescript typings ([#537](https://github.com/elastic/apm-agent-rum-js/issues/537)) ([dc4f391](https://github.com/elastic/apm-agent-rum-js/commit/dc4f391fe228a01b7b8e640a73127257a52d5d52))
* capture http-request transactions ([#517](https://github.com/elastic/apm-agent-rum-js/issues/517)) ([27ed994](https://github.com/elastic/apm-agent-rum-js/commit/27ed994ea9866e4493015eb3817ab12266f572a5))





# [4.6.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.5.1...@elastic/apm-rum@4.6.0) (2019-11-19)


### Bug Fixes

* **rum-core:** schedule xhr invoke task as a macro task ([#480](https://github.com/elastic/apm-agent-rum-js/issues/480)) ([d4f181f](https://github.com/elastic/apm-agent-rum-js/commit/d4f181f)), closes [#390](https://github.com/elastic/apm-agent-rum-js/issues/390)


### Features

* **rum-core:** improve the debug logs with transaction details ([#469](https://github.com/elastic/apm-agent-rum-js/issues/469)) ([b9629b4](https://github.com/elastic/apm-agent-rum-js/commit/b9629b4))
* **rum-core:** use etag for fetching config ([#439](https://github.com/elastic/apm-agent-rum-js/issues/439)) ([bac0e15](https://github.com/elastic/apm-agent-rum-js/commit/bac0e15))





## [4.5.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.5.0...@elastic/apm-rum@4.5.1) (2019-10-09)

**Note:** Version bump only for package @elastic/apm-rum





# [4.5.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.4.4...@elastic/apm-rum@4.5.0) (2019-09-30)


### Bug Fixes

* **rum:** publish all packages as transpiled modules ([#432](https://github.com/elastic/apm-agent-rum-js/issues/432)) ([1f4ee87](https://github.com/elastic/apm-agent-rum-js/commit/1f4ee87))


### Features

* Introduce managed transaction option ([#440](https://github.com/elastic/apm-agent-rum-js/issues/440)) ([a08f210](https://github.com/elastic/apm-agent-rum-js/commit/a08f210))
* Support central config management ([#415](https://github.com/elastic/apm-agent-rum-js/issues/415)) ([1382cc9](https://github.com/elastic/apm-agent-rum-js/commit/1382cc9))
* **rum-core:** capture unhandled promise rejection as errors ([#427](https://github.com/elastic/apm-agent-rum-js/issues/427)) ([ef34ccc](https://github.com/elastic/apm-agent-rum-js/commit/ef34ccc))





## [4.4.4](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.4.3...@elastic/apm-rum@4.4.4) (2019-09-17)

**Note:** Version bump only for package @elastic/apm-rum





## [4.4.3](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.4.2...@elastic/apm-rum@4.4.3) (2019-09-03)


### Bug Fixes

* **rum:** log unsupported message only on browser environment ([#382](https://github.com/elastic/apm-agent-rum-js/issues/382)) ([ff759d1](https://github.com/elastic/apm-agent-rum-js/commit/ff759d1))





## [4.4.2](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.4.1...@elastic/apm-rum@4.4.2) (2019-08-08)


### Bug Fixes

* **rum:** do not polyfill the global Promise variable ([#366](https://github.com/elastic/apm-agent-rum-js/issues/366)) ([f5dc95c](https://github.com/elastic/apm-agent-rum-js/commit/f5dc95c))





## [4.4.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.4.0...@elastic/apm-rum@4.4.1) (2019-08-05)


### Bug Fixes

* **rum:** sync version number with latest published version ([#362](https://github.com/elastic/apm-agent-rum-js/issues/362)) ([909f480](https://github.com/elastic/apm-agent-rum-js/commit/909f480))





# [4.4.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.3.1...@elastic/apm-rum@4.4.0) (2019-08-05)


### Features

* **rum:** add instrument flag to toggle instrumentations ([#360](https://github.com/elastic/apm-agent-rum-js/issues/360)) ([b7098dd](https://github.com/elastic/apm-agent-rum-js/commit/b7098dd))





## [4.3.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.3.0...@elastic/apm-rum@4.3.1) (2019-07-25)

**Note:** Version bump only for package @elastic/apm-rum





# [4.3.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.1.2...@elastic/apm-rum@4.3.0) (2019-07-11)


### Bug Fixes

* **rum:core:** send labels via context.tags in the payload ([#316](https://github.com/elastic/apm-agent-rum-js/issues/316)) ([526c3e7](https://github.com/elastic/apm-agent-rum-js/commit/526c3e7))


# [4.2.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.1.2...@elastic/apm-rum@4.2.0) (2019-07-08)


### Features

* **rum:** better log message on invalid configuration ([#216](https://github.com/elastic/apm-agent-rum-js/issues/216)) ([b65a806](https://github.com/elastic/apm-agent-rum-js/commit/b65a806))


### Performance Improvements

* **rum:** remove debug logs on production build ([#245](https://github.com/elastic/apm-agent-rum-js/issues/245)) ([2565844](https://github.com/elastic/apm-agent-rum-js/commit/2565844))





## [4.1.2](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.1.1...@elastic/apm-rum@4.1.2) (2019-06-20)

**Note:** Version bump only for package @elastic/apm-rum





## [4.1.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.1.0...@elastic/apm-rum@4.1.1) (2019-06-12)

**Note:** Version bump only for package @elastic/apm-rum





# [4.1.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.0.2...@elastic/apm-rum@4.1.0) (2019-06-12)


### Bug Fixes

* **rum-core:** capture all spans as part of page-load transaction ([#273](https://github.com/elastic/apm-agent-rum-js/issues/273)) ([0122bf7](https://github.com/elastic/apm-agent-rum-js/commit/0122bf7))


### Features

* **rum:** deprecate addTags in favor of addLabels ([#270](https://github.com/elastic/apm-agent-rum-js/issues/270)) ([3e313d3](https://github.com/elastic/apm-agent-rum-js/commit/3e313d3))
* **rum-core:** patch history API ([#259](https://github.com/elastic/apm-agent-rum-js/issues/259)) ([be58997](https://github.com/elastic/apm-agent-rum-js/commit/be58997))





## [4.0.2](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.0.1...@elastic/apm-rum@4.0.2) (2019-05-29)


### Bug Fixes

* **rum:** return noop agent when config is inactive ([#239](https://github.com/elastic/apm-agent-rum-js/issues/239)) ([7deef2d](https://github.com/elastic/apm-agent-rum-js/commit/7deef2d))
* **rum-core:** hardcode agent name and version in service metadata ([#236](https://github.com/elastic/apm-agent-rum-js/issues/236)) ([a90337d](https://github.com/elastic/apm-agent-rum-js/commit/a90337d))


### Performance Improvements

* **rum:** move to ES6 modules to reduce bundle size ([#237](https://github.com/elastic/apm-agent-rum-js/issues/237)) ([7aa4351](https://github.com/elastic/apm-agent-rum-js/commit/7aa4351))





## [4.0.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum@4.0.0...@elastic/apm-rum@4.0.1) (2019-03-21)


### Bug Fixes

* **rum:** keep page load transaction until load ([#224](https://github.com/elastic/apm-agent-rum-js/issues/224)) ([29afb27](https://github.com/elastic/apm-agent-rum-js/commit/29afb27))





# 4.0.0 (2019-03-11)


### Features

* **rum-core:** Add task API ([#194](https://github.com/elastic/apm-agent-rum-js/issues/194)) ([0153229](https://github.com/elastic/apm-agent-rum-js/commit/0153229))

### BREAKING CHANGES

* move IE 10 and Android 4 to unsupported list (#196) ([16f4440](https://github.com/elastic/apm-agent-rum-js/commit/16f4440)), closes [#196](https://github.com/elastic/apm-agent-rum-js/issues/196)
* Rename the final JS bundles (#202) ([68b37d](https://github.com/elastic/apm-agent-rum-js/commit/68b37d))
* resolve main field to source file (#179) ([923405](https://github.com/elastic/apm-agent-rum-js/commit/923405))
