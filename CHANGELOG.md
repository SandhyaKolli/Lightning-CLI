# Changelog

## v2.7.0

*22 nov 2021*

- Upgraded esbuild to version 0.12
- Added watcher support for `lng dist`
- Added `LNG_BUILD_FAIL_ON_WARNINGS` environment variable

## v2.6.0

*20 oct 2021*

- Added support for using `process.env.NODE_ENV` in Apps
- Added using the minified lightning library file in dist builds
- Added minification for esbuild bundler
- Improved error messages and handling
- Added babel-step to es6 config (for rollup and esbuild) to enable usage of class properties proposal syntax

## v2.5.1

*29 jun 2021*

- Fixes dynamic imports in rollup created bundle

## v2.5.0

*23 apr 2021*

- Updated CLI documentation
- Added es5 support for esbuild bundler
- Added support for different `settings.json`-files per environment
- Improved error messages
- Fixed missing `.gitignore`-file when creating new project with GIT options selected
- Fixed App specific environment variables not repopulating between builds in esbuild bundler
- Fixed version not showing in VersionLabel for dist version of App
- Added warning when upload package too large

## v2.2.0

*6 nov 2020*

- Added rollup image-plugin to bundle up image assets (as base64-images)

## v2.1.0

*30 oct 2020*

- Added `LNG_SERVE_PROXY` environment variable
- Added fix for polyfills not being copied over when using `lng dist --es5`-command
- Fixed auto-update functionality
- Added `lng update`-command

## v2.0.2

*19 oct 2020*

- Added fix for Lightning library not being copied over when using `lng dist`-command

## v2.0.1

*14 oct 2020*

- Changed package name from `wpe-lightning-cli` to `@lightningjs/cli` (and published on NPM)
- Updated minimum requirement to Node.js 10
- Support for building apps with new `@lightningjs/sdk` Loghtning-SDK (continued support for legacy `wpe-lightning-sdk`)
- Various smaller updates
