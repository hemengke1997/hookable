# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## v6.0.0


### 🚀 Enhancements

  - Rewrite for 1.0.0 ([88decae](https://github.com/unjs/hookable/commit/88decae))
  - Custom logger ([ada6e37](https://github.com/unjs/hookable/commit/ada6e37))
  - Optional fatal support for logger ([7c7355d](https://github.com/unjs/hookable/commit/7c7355d))
  - DeprecateHooks ([62f2d38](https://github.com/unjs/hookable/commit/62f2d38))
  - Hide deprecate warnings on production builds ([0861df3](https://github.com/unjs/hookable/commit/0861df3))
  - Bundle package ([53a2a0e](https://github.com/unjs/hookable/commit/53a2a0e))
  - Advanced deprecation ([5b88628](https://github.com/unjs/hookable/commit/5b88628))
  - Allow removing registered hooks ([#16](https://github.com/unjs/hookable/pull/16))
  - Migrate to typescript ([d63ea3e](https://github.com/unjs/hookable/commit/d63ea3e))
  - Allow disabling logger ([f8fb742](https://github.com/unjs/hookable/commit/f8fb742))
  - **types:** Implement strict types ([823cdca](https://github.com/unjs/hookable/commit/823cdca))
  - HookOnce ([225fa8a](https://github.com/unjs/hookable/commit/225fa8a))
  - `mergeHooks` helper ([#26](https://github.com/unjs/hookable/pull/26))
  - **pkg:** Expose module format ([2987b09](https://github.com/unjs/hookable/commit/2987b09))
  - ⚠️  Improve type checking ([c2e1e22](https://github.com/unjs/hookable/commit/c2e1e22))
  - ⚠️  Drop browser build and use exports field ([b626770](https://github.com/unjs/hookable/commit/b626770))
  - ⚠️  Use named exports and expose createHooks ([fadfcbd](https://github.com/unjs/hookable/commit/fadfcbd))
  - Drop logger and global error handler ([ee6ea87](https://github.com/unjs/hookable/commit/ee6ea87))
  - `callHookParallel` and `callHookWith` ([#35](https://github.com/unjs/hookable/pull/35))
  - Add `beforeEach` and `afterEach` spies ([#46](https://github.com/unjs/hookable/pull/46))
  - Allow registering a hook without showing deprecated message ([0fcd787](https://github.com/unjs/hookable/commit/0fcd787))
  - Add `createDebugger` utility ([#51](https://github.com/unjs/hookable/pull/51))
  - Add function name to hook for better dx in stacktraces ([#68](https://github.com/unjs/hookable/pull/68))
  - Use `console.createTask` to improve traces where supported ([#69](https://github.com/unjs/hookable/pull/69))
  - Add `removeAllHooks` utility ([#61](https://github.com/unjs/hookable/pull/61))

### 🔥 Performance

  - Minor refactor ([e4083aa](https://github.com/unjs/hookable/commit/e4083aa))
  - Handle fn as array faster ([ec35edc](https://github.com/unjs/hookable/commit/ec35edc))
  - Reduce transpiled dist size ([df607cf](https://github.com/unjs/hookable/commit/df607cf))
  - Use for in for hookObj ([3c8e2e7](https://github.com/unjs/hookable/commit/3c8e2e7))

### 🩹 Fixes

  - Bind hookObj to this context ([6f6f7bc](https://github.com/unjs/hookable/commit/6f6f7bc))
  - **package:** Lib ~> dist ([34a8d5c](https://github.com/unjs/hookable/commit/34a8d5c))
  - Hook with array or falsy key ([7e90de1](https://github.com/unjs/hookable/commit/7e90de1))
  - Fix package.json (2) ([7ff4ce9](https://github.com/unjs/hookable/commit/7ff4ce9))
  - Revert back hooks ([07f52dc](https://github.com/unjs/hookable/commit/07f52dc))
  - **pkg:** Typo in types entry name ([#19](https://github.com/unjs/hookable/pull/19))
  - **build:** Exclude regenerator and update target to ie 11 ([48acfc5](https://github.com/unjs/hookable/commit/48acfc5))
  - Typecheck for flatHooks ([7800190](https://github.com/unjs/hookable/commit/7800190))
  - Expose types ([0ffbaff](https://github.com/unjs/hookable/commit/0ffbaff))
  - Avoid creating extra wrapper when merging hooks ([790c1c4](https://github.com/unjs/hookable/commit/790c1c4))
  - Allow nested hooks type to omit some hooks ([#28](https://github.com/unjs/hookable/pull/28))
  - Allow type inference for `hook`, `hookOnce` and `removeHook` ([#29](https://github.com/unjs/hookable/pull/29))
  - Type nested/namespaced hooks ([#32](https://github.com/unjs/hookable/pull/32))
  - Always return caller result ([e9c51df](https://github.com/unjs/hookable/commit/e9c51df))
  - Handle deprecated hooks after being registred ([23d9ff4](https://github.com/unjs/hookable/commit/23d9ff4))
  - Deprecate hooks doesn't have to be passed all hooks ([#48](https://github.com/unjs/hookable/pull/48))
  - Ensure calling hooks always returns a promise ([44679c8](https://github.com/unjs/hookable/commit/44679c8))
  - Only specify return type for `callHook`/`callHookParallel` ([ed0d6a8](https://github.com/unjs/hookable/commit/ed0d6a8))
  - Show deprecation warning only once ([526e4dc](https://github.com/unjs/hookable/commit/526e4dc))
  - Accept any hookable ([#53](https://github.com/unjs/hookable/pull/53))
  - Handle case where hook adds debugger ([#54](https://github.com/unjs/hookable/pull/54))
  - Allow parallel hooks with unique time strings ([#55](https://github.com/unjs/hookable/pull/55))
  - Add types subpath export ([211ee2e](https://github.com/unjs/hookable/commit/211ee2e))
  - Shift name out of arg array ([#71](https://github.com/unjs/hookable/pull/71))
  - Clone hook arrays before calling ([#79](https://github.com/unjs/hookable/pull/79))
  - Hook callback parameters type ([ebf1583](https://github.com/unjs/hookable/commit/ebf1583))

### 💅 Refactors

  - Remove items-promise dependency ([cc85aec](https://github.com/unjs/hookable/commit/cc85aec))
  - Use internal _logger reference ([c2a286a](https://github.com/unjs/hookable/commit/c2a286a))
  - Avoid one line ifs ([b79063b](https://github.com/unjs/hookable/commit/b79063b))
  - Simplify deprecateHooks ([ea44f40](https://github.com/unjs/hookable/commit/ea44f40))
  - Remove `clearHook` and `clearHooks` as we have `removeHook` and `removeHooks` now ([50025fd](https://github.com/unjs/hookable/commit/50025fd))
  - ⚠️  Remove mergehooks from Hookable prototype ([d50af59](https://github.com/unjs/hookable/commit/d50af59))
  - Use unbuild ([50f0004](https://github.com/unjs/hookable/commit/50f0004))
  - Split debugger ([76db216](https://github.com/unjs/hookable/commit/76db216))

### 📖 Documentation

  - Remove invalid use of `callHookParallel` ([#17](https://github.com/unjs/hookable/pull/17))
  - Fix small typo in README ([#31](https://github.com/unjs/hookable/pull/31))
  - Update context ([#44](https://github.com/unjs/hookable/pull/44))
  - Update badges ([13b0c90](https://github.com/unjs/hookable/commit/13b0c90))
  - Add `removeAllHooks` and fix typos ([#72](https://github.com/unjs/hookable/pull/72))

### 🌊 Types

  - Work with strict config ([#63](https://github.com/unjs/hookable/pull/63))

### 🏡 Chore

  - **release:** 0.0.2 ([01a3857](https://github.com/unjs/hookable/commit/01a3857))
  - **release:** 0.0.3 ([374282a](https://github.com/unjs/hookable/commit/374282a))
  - **release:** 0.0.4 ([ff454df](https://github.com/unjs/hookable/commit/ff454df))
  - **release:** 0.0.5 ([fb51c14](https://github.com/unjs/hookable/commit/fb51c14))
  - **release:** 0.0.6 ([6b21906](https://github.com/unjs/hookable/commit/6b21906))
  - Update readme ([29236d0](https://github.com/unjs/hookable/commit/29236d0))
  - **release:** 0.0.7 ([a72a9cc](https://github.com/unjs/hookable/commit/a72a9cc))
  - **release:** 1.0.0 ([a0e5c7a](https://github.com/unjs/hookable/commit/a0e5c7a))
  - **release:** 1.0.1 ([c4f8783](https://github.com/unjs/hookable/commit/c4f8783))
  - **release:** 2.0.0 ([71db2f6](https://github.com/unjs/hookable/commit/71db2f6))
  - **release:** 2.0.1 ([69b4795](https://github.com/unjs/hookable/commit/69b4795))
  - **release:** 2.1.0 ([2860582](https://github.com/unjs/hookable/commit/2860582))
  - **release:** 2.2.0 ([55cf5c0](https://github.com/unjs/hookable/commit/55cf5c0))
  - **release:** 2.2.1 ([59e7482](https://github.com/unjs/hookable/commit/59e7482))
  - Remove unnecessary binds ([95ca9e9](https://github.com/unjs/hookable/commit/95ca9e9))
  - **release:** 2.3.0 ([791542b](https://github.com/unjs/hookable/commit/791542b))
  - Add ts types ([3943d93](https://github.com/unjs/hookable/commit/3943d93))
  - Add babel-jest for fixing test ([0d30bd4](https://github.com/unjs/hookable/commit/0d30bd4))
  - Update renovate ([da6859f](https://github.com/unjs/hookable/commit/da6859f))
  - Add jest transform ([3fb5251](https://github.com/unjs/hookable/commit/3fb5251))
  - Update yarn lock ([fb84112](https://github.com/unjs/hookable/commit/fb84112))
  - Use prepublishOnly ([1c2b340](https://github.com/unjs/hookable/commit/1c2b340))
  - Upgrade eslint packages ([179b614](https://github.com/unjs/hookable/commit/179b614))
  - Fix coverage report ([75d900a](https://github.com/unjs/hookable/commit/75d900a))
  - **release:** 3.0.0 ([1a5cbc7](https://github.com/unjs/hookable/commit/1a5cbc7))
  - Rename to hookable ([9c62ae9](https://github.com/unjs/hookable/commit/9c62ae9))
  - Add @RGBboy to creadits ([fbe4306](https://github.com/unjs/hookable/commit/fbe4306))
  - Update dependencies ([1f296a4](https://github.com/unjs/hookable/commit/1f296a4))
  - Update repo ([81ce3c7](https://github.com/unjs/hookable/commit/81ce3c7))
  - Fix test and eslint ([3d3b199](https://github.com/unjs/hookable/commit/3d3b199))
  - Use github actions ([f28dacd](https://github.com/unjs/hookable/commit/f28dacd))
  - **release:** 4.0.0 ([7fd52df](https://github.com/unjs/hookable/commit/7fd52df))
  - **release:** 4.1.0 ([add4cd9](https://github.com/unjs/hookable/commit/add4cd9))
  - Remove unused badge ([6adec04](https://github.com/unjs/hookable/commit/6adec04))
  - **release:** 4.1.1 ([2b15871](https://github.com/unjs/hookable/commit/2b15871))
  - **readme:** Fix url ([#21](https://github.com/unjs/hookable/pull/21))
  - **release:** 4.1.2 ([85d66a7](https://github.com/unjs/hookable/commit/85d66a7))
  - Update dependencies ([00a071a](https://github.com/unjs/hookable/commit/00a071a))
  - **release:** 4.2.0 ([7393a92](https://github.com/unjs/hookable/commit/7393a92))
  - Update dependencies ([9020f43](https://github.com/unjs/hookable/commit/9020f43))
  - **release:** 4.3.0 ([e521dfb](https://github.com/unjs/hookable/commit/e521dfb))
  - Update repo and improve dist ([191b7e2](https://github.com/unjs/hookable/commit/191b7e2))
  - **release:** 4.3.1 ([f69f8a7](https://github.com/unjs/hookable/commit/f69f8a7))
  - Fix ci ([48bb82c](https://github.com/unjs/hookable/commit/48bb82c))
  - **release:** 4.4.0 ([4d9fc75](https://github.com/unjs/hookable/commit/4d9fc75))
  - **release:** 4.4.1 ([2ae8c9b](https://github.com/unjs/hookable/commit/2ae8c9b))
  - Update org ([ae9e030](https://github.com/unjs/hookable/commit/ae9e030))
  - Update dev dependencies ([8b845fd](https://github.com/unjs/hookable/commit/8b845fd))
  - Fix eslint issues ([a225469](https://github.com/unjs/hookable/commit/a225469))
  - Update github action ([9219ce0](https://github.com/unjs/hookable/commit/9219ce0))
  - **release:** 5.0.0-0 ([b730909](https://github.com/unjs/hookable/commit/b730909))
  - Add migration guide ([7e29e07](https://github.com/unjs/hookable/commit/7e29e07))
  - **release:** 5.0.0-1 ([3071d29](https://github.com/unjs/hookable/commit/3071d29))
  - **release:** 5.0.0-2 ([739d483](https://github.com/unjs/hookable/commit/739d483))
  - **release:** 5.0.0 ([f05c66c](https://github.com/unjs/hookable/commit/f05c66c))
  - Add codecov action ([0188c21](https://github.com/unjs/hookable/commit/0188c21))
  - **release:** 5.1.0 ([bd49129](https://github.com/unjs/hookable/commit/bd49129))
  - **release:** 5.1.1 ([b053d3e](https://github.com/unjs/hookable/commit/b053d3e))
  - Migrate to pnpm + vitest ([#45](https://github.com/unjs/hookable/pull/45))
  - **release:** 5.1.2 ([2ca03b8](https://github.com/unjs/hookable/commit/2ca03b8))
  - Remove jest config ([203db13](https://github.com/unjs/hookable/commit/203db13))
  - Update repo ([5a46409](https://github.com/unjs/hookable/commit/5a46409))
  - **release:** 5.2.0 ([5738def](https://github.com/unjs/hookable/commit/5738def))
  - **release:** 5.2.1 ([4459dc6](https://github.com/unjs/hookable/commit/4459dc6))
  - **release:** 5.2.2 ([daf5c96](https://github.com/unjs/hookable/commit/daf5c96))
  - **release:** 5.3.0 ([22a2f77](https://github.com/unjs/hookable/commit/22a2f77))
  - **release:** 5.4.0 ([1793beb](https://github.com/unjs/hookable/commit/1793beb))
  - Update dependencies ([a61f494](https://github.com/unjs/hookable/commit/a61f494))
  - **release:** 5.4.1 ([4cfc67a](https://github.com/unjs/hookable/commit/4cfc67a))
  - **release:** 5.4.2 ([c3c2413](https://github.com/unjs/hookable/commit/c3c2413))
  - Add latest `@types/node` package ([#66](https://github.com/unjs/hookable/pull/66))
  - Add `.prettierrc` ([4b3e99b](https://github.com/unjs/hookable/commit/4b3e99b))
  - Use changelogen for releases ([151d16b](https://github.com/unjs/hookable/commit/151d16b))
  - Simplify variable names ([369a2fe](https://github.com/unjs/hookable/commit/369a2fe))
  - **release:** V5.5.0 ([eb3b1c5](https://github.com/unjs/hookable/commit/eb3b1c5))
  - **release:** V5.5.1 ([2a492ff](https://github.com/unjs/hookable/commit/2a492ff))
  - **lint:** Run lint:fix to fix formatting ([#77](https://github.com/unjs/hookable/pull/77))
  - Update dependencies ([9443040](https://github.com/unjs/hookable/commit/9443040))
  - **release:** V5.5.2 ([aff2fa5](https://github.com/unjs/hookable/commit/aff2fa5))
  - Update deps ([8b5765f](https://github.com/unjs/hookable/commit/8b5765f))
  - **release:** V5.5.3 ([ddc01ba](https://github.com/unjs/hookable/commit/ddc01ba))

### ✅ Tests

  - Ensure package.json main field is valid ([#2](https://github.com/unjs/hookable/pull/2))
  - Use es modules ([2ddf40c](https://github.com/unjs/hookable/commit/2ddf40c))
  - Import hable.js ([293fcbb](https://github.com/unjs/hookable/commit/293fcbb))
  - Fix vitest type issue ([#70](https://github.com/unjs/hookable/pull/70))

### 🎨 Styles

  - Format with prettier ([#65](https://github.com/unjs/hookable/pull/65))

### 🤖 CI

  - Update ci config ([e8b664f](https://github.com/unjs/hookable/commit/e8b664f))

#### ⚠️  Breaking Changes

  - ⚠️  Improve type checking ([c2e1e22](https://github.com/unjs/hookable/commit/c2e1e22))
  - ⚠️  Drop browser build and use exports field ([b626770](https://github.com/unjs/hookable/commit/b626770))
  - ⚠️  Use named exports and expose createHooks ([fadfcbd](https://github.com/unjs/hookable/commit/fadfcbd))
  - ⚠️  Remove mergehooks from Hookable prototype ([d50af59](https://github.com/unjs/hookable/commit/d50af59))

### ❤️  Contributors

- Hemengke <23536175@qq.com>
- Pooya Parsa ([@pi0](http://github.com/pi0))
- Daniel Roe ([@danielroe](http://github.com/danielroe))
- Rafał Chłodnicki ([@rchl](http://github.com/rchl))
- Vinccool96 <Vinccool96@gmail.com>
- Nozomu Ikuta ([@NozomuIkuta](http://github.com/NozomuIkuta))
- Sébastien Chopin <seb@nuxtjs.com>
- Markthree ([@markthree](http://github.com/markthree))
- Alex Barker ([@abarke](http://github.com/abarke))
- Voraczech ([@voraczech](http://github.com/voraczech))
- Matthieu Sieben 
- Clark Du <clark.duxin@gmail.com>

## v5.5.3

[compare changes](https://github.com/unjs/hookable/compare/v5.5.2...v5.5.3)


### 🩹 Fixes

  - Clone hook arrays before calling ([#79](https://github.com/unjs/hookable/pull/79))

### 🏡 Chore

  - Update deps ([8b5765f](https://github.com/unjs/hookable/commit/8b5765f))

### ❤️  Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))
- Daniel Roe <daniel@roe.dev>

## v5.5.2

[compare changes](https://github.com/unjs/hookable/compare/v5.5.1...v5.5.2)


### 📖 Documentation

  - Add `removeAllHooks` and fix typos ([#72](https://github.com/unjs/hookable/pull/72))

### 🌊 Types

  - Work with strict config ([#63](https://github.com/unjs/hookable/pull/63))

### 🏡 Chore

  - **lint:** Run lint:fix to fix formatting ([#77](https://github.com/unjs/hookable/pull/77))
  - Update dependencies ([9443040](https://github.com/unjs/hookable/commit/9443040))

### ❤️  Contributors

- Pooya Parsa ([@pi0](http://github.com/pi0))
- Rafał Chłodnicki ([@rchl](http://github.com/rchl))
- Vinccool96 <Vinccool96@gmail.com>
- Nozomu Ikuta

## v5.5.1

[compare changes](https://github.com/unjs/hookable/compare/v5.5.0...v5.5.1)


### 🩹 Fixes

  - Shift name out of arg array ([#71](https://github.com/unjs/hookable/pull/71))

### 📖 Documentation

  - Update badges ([13b0c90](https://github.com/unjs/hookable/commit/13b0c90))

### ❤️  Contributors

- Daniel Roe <daniel@roe.dev>
- Sébastien Chopin <seb@nuxtjs.com>

## v5.5.0

[compare changes](https://github.com/unjs/hookable/compare/v5.4.2...v5.5.0)


### 🚀 Enhancements

  - Add function name to hook for better dx in stacktraces ([#68](https://github.com/unjs/hookable/pull/68))
  - Use `console.createTask` to improve traces where supported ([#69](https://github.com/unjs/hookable/pull/69))
  - Add `removeAllHooks` utility ([#61](https://github.com/unjs/hookable/pull/61))

### 🏡 Chore

  - Add latest `@types/node` package ([#66](https://github.com/unjs/hookable/pull/66))
  - Add `.prettierrc` ([4b3e99b](https://github.com/unjs/hookable/commit/4b3e99b))
  - Use changelogen for releases ([151d16b](https://github.com/unjs/hookable/commit/151d16b))
  - Simplify variable names ([369a2fe](https://github.com/unjs/hookable/commit/369a2fe))

### ✅ Tests

  - Fix vitest type issue ([#70](https://github.com/unjs/hookable/pull/70))

### 🎨 Styles

  - Format with prettier ([#65](https://github.com/unjs/hookable/pull/65))

### ❤️  Contributors

- Nozomu Ikuta 
- Pooya Parsa ([@pi0](http://github.com/pi0))
- Daniel Roe <daniel@roe.dev>

### [5.4.2](https://github.com/unjs/hookable/compare/v5.4.1...v5.4.2) (2022-11-15)


### Bug Fixes

* add types subpath export ([211ee2e](https://github.com/unjs/hookable/commit/211ee2e36f2cccbf930a5fa1f029301b632f093c))

### [5.4.1](https://github.com/unjs/hookable/compare/v5.4.0...v5.4.1) (2022-10-15)


### Bug Fixes

* accept any hookable ([#53](https://github.com/unjs/hookable/issues/53)) ([0eac02c](https://github.com/unjs/hookable/commit/0eac02cc6f975990ca458a587007f3bfd33e8a95))
* allow parallel hooks with unique time strings ([#55](https://github.com/unjs/hookable/issues/55)) ([ee64dc8](https://github.com/unjs/hookable/commit/ee64dc8299d15367eb2c62806c5b96eb1f88db32))
* handle case where hook adds debugger ([#54](https://github.com/unjs/hookable/issues/54)) ([f6d4475](https://github.com/unjs/hookable/commit/f6d4475166a5941f6fba16f836c2c8e91971b974))

## [5.4.0](https://github.com/unjs/hookable/compare/v5.3.0...v5.4.0) (2022-10-13)


### Features

* add `createDebugger` utility ([#51](https://github.com/unjs/hookable/issues/51)) ([021eb34](https://github.com/unjs/hookable/commit/021eb34d999b61d8189cc1c10116252588dba34f))

## [5.3.0](https://github.com/unjs/hookable/compare/v5.2.2...v5.3.0) (2022-09-02)


### Features

* allow registering a hook without showing deprecated message ([0fcd787](https://github.com/unjs/hookable/commit/0fcd787fd2fd0fd8b660dda8706b90cc4bf14ba8))


### Bug Fixes

* show deprecation warning only once ([526e4dc](https://github.com/unjs/hookable/commit/526e4dc821e6edae51245f0cd44f0ba938719776))

### [5.2.2](https://github.com/unjs/hookable/compare/v5.2.1...v5.2.2) (2022-08-23)


### Bug Fixes

* only specify return type for `callHook`/`callHookParallel` ([ed0d6a8](https://github.com/unjs/hookable/commit/ed0d6a82d8aa11044851888ab5c71ccbe4369c69))

### [5.2.1](https://github.com/unjs/hookable/compare/v5.2.0...v5.2.1) (2022-08-23)


### Bug Fixes

* ensure calling hooks always returns a promise ([44679c8](https://github.com/unjs/hookable/commit/44679c890f7b3b92331bd5dffeac95b61eab2858))

## [5.2.0](https://github.com/unjs/hookable/compare/v5.1.2...v5.2.0) (2022-08-23)


### Features

* add `beforeEach` and `afterEach` spies ([#46](https://github.com/unjs/hookable/issues/46)) ([949d8b7](https://github.com/unjs/hookable/commit/949d8b76817dfc47e6b1ce4ed09204e7c33d0ec1))


### Bug Fixes

* deprecate hooks doesn't have to be passed all hooks ([#48](https://github.com/unjs/hookable/issues/48)) ([0c4fef0](https://github.com/unjs/hookable/commit/0c4fef0d39ccd123efca29a9506854f01ae685f7))

### [5.1.2](https://github.com/unjs/hookable/compare/v5.1.1...v5.1.2) (2022-08-23)


### Bug Fixes

* handle deprecated hooks after being registred ([23d9ff4](https://github.com/unjs/hookable/commit/23d9ff4f1313148942990e5e078d91838f78e8c2))

### [5.1.1](https://github.com/unjs/hookable/compare/v5.1.0...v5.1.1) (2021-12-21)


### Bug Fixes

* always return caller result ([e9c51df](https://github.com/unjs/hookable/commit/e9c51df612a2eb5f42cf7c2f2c3f61b2539bcfae))

## [5.1.0](https://github.com/unjs/hookable/compare/v5.0.0...v5.1.0) (2021-12-20)


### Features

* `callHookParallel` and `callHookWith` ([#35](https://github.com/unjs/hookable/issues/35)) ([4a8cc53](https://github.com/unjs/hookable/commit/4a8cc538a4fb938bfdf13d70a9158714b3d603b9))

## [5.0.0](https://github.com/unjs/hookable/compare/v5.0.0-2...v5.0.0) (2021-09-01)


### Bug Fixes

* type nested/namespaced hooks ([#32](https://github.com/unjs/hookable/issues/32)) ([a0d9146](https://github.com/unjs/hookable/commit/a0d9146c40fb9767842564225444c6c5a7dce70f))

## [5.0.0-2](https://github.com/unjs/hookable/compare/v5.0.0-1...v5.0.0-2) (2021-08-27)


### Bug Fixes

* allow type inference for `hook`, `hookOnce` and `removeHook` ([#29](https://github.com/unjs/hookable/issues/29)) ([22b74d3](https://github.com/unjs/hookable/commit/22b74d30805f35000709ba32220e6e4e059f4cc5))

## [5.0.0-1](https://github.com/unjs/hookable/compare/v5.0.0-0...v5.0.0-1) (2021-08-27)


### Bug Fixes

* allow nested hooks type to omit some hooks ([#28](https://github.com/unjs/hookable/issues/28)) ([75f2a05](https://github.com/unjs/hookable/commit/75f2a057a526d018b9cf39f01ddfd2a3d2a6bbc1))

## [5.0.0-0](https://github.com/unjs/hookable/compare/v4.4.1...v5.0.0-0) (2021-08-26)


### ⚠ BREAKING CHANGES

* You should directly handle errors with callHook
* use named exports and expose createHooks
* remove mergehooks from Hookable prototype
* drop browser build and use exports field
* improve type checking

### Features

* drop browser build and use exports field ([b626770](https://github.com/unjs/hookable/commit/b626770192a62b23acc1be16b4e4eac2383e9136))
* drop logger and global error handler ([ee6ea87](https://github.com/unjs/hookable/commit/ee6ea87ad0e15a52252389b9b3112060bd411330))
* improve type checking ([c2e1e22](https://github.com/unjs/hookable/commit/c2e1e223d16e7bf87117cd8d72ad3ba211a333d8))
* use named exports and expose createHooks ([fadfcbd](https://github.com/unjs/hookable/commit/fadfcbd07c3e2fa6905d0e31deabc37fc55d8317))


* remove mergehooks from Hookable prototype ([d50af59](https://github.com/unjs/hookable/commit/d50af595d3cb05be8fb5060374f4e28b3d6259fa))

### [4.4.1](https://github.com/unjs/hookable/compare/v4.4.0...v4.4.1) (2021-02-26)


### Bug Fixes

* avoid creating extra wrapper when merging hooks ([790c1c4](https://github.com/unjs/hookable/commit/790c1c4dbbd1f7b9cb1995b40baeecead5346ed0))

## [4.4.0](https://github.com/unjs/hookable/compare/v4.3.1...v4.4.0) (2021-01-21)


### Features

* **pkg:** expose module format ([2987b09](https://github.com/unjs/hookable/commit/2987b0901e292eb4570f8141ca51cfd9d2d3f94f))

### [4.3.1](https://github.com/unjs/hookable/compare/v4.3.0...v4.3.1) (2020-11-06)


### Bug Fixes

* expose types ([0ffbaff](https://github.com/unjs/hookable/commit/0ffbaffa91d38e333e0818cd73a084cf1e8657c8))

## [4.3.0](https://github.com/unjs/hookable/compare/v4.2.0...v4.3.0) (2020-11-06)


### Features

* `mergeHooks` helper ([#26](https://github.com/unjs/hookable/issues/26)) ([8c52d03](https://github.com/unjs/hookable/commit/8c52d034aa1a40bafb13d0b847c72593c51fcba5))

## [4.2.0](https://github.com/unjs/hookable/compare/v4.1.2...v4.2.0) (2020-10-23)


### Features

* hookOnce ([225fa8a](https://github.com/unjs/hookable/commit/225fa8af85e1a504916c357f57b047143b6bc5ab))


### Bug Fixes

* typecheck for flatHooks ([7800190](https://github.com/unjs/hookable/commit/7800190feb82134be5dd089ca184a18a6644da19))

### [4.1.2](https://github.com/unjs/hookable/compare/v4.1.1...v4.1.2) (2020-08-24)


### Bug Fixes

* **build:** exclude regenerator and update target to ie 11 ([48acfc5](https://github.com/unjs/hookable/commit/48acfc5c0a4b0fb8edc6e9790b37ad336c966215))

### [4.1.1](https://github.com/unjs/hookable/compare/v4.1.0...v4.1.1) (2020-04-28)


### Bug Fixes

* **pkg:** typo in types entry name (fixes [#19](https://github.com/unjs/hookable/issues/19)) ([b9ba90f](https://github.com/unjs/hookable/commit/b9ba90fbc725097e41c430d7df4205985c2faaec))

## [4.1.0](https://github.com/unjs/hookable/compare/v4.0.0...v4.1.0) (2020-04-17)


### Features

* **types:** implement strict types ([823cdca](https://github.com/unjs/hookable/commit/823cdcac728d189b802f75faa9a361ac5ea4883d))

## [4.0.0](https://github.com/unjs/hookable/compare/v3.0.0...v4.0.0) (2020-04-17)


### ⚠ BREAKING CHANGES

* only dist and types getting published

### Features

* allow disabling logger ([f8fb742](https://github.com/unjs/hookable/commit/f8fb74224f1277ec7f7d5a37bd312af7514fc962))
* allow removing registered hooks ([#16](https://github.com/unjs/hookable/issues/16)) ([4134c31](https://github.com/unjs/hookable/commit/4134c31c44256cc82cac3a7a3610ece9252431dc))
* migrate to typescript ([d63ea3e](https://github.com/unjs/hookable/commit/d63ea3e408ebea74ea3855af0c6e51880ebf9cac))

## [3.0.0](https://github.com/unjs/hookable/compare/v2.3.0...v3.0.0) (2020-02-25)


### Bug Fixes

* revert back hooks ([07f52dc](https://github.com/unjs/hookable/commit/07f52dc))


### Features

* advanced deprecation ([5b88628](https://github.com/unjs/hookable/commit/5b88628))
* bundle package ([53a2a0e](https://github.com/unjs/hookable/commit/53a2a0e))

# [2.3.0](https://github.com/unjs/hookable/compare/v2.2.1...v2.3.0) (2019-09-01)


### Features

* hide deprecate warnings on production builds ([0861df3](https://github.com/unjs/hookable/commit/0861df3))



## [2.2.1](https://github.com/unjs/hookable/compare/v2.2.0...v2.2.1) (2019-08-21)



# [2.2.0](https://github.com/unjs/hookable/compare/v2.1.0...v2.2.0) (2019-08-21)


### Features

* deprecateHooks ([62f2d38](https://github.com/unjs/hookable/commit/62f2d38))



# [2.1.0](https://github.com/unjs/hookable/compare/v2.0.1...v2.1.0) (2019-08-21)


### Features

* optional fatal support for logger ([7c7355d](https://github.com/unjs/hookable/commit/7c7355d))



## [2.0.1](https://github.com/unjs/hookable/compare/v2.0.0...v2.0.1) (2019-08-21)



# [2.0.0](https://github.com/unjs/hookable/compare/v1.0.1...v2.0.0) (2019-08-21)


### Features

* custom logger ([ada6e37](https://github.com/unjs/hookable/commit/ada6e37))


### BREAKING CHANGES

* console is replaced by consola by default



## [1.0.1](https://github.com/unjs/hookable/compare/v1.0.0...v1.0.1) (2019-03-16)


### Bug Fixes

* fix package.json (2) ([7ff4ce9](https://github.com/unjs/hookable/commit/7ff4ce9))



<a name="1.0.0"></a>
# [1.0.0](https://github.com/unjs/hookable/compare/v0.0.7...v1.0.0) (2019-02-11)


### Features

* rewrite for 1.0.0 ([88decae](https://github.com/unjs/hookable/commit/88decae))


### BREAKING CHANGES

* api change



<a name="0.0.7"></a>
## [0.0.7](https://github.com/pi0/hookable/compare/v0.0.6...v0.0.7) (2018-01-28)


### Bug Fixes

* hook with array or falsy key ([7e90de1](https://github.com/pi0/hookable/commit/7e90de1))


### Performance Improvements

* use for in for hookObj ([3c8e2e7](https://github.com/pi0/hookable/commit/3c8e2e7))



<a name="0.0.6"></a>
## [0.0.6](https://github.com/pi0/hookable/compare/v0.0.5...v0.0.6) (2018-01-26)


### Performance Improvements

* reduce transpiled dist size ([df607cf](https://github.com/pi0/hookable/commit/df607cf))



<a name="0.0.5"></a>
## [0.0.5](https://github.com/pi0/hookable/compare/v0.0.4...v0.0.5) (2018-01-26)


### Bug Fixes

* **package:** lib ~> dist ([34a8d5c](https://github.com/pi0/hookable/commit/34a8d5c))



<a name="0.0.4"></a>
## [0.0.4](https://github.com/pi0/hookable/compare/v0.0.3...v0.0.4) (2018-01-26)


### Performance Improvements

* handle fn as array faster ([ec35edc](https://github.com/pi0/hookable/commit/ec35edc))



<a name="0.0.3"></a>
## [0.0.3](https://github.com/pi0/hookable/compare/v0.0.2...v0.0.3) (2018-01-26)


### Bug Fixes

* bind hookObj to this context ([6f6f7bc](https://github.com/pi0/hookable/commit/6f6f7bc))


### Performance Improvements

* minor refactor ([e4083aa](https://github.com/pi0/hookable/commit/e4083aa))



<a name="0.0.2"></a>
## 0.0.2 (2018-01-26)
