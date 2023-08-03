## [1.3.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.3.3...v1.3.4) (2023-08-03)


### Bug Fixes

* improve message to output: meta not displayed ([#250](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/250)) ([ed58962](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/ed589629542b3d9f5d196f6cd1973d8804dfb956))

## [1.3.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.3.2...v1.3.3) (2023-02-24)


### Bug Fixes

* support for workspaces with directory(s) that do not contain known manifests [#244](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/244) ([#245](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/245)) ([315b08b](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/315b08b88ad24dd2d7bfb99010840ba4281af89c))

## [1.3.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.3.1...v1.3.2) (2023-02-23)


### Bug Fixes

* improved handling when the User you are connecting to Nexus Lifecycle does not have enough permissions + updated docs ([#243](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/243)) ([9cb94a5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/9cb94a5b022c30543681223ae5dee374dd6287c1))

## [1.3.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.3.0...v1.3.1) (2023-02-23)


### Bug Fixes

* increase in logging to diagnose [#241](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/241) ([#242](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/242)) ([3e36d61](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/3e36d61e981de61f492dc3d22be9868151b1fe4e))

# [1.3.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.2.5...v1.3.0) (2023-02-16)


### Features

* Simple color change for readability ([#240](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/240)) ([26f590a](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/26f590a0d8c5c60074d1353dfdd78d30e5b5dc4e))

## [1.2.5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.2.4...v1.2.5) (2022-08-19)


### Bug Fixes

* Deduplicate components when building SBOM ([#237](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/237)) ([80d35d4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/80d35d442cb85772ef46f731d825cab8d92b3647))

## [1.2.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.2.3...v1.2.4) (2022-06-16)


### Bug Fixes

* updated dependencies and removed console.log calls ([1391895](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/1391895985aa8df55a4d44cf0942423f95bdeb37))

## [1.2.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.2.2...v1.2.3) (2022-01-17)


### Bug Fixes

* change so that `gradlew` has priority over `gradle` ([#228](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/228)) ([8f6fea2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/8f6fea238e90e9224238ba4313177390c75d7cbb)), closes [#227](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/227)

## [1.2.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.2.1...v1.2.2) (2022-01-13)


### Bug Fixes

* redeploy with new token, tweak badge ([275882e](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/275882e347198de764907e6f923fa3c0097317f7))

## [1.2.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.2.0...v1.2.1) (2022-01-13)


### Bug Fixes

* add missing support for testRuntimeClasspath ([#225](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/225)) ([28d4b67](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/28d4b67edb9118220c96825a664052db09a00a64))

# [1.2.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.1.6...v1.2.0) (2021-10-20)


### Features

* add ability to exlude Development Dependencies for supported ecosystems (Gradle, Maven, NPM, Poetry) ([61a95f5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/61a95f5a9b1583356850690c61da476bee5605df))

## [1.1.6](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.1.5...v1.1.6) (2021-10-19)


### Bug Fixes

* bump hosted-git-info and path-parse dependency versions to mitigate known vulnerabilities ([#219](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/219)) ([6129fc1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/6129fc10ed72bfc54804f07890c60ab65f134f45))

## [1.1.5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.1.4...v1.1.5) (2021-10-19)


### Bug Fixes

* updated parsing logic for `mvn dependency:tree` output to exclude items reported as " ommitted for " ([#218](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/218)) ([ed96b91](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/ed96b91edb0c3d101ecbe556e151610be3e2fd6d))

## [1.1.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.1.3...v1.1.4) (2021-10-19)


### Bug Fixes

* removed reference to undefined Command to solve [#203](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/203) ([#217](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/217)) ([bf5610a](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/bf5610a99bc896634ab0a06743f1409c0aecd41b))

## [1.1.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.1.2...v1.1.3) (2021-10-19)


### Bug Fixes

* bump @sonatype/react-shared-components which includes removal of node-sass ([#216](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/216)) ([eb44f3c](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/eb44f3cacf2ca099db1d1c2d28ce3b99fdb2cf24))

## [1.1.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.1.1...v1.1.2) (2021-10-18)


### Bug Fixes

* bump node-sass ([#215](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/215)) ([bef7e41](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/bef7e4114d77b532cf3934bc6eed21b7df7453e1))

## [1.1.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.1.0...v1.1.1) (2021-10-18)

# [1.1.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.29...v1.1.0) (2021-10-18)


### Features

* attempt to force v1.1.0 ([ace5cf5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/ace5cf58cc9e37836acdeddbba604f37f6b650e2))

## [1.0.29](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.28...v1.0.29) (2021-04-16)


### Bug Fixes

* add logging to Gradle to get more information ([9af2a65](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/9af2a65a61107e3c6686b99a09ab0af1468210bb))

## [1.0.28](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.27...v1.0.28) (2021-04-16)


### Bug Fixes

* Golang build error, and minor tweak to Gradle ([330c5cb](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/330c5cb856aeec2ecdd644eec4688064b0e6a698))

## [1.0.27](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.26...v1.0.27) (2021-04-16)


### Bug Fixes

* Golang Improvement: Use go list -m -json all so we get the replace stuff on the easy ([#198](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/198)) ([b27bd7a](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/b27bd7a257d5207a4ac6b65ba6a8b9eed7e424d5))

## [1.0.26](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.25...v1.0.26) (2021-04-16)


### Bug Fixes

* Try out using the Gradle Wrapper ([#201](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/201)) ([de4cf33](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/de4cf338de4defb8e98e71ebcbf76689fc3b113d))

## [1.0.25](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.24...v1.0.25) (2021-03-31)


### Bug Fixes

* OSS Index environment variables ([#197](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/197)) ([c9e4c3e](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/c9e4c3e9dff8032fe91ba6c13fde40b57ff45e8e))

## [1.0.24](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.23...v1.0.24) (2021-03-26)


### Bug Fixes

* Ensure url is set if loaded from config ([#196](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/196)) ([e1f1dcf](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/e1f1dcf0acbe5e0df91028aea8c35ac88579fb6f))

## [1.0.23](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.22...v1.0.23) (2021-03-24)


### Bug Fixes

* Merge Process Environment on Exec Calls ([#192](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/192)) ([7eaa72f](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/7eaa72f622c524df32ed6de5b6b84775a967db51))

## [1.0.22](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.21...v1.0.22) (2021-03-23)


### Bug Fixes

* Get application specific config from a .sonatype-config file ([#188](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/188)) ([f9c7079](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/f9c7079235967e4e0ae6fc05c0837aba80892a9b))

## [1.0.21](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.20...v1.0.21) (2021-03-15)


### Bug Fixes

* Pick up username or token from environment variables ([#187](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/187)) ([a2c4f84](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/a2c4f8470e4776a2c9d3591123fc4dc47aafeaee))

## [1.0.20](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.19...v1.0.20) (2021-02-12)


### Bug Fixes

* Split on == and ~= for requirements.txt ([#185](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/185)) ([b288252](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/b2882526f9907c5778c5e20b62ae34eec20b7ff7)), closes [#184](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/184)

## [1.0.19](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.18...v1.0.19) (2021-02-11)


### Bug Fixes

* handling trailing slash for iq report url  ([#183](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/183)) ([fcd2490](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/fcd2490baf425b6c2b89d06594827c8bd7e1a647))

## [1.0.18](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.17...v1.0.18) (2021-02-11)


### Bug Fixes

* why not give someone the report url ([3631991](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/36319918baf1735863e18aab5466b7de22f0a3fa))

## [1.0.17](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.16...v1.0.17) (2021-02-11)


### Bug Fixes

* Gradle - minimal format implementation ([#182](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/182)) ([dc48891](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/dc4889194d576f346472c8d2118d6120e084d276))

## [1.0.16](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.15...v1.0.16) (2021-02-03)


### Bug Fixes

* absolute links ([4e4d43e](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/4e4d43e0bc968b2b767dc7d8a1f16dcb1c6dc2cc))

## [1.0.15](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.14...v1.0.15) (2021-02-03)


### Bug Fixes

* just a tiny newline to test something ([b728de9](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/b728de9c172ef222066779f0ecd41e9aacef88fd))

## [1.0.14](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.13...v1.0.14) (2021-02-03)


### Bug Fixes

* Switch over to main from master ([#181](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/181)) ([4ae7681](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/4ae76811fa09aabeaf1f0b4dff203d616ded344d))

## [1.0.13](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.12...v1.0.13) (2021-01-26)


### Bug Fixes

* these extra commands and events were from the original template and can be removed ([ab8b33b](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/ab8b33becf786db0935c7792ccfac96d75bd54ce))

## [1.0.12](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.11...v1.0.12) (2021-01-22)


### Bug Fixes

* Add poetry.lock file to the theseAreTheLockFilesIKnow array in ConanUtils.ts ([#179](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/179)) ([9780711](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/978071117988470298353bd2e65a2425141a4604))

## [1.0.11](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.10...v1.0.11) (2021-01-21)


### Bug Fixes

* Refresh IQ stuff when App ID is changed ([#178](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/178)) ([49a9028](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/49a9028a39321ce1e15b6cf61963227ca8fad0ff))

## [1.0.10](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.9...v1.0.10) (2021-01-20)


### Bug Fixes

* Better error from a bad application ID response ([#177](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/177)) ([57e4cc8](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/57e4cc8a8390c5e6ac43089089553f08a85d2067))

## [1.0.9](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.8...v1.0.9) (2021-01-14)


### Bug Fixes

* Readme changes and screenshots ([#176](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/176)) ([877eeb5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/877eeb5777aacacba8872d8179ff436752509171))

## [1.0.8](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.7...v1.0.8) (2021-01-14)


### Bug Fixes

* Handle semicolons in auto-generated requirements.txt files ([#175](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/175)) ([2a43863](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/2a438638ae876f95e3de275ab29c505457d4cd70))

## [1.0.7](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.6...v1.0.7) (2021-01-14)


### Bug Fixes

* better error message for a project where we cannot find a manifest to scan ([e729d9b](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/e729d9b3a25c9183dfc36964e0654d6f1f53fafd))

## [1.0.6](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.5...v1.0.6) (2021-01-14)


### Bug Fixes

* install vsce ([115c070](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/115c07022174f3bb0442b99147848d75a2a4f545))

## [1.0.5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.4...v1.0.5) (2021-01-14)


### Bug Fixes

* webpack bundle and goodbye node_modules ([55287f1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/55287f197e0f8e479acef28919e0a6bd4ec4151f))

## [1.0.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.3...v1.0.4) (2021-01-14)


### Bug Fixes

* update node while we are at it ([3701345](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/37013456155d85a0f16adcb07d1092536112044e))
* yarn, why not ([6f428f1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/6f428f10f23b3c65acceaf93072dab95a21c4b1c))

## [1.0.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.2...v1.0.3) (2021-01-14)


### Bug Fixes

* prune before anything else, so we are down to the smallest list of dependencies needed ([a809a6f](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/a809a6f90410c0dbad3ac38ebc2bb0436ef83012))

## [1.0.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.1...v1.0.2) (2021-01-14)


### Bug Fixes

* run npm i to ensure dependencies are there, but still avoid npm list ([94ad6fc](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/94ad6fc07d466ecc4e91b8a3fddfcbaacafdd163))

## [1.0.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v1.0.0...v1.0.1) (2021-01-14)


### Bug Fixes

* See if we can bypass bad npm list command ([55de861](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/55de861bdc85c077037b58b45fb636bea35fb4d1))

# [1.0.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.8.3...v1.0.0) (2021-01-14)

## [0.8.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.8.2...v0.8.3) (2020-12-18)


### Bug Fixes

* test release credentials ([cd41ee0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/cd41ee0c1cc6c5b132c99bb4793db9ce05bdb89e))
* test release credentials again ([958d933](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/958d9339e3f4ed3eb99ec4f8e7c1cb6a6bae6bac))
* test release credentials from approved branch ([#144](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/144)) ([9a03357](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/9a033578cee01dd70a7bba0fc83c4e840c5b6e4c))
* updated SECURITY.md ([#143](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/143)) ([6a4898a](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/6a4898ab59f3961f25925324cf68a27df527f0b6))

## [0.8.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.8.1...v0.8.2) (2020-12-08)


### Bug Fixes

* CWE-20: Improper Input Validation (fixes [#140](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/140)) ([2450e60](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/2450e60e488793404e03e394c89c685a3cb31150))

## [0.8.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.8.0...v0.8.1) (2020-12-08)


### Bug Fixes

* **127:** `policyViolations of undefined` when loading a python project with requirements.txt ([f1b4585](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/f1b458553710df18914aa2e23c677d8c66639208))

# [0.8.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.8...v0.8.0) (2020-10-22)


### Features

* Allow for strict SSL to be controlled by config ([#133](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/133)) ([739bebe](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/739bebe06ed6679ba52bdf67896b02e41e14814d))

## [0.7.8](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.7...v0.7.8) (2020-10-20)


### Bug Fixes

* 1) update mvn dep:tree to support multi-module projects. 2) add dedupe logic to the component list ([#99](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/99)) ([afaa7f4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/afaa7f46bea96b0ace01562572729de202529e49))

## [0.7.7](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.6...v0.7.7) (2020-10-09)


### Bug Fixes

* Add in ability to publish to Open VSX ([#126](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/126)) ([6421d21](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/6421d21de6d4719bbf7251ff2cb0943af3e02fe9))

## [0.7.6](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.5...v0.7.6) (2020-10-06)


### Bug Fixes

* Trim trailing slash on construction of IQRequestService for [#122](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/122) ([#123](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/123)) ([d580634](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/d580634bde9dcffcdc6a9e5e57ddb935ab2a719e))

## [0.7.5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.4...v0.7.5) (2020-09-15)


### Bug Fixes

* Remove yarn.lock, run npm i ([#96](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/96)) ([96194e0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/96194e01e1276f7299816a152c137a9affb4e0e2))

## [0.7.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.3...v0.7.4) (2020-04-01)


### Bug Fixes

* Make Python work for Windows ([#88](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/88)) ([5a0fe66](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/5a0fe668edcb13d2feea2fd7d772b757450e1664))

## [0.7.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.2...v0.7.3) (2020-03-10)


### Bug Fixes

* update changelog.md to 0.7.2 ([bfc1057](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/bfc10572705f11cb035f58750b49d6ea5da961f3))
* update package-lock.json to 0.7.2 ([bbfe78e](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/bbfe78e0d415a2a96367079c04c19c0c234d16c4))
* update package.json for 0.7.2 manually ([78e11aa](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/78e11aafff6385dc4b418cd78a5e71fe2d332a8e))
* update semantic-release git to 7.10.0-beta for now ([c7ca635](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/c7ca635ac83ec5dd3da66708521916cf19cd7228))
* Updating getWorkspaceRoot ([#84](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/84)) ([1dafca8](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/1dafca812afd81db1edde6eb9d27483f781c0cb0))

## [0.7.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.1...v0.7.2) (2020-02-21)


### Bug Fixes

* make it work for both, why not ([9f14d50](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/9f14d50b764abb66fb3664e43312086b52ed7756))
* Update CircleCI to newer node ([12a25db](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/12a25db19e419abea588030f66e5e13425cadd6b))
* version history fixed for newer IQ clients ([62f9348](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/62f93489c005c9e8d31b4a1c024510cda5c38767))


## [0.7.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.7.0...v0.7.1) (2019-12-17)


### Bug Fixes

* Fix market place link ([#76](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/76)) ([72ff663](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/72ff663f5caa0c115bf83fd2ed1f0c296945ad6b))

# [0.7.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.6.6...v0.7.0) (2019-12-17)


### Features

* **sorting:** default sort policy descending ([#75](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/75)) ([9a6e209](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/9a6e209545d5113555d156fa6abb1c5e18dbe82b))

## [0.6.6](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.6.5...v0.6.6) (2019-12-13)

### Bug Fixes

- tiny tweak ([02b3f60](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/02b3f60))

## [0.6.5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.6.4...v0.6.5) (2019-12-13)

### Bug Fixes

- dag nabbit, fix badge ([635c0c8](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/635c0c8))

## [0.6.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.6.3...v0.6.4) (2019-12-13)

### Bug Fixes

- Fix link for VS Code Marketplace badge ([4d44b6d](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/4d44b6d))

## [0.6.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.6.2...v0.6.3) (2019-12-13)

## [0.6.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.6.1...v0.6.2) (2019-12-13)

## [0.6.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.6.0...v0.6.1) (2019-12-13)

### Bug Fixes

- Improve changelog ([4a2033c](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/4a2033c))

# [0.6.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.5.3...v0.6.0) (2019-12-11)

### Features

- Improve UX of Scans, etc... so that the user knows what is going on ([#69](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/69)) ([d7a68d0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/d7a68d0))

## [0.5.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.5.2...v0.5.3) (2019-12-10)

## [0.5.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.5.1...v0.5.2) (2019-12-10)

### Bug Fixes

- Workspace rootPath deprecation, move to new method and leave comment on why ([65d035c](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/65d035c))

## [0.5.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.5.0...v0.5.1) (2019-12-10)

### Bug Fixes

- some more robust handling of npm list, yarn list, etc... ([e5822a1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/e5822a1))

# [0.5.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.4.4...v0.5.0) (2019-12-10)

### Features

- Show what we can for people using dep in the Golang world ([#64](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/64)) ([7c9b1e9](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/7c9b1e9))

## [0.4.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.4.3...v0.4.4) (2019-12-10)

### Bug Fixes

- we do not really use jquery, but update the version to fake out everything ([affa8e1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/affa8e1))

## [0.4.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.4.2...v0.4.3) (2019-12-10)

### Bug Fixes

- choose your master, Elvis wins ([9e29038](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/9e29038))

## [0.4.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.4.1...v0.4.2) (2019-12-10)

### Bug Fixes

- remove empty reject so we get some info ([2e06f9f](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/2e06f9f))

## [0.4.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.4.0...v0.4.1) (2019-12-10)

### Bug Fixes

- throw error on npm issues ([7aca28c](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/7aca28c))

# [0.4.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.3.1...v0.4.0) (2019-12-09)

### Features

- NPM multi type parser ([#63](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/63)) ([1e8aa37](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/1e8aa37))

## [0.3.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.3.0...v0.3.1) (2019-12-02)

### Bug Fixes

- User Agent string ([a743e41](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/a743e41))

# [0.3.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.2.6...v0.3.0) (2019-11-26)

### Features

- Added R capability ([b3af942](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/b3af942))

## [0.2.6](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.2.5...v0.2.6) (2019-11-26)

### Bug Fixes

- match types with vs code engine ([8e30a3e](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/8e30a3e))

## [0.2.5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.2.4...v0.2.5) (2019-11-26)

### Bug Fixes

- just do a tiny release to see if R works when packaged ([#62](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/62)) ([b8d4241](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/b8d4241))

## [0.2.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.2.3...v0.2.4) (2019-11-26)

### Bug Fixes

- to use typing instead of old package to fix a DepShield issue ([#60](https://github.com/sonatype-nexus-community/vscode-iq-plugin/issues/60)) ([21a61d1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/21a61d1))

## [0.2.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.2.2...v0.2.3) (2019-11-26)

### Bug Fixes

- temp fix to PyPI for IQ to get results, set extension to tar.gz for now ([25eed9d](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/25eed9d))

## [0.2.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.2.1...v0.2.2) (2019-11-25)

### Bug Fixes

- update Extension code ([0e0333d](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/0e0333d))

## [0.2.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.2.0...v0.2.1) (2019-11-25)

# [0.2.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.1.3...v0.2.0) (2019-11-25)

### Features

- Add RubyGems OSS Index capability ([d187ae4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/d187ae4))

## [0.1.3](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.1.2...v0.1.3) (2019-11-22)

### Bug Fixes

- re-exclude ext-src/ ([2177797](https://github.com/sonatype-nexus-community/vscode-iq-plugin/commit/2177797))

## [0.1.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.1.1...v0.1.2) (2019-11-22)

## [0.1.1](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.1.0...v0.1.1) (2019-11-22)

# [0.1.0](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.0.5...v0.1.0) (2019-11-22)

## [0.0.5](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.0.4...v0.0.5) (2019-11-22)

## [0.0.4](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.0.3...v0.0.4) (2019-11-22)

## [0.0.2](https://github.com/sonatype-nexus-community/vscode-iq-plugin/compare/v0.0.1...0.0.2) (2019-06-13)

## 0.0.1 (2019-05-30)

- Initial release of Sonatype Nexus IQ VS Code Extension with GUI
- NPM scanning
- Security details
- Version history
- License Id
- link to Wikipedia license article
