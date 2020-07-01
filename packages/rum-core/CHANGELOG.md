# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.1.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@cobo/apm-rum-core@0.1.0...@cobo/apm-rum-core@1.1.0) (2020-07-01)


### Features

* **dev:** fix document issue ([0f30747](https://github.com/CoboVault/apm-agent-rum-js/commit/0f30747a4e9b69a468ef0b52519bcbbb79146823))
* **dev:** update version number ([b11b607](https://github.com/CoboVault/apm-agent-rum-js/commit/b11b607fac660bb14c55ee6ec166793875113539))
* **dev:** update version number ([fb68760](https://github.com/CoboVault/apm-agent-rum-js/commit/fb68760cfbed2f8b0b38dd87f2c35d7e223a7255))





# [0.2.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@cobo/apm-rum-core@0.1.0...@cobo/apm-rum-core@0.2.0) (2020-07-01)


### Features

* **dev:** fix document issue ([0f30747](https://github.com/CoboVault/apm-agent-rum-js/commit/0f30747a4e9b69a468ef0b52519bcbbb79146823))





# 0.1.0 (2020-06-03)


* BREAKING CHANGE: tags are not added to individual events (#700) ([e968c54](https://github.com/CoboVault/apm-agent-rum-js/commit/e968c54fb55bece8176e4663bfcf842ccef3244f)), closes [#700](https://github.com/CoboVault/apm-agent-rum-js/issues/700)
* BREAKING CHANGE: add support for boolean and number values in addLabels (#697) ([4533b67](https://github.com/CoboVault/apm-agent-rum-js/commit/4533b67b658943a1370eeaf90a64f866cd271269)), closes [#697](https://github.com/CoboVault/apm-agent-rum-js/issues/697)
* BREAKING CHANGE: move IE 10 and Android 4 to unsupported list (#196) ([16f4440](https://github.com/CoboVault/apm-agent-rum-js/commit/16f444062331d8f14e58cc4fa3ad72c9d0e1b35f)), closes [#196](https://github.com/CoboVault/apm-agent-rum-js/issues/196)


### Bug Fixes

* **rum:** do not polyfill the global Promise variable ([#366](https://github.com/CoboVault/apm-agent-rum-js/issues/366)) ([f5dc95c](https://github.com/CoboVault/apm-agent-rum-js/commit/f5dc95c4c0d69494d706b70af3782ff4b37e6081))
* **rum:** publish all packages as transpiled modules ([#432](https://github.com/CoboVault/apm-agent-rum-js/issues/432)) ([1f4ee87](https://github.com/CoboVault/apm-agent-rum-js/commit/1f4ee873429e678f39d23076bead1e6399c49525))
* **rum:** return noop agent when config is inactive ([#239](https://github.com/CoboVault/apm-agent-rum-js/issues/239)) ([7deef2d](https://github.com/CoboVault/apm-agent-rum-js/commit/7deef2d8a6b65c63fc1a268d878d8ba822a7b006))
* **rum-core:** add error properties to custom context by default ([#586](https://github.com/CoboVault/apm-agent-rum-js/issues/586)) ([15ef0b6](https://github.com/CoboVault/apm-agent-rum-js/commit/15ef0b623da844ab05886b2a5d61fdf3dc383d1b))
* **rum-core:** add subtype span info without camelcasing ([#753](https://github.com/CoboVault/apm-agent-rum-js/issues/753)) ([8b97075](https://github.com/CoboVault/apm-agent-rum-js/commit/8b9707561f20ceb44caeb8ab6f6cf6cfe97e4f40))
* **rum-core:** apply truncation on keyword fields in payload ([#241](https://github.com/CoboVault/apm-agent-rum-js/issues/241)) ([8a3927b](https://github.com/CoboVault/apm-agent-rum-js/commit/8a3927b8405138837c9d3bdc2d668f2f62f293b9))
* **rum-core:** avoid creating multiple transactions in startTransaction ([#296](https://github.com/CoboVault/apm-agent-rum-js/issues/296)) ([70c3fb4](https://github.com/CoboVault/apm-agent-rum-js/commit/70c3fb4504ef8b212d1ee09e04ebeca68440ea42))
* **rum-core:** capture all spans as part of page-load transaction ([#273](https://github.com/CoboVault/apm-agent-rum-js/issues/273)) ([0122bf7](https://github.com/CoboVault/apm-agent-rum-js/commit/0122bf71b62e48481833fdae0e2abd0cd79d9c73))
* **rum-core:** Check if first-contentful-paint exists before setting the agent marks ([#681](https://github.com/CoboVault/apm-agent-rum-js/issues/681)) ([a2298f7](https://github.com/CoboVault/apm-agent-rum-js/commit/a2298f723a1d774e6d099c6fe811b8344deb8287)), closes [#680](https://github.com/CoboVault/apm-agent-rum-js/issues/680) [elastic/apm-agent-rum-js#680](https://github.com/elastic/apm-agent-rum-js/issues/680) [#680](https://github.com/CoboVault/apm-agent-rum-js/issues/680) [#680](https://github.com/CoboVault/apm-agent-rum-js/issues/680)
* **rum-core:** check ignoreTransactions config value ([#337](https://github.com/CoboVault/apm-agent-rum-js/issues/337)) ([aff6bc8](https://github.com/CoboVault/apm-agent-rum-js/commit/aff6bc8de773777ed83597842bff1d9dda1b1633))
* **rum-core:** create temporary transaction on startSpan ([#533](https://github.com/CoboVault/apm-agent-rum-js/issues/533)) ([8c951d2](https://github.com/CoboVault/apm-agent-rum-js/commit/8c951d2fb52c1fe61aa90be2cd3ecca3fe6cff1b))
* **rum-core:** do not capture timing spans for unsampled transactions ([#590](https://github.com/CoboVault/apm-agent-rum-js/issues/590)) ([88b61ec](https://github.com/CoboVault/apm-agent-rum-js/commit/88b61ec98a328eb84ed87023b219c8eeb0f6b462))
* **rum-core:** ensure context metadata is shallow merged on transaction ([#453](https://github.com/CoboVault/apm-agent-rum-js/issues/453)) ([30b954e](https://github.com/CoboVault/apm-agent-rum-js/commit/30b954e02fdf3ec54ef19bb3369bd1af2bfdb750))
* **rum-core:** export browser responsiveness interval correctly ([#658](https://github.com/CoboVault/apm-agent-rum-js/issues/658)) ([2ecf060](https://github.com/CoboVault/apm-agent-rum-js/commit/2ecf060a35dd1b64110149edc5bbdd4a4613caa9))
* **rum-core:** filter API calls from resource spans ([#724](https://github.com/CoboVault/apm-agent-rum-js/issues/724)) ([15dba46](https://github.com/CoboVault/apm-agent-rum-js/commit/15dba464f0e4db1268b1fecbe4f4bf83b0b38c54))
* **rum-core:** fix custom marks for page-load ([#225](https://github.com/CoboVault/apm-agent-rum-js/issues/225)) ([6cd392a](https://github.com/CoboVault/apm-agent-rum-js/commit/6cd392ac39eb6eb061f82b0c29d5f45ff340a5db)), closes [#221](https://github.com/CoboVault/apm-agent-rum-js/issues/221)
* **rum-core:** handle error when `performance` is not available ([#708](https://github.com/CoboVault/apm-agent-rum-js/issues/708)) ([bb1740a](https://github.com/CoboVault/apm-agent-rum-js/commit/bb1740a20c65a5ce7649a122d1e27deeb97ed994))
* **rum-core:** handle relative urls without slash properly ([#446](https://github.com/CoboVault/apm-agent-rum-js/issues/446)) ([288e8b1](https://github.com/CoboVault/apm-agent-rum-js/commit/288e8b100c38dc7d7e78e5851e9699112f750d4c))
* **rum-core:** handle script error events properly ([#418](https://github.com/CoboVault/apm-agent-rum-js/issues/418)) ([c862ab7](https://github.com/CoboVault/apm-agent-rum-js/commit/c862ab78aea3fda24bcd2d6c4008bd75f28555cb))
* **rum-core:** hardcode agent name and version in service metadata ([#236](https://github.com/CoboVault/apm-agent-rum-js/issues/236)) ([a90337d](https://github.com/CoboVault/apm-agent-rum-js/commit/a90337d949f4606a23b5095d36f7994665135c4d))
* **rum-core:** in truncate check for empty values ([#256](https://github.com/CoboVault/apm-agent-rum-js/issues/256)) ([cccb172](https://github.com/CoboVault/apm-agent-rum-js/commit/cccb1721c4fe188cb82f49b8f7b5fea37ed35cdb))
* **rum-core:** Only capture events on Elements ([#625](https://github.com/CoboVault/apm-agent-rum-js/issues/625)) ([133a3f4](https://github.com/CoboVault/apm-agent-rum-js/commit/133a3f4cc4b44074a80e147d47de53b896f2967e))
* **rum-core:** remove sensitive info from span context ([#274](https://github.com/CoboVault/apm-agent-rum-js/issues/274)) ([b073f7f](https://github.com/CoboVault/apm-agent-rum-js/commit/b073f7f7a4c2ffdc248b8c5d6eff5a13c5eb0afd))
* **rum-core:** replace >> in click transaction name with '-' ([#690](https://github.com/CoboVault/apm-agent-rum-js/issues/690)) ([ca43a71](https://github.com/CoboVault/apm-agent-rum-js/commit/ca43a7104a4820b3d880282d32c0509e4190a9d0))
* **rum-core:** schedule xhr invoke task as a macro task ([#480](https://github.com/CoboVault/apm-agent-rum-js/issues/480)) ([d4f181f](https://github.com/CoboVault/apm-agent-rum-js/commit/d4f181fd6c521dd85ec4d5a8abc9b516a75fb269)), closes [#390](https://github.com/CoboVault/apm-agent-rum-js/issues/390)
* add transaction type redefine order ([#535](https://github.com/CoboVault/apm-agent-rum-js/issues/535)) ([9e0b311](https://github.com/CoboVault/apm-agent-rum-js/commit/9e0b311b20f2db0f00702eb5a8389c67dd4628fe))
* **rum-core:** transaction onstart hook must be consistent ([#585](https://github.com/CoboVault/apm-agent-rum-js/issues/585)) ([dd792d1](https://github.com/CoboVault/apm-agent-rum-js/commit/dd792d167a13c072e8870c3ea29efdae015fe9d4))
* **rum-core:** treat truncated spans as actual in breakdown ([#777](https://github.com/CoboVault/apm-agent-rum-js/issues/777)) ([93d8fc2](https://github.com/CoboVault/apm-agent-rum-js/commit/93d8fc2ff1b506aeeb7e4f6b7268f065922c21cc))
* **rum-core:** use rum endpoint for central config ([#489](https://github.com/CoboVault/apm-agent-rum-js/issues/489)) ([43ce47e](https://github.com/CoboVault/apm-agent-rum-js/commit/43ce47e35859e7057935de574e79bfa872da9856))
* **rum-react:** reduce transaction reusability threshold to 5 seconds ([#354](https://github.com/CoboVault/apm-agent-rum-js/issues/354)) ([dd32e41](https://github.com/CoboVault/apm-agent-rum-js/commit/dd32e41b06e7b763e81b02f5f53bddcf6ef5a725))
* **rum:core:** send labels via context.tags in the payload ([#316](https://github.com/CoboVault/apm-agent-rum-js/issues/316)) ([526c3e7](https://github.com/CoboVault/apm-agent-rum-js/commit/526c3e7bf0eaaaf401dad78230b20d77416268cc))
* pass correct properties to payload filters ([#616](https://github.com/CoboVault/apm-agent-rum-js/issues/616)) ([44d6740](https://github.com/CoboVault/apm-agent-rum-js/commit/44d674064dd1b7b992c7bf22fe82fb9cc48582da))


### Features

* **dev:** changes ([3910f84](https://github.com/CoboVault/apm-agent-rum-js/commit/3910f847fb8f0c6c1d9dfd9c38f88124039e58c6))
* **dev:** modify dependencies ([40be9ae](https://github.com/CoboVault/apm-agent-rum-js/commit/40be9ae64495c6217f307ff8b8b6c1f0e6807bd0))
* **dev:** modify package.json ([e16a74c](https://github.com/CoboVault/apm-agent-rum-js/commit/e16a74cc6a683463ffe5ec3225ef7e19a52e2c95))
* **dev:** modify readme ([882e2b3](https://github.com/CoboVault/apm-agent-rum-js/commit/882e2b361a9786471c195b74871195dd185f1bef))
* **rum:** better log message on invalid configuration ([#216](https://github.com/CoboVault/apm-agent-rum-js/issues/216)) ([b65a806](https://github.com/CoboVault/apm-agent-rum-js/commit/b65a8067994b45100fef7d442c3bcce01d64d5a9))
* **rum:** deprecate addTags in favor of addLabels ([#270](https://github.com/CoboVault/apm-agent-rum-js/issues/270)) ([3e313d3](https://github.com/CoboVault/apm-agent-rum-js/commit/3e313d3adbce1508da5b2d738751fb4b97bfff57))
* **rum-core:** add config option to monitor longtasks ([#600](https://github.com/CoboVault/apm-agent-rum-js/issues/600)) ([34b4fb3](https://github.com/CoboVault/apm-agent-rum-js/commit/34b4fb300d47833acfaccbd6b07d155d299b2b6e))
* **rum-core:** add event listeners for transactions ([#279](https://github.com/CoboVault/apm-agent-rum-js/issues/279)) ([d98f7c7](https://github.com/CoboVault/apm-agent-rum-js/commit/d98f7c7166b605c7fb4b4c97a4389461915672cb))
* **rum-core:** add EventTarget patch ([#588](https://github.com/CoboVault/apm-agent-rum-js/issues/588)) ([755bab4](https://github.com/CoboVault/apm-agent-rum-js/commit/755bab4124c0c7928071434901ddf642b43387a2))
* **rum-core:** add service env to metadata payload ([#198](https://github.com/CoboVault/apm-agent-rum-js/issues/198)) ([adc038b](https://github.com/CoboVault/apm-agent-rum-js/commit/adc038b1eed28ad59f88ed86bba9ec044f6310af))
* **rum-core:** add size & server timing information to traces ([#206](https://github.com/CoboVault/apm-agent-rum-js/issues/206)) ([c743f70](https://github.com/CoboVault/apm-agent-rum-js/commit/c743f701a1cd65104612461fd19f36faceba5ed4))
* **rum-core:** Add task API ([#194](https://github.com/CoboVault/apm-agent-rum-js/issues/194)) ([0153229](https://github.com/CoboVault/apm-agent-rum-js/commit/015322981c1c560420b8838fbb144d10b64c2eda))
* **rum-core:** add user timing spans to the page-load transaction ([#276](https://github.com/CoboVault/apm-agent-rum-js/issues/276)) ([11a62f1](https://github.com/CoboVault/apm-agent-rum-js/commit/11a62f1a278bfc1ae142617c321ac6005af5863d))
* **rum-core:** align breakdown types based on navigation timing ([#464](https://github.com/CoboVault/apm-agent-rum-js/issues/464)) ([61ed16b](https://github.com/CoboVault/apm-agent-rum-js/commit/61ed16b6ddd007b221e2874c9a360dd49c47ad6b))
* **rum-core:** breakdown graphs for transaction ([#412](https://github.com/CoboVault/apm-agent-rum-js/issues/412)) ([28df070](https://github.com/CoboVault/apm-agent-rum-js/commit/28df070ed4001d1e3ee3fcb929364e5960339793))
* **rum-core:** capture long tasks and lcp using performance observer ([#581](https://github.com/CoboVault/apm-agent-rum-js/issues/581)) ([a52ca9d](https://github.com/CoboVault/apm-agent-rum-js/commit/a52ca9d43abc83a15de6ac3bd7ab54559d36143b))
* **rum-core:** capture resource and user timing spans for soft navigation ([#423](https://github.com/CoboVault/apm-agent-rum-js/issues/423)) ([d461ae5](https://github.com/CoboVault/apm-agent-rum-js/commit/d461ae5ca17104957e9e62fc4b72a3e847f43fa3))
* **rum-core:** capture total blocking time for navigation ([#788](https://github.com/CoboVault/apm-agent-rum-js/issues/788)) ([a48980b](https://github.com/CoboVault/apm-agent-rum-js/commit/a48980b5819d92854923f9ebe5b89f2b28b25b61))
* **rum-core:** capture unhandled promise rejection as errors ([#427](https://github.com/CoboVault/apm-agent-rum-js/issues/427)) ([ef34ccc](https://github.com/CoboVault/apm-agent-rum-js/commit/ef34ccc1f8d8784f31d7ee2e5fb9ba9aac3439d4))
* **rum-core:** copy transaction context info to error ([#458](https://github.com/CoboVault/apm-agent-rum-js/issues/458)) ([fa81fb7](https://github.com/CoboVault/apm-agent-rum-js/commit/fa81fb7382668473d6d4500f53336a7eed894d3f))
* **rum-core:** end spa navigations after browser frame ([#730](https://github.com/CoboVault/apm-agent-rum-js/issues/730)) ([5397fa2](https://github.com/CoboVault/apm-agent-rum-js/commit/5397fa22eb88c080f7a6d07ef5b89dfefc572fb3))
* **rum-core:** enrich span context with desination metadata ([#515](https://github.com/CoboVault/apm-agent-rum-js/issues/515)) ([38276b5](https://github.com/CoboVault/apm-agent-rum-js/commit/38276b5130c12d0de5d4d3e60c14cd645c10550e))
* **rum-core:** improve the debug logs with transaction details ([#469](https://github.com/CoboVault/apm-agent-rum-js/issues/469)) ([b9629b4](https://github.com/CoboVault/apm-agent-rum-js/commit/b9629b450b1eff9b0a53bcaff5a28c9926c61d49))
* **rum-core:** improver error message on payload failure ([#330](https://github.com/CoboVault/apm-agent-rum-js/issues/330)) ([73e7015](https://github.com/CoboVault/apm-agent-rum-js/commit/73e7015894cf07017090ab8a7ac9c5637df6a74d))
* **rum-core:** log when dt header isnt injected ([#630](https://github.com/CoboVault/apm-agent-rum-js/issues/630)) ([6d2d9a7](https://github.com/CoboVault/apm-agent-rum-js/commit/6d2d9a75d72506c21c7e1891994646819ee2bae4))
* **rum-core:** measure all resource entries in page load ([#173](https://github.com/CoboVault/apm-agent-rum-js/issues/173)) ([7cd4e0d](https://github.com/CoboVault/apm-agent-rum-js/commit/7cd4e0d8230aa9f7413ef2be0e953914d9a72aca))
* add labels config to metadata payload ([#617](https://github.com/CoboVault/apm-agent-rum-js/issues/617)) ([2d8e46d](https://github.com/CoboVault/apm-agent-rum-js/commit/2d8e46da1919e15563568945f2e2a0a6adcabe0c))
* capture click user-interaction transactions ([#604](https://github.com/CoboVault/apm-agent-rum-js/issues/604)) ([30530c1](https://github.com/CoboVault/apm-agent-rum-js/commit/30530c11c4b4ae46ad5fe140f1a15c1f3d240199))
* capture http-request transactions ([#517](https://github.com/CoboVault/apm-agent-rum-js/issues/517)) ([27ed994](https://github.com/CoboVault/apm-agent-rum-js/commit/27ed994ea9866e4493015eb3817ab12266f572a5))
* Initial react integration ([#265](https://github.com/CoboVault/apm-agent-rum-js/issues/265)) ([83cbebd](https://github.com/CoboVault/apm-agent-rum-js/commit/83cbebd7f8a0ae12f2b420e9095d4efff8d10d73))
* **rum-core:** monitor longtasks by default during active transaction ([#677](https://github.com/CoboVault/apm-agent-rum-js/issues/677)) ([7de5169](https://github.com/CoboVault/apm-agent-rum-js/commit/7de5169922dba2cc1e8b6b67c0f98a6b0dee7e71))
* **rum-core:** move breakdown algorithm post transaction finish ([#438](https://github.com/CoboVault/apm-agent-rum-js/issues/438)) ([ad42fda](https://github.com/CoboVault/apm-agent-rum-js/commit/ad42fda9871c8d4c0a4cdb0519b9bb340b439a68))
* **rum-core:** patch history API ([#259](https://github.com/CoboVault/apm-agent-rum-js/issues/259)) ([be58997](https://github.com/CoboVault/apm-agent-rum-js/commit/be58997e1efa212dd0eabdf427fbbff1b9662a43))
* **rum-core:** provide debug logs when transaction was discarded ([#351](https://github.com/CoboVault/apm-agent-rum-js/issues/351)) ([d6728d8](https://github.com/CoboVault/apm-agent-rum-js/commit/d6728d8de7ba42fd819bd55f32af91c31a2abb4e))
* **rum-core:** send transactions with no spans ([#540](https://github.com/CoboVault/apm-agent-rum-js/issues/540)) ([dd90bf4](https://github.com/CoboVault/apm-agent-rum-js/commit/dd90bf4e9b63424edf3c53730f94c01bd05e4e34))
* **rum-core:** set sync field only for synchronous spans ([#699](https://github.com/CoboVault/apm-agent-rum-js/issues/699)) ([3fd4bca](https://github.com/CoboVault/apm-agent-rum-js/commit/3fd4bca0e577e45d84fad8b79b55d29a2ac2d7ca))
* **rum-core:** support rn ([439061b](https://github.com/CoboVault/apm-agent-rum-js/commit/439061b908a8cdc60df8f5b449adf20a0bc8d825))
* **rum-core:** use error event instead of global onerror method ([#281](https://github.com/CoboVault/apm-agent-rum-js/issues/281)) ([ef61121](https://github.com/CoboVault/apm-agent-rum-js/commit/ef61121eaff86a30f8b48a598379c6d8d9fadf53))
* **rum-core:** use etag for fetching config ([#439](https://github.com/CoboVault/apm-agent-rum-js/issues/439)) ([bac0e15](https://github.com/CoboVault/apm-agent-rum-js/commit/bac0e15aeccfa84423e102b1b7ea3716ac7826f0))
* **rum-core:** use global promise when available and fallback ([#629](https://github.com/CoboVault/apm-agent-rum-js/issues/629)) ([65f08e0](https://github.com/CoboVault/apm-agent-rum-js/commit/65f08e06d2819a5ba76f476d9a4bc1dfd7fe788b))
* **rum-core:** use performance observer to capture FCP ([#749](https://github.com/CoboVault/apm-agent-rum-js/issues/749)) ([fc60eb3](https://github.com/CoboVault/apm-agent-rum-js/commit/fc60eb3744b45792dff7e1dbd4aefe72b023d372))
* Introduce managed transaction option ([#440](https://github.com/CoboVault/apm-agent-rum-js/issues/440)) ([a08f210](https://github.com/CoboVault/apm-agent-rum-js/commit/a08f21093735abf578be1de46f03beb89368ef88))
* Support central config management ([#415](https://github.com/CoboVault/apm-agent-rum-js/issues/415)) ([1382cc9](https://github.com/CoboVault/apm-agent-rum-js/commit/1382cc972d6c1b215374b76fe1f965717b6c2fcd))
* vue router integration with rum agent ([#460](https://github.com/CoboVault/apm-agent-rum-js/issues/460)) ([228e157](https://github.com/CoboVault/apm-agent-rum-js/commit/228e157851f4df7448f8bfcdd4b4b57129707992))


### Performance Improvements

* **rum:** move to ES6 modules to reduce bundle size ([#237](https://github.com/CoboVault/apm-agent-rum-js/issues/237)) ([7aa4351](https://github.com/CoboVault/apm-agent-rum-js/commit/7aa43513ad75736ae42410cc32ae1a44bc31280c))
* **rum:** remove debug logs on production build ([#245](https://github.com/CoboVault/apm-agent-rum-js/issues/245)) ([2565844](https://github.com/CoboVault/apm-agent-rum-js/commit/2565844febe9596eafe0f9fc07627bb23b0f097e))
* **rum-core:** avoid url parsing on resource timing entries ([#174](https://github.com/CoboVault/apm-agent-rum-js/issues/174)) ([54ea6b9](https://github.com/CoboVault/apm-agent-rum-js/commit/54ea6b97775d2eb7ee075182530c12ded34d7a0f))
* **rum-core:** check span validition before creating arbitrary spans ([#277](https://github.com/CoboVault/apm-agent-rum-js/issues/277)) ([dcba903](https://github.com/CoboVault/apm-agent-rum-js/commit/dcba903432db50d01ffca6e79853f03a43dcfd9d))
* refactor ServiceFactory to use constant service names ([#764](https://github.com/CoboVault/apm-agent-rum-js/issues/764)) ([fdda235](https://github.com/CoboVault/apm-agent-rum-js/commit/fdda23555b418166727d85f143e84a16079d83e6)), closes [#238](https://github.com/CoboVault/apm-agent-rum-js/issues/238)
* **rum-core:** compress server payload for all events ([#771](https://github.com/CoboVault/apm-agent-rum-js/issues/771)) ([5a3c604](https://github.com/CoboVault/apm-agent-rum-js/commit/5a3c6048482b47a9ac6ef565e88ff3eff786cabf))
* **rum-core:** ignored XHR's are exempted from task creation process ([#498](https://github.com/CoboVault/apm-agent-rum-js/issues/498)) ([eb2a376](https://github.com/CoboVault/apm-agent-rum-js/commit/eb2a376f08364686955453edb27d0f0388ad6d49))
* **rum-core:** move unexposed configs inside constants to reduce bundlesize ([#521](https://github.com/CoboVault/apm-agent-rum-js/issues/521)) ([2472e1f](https://github.com/CoboVault/apm-agent-rum-js/commit/2472e1fd3052faa24ca03dfaa0a3ac961ff32da1))
* **rum-core:** random number generator using crypto.getRandomValues ([#705](https://github.com/CoboVault/apm-agent-rum-js/issues/705)) ([ce0db92](https://github.com/CoboVault/apm-agent-rum-js/commit/ce0db92d1ba057def0c81595340de4e9e59c4872))
* **rum-core:** refactor transaction & stack service to improve bundlesize ([#233](https://github.com/CoboVault/apm-agent-rum-js/issues/233)) ([f2b2562](https://github.com/CoboVault/apm-agent-rum-js/commit/f2b256238c702c04970dd990a5d17d1e0b5bdf1a))


### BREAKING CHANGES

* tags are not added to individual events

instead we rely on metadata labels

* apply truncation logic to metadata.labels

* revert removing tags truncation from context
* add support for boolean and number values in addLabels

* address review

* simplify if statement
* Dropping the support for IE 10 and android 4* versions. Bundling condigurations and testing environments are changed to reflect the same

* parallelize the e2e tests and use single tunnel

* update contributing.md





# [5.5.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@elastic/apm-rum-core@5.3.0...@elastic/apm-rum-core@5.5.0) (2020-05-29)


### Features

* **dev:** modify repo config ([c89979e](https://github.com/CoboVault/apm-agent-rum-js/commit/c89979e78c2559d78319c7ecda84dcaef2126062))





# [5.4.0](https://github.com/CoboVault/apm-agent-rum-js/compare/@elastic/apm-rum-core@5.3.0...@elastic/apm-rum-core@5.4.0) (2020-05-28)


### Features

* **dev:** modify repo config ([c89979e](https://github.com/CoboVault/apm-agent-rum-js/commit/c89979e78c2559d78319c7ecda84dcaef2126062))





# [5.3.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@5.2.0...@elastic/apm-rum-core@5.3.0) (2020-05-22)


### Bug Fixes

* **rum-core:** add subtype span info without camelcasing ([#753](https://github.com/elastic/apm-agent-rum-js/issues/753)) ([8b97075](https://github.com/elastic/apm-agent-rum-js/commit/8b9707561f20ceb44caeb8ab6f6cf6cfe97e4f40))
* **rum-core:** treat truncated spans as actual in breakdown ([#777](https://github.com/elastic/apm-agent-rum-js/issues/777)) ([93d8fc2](https://github.com/elastic/apm-agent-rum-js/commit/93d8fc2ff1b506aeeb7e4f6b7268f065922c21cc))


### Features

* **rum-core:** capture total blocking time for navigation ([#788](https://github.com/elastic/apm-agent-rum-js/issues/788)) ([a48980b](https://github.com/elastic/apm-agent-rum-js/commit/a48980b5819d92854923f9ebe5b89f2b28b25b61))
* **rum-core:** support rn ([8b210aa](https://github.com/elastic/apm-agent-rum-js/commit/8b210aaa228b4115624b033a459b934ec191d6fc))


### Performance Improvements

* refactor ServiceFactory to use constant service names ([#764](https://github.com/elastic/apm-agent-rum-js/issues/764)) ([fdda235](https://github.com/elastic/apm-agent-rum-js/commit/fdda23555b418166727d85f143e84a16079d83e6)), closes [#238](https://github.com/elastic/apm-agent-rum-js/issues/238)
* **rum-core:** compress server payload for all events ([#771](https://github.com/elastic/apm-agent-rum-js/issues/771)) ([5a3c604](https://github.com/elastic/apm-agent-rum-js/commit/5a3c6048482b47a9ac6ef565e88ff3eff786cabf))





# [5.2.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@5.1.0...@elastic/apm-rum-core@5.2.0) (2020-04-15)


### Features

* **rum-core:** use performance observer to capture FCP ([#749](https://github.com/elastic/apm-agent-rum-js/issues/749)) ([fc60eb3](https://github.com/elastic/apm-agent-rum-js/commit/fc60eb3744b45792dff7e1dbd4aefe72b023d372))





# [5.1.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@5.0.0...@elastic/apm-rum-core@5.1.0) (2020-04-08)


### Bug Fixes

* **rum-core:** filter API calls from resource spans ([#724](https://github.com/elastic/apm-agent-rum-js/issues/724)) ([15dba46](https://github.com/elastic/apm-agent-rum-js/commit/15dba464f0e4db1268b1fecbe4f4bf83b0b38c54))
* **rum-core:** handle error when `performance` is not available ([#708](https://github.com/elastic/apm-agent-rum-js/issues/708)) ([bb1740a](https://github.com/elastic/apm-agent-rum-js/commit/bb1740a20c65a5ce7649a122d1e27deeb97ed994))


### Features

* **rum-core:** end spa navigations after browser frame ([#730](https://github.com/elastic/apm-agent-rum-js/issues/730)) ([5397fa2](https://github.com/elastic/apm-agent-rum-js/commit/5397fa22eb88c080f7a6d07ef5b89dfefc572fb3))


### Performance Improvements

* **rum-core:** random number generator using crypto.getRandomValues ([#705](https://github.com/elastic/apm-agent-rum-js/issues/705)) ([ce0db92](https://github.com/elastic/apm-agent-rum-js/commit/ce0db92d1ba057def0c81595340de4e9e59c4872))





# [5.0.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.10.1...@elastic/apm-rum-core@5.0.0) (2020-03-18)


### Features

* **rum-core:** monitor longtasks by default during active transaction ([#677](https://github.com/elastic/apm-agent-rum-js/issues/677)) ([7de5169](https://github.com/elastic/apm-agent-rum-js/commit/7de5169922dba2cc1e8b6b67c0f98a6b0dee7e71))
* **rum-core:** set sync field only for synchronous spans ([#699](https://github.com/elastic/apm-agent-rum-js/issues/699)) ([3fd4bca](https://github.com/elastic/apm-agent-rum-js/commit/3fd4bca0e577e45d84fad8b79b55d29a2ac2d7ca))



### BREAKING CHANGES

* BREAKING CHANGE: tags are not added to individual events (#700) ([e968c54](https://github.com/elastic/apm-agent-rum-js/commit/e968c54fb55bece8176e4663bfcf842ccef3244f)), closes [#700](https://github.com/elastic/apm-agent-rum-js/issues/700)
* BREAKING CHANGE: add support for boolean and number values in addLabels (#697) ([4533b67](https://github.com/elastic/apm-agent-rum-js/commit/4533b67b658943a1370eeaf90a64f866cd271269)), closes [#697](https://github.com/elastic/apm-agent-rum-js/issues/697)





## [4.10.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.10.0...@elastic/apm-rum-core@4.10.1) (2020-03-09)


### Bug Fixes

* **rum-core:** Check if first-contentful-paint exists before setting the agent marks ([#681](https://github.com/elastic/apm-agent-rum-js/issues/681)) ([a2298f7](https://github.com/elastic/apm-agent-rum-js/commit/a2298f723a1d774e6d099c6fe811b8344deb8287)), closes [#680](https://github.com/elastic/apm-agent-rum-js/issues/680) [elastic/apm-agent-rum-js#680](https://github.com/elastic/apm-agent-rum-js/issues/680) [#680](https://github.com/elastic/apm-agent-rum-js/issues/680) [#680](https://github.com/elastic/apm-agent-rum-js/issues/680)
* **rum-core:** replace >> in click transaction name with '-' ([#690](https://github.com/elastic/apm-agent-rum-js/issues/690)) ([ca43a71](https://github.com/elastic/apm-agent-rum-js/commit/ca43a7104a4820b3d880282d32c0509e4190a9d0))





# [4.10.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.9.1...@elastic/apm-rum-core@4.10.0) (2020-03-03)


### Bug Fixes

* **rum-core:** export browser responsiveness interval correctly ([#658](https://github.com/elastic/apm-agent-rum-js/issues/658)) ([2ecf060](https://github.com/elastic/apm-agent-rum-js/commit/2ecf060a35dd1b64110149edc5bbdd4a4613caa9))


### Features

* **rum-core:** log when dt header isnt injected ([#630](https://github.com/elastic/apm-agent-rum-js/issues/630)) ([6d2d9a7](https://github.com/elastic/apm-agent-rum-js/commit/6d2d9a75d72506c21c7e1891994646819ee2bae4))
* **rum-core:** use global promise when available and fallback ([#629](https://github.com/elastic/apm-agent-rum-js/issues/629)) ([65f08e0](https://github.com/elastic/apm-agent-rum-js/commit/65f08e06d2819a5ba76f476d9a4bc1dfd7fe788b))





## [4.9.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.9.0...@elastic/apm-rum-core@4.9.1) (2020-02-14)


### Bug Fixes

* **rum-core:** Only capture events on Elements ([#625](https://github.com/elastic/apm-agent-rum-js/issues/625)) ([133a3f4](https://github.com/elastic/apm-agent-rum-js/commit/133a3f4cc4b44074a80e147d47de53b896f2967e))





# [4.9.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.8.1...@elastic/apm-rum-core@4.9.0) (2020-02-13)


### Bug Fixes

* pass correct properties to payload filters ([#616](https://github.com/elastic/apm-agent-rum-js/issues/616)) ([44d6740](https://github.com/elastic/apm-agent-rum-js/commit/44d674064dd1b7b992c7bf22fe82fb9cc48582da))


### Features

* add labels config to metadata payload ([#617](https://github.com/elastic/apm-agent-rum-js/issues/617)) ([2d8e46d](https://github.com/elastic/apm-agent-rum-js/commit/2d8e46da1919e15563568945f2e2a0a6adcabe0c))
* capture click user-interaction transactions ([#604](https://github.com/elastic/apm-agent-rum-js/issues/604)) ([30530c1](https://github.com/elastic/apm-agent-rum-js/commit/30530c11c4b4ae46ad5fe140f1a15c1f3d240199))
* **rum-core:** add config option to monitor longtasks ([#600](https://github.com/elastic/apm-agent-rum-js/issues/600)) ([34b4fb3](https://github.com/elastic/apm-agent-rum-js/commit/34b4fb300d47833acfaccbd6b07d155d299b2b6e))
* **rum-core:** add EventTarget patch ([#588](https://github.com/elastic/apm-agent-rum-js/issues/588)) ([755bab4](https://github.com/elastic/apm-agent-rum-js/commit/755bab4124c0c7928071434901ddf642b43387a2))
* **rum-core:** capture long tasks and lcp using performance observer ([#581](https://github.com/elastic/apm-agent-rum-js/issues/581)) ([a52ca9d](https://github.com/elastic/apm-agent-rum-js/commit/a52ca9d43abc83a15de6ac3bd7ab54559d36143b))





## [4.8.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.8.0...@elastic/apm-rum-core@4.8.1) (2020-01-30)


### Bug Fixes

* **rum-core:** add error properties to custom context by default ([#586](https://github.com/elastic/apm-agent-rum-js/issues/586)) ([15ef0b6](https://github.com/elastic/apm-agent-rum-js/commit/15ef0b623da844ab05886b2a5d61fdf3dc383d1b))
* **rum-core:** do not capture timing spans for unsampled transactions ([#590](https://github.com/elastic/apm-agent-rum-js/issues/590)) ([88b61ec](https://github.com/elastic/apm-agent-rum-js/commit/88b61ec98a328eb84ed87023b219c8eeb0f6b462))
* **rum-core:** transaction onstart hook must be consistent ([#585](https://github.com/elastic/apm-agent-rum-js/issues/585)) ([dd792d1](https://github.com/elastic/apm-agent-rum-js/commit/dd792d167a13c072e8870c3ea29efdae015fe9d4))





# [4.8.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.7.0...@elastic/apm-rum-core@4.8.0) (2020-01-15)


### Bug Fixes

* add transaction type redefine order ([#535](https://github.com/elastic/apm-agent-rum-js/issues/535)) ([9e0b311](https://github.com/elastic/apm-agent-rum-js/commit/9e0b311b20f2db0f00702eb5a8389c67dd4628fe))
* **rum-core:** create temporary transaction on startSpan ([#533](https://github.com/elastic/apm-agent-rum-js/issues/533)) ([8c951d2](https://github.com/elastic/apm-agent-rum-js/commit/8c951d2fb52c1fe61aa90be2cd3ecca3fe6cff1b))


### Features

* **rum-core:** enrich span context with desination metadata ([#515](https://github.com/elastic/apm-agent-rum-js/issues/515)) ([38276b5](https://github.com/elastic/apm-agent-rum-js/commit/38276b5130c12d0de5d4d3e60c14cd645c10550e))
* **rum-core:** send transactions with no spans ([#540](https://github.com/elastic/apm-agent-rum-js/issues/540)) ([dd90bf4](https://github.com/elastic/apm-agent-rum-js/commit/dd90bf4e9b63424edf3c53730f94c01bd05e4e34))
* capture http-request transactions ([#517](https://github.com/elastic/apm-agent-rum-js/issues/517)) ([27ed994](https://github.com/elastic/apm-agent-rum-js/commit/27ed994ea9866e4493015eb3817ab12266f572a5))


### Performance Improvements

* **rum-core:** ignored XHR's are exempted from task creation process ([#498](https://github.com/elastic/apm-agent-rum-js/issues/498)) ([eb2a376](https://github.com/elastic/apm-agent-rum-js/commit/eb2a376f08364686955453edb27d0f0388ad6d49))
* **rum-core:** move unexposed configs inside constants to reduce bundlesize ([#521](https://github.com/elastic/apm-agent-rum-js/issues/521)) ([2472e1f](https://github.com/elastic/apm-agent-rum-js/commit/2472e1fd3052faa24ca03dfaa0a3ac961ff32da1))





# [4.7.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.6.1...@elastic/apm-rum-core@4.7.0) (2019-11-19)


### Bug Fixes

* **rum-core:** ensure context metadata is shallow merged on transaction ([#453](https://github.com/elastic/apm-agent-rum-js/issues/453)) ([30b954e](https://github.com/elastic/apm-agent-rum-js/commit/30b954e))
* **rum-core:** schedule xhr invoke task as a macro task ([#480](https://github.com/elastic/apm-agent-rum-js/issues/480)) ([d4f181f](https://github.com/elastic/apm-agent-rum-js/commit/d4f181f)), closes [#390](https://github.com/elastic/apm-agent-rum-js/issues/390)
* **rum-core:** use rum endpoint for central config ([#489](https://github.com/elastic/apm-agent-rum-js/issues/489)) ([43ce47e](https://github.com/elastic/apm-agent-rum-js/commit/43ce47e))


### Features

* **rum-core:** align breakdown types based on navigation timing ([#464](https://github.com/elastic/apm-agent-rum-js/issues/464)) ([61ed16b](https://github.com/elastic/apm-agent-rum-js/commit/61ed16b))
* **rum-core:** copy transaction context info to error ([#458](https://github.com/elastic/apm-agent-rum-js/issues/458)) ([fa81fb7](https://github.com/elastic/apm-agent-rum-js/commit/fa81fb7))
* vue router integration with rum agent ([#460](https://github.com/elastic/apm-agent-rum-js/issues/460)) ([228e157](https://github.com/elastic/apm-agent-rum-js/commit/228e157))
* **rum-core:** improve the debug logs with transaction details ([#469](https://github.com/elastic/apm-agent-rum-js/issues/469)) ([b9629b4](https://github.com/elastic/apm-agent-rum-js/commit/b9629b4))
* **rum-core:** move breakdown algorithm post transaction finish ([#438](https://github.com/elastic/apm-agent-rum-js/issues/438)) ([ad42fda](https://github.com/elastic/apm-agent-rum-js/commit/ad42fda))
* **rum-core:** use etag for fetching config ([#439](https://github.com/elastic/apm-agent-rum-js/issues/439)) ([bac0e15](https://github.com/elastic/apm-agent-rum-js/commit/bac0e15))





## [4.6.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.6.0...@elastic/apm-rum-core@4.6.1) (2019-10-09)


### Bug Fixes

* **rum-core:** handle relative urls without slash properly ([#446](https://github.com/elastic/apm-agent-rum-js/issues/446)) ([288e8b1](https://github.com/elastic/apm-agent-rum-js/commit/288e8b1))





# [4.6.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.5.4...@elastic/apm-rum-core@4.6.0) (2019-09-30)


### Bug Fixes

* **rum:** publish all packages as transpiled modules ([#432](https://github.com/elastic/apm-agent-rum-js/issues/432)) ([1f4ee87](https://github.com/elastic/apm-agent-rum-js/commit/1f4ee87))


### Features

* **rum-core:** breakdown graphs for transaction ([#412](https://github.com/elastic/apm-agent-rum-js/issues/412)) ([28df070](https://github.com/elastic/apm-agent-rum-js/commit/28df070))
* **rum-core:** capture resource and user timing spans for soft navigation ([#423](https://github.com/elastic/apm-agent-rum-js/issues/423)) ([d461ae5](https://github.com/elastic/apm-agent-rum-js/commit/d461ae5))
* Introduce managed transaction option ([#440](https://github.com/elastic/apm-agent-rum-js/issues/440)) ([a08f210](https://github.com/elastic/apm-agent-rum-js/commit/a08f210))
* Support central config management ([#415](https://github.com/elastic/apm-agent-rum-js/issues/415)) ([1382cc9](https://github.com/elastic/apm-agent-rum-js/commit/1382cc9))
* **rum-core:** capture unhandled promise rejection as errors ([#427](https://github.com/elastic/apm-agent-rum-js/issues/427)) ([ef34ccc](https://github.com/elastic/apm-agent-rum-js/commit/ef34ccc))





## [4.5.4](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.5.3...@elastic/apm-rum-core@4.5.4) (2019-09-17)


### Bug Fixes

* **rum-core:** handle script error events properly ([#418](https://github.com/elastic/apm-agent-rum-js/issues/418)) ([c862ab7](https://github.com/elastic/apm-agent-rum-js/commit/c862ab7))





## [4.5.3](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.5.2...@elastic/apm-rum-core@4.5.3) (2019-09-03)

**Note:** Version bump only for package @elastic/apm-rum-core





## [4.5.2](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.5.1...@elastic/apm-rum-core@4.5.2) (2019-08-08)


### Bug Fixes

* **rum-core:** do not polyfill the global Promise variable ([#366](https://github.com/elastic/apm-agent-rum-js/issues/366)) ([f5dc95c](https://github.com/elastic/apm-agent-rum-js/commit/f5dc95c))





## [4.5.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.5.0...@elastic/apm-rum-core@4.5.1) (2019-08-05)

**Note:** Version bump only for package @elastic/apm-rum-core





# [4.5.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.4.0...@elastic/apm-rum-core@4.5.0) (2019-08-05)


### Bug Fixes

* **rum-core:** reduce transaction reusability threshold to 5 seconds ([#354](https://github.com/elastic/apm-agent-rum-js/issues/354)) ([dd32e41](https://github.com/elastic/apm-agent-rum-js/commit/dd32e41))


### Features

* **rum-core:** add event listeners for transactions ([#279](https://github.com/elastic/apm-agent-rum-js/issues/279)) ([d98f7c7](https://github.com/elastic/apm-agent-rum-js/commit/d98f7c7))
* **rum-core:** provide debug logs when transaction was discarded ([#351](https://github.com/elastic/apm-agent-rum-js/issues/351)) ([d6728d8](https://github.com/elastic/apm-agent-rum-js/commit/d6728d8))





# [4.4.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.3.0...@elastic/apm-rum-core@4.4.0) (2019-07-25)


### Bug Fixes

* **rum-core:** check ignoreTransactions config value ([#337](https://github.com/elastic/apm-agent-rum-js/issues/337)) ([aff6bc8](https://github.com/elastic/apm-agent-rum-js/commit/aff6bc8))


### Features

* **rum-core:** add size & server timing information to traces ([#206](https://github.com/elastic/apm-agent-rum-js/issues/206)) ([c743f70](https://github.com/elastic/apm-agent-rum-js/commit/c743f70))
* **rum-core:** improve error message on payload failure ([#330](https://github.com/elastic/apm-agent-rum-js/issues/330)) ([73e7015](https://github.com/elastic/apm-agent-rum-js/commit/73e7015))





# [4.3.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.1.1...@elastic/apm-rum-core@4.3.0) (2019-07-11)


### Bug Fixes

* **rum:core:** send labels via context.tags in the payload ([#316](https://github.com/elastic/apm-agent-rum-js/issues/316)) ([526c3e7](https://github.com/elastic/apm-agent-rum-js/commit/526c3e7))


# [4.2.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.1.1...@elastic/apm-rum-core@4.2.0) (2019-07-08)


### Bug Fixes

* **rum-core:** remove sensitive info from span context ([#274](https://github.com/elastic/apm-agent-rum-js/issues/274)) ([b073f7f](https://github.com/elastic/apm-agent-rum-js/commit/b073f7f))


### Features

* **rum-core:** add user timing spans to the page-load transaction ([#276](https://github.com/elastic/apm-agent-rum-js/issues/276)) ([11a62f1](https://github.com/elastic/apm-agent-rum-js/commit/11a62f1))


### Performance Improvements

* **rum-core:** check span validition before creating arbitrary spans ([#277](https://github.com/elastic/apm-agent-rum-js/issues/277)) ([dcba903](https://github.com/elastic/apm-agent-rum-js/commit/dcba903))





## [4.1.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.1.0...@elastic/apm-rum-core@4.1.1) (2019-06-20)


### Bug Fixes

* **rum-core:** avoid creating multiple transactions in startTransaction ([#296](https://github.com/elastic/apm-agent-rum-js/issues/296)) ([70c3fb4](https://github.com/elastic/apm-agent-rum-js/commit/70c3fb4))





# [4.1.0](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.0.2...@elastic/apm-rum-core@4.1.0) (2019-06-12)


### Bug Fixes

* **rum-core:** capture all spans as part of page-load transaction ([#273](https://github.com/elastic/apm-agent-rum-js/issues/273)) ([0122bf7](https://github.com/elastic/apm-agent-rum-js/commit/0122bf7))


### Features

* **rum:** deprecate addTags in favor of addLabels ([#270](https://github.com/elastic/apm-agent-rum-js/issues/270)) ([3e313d3](https://github.com/elastic/apm-agent-rum-js/commit/3e313d3))
* **rum-core:** patch history API ([#259](https://github.com/elastic/apm-agent-rum-js/issues/259)) ([be58997](https://github.com/elastic/apm-agent-rum-js/commit/be58997))
* **rum-core:** use error event instead of global onerror method ([#281](https://github.com/elastic/apm-agent-rum-js/issues/281)) ([ef61121](https://github.com/elastic/apm-agent-rum-js/commit/ef61121))


### Performance Improvements

* **rum-core:** refactor transaction & stack service to improve bundlesize ([#233](https://github.com/elastic/apm-agent-rum-js/issues/233)) ([f2b2562](https://github.com/elastic/apm-agent-rum-js/commit/f2b2562))





## [4.0.2](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.0.1...@elastic/apm-rum-core@4.0.2) (2019-05-29)


### Bug Fixes

* **rum:** return noop agent when config is inactive ([#239](https://github.com/elastic/apm-agent-rum-js/issues/239)) ([7deef2d](https://github.com/elastic/apm-agent-rum-js/commit/7deef2d))
* **rum-core:** apply truncation on keyword fields in payload ([#241](https://github.com/elastic/apm-agent-rum-js/issues/241)) ([8a3927b](https://github.com/elastic/apm-agent-rum-js/commit/8a3927b))
* **rum-core:** hardcode agent name and version in service metadata ([#236](https://github.com/elastic/apm-agent-rum-js/issues/236)) ([a90337d](https://github.com/elastic/apm-agent-rum-js/commit/a90337d))
* **rum-core:** in truncate check for empty values ([#256](https://github.com/elastic/apm-agent-rum-js/issues/256)) ([cccb172](https://github.com/elastic/apm-agent-rum-js/commit/cccb172))


### Performance Improvements

* **rum:** move to ES6 modules to reduce bundle size ([#237](https://github.com/elastic/apm-agent-rum-js/issues/237)) ([7aa4351](https://github.com/elastic/apm-agent-rum-js/commit/7aa4351))





## [4.0.1](https://github.com/elastic/apm-agent-rum-js/compare/@elastic/apm-rum-core@4.0.0...@elastic/apm-rum-core@4.0.1) (2019-03-21)


### Bug Fixes

* **rum-core:** fix custom marks for page-load ([#225](https://github.com/elastic/apm-agent-rum-js/issues/225)) ([6cd392a](https://github.com/elastic/apm-agent-rum-js/commit/6cd392a)), closes [#221](https://github.com/elastic/apm-agent-rum-js/issues/221)





# 4.0.0 (2019-03-11)


### Features

* **rum-core:** add service env to metadata payload ([#198](https://github.com/elastic/apm-agent-rum-js/issues/198)) ([adc038b](https://github.com/elastic/apm-agent-rum-js/commit/adc038b))
* **rum-core:** Add task API ([#194](https://github.com/elastic/apm-agent-rum-js/issues/194)) ([0153229](https://github.com/elastic/apm-agent-rum-js/commit/0153229))
* **rum-core:** measure all resource entries in page load ([#173](https://github.com/elastic/apm-agent-rum-js/issues/173)) ([7cd4e0d](https://github.com/elastic/apm-agent-rum-js/commit/7cd4e0d))


### Performance Improvements

* **rum-core:** avoid url parsing on resource timing entries ([#174](https://github.com/elastic/apm-agent-rum-js/issues/174)) ([54ea6b9](https://github.com/elastic/apm-agent-rum-js/commit/54ea6b9))


### BREAKING CHANGES

* move IE 10 and Android 4 to unsupported list (#196) ([16f4440](https://github.com/elastic/apm-agent-rum-js/commit/16f4440)), closes [#196](https://github.com/elastic/apm-agent-rum-js/issues/196)
