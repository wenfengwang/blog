---
id: 5pqijcoc
title: CHANGELOG
file_version: 1.1.3
app_version: 1.14.2
---

### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.

#### [Unreleased](https://github.com/browserify/resolve/compare/v1.9.0...HEAD)

*   \[Fix\] `sync`/`async`: when package.json `main` is not a string, throw an error (\[`#178`\]\[\])

*   \[Tests\] up to `v11.6`, `v10.15`, `v8.15`, `v6.16` (([code class="code-span"083e78c](https://github.com/browserify/resolve/commit/083e78c1ae5c1708b7d41c9ad7c608caffeddcbf))

*   \[Dev Deps\] update `eslint`, `@ljharb/eslint-config`, `tape` (([code class="code-span"29a4994](https://github.com/browserify/resolve/commit/29a499418d54b5befe9deef1bc7c38a9174cfbd8))

*   \[Tests\] add an additional test (([code class="code-span"2c67936](https://github.com/browserify/resolve/commit/2c679363e852f7a0d570593527ea7038f0cd2c19))

#### [v1.9.0](https://github.com/browserify/resolve/compare/v1.8.1...v1.9.0) - 17 December 2018

*   \[Fix\] `sync`/`async`: fix `preserveSymlinks` option (\[`#177`\]\[\])

*   \[Fix\] `sync`/`async`: when package.json `main` is not a string, throw an error (\[`#178`\]\[\])

*   \[Refactor\] `node-modules-paths`: Change `paths` function option to receive a thunk for node modules resolution paths (([code class="code-span"d652f01](https://github.com/browserify/resolve/commit/d652f018b2561f4863ffcd0f3ecdb0dfe65ee223))

*   \[Tests\] up to `node` `v11.4`, `v10.14`, `v8.14`, `v6.15` (([code class="code-span"2b4f3a8](https://github.com/browserify/resolve/commit/2b4f3a898a3943e45cdff539b542c4ebee2b608a))

*   \[New\] `async`/`sync`/`node-modules-paths`: Adds support for “paths” being a function (([code class="code-span"7112873](https://github.com/browserify/resolve/commit/711287339aad544788a4b8b5335221cea645572c))

*   \[Dev Deps\] update `eslint`, `@ljharb/eslint-config`, `object-keys`, `safe-publish-latest`, `tape` (([code class="code-span"5542700](https://github.com/browserify/resolve/commit/554270035e1997ae34865500c629888249baa304))

*   \[New\] Implements a "normalize-options" pseudo-hook (([code class="code-span"f3961df](https://github.com/browserify/resolve/commit/f3961dfcb7b2993d935c255e65309e7028a88b8d))

*   \[Tests\] better failure messages (([code class="code-span"f839d20](https://github.com/browserify/resolve/commit/f839d20ab16ef814214d80183452d02379cbbf15))

*   \[Deps\] update `path-parse` (([code class="code-span"1018c0e](https://github.com/browserify/resolve/commit/1018c0e49851bfb62176d8adbc94125ae85cd158))

#### [v1.8.1](https://github.com/browserify/resolve/compare/v1.8.0...v1.8.1) - 17 June 2018

*   \[Docs\] clean up readme code (([code class="code-span"f5394d8](https://github.com/browserify/resolve/commit/f5394d801350ff32be08dfc5ca37bcb677b4c08b))

*   \[Fix\] resolution when `filename` option is passed (([code class="code-span"9c370c9](https://github.com/browserify/resolve/commit/9c370c9848eaecb36fb8e0b004930e2dd49e1e71))

*   \[Tests\] up to `node` `v10.4` (([code class="code-span"3a64219](https://github.com/browserify/resolve/commit/3a64219a7385d5d51f3d4ff7b3de0ce749d6cf09))

*   \[Tests\] improve output of symlink tests that fail on Mac (([code class="code-span"6f771b2](https://github.com/browserify/resolve/commit/6f771b215b4f40b0ba0009ef564bde85212e79eb))

#### [v1.8.0](https://github.com/browserify/resolve/compare/v1.7.1...v1.8.0) - 15 June 2018

*   \[New\] include filename in error message ([code class="code-span"#162](https://github.com/browserify/resolve/pull/162))

*   \[Tests\] up to `node` `v10.1`, `v9.11`, `v8.11`, `v6.14`, `4.9` (([code class="code-span"ad16af2](https://github.com/browserify/resolve/commit/ad16af2f4f6eb1dc964f5b119f6d94bd64b2607a))

*   Fix eslint problems and update count of tests (([code class="code-span"def5931](https://github.com/browserify/resolve/commit/def59317704d787adcddc9695b923e65c6bf5232))

*   \[New\] add fs/promises to the list of core modules (([code class="code-span"756419a](https://github.com/browserify/resolve/commit/756419a94432fd753a62f5a58b797776efb543f9))

*   \[New\] core: add `trace_events`, `v8/tools/arguments` (([code class="code-span"bae0338](https://github.com/browserify/resolve/commit/bae033824c82153ccb4f32abdd0e70ca677968bc))

*   \[Fix\] core: `_tls_legacy` is removed in node 10 (([code class="code-span"4225ac5](https://github.com/browserify/resolve/commit/4225ac5f4b90d26db664ed32f5b08416fea69b86))

#### [v1.7.1](https://github.com/browserify/resolve/compare/v1.7.0...v1.7.1) - 12 April 2018

*   \[Fix\] revert proper but unintended breaking change in sync packageFilter (\[`#157`\]\[\])

#### [v1.7.0](https://github.com/browserify/resolve/compare/v1.6.0...v1.7.0) - 7 April 2018

*   \[Fix\] Make loadAsFileSync() work the same as async loadAsFile() ([code class="code-span"#146](https://github.com/browserify/resolve/pull/146))

*   \[Tests\] add more pathfilter tests (([code class="code-span"c3621a3](https://github.com/browserify/resolve/commit/c3621a35675b275b2b241dd367459ed7afe1c22a))

*   \[Tests\] add some tests for browser field (([code class="code-span"13fb572](https://github.com/browserify/resolve/commit/13fb572337623622d06450696af6c15b68be26c3))

*   \[Refactor\] cache default isFile functions at module level (([code class="code-span"fa6e6f5](https://github.com/browserify/resolve/commit/fa6e6f5a2d34377f6973701733177a280adf0511))

*   \[Docs\] fix default “isFile” implementations (([code class="code-span"0f29c93](https://github.com/browserify/resolve/commit/0f29c93f0c74fc4e52ec6ed6678ce0fec6347e2d))

*   \[Tests\] add some tests for a non-directory basedir (([code class="code-span"0c18e40](https://github.com/browserify/resolve/commit/0c18e40e4929ba2c9426a77079c153c43e50a025))

*   \[Refactor\] use "basedir" instead of "y", because meaningful variable names (([code class="code-span"876b0b0](https://github.com/browserify/resolve/commit/876b0b08da9fe44d81681d0c815900485536be9e))

*   \[Docs\] fix options formatting (([code class="code-span"23df5f5](https://github.com/browserify/resolve/commit/23df5f526823e27e33b01333016b7f58b4f63b6f))

*   Minor cleanup (([code class="code-span"c449d48](https://github.com/browserify/resolve/commit/c449d4809cf8461a3d54e458780902b95119a969))

*   \[Fix\] support `opts.package` in non-relative lookups (([code class="code-span"c8a2052](https://github.com/browserify/resolve/commit/c8a20524c7d08671c22903e70b952575b0502f7b))

*   \[Tests\] work around npm SSL issue (([code class="code-span"04cb0bb](https://github.com/browserify/resolve/commit/04cb0bb94628e560bfa4163e73637d3803591714))

*   \[Tests\] add node 8 and 9 to appveyor (([code class="code-span"7cbd17a](https://github.com/browserify/resolve/commit/7cbd17ae270f9ec24ef05779c3a5e9da3e75c598))

*   \[Tests\] work around npm SSL issue (([code class="code-span"4b10996](https://github.com/browserify/resolve/commit/4b1099668477e28117c34f9db3509ff096a49190))

#### [v1.6.0](https://github.com/browserify/resolve/compare/v1.5.0...v1.6.0) - 20 March 2018

*   \[New\] add `async_hooks` core module, added in node 8 (\[`#144`\]\[\])

*   \[New\] add many missing core modules. (([code class="code-span"88c0778](https://github.com/browserify/resolve/commit/88c0778be359caaeb4ca74b24a7b5f7903bc39e8))

*   Made loadAsFileSync() work the same as async loadAsFile(). (([code class="code-span"dc23387](https://github.com/browserify/resolve/commit/dc23387adb93f497d67def7ee99fae48e5958fb3))

*   \[Tests\] up to `v9.8`, `v8.10`, `v6.13` (([code class="code-span"315d729](https://github.com/browserify/resolve/commit/315d729afe7074ffae5d6ca6509a73d747985d45))

*   \[Tests\] up to `node` `v9.3`, `v8.8`, `v6.12`; pin included builds to LTS (([code class="code-span"5091aa2](https://github.com/browserify/resolve/commit/5091aa2c076b67ff762937401e81da66ef7988ca))

*   \[Tests\] add a failing test (([code class="code-span"90b1192](https://github.com/browserify/resolve/commit/90b11921181c2783209e9aa31f1e20d98c11ed17))

*   \[Dev Deps\] update `eslint`, `tape` (([code class="code-span"2acf953](https://github.com/browserify/resolve/commit/2acf953ce2a94b38528372b5f8848ac95a2aabe5))

*   \[Tests\] restore node 0.6 (([code class="code-span"2764758](https://github.com/browserify/resolve/commit/2764758aae576aef98f41af5d46f76ada3523012))

*   \[Dev Deps\] update `eslint` (([code class="code-span"699a54e](https://github.com/browserify/resolve/commit/699a54e91222dc8b3e1f0af8e9859c734d99d50a))

*   \[Dev Deps\] update `eslint` (([code class="code-span"2674fad](https://github.com/browserify/resolve/commit/2674fadcfcf2b253fdcf5e9d8564fd2b23b0b57c))

#### [v1.5.0](https://github.com/browserify/resolve/compare/v1.4.0...v1.5.0) - 24 October 2017

*   \[New\] node v8.8+ supports `http2` (\[`#139`\]\[\])

*   \[Fix\] fix broken core tests; change core.json to be an object instead of an array; fix results (([code class="code-span"b826f30](https://github.com/browserify/resolve/commit/b826f3007dc8903b95e39984f93c68bb5e4c85b9))

*   \[Tests\] up to `v8.4`; node 0.6 is failing due to travis-ci changes; allow it to fail for now. (([code class="code-span"e9d3a24](https://github.com/browserify/resolve/commit/e9d3a24ae0a4d8e3eefc6431c918c23f7c8fc6d3))

*   \[Tests\] up to `node` `8.7`; use `nvm install-latest-npm` so new npm doesn’t break old node (([code class="code-span"d0de222](https://github.com/browserify/resolve/commit/d0de222e4b55b67224ddec0421ee66ce8cb5ee8d))

*   \[Dev Deps\] update `eslint`, `@ljharb/eslint-config`, `tape` (([code class="code-span"76f28a3](https://github.com/browserify/resolve/commit/76f28a3d275a63b0511449d28900ab5749f27fa5))

*   \[Tests\] on `node` `v8.8` (([code class="code-span"e0c5d51](https://github.com/browserify/resolve/commit/e0c5d518abfaadc4107ca8f3f8c30caf46490444))

*   \[Docs\] update repo URL (([code class="code-span"3412f98](https://github.com/browserify/resolve/commit/3412f984a03a345b9a5ef1f0642a0308d676a2c2))

*   \[New\] add `perf_hooks`, added in node v8.5 (([code class="code-span"e66117d](https://github.com/browserify/resolve/commit/e66117df49d9f967b46fde633770307c9d5a7066))

*   \[Dev Deps\] update `eslint` (([code class="code-span"5bfb072](https://github.com/browserify/resolve/commit/5bfb072f152c77c8247f4c06c1efa9246bbdddb0))

#### [v1.4.0](https://github.com/browserify/resolve/compare/v1.3.3...v1.4.0) - 26 July 2017

*   \[New\]: add `preserveSymlinks` option (\[`#130`\]\[\])

*   \[Fix\] `sync`: fix when package.json main = ‘.’ or main = ‘./‘ (\[`#125`\]\[\])

*   \[Tests\] up to `node` `v8.2`, `v7.10`, `v6.11`; npm 4.6+ breaks on node < 4 (([code class="code-span"41a3604](https://github.com/browserify/resolve/commit/41a3604f6408dbe9693febf895251db924c87a8f))

*   \[Tests\] fix 0.6 and linting (([code class="code-span"703517b](https://github.com/browserify/resolve/commit/703517b78e7e0f8093a79c0a7a413a708ac82d06))

*   Only apps should have lockfiles (([code class="code-span"11fb3d8](https://github.com/browserify/resolve/commit/11fb3d85bb107a24476bd8d764ba25b3c60c184a))

*   \[Dev Deps\] update `eslint`, `@ljharb/eslint-config`, `tape` (([code class="code-span"bc2f7bf](https://github.com/browserify/resolve/commit/bc2f7bf29d172fa54d66cf909fb47a858f7765aa))

#### [v1.3.3](https://github.com/browserify/resolve/compare/v1.3.2...v1.3.3) - 20 April 2017

*   \[Fix\] error code MODULE\_NOT\_FOUND instead of ENOTDIR (\[`#121`\]\[\])

*   \[Tests\] \[eslint\] add `npm run lint` (([code class="code-span"3677928](https://github.com/browserify/resolve/commit/36779282881ec4abce32b2c9b7f7b10bcd09d953))

*   \[Tests\] up to `node` `v7.7`, `v6.10`, `v4.8`; comment out OSX builds since they block linux builds. (([code class="code-span"1d3883c](https://github.com/browserify/resolve/commit/1d3883c40d55242d7dfeafa43fa782dc6f4ab4a6))

*   \[Fix\] correctly resolve dir paths when file with the same name exists (([code class="code-span"a983d38](https://github.com/browserify/resolve/commit/a983d38c47ea26e57e0824f22929985ecb24faca))

*   \[Tests\] up to `node` `v7.9` (([code class="code-span"0da055c](https://github.com/browserify/resolve/commit/0da055cc75bebd7e0044cd4184e7c5386a7bd7de))

*   \[Tests\] improve failure scenarios. (([code class="code-span"1de578f](https://github.com/browserify/resolve/commit/1de578f2879f83ba94789041420fd3d3b929127e))

*   \[Fix\] `sync`: ensure that the path is a string, explicitly. (([code class="code-span"b7ba83d](https://github.com/browserify/resolve/commit/b7ba83d43519c3c77af823ef1badd7f452d8b8e3))

*   \[Dev Deps\] update `eslint` (([code class="code-span"452fdf9](https://github.com/browserify/resolve/commit/452fdf981330f96d7fef88805b24e40ea24a89e1))

*   \[Tests\] node 0.6 can’t support an npm that understands scoped packages (([code class="code-span"26369cf](https://github.com/browserify/resolve/commit/26369cfe6ce4eae7404f3c003c88618f098d6814))

#### [v1.3.2](https://github.com/browserify/resolve/compare/v1.2.1...v1.3.2) - 26 February 2017

*   Fix prepublish script. (([code class="code-span"1aa1d9d](https://github.com/browserify/resolve/commit/1aa1d9d9adc60691431efbde8d915c143cd54916))

#### [v1.3.1](https://github.com/browserify/resolve/compare/v1.3.0...v1.3.1) - 24 February 2017

*   Revert "\[New\] add searched extensions to error messages" (([code class="code-span"68a081d](https://github.com/browserify/resolve/commit/68a081d1c7ff6e0fb58aeff4b6ac06aada7812c4))

#### [v1.3.0](https://github.com/browserify/resolve/compare/v1.2.0...v1.3.0) - 24 February 2017

#### [v1.2.1](https://github.com/browserify/resolve/compare/v1.3.1...v1.2.1) - 26 February 2017

*   \[Fix\] for browserify compat, do not assume `process.versions.node` exists. (\[`#120`\]\[\])

*   \[Fix\] for browserify compat, do not assume `process.versions.node` exists. (\[`#120`\]\[\])

#### [v1.2.0](https://github.com/browserify/resolve/compare/v1.1.7...v1.2.0) - 13 December 2016

*   \[Fix\] `resolve.sync` should re-throw non `ENOENT errors. ([`#79\`\]\[\])

*   \[New\] add missing core modules, and determine them dynamically by node version. (\[`#100`\]\[\]\[`#110`\]\[\]\[`#111`\]\[\]\[`#112`\]\[\])

*   \[Tests\] test on every minor version of node. (\[`#109`\]\[\]\[`#75`\]\[\]\[`#74`\]\[\]\[`#70`\]\[\])

*   code style: tabs → spaces (([code class="code-span"0ab33b2](https://github.com/browserify/resolve/commit/0ab33b29b814e030021ff2df391e60a1c52dcc46))

*   \[Dev Deps\] add `safe-publish-latest` (([code class="code-span"83c25dd](https://github.com/browserify/resolve/commit/83c25dde8aa5a663bc3863d946fdc62fab5fd080))

*   \[Fix\] Create error outside process.nextTick (([code class="code-span"3fa5f02](https://github.com/browserify/resolve/commit/3fa5f02f2ace0683fbd42196619c4e2bbd9eef60))

*   readme: update API docs link for require.resolve() (([code class="code-span"7e98547](https://github.com/browserify/resolve/commit/7e98547319f1dada4f26d7a24f3b92a08f85c56b))

*   \[Dev Deps\] update `tape` (([code class="code-span"764f3a2](https://github.com/browserify/resolve/commit/764f3a231c26c370c4e6b94f0bb10166c20551b7))

*   gitignore node\_modules (([code class="code-span"3e8a8da](https://github.com/browserify/resolve/commit/3e8a8da3c9d545e00e15f5bed24623eb134b2221))

#### [v1.1.7](https://github.com/browserify/resolve/compare/v1.1.6...v1.1.7) - 24 January 2016

*   (typo) Change againt to against ([code class="code-span"#83](https://github.com/browserify/resolve/pull/83))

*   Fix node\_modules paths on Windows (([code class="code-span"35b2b64](https://github.com/browserify/resolve/commit/35b2b642d91e9b81e7cc26b6fd19912e18901d55))

#### [v1.1.6](https://github.com/browserify/resolve/compare/v1.1.5...v1.1.6) - 15 March 2015

*   Use path.dirname to walk up looking for a package.json (\[`#76`\]\[\])

*   add back pkg assertions to pick up the root package (([code class="code-span"4c25e45](https://github.com/browserify/resolve/commit/4c25e45625fea7980463fc107fc843aab7e0d993))

#### [v1.1.5](https://github.com/browserify/resolve/compare/v1.1.4...v1.1.5) - 21 February 2015

*   another test, not quite the failing case (([code class="code-span"612cac2](https://github.com/browserify/resolve/commit/612cac2beac41fb13b7b12a9dfdb4207391260c1))

*   fix for the failing case (([code class="code-span"503c746](https://github.com/browserify/resolve/commit/503c746a6e64d50f2c9b18b4476ffcfed49947f2))

#### [v1.1.4](https://github.com/browserify/resolve/compare/v1.1.3...v1.1.4) - 20 February 2015

*   finally seems to fully handle browser field from outside foo/bar resolution (([code class="code-span"5b737d5](https://github.com/browserify/resolve/commit/5b737d58b38ce891ef3f06d600d0562dbbc8539c))

*   flatter nodeModules function (([code class="code-span"5ebb39a](https://github.com/browserify/resolve/commit/5ebb39a19b62c052ff6201600c3d2fffb3f5fdcb))

#### [v1.1.3](https://github.com/browserify/resolve/compare/v1.1.2...v1.1.3) - 17 February 2015

*   re-implemented pathfilter feature nearly passes the test (([code class="code-span"60ff554](https://github.com/browserify/resolve/commit/60ff5545ec3cd15367c89c08cf3f139fa9c23796))

*   another precedence test (([code class="code-span"98d22e0](https://github.com/browserify/resolve/commit/98d22e0e21dd57fe1ab8d9573c1f63903c2b7321))

*   move pathfilter test to its own file (([code class="code-span"90826f5](https://github.com/browserify/resolve/commit/90826f575fe37cb3852de17e764b62e3754484b2))

*   path logic fix that seems to handle all the cases across this package and browserify (([code class="code-span"70146a5](https://github.com/browserify/resolve/commit/70146a5ebc4d96438383ada02785d4e722c6f5d9))

*   tape everywhere (([code class="code-span"47bbfcd](https://github.com/browserify/resolve/commit/47bbfcd9d9c8a68ce97fa37e0563930cee67093d))

*   move pathfilter files into their own dir (([code class="code-span"7f0a3f1](https://github.com/browserify/resolve/commit/7f0a3f1545f4b53f1bdd099b67561f9516693325))

*   failing precedence test (([code class="code-span"73e958e](https://github.com/browserify/resolve/commit/73e958e905eed000787f0596f81c212ca2cdb3b3))

*   nearly nearly working (([code class="code-span"e7bffbf](https://github.com/browserify/resolve/commit/e7bffbf1b39b6239732c0e7fb01eeb9dad605d15))

*   packageFilter should have been giving the pkgfile as an argument, fixed (([code class="code-span"70b71e7](https://github.com/browserify/resolve/commit/70b71e7980b3235018a0f5ac0bd52b8393548beb))

*   this fixes the directory precedence problem (([code class="code-span"caca9f9](https://github.com/browserify/resolve/commit/caca9f9c3576c85d8972d25012ea5d12aeaa50f4))

*   disable faulty basedir test except on windows for now (([code class="code-span"3be4b79](https://github.com/browserify/resolve/commit/3be4b796f1a9aadfb293b36c0c7f781ca9169f09))

*   passes pathfilter test (([code class="code-span"644f814](https://github.com/browserify/resolve/commit/644f81478c892874f9829aa6cca36ca72474db00))

*   fix node\_path test, was clearly wrong for some reason (([code class="code-span"9aa36e7](https://github.com/browserify/resolve/commit/9aa36e77eca50e177498984fdef5d564903d3964))

#### [v1.1.2](https://github.com/browserify/resolve/compare/v1.1.0...v1.1.2) - 16 February 2015

*   Adding pathFilter docs ([code class="code-span"#67](https://github.com/browserify/resolve/pull/67))

*   adding pathFilter docs (([code class="code-span"44480ff](https://github.com/browserify/resolve/commit/44480ff041f791f32b80d212302180be210901a1))

#### [v1.1.0](https://github.com/browserify/resolve/compare/v1.0.0...v1.1.0) - 27 January 2015

*   Update docs re: input and cb args. ([code class="code-span"#65](https://github.com/browserify/resolve/pull/65))

*   Update main README--change word order for clarity ([code class="code-span"#55](https://github.com/browserify/resolve/pull/55))

*   attempts to find package.json data for deep references [https://github.com/substack/node-resolve/issues/62](https://github.com/substack/node-resolve/issues/62) (([code class="code-span"caff2ba](https://github.com/browserify/resolve/commit/caff2ba60dc5d85eaded388dc6025afd05ba183b))

*   formatting (([code class="code-span"b8d09e3](https://github.com/browserify/resolve/commit/b8d09e3a2d679f6b61515d49eca3f6d8d0d2ac7f))

*   Add failing test for parent filename in error msg. (([code class="code-span"96d38c6](https://github.com/browserify/resolve/commit/96d38c6aaa575d12781c28b34243b4939359a335))

*   split before computing the pivot to prevent abcnode\_modulesxyz from matching (([code class="code-span"10380e1](https://github.com/browserify/resolve/commit/10380e16d3cf03f25941c3f1545ef73ed11bc1e1))

*   Utilize opts.filename when available to ID parent. (([code class="code-span"f6edcd9](https://github.com/browserify/resolve/commit/f6edcd95ad5d27bfbdee0fa51951aa3d45d77cba))

### [v1.0.0](https://github.com/browserify/resolve/compare/v0.7.4...v1.0.0) - 11 August 2014

*   reformat package.json (([code class="code-span"695bbc1](https://github.com/browserify/resolve/commit/695bbc1d9eeb35339b4a01e141c6f6e1dff3a6e3))

#### [v0.7.4](https://github.com/browserify/resolve/compare/v0.7.3...v0.7.4) - 25 July 2014

*   merged (([code class="code-span"5cae82f](https://github.com/browserify/resolve/commit/5cae82fb22cb64d5b72f703c787dc0fd418ed412))

#### [v0.7.3](https://github.com/browserify/resolve/compare/v0.7.2...v0.7.3) - 25 July 2014

*   cb(err) for non-string args (([code class="code-span"965c70b](https://github.com/browserify/resolve/commit/965c70b27ff796fc0ac3dba186d95b61d82446df))

#### [v0.7.2](https://github.com/browserify/resolve/compare/v0.7.1...v0.7.2) - 25 July 2014

*   failing dotdot test (([code class="code-span"3ee0f0e](https://github.com/browserify/resolve/commit/3ee0f0eb97971d246a4a3f183374f60938f1ca8a))

*   fixes for dotdot tests (([code class="code-span"a67f230](https://github.com/browserify/resolve/commit/a67f230133050568ca14a04c0d36aaf6bf14fa89))

*   failing sync dotdot test (([code class="code-span"55515e7](https://github.com/browserify/resolve/commit/55515e7f816571fb9d71fdd6d0f012185b2eeefb))

#### [v0.7.1](https://github.com/browserify/resolve/compare/v0.7.0...v0.7.1) - 9 June 2014

*   \[Fix\] `node-modules-paths`: `opts` should be optional, and `opts.paths` should not be concatenated when omitted. (\[`#96`\]\[\])

*   \[Refactor\] consistent spacing and quotes; run some basic linting manually. (([code class="code-span"f63faaf](https://github.com/browserify/resolve/commit/f63faaf9df5dbd8da388c674de0b14e3286e5e91))

*   \[Tests\] use `path.join` more often to normalize paths across OS’s. (([code class="code-span"8280c53](https://github.com/browserify/resolve/commit/8280c53eae6b612f586e133052ed2b2a56ae6649))

*   \[Tests\] use `path` methods to make tests pass on both linux and Windows. (([code class="code-span"af9a885](https://github.com/browserify/resolve/commit/af9a8858a618ab64dd4bb311ef1be37822ade2b7))

*   \[Tests\] make matrix more efficient (([code class="code-span"7f0ce87](https://github.com/browserify/resolve/commit/7f0ce871b6d2b5cb2082b04cd72ddd4055cb7a05))

*   \[Tests\] fix indentation, manual linting. (([code class="code-span"6984dcb](https://github.com/browserify/resolve/commit/6984dcb1407fec6af46f744ad2c63f502645bdd6))

*   \[Tests\] \[Refactor\] refactor `node-modules-paths` and add tests. (([code class="code-span"58b99a3](https://github.com/browserify/resolve/commit/58b99a36f882d7ee65df725224f204abd27379db))

*   \[Tests\] add `appveyor` (([code class="code-span"caffe35](https://github.com/browserify/resolve/commit/caffe358566bb3c2f9b4cbd8c0f910debfb6df3b))

*   \[new\] Add err.code = 'MODULE\_NOT\_FOUND' (([code class="code-span"c622aef](https://github.com/browserify/resolve/commit/c622aefeb286e479d536601e30bb828e69f86ec3))

*   \[New\] add searched extensions to error messages (([code class="code-span"1260d9d](https://github.com/browserify/resolve/commit/1260d9d1e2f55efb514540db9aa1b3d679f9db10))

*   node-modules-paths: absolutize the `start` path (([code class="code-span"9d6b7af](https://github.com/browserify/resolve/commit/9d6b7af28c054676d6ea8a5037353ed750ea13bb))

*   \[Refactor\] `async`: remove unnecessary slashes, since `path.join` adds them. (([code class="code-span"dd50615](https://github.com/browserify/resolve/commit/dd506158089f7d071d2a9f61cd4385365d177219))

*   \[Tests\] ensure node\_path test is independent of the `tap` module’s “main” (([code class="code-span"ddca9ed](https://github.com/browserify/resolve/commit/ddca9ed7e1d980d5ec561450875cb09463effd5a))

#### [v0.7.0](https://github.com/browserify/resolve/compare/v0.6.3...v0.7.0) - 17 May 2014

*   array opts.moduleDirectory tests (([code class="code-span"0f6d088](https://github.com/browserify/resolve/commit/0f6d08801db6bc2044df8767226421172a2d9461))

*   opts.moduleDirectory string tests (([code class="code-span"a15ffd6](https://github.com/browserify/resolve/commit/a15ffd6c20772831c41146189c117ab0a0650e0b))

*   Support more than one directory in opts.moduleDirectory. (([code class="code-span"4183463](https://github.com/browserify/resolve/commit/41834633e84d76d86297968ba34c375f26fe4f08))

*   formatting (([code class="code-span"b89f089](https://github.com/browserify/resolve/commit/b89f08902e8551e07d66e81a3dc33840e24266c5))

*   Remove variable leftover from 325584a685 (([code class="code-span"12fa78c](https://github.com/browserify/resolve/commit/12fa78ce43c4363e1c9600b635d18cd295c6949f))

#### [v0.6.3](https://github.com/browserify/resolve/compare/v0.6.2...v0.6.3) - 16 April 2014

*   Fixed the case when main is specified as "." or "./" causing the resolve to infinite loop as documented at [https://github.com/substack/node-browserify/issues/732](https://github.com/substack/node-browserify/issues/732). (([code class="code-span"b11f273](https://github.com/browserify/resolve/commit/b11f2739ad8c9730e1076271eff54850755e2ee1))

#### [v0.6.2](https://github.com/browserify/resolve/compare/v0.6.1...v0.6.2) - 21 March 2014

*   passing tests for paths (([code class="code-span"4f56bb6](https://github.com/browserify/resolve/commit/4f56bb67fa45d35adfa6a0022cc77afbf8117234))

*   faulty basedir does not always produce error properly in windows, because when the dirs are sliced down the final path has improper prefix, causing it to load relative to cwd (([code class="code-span"110168a](https://github.com/browserify/resolve/commit/110168adae1dfbedcb9a12086cacf0ce68cc67f6))

#### [v0.6.1](https://github.com/browserify/resolve/compare/v0.6.0...v0.6.1) - 27 November 2013

*   merged the context error patches (([code class="code-span"8408e6e](https://github.com/browserify/resolve/commit/8408e6e8902b4bec8c859d606f53366e42058378))

#### [v0.6.0](https://github.com/browserify/resolve/compare/v0.5.1...v0.6.0) - 26 November 2013

*   fixes #25: resolve modules with the same name as node stdlib modules (\[`#25`\]\[\])

#### [v0.5.1](https://github.com/browserify/resolve/compare/v0.5.0...v0.5.1) - 22 September 2013

*   Separate duplicated nodeModulesPaths function (([code class="code-span"325584a](https://github.com/browserify/resolve/commit/325584a685db8f42aae3d4876ffbe64069233601))

*   Fix prefix for windows azure (([code class="code-span"b5ba043](https://github.com/browserify/resolve/commit/b5ba0430b012d93367a4f87c304f1d4c8c22941c))

#### [v0.5.0](https://github.com/browserify/resolve/compare/v0.4.3...v0.5.0) - 2 September 2013

*   opts.modules => opts.moduleDirectory, documented (([code class="code-span"c46593d](https://github.com/browserify/resolve/commit/c46593de74b256196d7ea12c85422698652cff10))

*   modules folder name is configurable (([code class="code-span"d65a422](https://github.com/browserify/resolve/commit/d65a42238101ea284ddafb788debdad0e5a59504))

#### [v0.4.3](https://github.com/browserify/resolve/compare/v0.4.2...v0.4.3) - 7 August 2013

*   Fix default basedir calculation (([code class="code-span"cd7169b](https://github.com/browserify/resolve/commit/cd7169b204b9f474b6a924adf47564f33a469f07))

*   use getCaller() in both async and sync versions (([code class="code-span"20f8945](https://github.com/browserify/resolve/commit/20f89456f7fc1d8e51b95ec1ab38b1ac154d9fc4))

#### [v0.4.2](https://github.com/browserify/resolve/compare/v0.4.1...v0.4.2) - 3 August 2013

*   Failing test case for pkg.main pointing to a directory. (([code class="code-span"b57a75a](https://github.com/browserify/resolve/commit/b57a75aefc394ead20d54ed107741f1f7151b90f))

*   Fix for failing test case where pkg.main points to directory. (([code class="code-span"8c4078c](https://github.com/browserify/resolve/commit/8c4078c9dd45c6a92f1f409d70aaccc95be3bfc6))

#### [v0.4.1](https://github.com/browserify/resolve/compare/v0.4.0...v0.4.1) - 30 July 2013

*   adding tests to reproduce the problem (([code class="code-span"ad3a477](https://github.com/browserify/resolve/commit/ad3a4772ddd7187ff38cb56e00635b37a491e1fa))

*   async resolve now falls back to 'index.js' if main field in package.json is incorrect (([code class="code-span"62a5726](https://github.com/browserify/resolve/commit/62a572635f21bf1c28360ea5c2238be62736429b))

#### [v0.4.0](https://github.com/browserify/resolve/compare/v0.3.1...v0.4.0) - 9 June 2013

*   Implement async support for returning package a module was resolved from. (([code class="code-span"b7b2806](https://github.com/browserify/resolve/commit/b7b28069acb7c749a2053dbb0c8d606515954694))

*   Document package option. (([code class="code-span"7f84028](https://github.com/browserify/resolve/commit/7f8402881b725938cfaf1d4835ec2fb6cee4862d))

#### [v0.3.1](https://github.com/browserify/resolve/compare/v0.3.0...v0.3.1) - 29 March 2013

*   use isFIFO() instead to more narrowly target <() usage (([code class="code-span"790cdf5](https://github.com/browserify/resolve/commit/790cdf5ab7c92bb146e8ace05ba0b26c5f51ffb3))

*   check !isDirectory() instead of isFile() so that <(echo "beep") inline bash fds work (([code class="code-span"c396065](https://github.com/browserify/resolve/commit/c3960650f1a1417e52238011e08a6da2b0d9fee4))

#### [v0.3.0](https://github.com/browserify/resolve/compare/v0.2.8...v0.3.0) - 19 February 2013

*   failing translated async test with parameterized readFile on account of 3-arg form (([code class="code-span"7033bbb](https://github.com/browserify/resolve/commit/7033bbb6e21ecfd13476ca8de247580aa2f97e7c))

*   factor out .sync into lib/sync.js (([code class="code-span"ba7038a](https://github.com/browserify/resolve/commit/ba7038a56d78212329b64287dfaf895b1a85cf2c))

*   updated the docs for async (([code class="code-span"34a958e](https://github.com/browserify/resolve/commit/34a958e84b7fc4cdccd7b71f9a116027a6f3a123))

*   first async test passes (([code class="code-span"e427ca8](https://github.com/browserify/resolve/commit/e427ca85b7e3b1d01b05f94783b76516b8594a03))

*   sync parity with async tests (([code class="code-span"d1191a9](https://github.com/browserify/resolve/commit/d1191a9958581a040f4f18b3aecdd50714bffc7a))

*   stub out async (([code class="code-span"f4b02e3](https://github.com/browserify/resolve/commit/f4b02e3bbf0c3b09f83cfb2b22b12b0f55afdf92))

*   factor out core into lib/ (([code class="code-span"a800954](https://github.com/browserify/resolve/commit/a80095482ef2d16425e6e12759c9735d89f7f50b))

*   synchronous example (([code class="code-span"3534992](https://github.com/browserify/resolve/commit/3534992946294811d20aaf9857ee453078cbe828))

*   adapted async test (([code class="code-span"c9111d2](https://github.com/browserify/resolve/commit/c9111d293ab35fb611d9c65ea2f88ae8cf853f8e))

*   async example (([code class="code-span"e1a9809](https://github.com/browserify/resolve/commit/e1a98093094cded0a251ef36f4f2eb0adb280acb))

*   fix for async parameterized readFile (([code class="code-span"2d4e80e](https://github.com/browserify/resolve/commit/2d4e80e139d01176bf70132bc80caed946cd6682))

*   drop 0.4, add 0.8 in travis (([code class="code-span"8a1ba59](https://github.com/browserify/resolve/commit/8a1ba593ab924995a45099e164cc7b769c44e9a0))

#### [v0.2.8](https://github.com/browserify/resolve/compare/v0.2.7...v0.2.8) - 18 February 2013

*   add the domain module to .core (([code class="code-span"2979cde](https://github.com/browserify/resolve/commit/2979cdea615fe724de62d88cb221c1d1824d0f10))

#### [v0.2.7](https://github.com/browserify/resolve/compare/v0.2.6...v0.2.7) - 18 February 2013

#### [v0.2.6](https://github.com/browserify/resolve/compare/v0.2.5...v0.2.6) - 18 February 2013

#### [v0.2.5](https://github.com/browserify/resolve/compare/v0.2.4...v0.2.5) - 18 February 2013

#### [v0.2.4](https://github.com/browserify/resolve/compare/v0.2.3...v0.2.4) - 18 February 2013

*   resolve '../baz' correct (([code class="code-span"46fe923](https://github.com/browserify/resolve/commit/46fe923c20feeceac783e67cfa84d07222bc17fa))

#### [v0.2.3](https://github.com/browserify/resolve/compare/v0.2.2...v0.2.3) - 12 August 2012

*   license file (([code class="code-span"a964396](https://github.com/browserify/resolve/commit/a9643965438eb4fcb068a5876b317f516199879a))

*   existsSync (([code class="code-span"d1c1012](https://github.com/browserify/resolve/commit/d1c1012f14c50212ea49a9a1255c902f5ad6cb37))

*   pass dir to packageFilter (([code class="code-span"3bea5b6](https://github.com/browserify/resolve/commit/3bea5b6475b39e7f4974d29c6fa1e8eb8b1589af))

*   pkg.main may be a directory (([code class="code-span"3521c2f](https://github.com/browserify/resolve/commit/3521c2f2b93234e5a50dc47598554a76589d6d8c))

*   Prioritize parent tree in nodeModulesPathsSync before fallback options.paths/ NODE\_PATH equivalent, in accordance with [http://nodejs.org/docs/latest/api/all.html#all\_loading\_from\_the\_global\_folders](http://nodejs.org/docs/latest/api/all.html#all_loading_from_the_global_folders) (([code class="code-span"27fa227](https://github.com/browserify/resolve/commit/27fa22707e87738ddde61cb4ad90508cfe0d7755))

#### [v0.2.2](https://github.com/browserify/resolve/compare/v0.2.1...v0.2.2) - 30 April 2012

*   fix indentation (([code class="code-span"98fc4a5](https://github.com/browserify/resolve/commit/98fc4a50b68456d497a862b9c4e4e0a79570c770))

*   Updated to work with windows, tested on Windows 7 64-bit and OS X 10.6 (([code class="code-span"a6646cc](https://github.com/browserify/resolve/commit/a6646ccceb1a6c411d5b9dfdc97106c80d8a0a09))

*   bump for windows fixes (([code class="code-span"d67d595](https://github.com/browserify/resolve/commit/d67d5959e1be31eb67d5b62e7050bff318572373))

#### [v0.2.1](https://github.com/browserify/resolve/compare/v0.2.0...v0.2.1) - 12 April 2012

*   now using tap (([code class="code-span"b625169](https://github.com/browserify/resolve/commit/b62516922eaaafe533806cd385017109ea057baa))

*   using travis (([code class="code-span"30cc7b3](https://github.com/browserify/resolve/commit/30cc7b3af9299a0e08f34c314015a1395ef16ea3))

*   split on multiple slashes (([code class="code-span"ebeafab](https://github.com/browserify/resolve/commit/ebeafab4a43c6ac4df7a8a7ee578629f81b7b9e7))

*   fix splitting of paths to support windows as well (([code class="code-span"5e7e24b](https://github.com/browserify/resolve/commit/5e7e24bf11c48f14385886d7dd3661f786cc109b))

#### [v0.2.0](https://github.com/browserify/resolve/compare/v0.1.3...v0.2.0) - 25 February 2012

*   updated the core list for 0.6.11 (([code class="code-span"12d4c16](https://github.com/browserify/resolve/commit/12d4c164ef99bd35c13b0f566feaa70bc3560082))

#### [v0.1.3](https://github.com/browserify/resolve/compare/v0.1.2...v0.1.3) - 14 December 2011

*   bump (([code class="code-span"2dffd07](https://github.com/browserify/resolve/commit/2dffd072ce65b4aae4974e934ca5b58ec741f598))

*   Added readline to core modules (([code class="code-span"4ab55a2](https://github.com/browserify/resolve/commit/4ab55a2d4eb95be2399fe94fd5d33879271b5a9f))

#### [v0.1.2](https://github.com/browserify/resolve/compare/v0.1.1...v0.1.2) - 31 October 2011

*   Add opts.paths to list of node\_modules directories (([code class="code-span"7bb6ef4](https://github.com/browserify/resolve/commit/7bb6ef4a1805523169f30b6ea38776796a714c3a))

*   bump (([code class="code-span"5e3fcc6](https://github.com/browserify/resolve/commit/5e3fcc63cfec322779be5435820d3236e6d13dba))

#### [v0.1.1](https://github.com/browserify/resolve/compare/v0.1.0...v0.1.1) - 18 October 2011

*   bump for windows paths (([code class="code-span"3fb86d0](https://github.com/browserify/resolve/commit/3fb86d07c77b09a7d6fa6d2a8b89432a070a6aa0))

*   Added support for Windows-style paths. (([code class="code-span"638951e](https://github.com/browserify/resolve/commit/638951ed92fa4435d9752df30c3bcb9eb49573cd))

#### [v0.1.0](https://github.com/browserify/resolve/compare/v0.0.4...v0.1.0) - 3 October 2011

*   passing mock test (([code class="code-span"030f0d3](https://github.com/browserify/resolve/commit/030f0d391e02558574bc673077fb1b4057f8358d))

*   passing mock test with package.json (([code class="code-span"d2b19c8](https://github.com/browserify/resolve/commit/d2b19c893b7f8c63154c5b5ff2c419ffdc8baa0c))

*   isFile and readFileSync as parameters (([code class="code-span"d30c22d](https://github.com/browserify/resolve/commit/d30c22d1e13b000016f2592d6d6f3489a2d29988))

*   doc updates and a minor bump for custom isFile and readFileSync params (([code class="code-span"b0af4c3](https://github.com/browserify/resolve/commit/b0af4c3ac1a51acf9995cb4e078bf5619f257952))

#### [v0.0.4](https://github.com/browserify/resolve/compare/v0.0.3...v0.0.4) - 21 June 2011

*   bump for packageFilter and a note in the docs (([code class="code-span"9fbb632](https://github.com/browserify/resolve/commit/9fbb632a5c0c38641ed7c10399306a56651e0789))

*   new packageFilter option (([code class="code-span"c92c883](https://github.com/browserify/resolve/commit/c92c883bed3e50dd8ed9a2e1d4b9fefc9f3ced64))

#### [v0.0.3](https://github.com/browserify/resolve/compare/v0.0.2...v0.0.3) - 20 June 2011

*   custom extensions now work (([code class="code-span"502b6e9](https://github.com/browserify/resolve/commit/502b6e9c8b9f258e5c943954467016e9c048fa0f))

*   failing test for extensions (([code class="code-span"ce56f56](https://github.com/browserify/resolve/commit/ce56f56b4e1a5c1df495a7bf061fb0242103b4d8))

*   bump and a note in the docs for extensions (([code class="code-span"2ad8287](https://github.com/browserify/resolve/commit/2ad8287bc8b34929c2074a739410d08955ccdea7))

*   passing normalize test (([code class="code-span"055c7ce](https://github.com/browserify/resolve/commit/055c7cea391ff0ce9cd8c585e8244f553b62f6e7))

#### [v0.0.2](https://github.com/browserify/resolve/compare/v0.0.1...v0.0.2) - 19 June 2011

*   failing biz test for going up and down the path directory (([code class="code-span"cf4f5a5](https://github.com/browserify/resolve/commit/cf4f5a58d092124c517c55dd180559f5a444eb06))

*   don't stop on the first node\_modules since that's going away in node anyhow, all tests pass again (([code class="code-span"9049abf](https://github.com/browserify/resolve/commit/9049abfb60cac49bb547b8ca02cc2617d406ff1a))

#### v0.0.1

*   implementation seems to work but no tests yet (([code class="code-span"5218f01](https://github.com/browserify/resolve/commit/5218f0106e78edce4cfb905d0ea4492ed3fd38af))

*   a package.json all up in this (([code class="code-span"4084043](https://github.com/browserify/resolve/commit/40840435a621120db78126c1792df7fdd0570703))

*   new resolve.{core,isCore} with tests and documentation, bump to 0.0.1 (([code class="code-span"a9ef081](https://github.com/browserify/resolve/commit/a9ef081a4897e9882bf6bc6b31457c53b8d0fc0d))

*   failing foo test (([code class="code-span"463b108](https://github.com/browserify/resolve/commit/463b108dd6e750196cba150348bd68397522c908))

*   readme before any code (([code class="code-span"7885443](https://github.com/browserify/resolve/commit/7885443d8a3dba7223b1bfca2d62cafc08a46436))

*   opts.path => opts.basedir, more descriptive I think (([code class="code-span"78010b1](https://github.com/browserify/resolve/commit/78010b1f91251447d1e74c6ac9cd0baebc6ddf60))

*   failing bar test (([code class="code-span"c40c5c1](https://github.com/browserify/resolve/commit/c40c5c14038acbe8bec91cf979d12382c2e6ddfe))

*   passing baz test to check package.json resolution (([code class="code-span"410635e](https://github.com/browserify/resolve/commit/410635ef6226c030f74c4475e73724a01a102896))

*   a path.resolve() fixed the relative loads (([code class="code-span"dfef4b6](https://github.com/browserify/resolve/commit/dfef4b6185d02259c119a10c8a938e1ab148b140))

*   passing the bar test after taking out the dirname() around y (([code class="code-span"eda2247](https://github.com/browserify/resolve/commit/eda22479bd47c5d0b2e8a88851d9ffabbea2329c))

*   trailing comma in the package.json (([code class="code-span"2032753](https://github.com/browserify/resolve/commit/20327532053284676a269ec2441a87f16456fbf3))

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://app.swimm.io/repos/Z2l0aHViJTNBJTNBYmxvZyUzQSUzQXdlbmZlbmd3YW5n/docs/5pqijcoc).
