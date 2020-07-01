# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [0.2.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@cobo/apm-rum-react@0.1.0...@cobo/apm-rum-react@0.2.0) (2020-07-01)


### Features

* **dev:** update version number ([62a66f0](https://github.com/CoboVault/apm-agent-rum-js/commit/62a66f0721103001511eb1a02e6e2e12164d077a))





## [0.1.1](https://github.com/CoboVault/apm-agent-rum-js/compare/@cobo/apm-rum-react@0.1.0...@cobo/apm-rum-react@0.1.1) (2020-07-01)

**Note:** Version bump only for package @cobo/apm-rum-react





# 0.1.0 (2020-06-03)


### Bug Fixes

* **rum:** publish all packages as transpiled modules ([#432](https://github.com/CoboVault/apm-agent-rum-js/issues/432)) ([1f4ee87](https://github.com/CoboVault/apm-agent-rum-js/commit/1f4ee873429e678f39d23076bead1e6399c49525))
* **rum-react:** avoid rerendering on query param changes ([#748](https://github.com/CoboVault/apm-agent-rum-js/issues/748)) ([6a4ab16](https://github.com/CoboVault/apm-agent-rum-js/commit/6a4ab16e283dbed89d05327a6ad068360857e2cb))
* **rum-react:** capture network requests inside useEffect hook ([#353](https://github.com/CoboVault/apm-agent-rum-js/issues/353)) ([ae25200](https://github.com/CoboVault/apm-agent-rum-js/commit/ae25200642c1eeb5dcd629b0219513deacf14d6b))
* **rum-react:** check component in withTransaction ([#328](https://github.com/CoboVault/apm-agent-rum-js/issues/328)) ([e348874](https://github.com/CoboVault/apm-agent-rum-js/commit/e348874feb128be347814b93b3d654e9c76b92c5))
* **rum-react:** create transaction only on component mount ([#419](https://github.com/CoboVault/apm-agent-rum-js/issues/419)) ([a290448](https://github.com/CoboVault/apm-agent-rum-js/commit/a290448fc331126c8d036d5184297d79f415d352))
* **rum-react:** render the correct component when using ApmRoute with Switch ([#342](https://github.com/CoboVault/apm-agent-rum-js/issues/342)) ([0b3f0a0](https://github.com/CoboVault/apm-agent-rum-js/commit/0b3f0a050b2ee4b7b122748bce9e4b1956494d65))
* **rum-react:** respect active flag in react integration ([#392](https://github.com/CoboVault/apm-agent-rum-js/issues/392)) ([6d7e9db](https://github.com/CoboVault/apm-agent-rum-js/commit/6d7e9db80e8e4f284e88cbd8160b70f5f29581cf))


### Features

* **rum-core:** use global promise when available and fallback ([#629](https://github.com/CoboVault/apm-agent-rum-js/issues/629)) ([65f08e0](https://github.com/CoboVault/apm-agent-rum-js/commit/65f08e06d2819a5ba76f476d9a4bc1dfd7fe788b))
* Initial react integration ([#265](https://github.com/CoboVault/apm-agent-rum-js/issues/265)) ([83cbebd](https://github.com/CoboVault/apm-agent-rum-js/commit/83cbebd7f8a0ae12f2b420e9095d4efff8d10d73))
* **dev:** changes ([3910f84](https://github.com/CoboVault/apm-agent-rum-js/commit/3910f847fb8f0c6c1d9dfd9c38f88124039e58c6))
* Introduce managed transaction option ([#440](https://github.com/CoboVault/apm-agent-rum-js/issues/440)) ([a08f210](https://github.com/CoboVault/apm-agent-rum-js/commit/a08f21093735abf578be1de46f03beb89368ef88))
* Support central config management ([#415](https://github.com/CoboVault/apm-agent-rum-js/issues/415)) ([1382cc9](https://github.com/CoboVault/apm-agent-rum-js/commit/1382cc972d6c1b215374b76fe1f965717b6c2fcd))
* **dev:** modify dependencies ([40be9ae](https://github.com/CoboVault/apm-agent-rum-js/commit/40be9ae64495c6217f307ff8b8b6c1f0e6807bd0))
* **dev:** modify package.json ([e16a74c](https://github.com/CoboVault/apm-agent-rum-js/commit/e16a74cc6a683463ffe5ec3225ef7e19a52e2c95))
* **dev:** modify readme ([882e2b3](https://github.com/CoboVault/apm-agent-rum-js/commit/882e2b361a9786471c195b74871195dd185f1bef))
* **rum-core:** capture resource and user timing spans for soft navigation ([#423](https://github.com/CoboVault/apm-agent-rum-js/issues/423)) ([d461ae5](https://github.com/CoboVault/apm-agent-rum-js/commit/d461ae5ca17104957e9e62fc4b72a3e847f43fa3))
* **rum-core:** end spa navigations after browser frame ([#730](https://github.com/CoboVault/apm-agent-rum-js/issues/730)) ([5397fa2](https://github.com/CoboVault/apm-agent-rum-js/commit/5397fa22eb88c080f7a6d07ef5b89dfefc572fb3))
* **rum-core:** support rn ([439061b](https://github.com/CoboVault/apm-agent-rum-js/commit/439061b908a8cdc60df8f5b449adf20a0bc8d825))
* **rum-react:** publish traspiled react elements as es modules ([#356](https://github.com/CoboVault/apm-agent-rum-js/issues/356)) ([7c651c7](https://github.com/CoboVault/apm-agent-rum-js/commit/7c651c7d4d6a12bf04872480e7c56876bba1d109))


### Performance Improvements

* **rum-core:** random number generator using crypto.getRandomValues ([#705](https://github.com/CoboVault/apm-agent-rum-js/issues/705)) ([ce0db92](https://github.com/CoboVault/apm-agent-rum-js/commit/ce0db92d1ba057def0c81595340de4e9e59c4872))
* refactor ServiceFactory to use constant service names ([#764](https://github.com/CoboVault/apm-agent-rum-js/issues/764)) ([fdda235](https://github.com/CoboVault/apm-agent-rum-js/commit/fdda23555b418166727d85f143e84a16079d83e6)), closes [#238](https://github.com/CoboVault/apm-agent-rum-js/issues/238)





# [1.4.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@elastic/apm-rum-react@1.2.0...@elastic/apm-rum-react@1.4.0) (2020-05-29)


### Features

* **dev:** modify repo config ([c89979e](https://github.com/CoboVault/apm-agent-rum-js/commit/c89979e78c2559d78319c7ecda84dcaef2126062))





# [1.3.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@elastic/apm-rum-react@1.2.0...@elastic/apm-rum-react@1.3.0) (2020-05-28)


### Features

* **dev:** modify repo config ([c89979e](https://github.com/CoboVault/apm-agent-rum-js/commit/c89979e78c2559d78319c7ecda84dcaef2126062))





# [1.2.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@1.1.1...@elastic/apm-rum-react@1.2.0) (2020-05-22)


### Features

* **rum-core:** support rn ([8b210aa](https://github.com/elastic/apm-agent-rum-js/commit/8b210aaa228b4115624b033a459b934ec191d6fc))


### Performance Improvements

* refactor ServiceFactory to use constant service names ([#764](https://github.com/elastic/apm-agent-rum-js/issues/764)) ([fdda235](https://github.com/elastic/apm-agent-rum-js/commit/fdda23555b418166727d85f143e84a16079d83e6)), closes [#238](https://github.com/elastic/apm-agent-rum-js/issues/238)





## [1.1.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@1.1.0...@elastic/apm-rum-react@1.1.1) (2020-04-15)


### Bug Fixes

* **rum-react:** avoid rerendering on query param changes ([#748](https://github.com/elastic/apm-agent-rum-js/issues/748)) ([6a4ab16](https://github.com/elastic/apm-agent-rum-js/commit/6a4ab16e283dbed89d05327a6ad068360857e2cb))





# [1.1.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@1.0.0...@elastic/apm-rum-react@1.1.0) (2020-04-08)


### Features

* **rum-core:** end spa navigations after browser frame ([#730](https://github.com/elastic/apm-agent-rum-js/issues/730)) ([5397fa2](https://github.com/elastic/apm-agent-rum-js/commit/5397fa22eb88c080f7a6d07ef5b89dfefc572fb3))


### Performance Improvements

* **rum-core:** random number generator using crypto.getRandomValues ([#705](https://github.com/elastic/apm-agent-rum-js/issues/705)) ([ce0db92](https://github.com/elastic/apm-agent-rum-js/commit/ce0db92d1ba057def0c81595340de4e9e59c4872))





# [1.0.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.4.1...@elastic/apm-rum-react@1.0.0) (2020-03-18)

**Note:** Version bump only for package @elastic/apm-rum-react





## [0.4.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.4.0...@elastic/apm-rum-react@0.4.1) (2020-03-09)

**Note:** Version bump only for package @elastic/apm-rum-react





# [0.4.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.3.6...@elastic/apm-rum-react@0.4.0) (2020-03-03)


### Features

* **rum-core:** use global promise when available and fallback ([#629](https://github.com/elastic/apm-agent-rum-js/issues/629)) ([65f08e0](https://github.com/elastic/apm-agent-rum-js/commit/65f08e06d2819a5ba76f476d9a4bc1dfd7fe788b))





## [0.3.6](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.3.5...@elastic/apm-rum-react@0.3.6) (2020-02-14)

**Note:** Version bump only for package @elastic/apm-rum-react





## [0.3.5](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.3.4...@elastic/apm-rum-react@0.3.5) (2020-02-13)

**Note:** Version bump only for package @elastic/apm-rum-react





## [0.3.4](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.3.3...@elastic/apm-rum-react@0.3.4) (2020-01-30)

**Note:** Version bump only for package @elastic/apm-rum-react





## [0.3.3](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.3.2...@elastic/apm-rum-react@0.3.3) (2020-01-15)

**Note:** Version bump only for package @elastic/apm-rum-react





## [0.3.2](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.3.1...@elastic/apm-rum-react@0.3.2) (2019-11-19)

**Note:** Version bump only for package @elastic/apm-rum-react





## [0.3.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.3.0...@elastic/apm-rum-react@0.3.1) (2019-10-09)

**Note:** Version bump only for package @elastic/apm-rum-react





# [0.3.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.2.4...@elastic/apm-rum-react@0.3.0) (2019-09-30)


### Bug Fixes

* **rum:** publish all packages as transpiled modules ([#432](https://github.com/elastic/apm-agent-rum-js/issues/432)) ([1f4ee87](https://github.com/elastic/apm-agent-rum-js/commit/1f4ee87))


### Features

* **rum-core:** capture resource and user timing spans for soft navigation ([#423](https://github.com/elastic/apm-agent-rum-js/issues/423)) ([d461ae5](https://github.com/elastic/apm-agent-rum-js/commit/d461ae5))
* Introduce managed transaction option ([#440](https://github.com/elastic/apm-agent-rum-js/issues/440)) ([a08f210](https://github.com/elastic/apm-agent-rum-js/commit/a08f210))
* Support central config management ([#415](https://github.com/elastic/apm-agent-rum-js/issues/415)) ([1382cc9](https://github.com/elastic/apm-agent-rum-js/commit/1382cc9))





## [0.2.4](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.2.3...@elastic/apm-rum-react@0.2.4) (2019-09-17)


### Bug Fixes

* **rum-react:** create transaction only on component mount ([#419](https://github.com/elastic/apm-agent-rum-js/issues/419)) ([a290448](https://github.com/elastic/apm-agent-rum-js/commit/a290448))





## [0.2.3](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.2.2...@elastic/apm-rum-react@0.2.3) (2019-09-03)


### Bug Fixes

* **rum-react:** respect active flag in react integration ([#392](https://github.com/elastic/apm-agent-rum-js/issues/392)) ([6d7e9db](https://github.com/elastic/apm-agent-rum-js/commit/6d7e9db))





## [0.2.2](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.2.1...@elastic/apm-rum-react@0.2.2) (2019-08-08)

**Note:** Version bump only for package @elastic/apm-rum-react





## [0.2.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.2.0...@elastic/apm-rum-react@0.2.1) (2019-08-05)

**Note:** Version bump only for package @elastic/apm-rum-react





# [0.2.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.1.1...@elastic/apm-rum-react@0.2.0) (2019-08-05)


### Bug Fixes

* **rum-react:** capture network requests inside useEffect hook ([#353](https://github.com/elastic/apm-agent-rum-js/issues/353)) ([ae25200](https://github.com/elastic/apm-agent-rum-js/commit/ae25200))


### Features

* **rum-react:** publish transpiled react elements as es modules ([#356](https://github.com/elastic/apm-agent-rum-js/issues/356)) ([7c651c7](https://github.com/elastic/apm-agent-rum-js/commit/7c651c7))





## [0.1.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-react@0.1.0...@elastic/apm-rum-react@0.1.1) (2019-07-25)


### Bug Fixes

* **rum-react:** check component in withTransaction ([#328](https://github.com/elastic/apm-agent-rum-js/issues/328)) ([e348874](https://github.com/elastic/apm-agent-rum-js/commit/e348874))
* **rum-react:** render the correct component when using ApmRoute with Switch ([#342](https://github.com/elastic/apm-agent-rum-js/issues/342)) ([0b3f0a0](https://github.com/elastic/apm-agent-rum-js/commit/0b3f0a0))





# 0.1.0 (2019-07-11)


### Features

* Initial react integration ([#265](https://github.com/elastic/apm-agent-rum-js/issues/265)) ([83cbebd](https://github.com/elastic/apm-agent-rum-js/commit/83cbebd))
