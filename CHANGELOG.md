#  (2018-07-18)



# [1.0.0](https://github.com/bycedric/docker/compare/d24745c...1.0.0) (2018-07-18)


### Bug fixes

* **node-sentry-ci:** use master as leading cdn branch ([557db7f](https://github.com/bycedric/docker/commit/557db7f))
* pinned php to `7.1` to have xdebug working ([d24745c](https://github.com/bycedric/docker/commit/d24745c))
* **laravel-serve:** add missing `php7-json` and `php7-session` packages ([93f0652](https://github.com/bycedric/docker/commit/93f0652))
* **laravel-test:** install gd php extension ([41cecc1](https://github.com/bycedric/docker/commit/41cecc1))
* **laravel-test:** install zip php extension ([d760134](https://github.com/bycedric/docker/commit/d760134))
* **node-sentry-ci:** add cdn to docker ignore to minimise images ([3e8efc8](https://github.com/bycedric/docker/commit/3e8efc8))
* **node-sentry-ci:** use custom cdn for installing with npm ([4d1cd66](https://github.com/bycedric/docker/commit/4d1cd66))
* prepend `bycedric/` namespace to the images ([dfb969e](https://github.com/bycedric/docker/commit/dfb969e))
* **node-sentry-ci:** use proper raw git cdn url ([a60fa96](https://github.com/bycedric/docker/commit/a60fa96))
* **node-sentry-ci:** use proper subdirectory in cdn ([77e51b3](https://github.com/bycedric/docker/commit/77e51b3))
* **serve-larave:** add missing php fpm configuration ([cb5c2f8](https://github.com/bycedric/docker/commit/cb5c2f8))
* **serve-larave:** remove duplicate php pdo install ([4c443b4](https://github.com/bycedric/docker/commit/4c443b4))
* **serve-larave:** use underscore notation for pdo extensions ([3497da0](https://github.com/bycedric/docker/commit/3497da0))
* **serve-laravel:** add iconv php extension for symfony ([684f047](https://github.com/bycedric/docker/commit/684f047))
* **serve-laravel:** add missing php dom extension for mail rendering ([c3e6477](https://github.com/bycedric/docker/commit/c3e6477))
* **serve-laravel:** add missing php tokenizer dependency ([007aa70](https://github.com/bycedric/docker/commit/007aa70))
* **webapp-serve:** use server file environment variable instead of hard coded index.html ([bb026b0](https://github.com/bycedric/docker/commit/bb026b0))


### Code refactors

* **ci-expo:** move to dedicated images folder ([bf5adb2](https://github.com/bycedric/docker/commit/bf5adb2))
* **ci-expo:** remove sonarqube scanner ([91f9f28](https://github.com/bycedric/docker/commit/91f9f28))
* **ci-expo:** use the more descriptive `npm cache rm` ([6ed416b](https://github.com/bycedric/docker/commit/6ed416b))
* **laravel-serve:** rename `laravel-serve` to `serve-laravel` ([a89f88e](https://github.com/bycedric/docker/commit/a89f88e))
* **laravel-serve:** use serve as base image ([146463f](https://github.com/bycedric/docker/commit/146463f))
* **laravel-test:** move to dedicated images folder ([abd120f](https://github.com/bycedric/docker/commit/abd120f))
* **node-ci:** move to dedicated deprecations folder ([df8d586](https://github.com/bycedric/docker/commit/df8d586))
* **node-ci:** use node lts version instead of latest ([4f49801](https://github.com/bycedric/docker/commit/4f49801))
* **node-sentry-ci:** remove sentry docker image and cdn ([4b85131](https://github.com/bycedric/docker/commit/4b85131))
* **node-sentry-ci:** use local binary folder and simplify container name ([4854c0d](https://github.com/bycedric/docker/commit/4854c0d))
* **serve:** move enable to entrypoint to allow overrides ([1b511ed](https://github.com/bycedric/docker/commit/1b511ed))
* **serve:** move to dedicated images folder ([56aa2ce](https://github.com/bycedric/docker/commit/56aa2ce))
* **serve:** remove the extraneous `.tmpl` extension ([9030902](https://github.com/bycedric/docker/commit/9030902))
* **serve:** remove unused start script ([4220c28](https://github.com/bycedric/docker/commit/4220c28))
* **serve:** revert back to command templating, enabling and starting ([e9be7bf](https://github.com/bycedric/docker/commit/e9be7bf))
* **serve:** simplify the server config by removing location block ([49c34a5](https://github.com/bycedric/docker/commit/49c34a5))
* **serve:** use latest alpine and install nginx from official repository ([c33d0a0](https://github.com/bycedric/docker/commit/c33d0a0))
* **serve:** use nginx site helper to improve customisation ([49a5ffa](https://github.com/bycedric/docker/commit/49a5ffa))
* **serve:** use plain nginx alpine instead of perl ([cefa764](https://github.com/bycedric/docker/commit/cefa764))
* **serve:** use single command to template, enable and start everything ([74126f9](https://github.com/bycedric/docker/commit/74126f9))
* **serve-laravel:** move to dedicated images folder ([88b5502](https://github.com/bycedric/docker/commit/88b5502))
* **serve-webapp:** move to dedicated images folder ([eef32cf](https://github.com/bycedric/docker/commit/eef32cf))
* **serve-webapp:** rename `webapp-serve` to `serve-webapp` ([21b5cc7](https://github.com/bycedric/docker/commit/21b5cc7))


### Documentation changes

* **ci-expo:** remove grammar errors in readme ([facea7d](https://github.com/bycedric/docker/commit/facea7d))
* **node-ci:** add deprecation warning ([b34abdc](https://github.com/bycedric/docker/commit/b34abdc))


### New features

* **ci-expo:** add image for Expo CI/CD environments ([bd63316](https://github.com/bycedric/docker/commit/bd63316))
* **laravel-serve:** first draft of the laravel-serve container ([13505ec](https://github.com/bycedric/docker/commit/13505ec))
* **laravel-test:** upgrade to php 7.2 with xdebug 2.6.0 ([a5fcb8b](https://github.com/bycedric/docker/commit/a5fcb8b))
* **laravel-test:** use the latest npm when building image ([a5d9451](https://github.com/bycedric/docker/commit/a5d9451))
* **node-ci:** add git as system library for improved npm usage ([6b95d15](https://github.com/bycedric/docker/commit/6b95d15))
* add bash script to locally update all images ([d935786](https://github.com/bycedric/docker/commit/d935786))
* add changelog generation ([d7ae109](https://github.com/bycedric/docker/commit/d7ae109))
* **node-ci:** add patched node alpine image for `npm ci` ([7c6f72e](https://github.com/bycedric/docker/commit/7c6f72e))
* add node scripts for ci management ([ffa2ac0](https://github.com/bycedric/docker/commit/ffa2ac0))
* **node-sentry-ci:** add cdn update script and add all binary versions ([9e6a6b2](https://github.com/bycedric/docker/commit/9e6a6b2))
* **node-sentry-ci:** add patched node alpine image for `sentry-cli` ([ca7102c](https://github.com/bycedric/docker/commit/ca7102c))
* **serve:** add nginx site helper to enable, disable and build templates ([4da235f](https://github.com/bycedric/docker/commit/4da235f))
* **serve:** create simple env-configurable serve image ([afb5483](https://github.com/bycedric/docker/commit/afb5483))
* **serve-laravel:** add php pdo and both mysql and sqlite by default ([f79ee6f](https://github.com/bycedric/docker/commit/f79ee6f))
* **webapp-serve:** create simple web app serve image ([fb103bb](https://github.com/bycedric/docker/commit/fb103bb))


### Other chores

* **node-sentry-ci:** add deprecation warning ([68dbe2a](https://github.com/bycedric/docker/commit/68dbe2a))
* **node-sentry-cli:** add latest alpine binaries to cdn ([b15c0c8](https://github.com/bycedric/docker/commit/b15c0c8))


### Pipeline changes

* add travis configuration ([be4717f](https://github.com/bycedric/docker/commit/be4717f))
* clean travis images names ([0bb189e](https://github.com/bycedric/docker/commit/0bb189e))
* limit branches to develop and master ([a08a8df](https://github.com/bycedric/docker/commit/a08a8df))
* make travis run in parallel ([56ba248](https://github.com/bycedric/docker/commit/56ba248))
* move to single parallel jobs ([09b76df](https://github.com/bycedric/docker/commit/09b76df))
* shorten git commit as docker tag ([8522ead](https://github.com/bycedric/docker/commit/8522ead))
* update travis configuration and fix environment variables ([655f8a4](https://github.com/bycedric/docker/commit/655f8a4))
* use short commit instead of short tag ([e8dafc3](https://github.com/bycedric/docker/commit/e8dafc3))


