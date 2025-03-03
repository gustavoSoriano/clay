# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [3.38.0](https://github.com/liferay/clay/compare/v3.37.0...v3.38.0) (2021-10-22)


### Bug Fixes

* **@clayui/css:** Alert convert components to use `clay-css` mixin pattern ([adbc3ed](https://github.com/liferay/clay/commit/adbc3ed9abd47e15ad0165411feba034dbbe9214))
* **@clayui/css:** Alerts allow customizing `.btn-group` inside `.alert-inline` and increase space between alert-inline buttons and close (48px) ([1fb3075](https://github.com/liferay/clay/commit/1fb3075147ea96012e732a51c825826434e6e350))
* **@clayui/css:** Alerts and Cadmin Alerts tweak position of `.alert-inline .alert-indicator` so it's more centered with the text ([6991050](https://github.com/liferay/clay/commit/6991050db719c8a301747b146c3c14575e30d46c))
* **@clayui/css:** Atlas / Base variables and components use Clay Color functions instead of Sass color functions for better CSS Custom Property support ([bd72797](https://github.com/liferay/clay/commit/bd72797c6059500587fe2959b3ff44df2a266c76))
* **@clayui/css:** Atlas Alerts and Cadmin Alerts spacing between `alert-indicator` and text should be 8px ([abb1ad9](https://github.com/liferay/clay/commit/abb1ad97128b29a1d77fe660323b65803206796c))
* **@clayui/css:** Atlas Alerts use `$alert-indicator-font-size` instead of `$alert-font-size` when calculating spacing for the `.alert-indicator` ([10809da](https://github.com/liferay/clay/commit/10809dae86c2e68fb6b7c9fe60209efdc6336916))
* **@clayui/css:** Badge updates `$badge-close` Sass map to use newer keys for hover and focus ([485862c](https://github.com/liferay/clay/commit/485862cb62c0d5ba42d1706ef1020bf5fd1f6743))
* **@clayui/css:** Border utilities `border-color` is the wrong value. Table Row Variants scoped `$border-color` variable was overwriting global `$border-color` variable ([834209a](https://github.com/liferay/clay/commit/834209a7b0a64805aa134d15127db5a8f3105a68))
* **@clayui/css:** Cadmin Alert convert components to use `clay-css` mixin pattern ([915c748](https://github.com/liferay/clay/commit/915c748788d0ff4c6ffbdbc8b75e07a910a4412e))
* **@clayui/css:** Cadmin Alerts allow customizing `.btn-group` inside `.alert-inline` and increase space between alert-inline buttons and close (48px) ([f6c7a02](https://github.com/liferay/clay/commit/f6c7a02ff79f351ad98586d3c17f9f903e17b755))
* **@clayui/css:** Cadmin Modals `modal-body` should have border-top to create separation when components are inserted between `modal-header` and `modal-body` ([b5b33c0](https://github.com/liferay/clay/commit/b5b33c03918c1ac34556403caa657fcac169208a))
* **@clayui/css:** Cadmin variables and components use Clay Color functions instead of Sass color functions for better CSS Custom Property support ([2c77b7b](https://github.com/liferay/clay/commit/2c77b7b7054fd18ebc5ffe01fadf8820cd2242fe))
* **@clayui/css:** cleanup build script ([60be3dd](https://github.com/liferay/clay/commit/60be3ddd225dcc76500319555eef938e99835044))
* **@clayui/css:** Global Color Functions adds aliases for Sass color functions `clay-darken`, `clay-lighten`, `clay-adjust-hue`, `clay-desaturate`, `clay-saturate`, `clay-mix`, `clay-blue`, `clay-green`, `clay-red`. It converts CSS Custom Property fallback values to the correct type before running them through the Sass functions. ([189e281](https://github.com/liferay/clay/commit/189e281a9a1329ca4efabfa79e8df9c05a5e6eaa))
* **@clayui/css:** Global Functions `math-sign` uses deprecated `[@elseif](https://github.com/elseif)` syntax, changed to `[@else](https://github.com/else) if` ([bd22a48](https://github.com/liferay/clay/commit/bd22a48bd54bd6c3bdf25493c81bf47d8fd46bbc)), closes [#4353](https://github.com/liferay/clay/issues/4353)
* **@clayui/css:** Global Functions use Clay Color Functions that support CSS Custom Properties with fallback value ([e7b1abf](https://github.com/liferay/clay/commit/e7b1abf2e49b208e3b24667431351a8faf2f15ca))
* **@clayui/css:** Mixins use Clay Color Functions instead of Sass color functions ([baaddfc](https://github.com/liferay/clay/commit/baaddfc2e3c253b4bfd256a9b5afbc0e4a08c0ab))
* **@clayui/css:** Modals `modal-body` should have border-top to create separation when components are inserted between `modal-header` and `modal-body` ([b3f648e](https://github.com/liferay/clay/commit/b3f648e9f873112bb7525440726304e8503f628d))
* **@clayui/css:** Modals `modal-header` increase z-index so it appears on top of `modal-body`. `modal-header` border gets hidden by `modal-body` border due to last commit. ([fd3ae71](https://github.com/liferay/clay/commit/fd3ae71089b7cc18f1381a886cecfceee9deac06))
* **@clayui/css:** remove `node-sass` and add new build file ([80f6ec2](https://github.com/liferay/clay/commit/80f6ec2457b290865f5cf0c58f3dedb2bf822085))


### Features

* **@clayui/css:** Alerts and Cadmin Alerts use Sass placeholders for alert variants for cleaner extends ([2c34258](https://github.com/liferay/clay/commit/2c3425892d7a78a345be145160ca4db7ad83eb07))
* **@clayui/css:** Badge converts `.badge`, `.badge-pill`, and badge variants to use `clay-badge-variant` mixin ([8c9d4eb](https://github.com/liferay/clay/commit/8c9d4ebc7702573841ffb313d64228a644029a21))
* **@clayui/css:** Cadmin Badge converts `.badge` and badge variants to use `clay-badge-variant` mixin ([a2b04b2](https://github.com/liferay/clay/commit/a2b04b2172b789175c1b64909ae6e055e112f462))
* **@clayui/css:** Globals and Cadmin Globals adds `$enable-clay-color-functions-process-fallback` and `$cadmin-enable-clay-color-functions-process-fallback` variables. This forces Clay color functions to return the CSS Custom Property instead of processing the fallback color and returning a hex value. ([15a6bc1](https://github.com/liferay/clay/commit/15a6bc180881422a87176a69974213ffb23f8b3e))
* **@clayui/css:** Mixins `clay-alert-variant` adds option to configure `.alert-indicator` ([0c9f913](https://github.com/liferay/clay/commit/0c9f913257935962fab0334521d1d871e264259b))
* **@clayui/css:** Mixins `clay-alert-variant` adds option to pass in styles to `.alert-indicator + .lead` ([ff5146b](https://github.com/liferay/clay/commit/ff5146b1f2a9bbee249a2ba696a0833c8706eb71))
* **@clayui/css:** Mixins adds `clay-badge-variant` ([dc52ed1](https://github.com/liferay/clay/commit/dc52ed18cfa6034b0219cd9f0c2c0ed6932ea18a))





# [3.37.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.36.0...v3.37.0) (2021-10-06)


### Bug Fixes

* **@clayui/css:** Alert update `$alert-*-btn` variant Sass maps to use newer keys ([ecdd38a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ecdd38a))
* **@clayui/css:** Alerts allow better customization of alert variant components, use `clay-alert-variant` mixin to generate alert variant styles ([9be70d7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9be70d7))
* **@clayui/css:** Alerts and Cadmin Alerts `alert-inline` should have more space between text and top / bottom borders ([29c4764](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/29c4764))
* **@clayui/css:** Atlas Alert changed back `$alert-font-size` to `0.875rem` and change `$alert-indicator-font-size` to `1rem` ([21d33ed](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/21d33ed))
* **@clayui/css:** Atlas and Cadmin Stickers swap background and foreground colors for `sticker-light` and `sticker-dark` ([adcd19f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/adcd19f))
* **@clayui/css:** Cadmin Alert update `$alert-*-btn` variant Sass maps to use newer keys and update `$cadmin-alert-palette` to use `$alert-*` variant Sass maps ([6a4a100](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6a4a100))
* **@clayui/css:** Cadmin Alerts allow better customization of alert variant components, use `clay-alert-variant` mixin to generate alert variant styles ([3410faf](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3410faf))
* **@clayui/css:** Cadmin Cards and Panels remove decision making if statements from border-radius and border-width. They were used to save a few bytes of CSS, not worth. ([677e804](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/677e804))
* **@clayui/css:** Cadmin Form Validation adds missing styles for `.form-feedback-group`, `.form-feedback-item`,`.form-feedback-indicator`, and `.form-text` ([db26016](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/db26016)), closes [#4298](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4298)
* **@clayui/css:** Cadmin Forms `fieldset[disabled] .form-control` should use values from the `$cadmin-input` Sass map and move rule-set closer to the `.form-control` rule-set ([0504ff2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0504ff2))
* **@clayui/css:** Cadmin Forms `label.disabled` should use properties declared in `$cadmin-input-label` map and move the `label.disabled` rule-set closer to the `label` rule-set ([d00b97b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d00b97b))
* **@clayui/css:** Cards and Panels remove decision making if statements from border-radius and border-width. They were used to save a few bytes of CSS, not worth. ([be44a21](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/be44a21))
* **@clayui/css:** Carousel, Custom Forms convert variables using Bootstrap's `url("data:image/svg+xml,<svg></svg>")` to use `clay-svg-url` ([c1cd8a2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c1cd8a2))
* **@clayui/css:** Form Validation use `clay-form-control-variant` to style Danger, Warning, Success readonly inputs instead of `clay-button-variant` ([23ed8cb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/23ed8cb))
* **@clayui/css:** Forms `fieldset[disabled] .form-control` should use values from the `$input` Sass map and move rule-set closer to the `.form-control` rule-set ([9ffc635](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9ffc635))
* **@clayui/css:** Forms `label.disabled` should use properties declared in `$input-label` map and move the `label.disabled` rule-set closer to the `label` rule-set ([0ea7c72](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0ea7c72))
* **@clayui/css:** Global Functions `math-sign` should return a negative calc value if a CSS custom property is passed in ([e824c5d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e824c5d))
* **@clayui/css:** Global Functions deprecate Bootstrap's `escape-svg` function ([e8ffa5d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e8ffa5d))
* **@clayui/css:** Global Variables deprecate Bootstrap 4 `$enable-hover-media-query`, `$caret-width`, `$caret-vertical-align`, `$caret-spacing`, `$emphasized-link-hover-darken-percentage` ([54d39f9](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/54d39f9))
* **@clayui/css:** Global Variables deprecate Bootstrap's `$escaped-characters` variable ([9b93ca0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9b93ca0))
* **@clayui/css:** Inverse Sass variable values should use the `math-sign` function ([835a62a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/835a62a))
* **@clayui/css:** Mixins Alerts adds `clay-alert-variant` mixin and deprecate Bootstrap's `alert-variant` mixin ([a3f1722](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a3f1722))


### Features

* **@clayui/css:** adds new classes `treeview-dropping-bottom`, `treeview-dropping-inside` and `treeview-dropping-top` ([f0b4c5e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f0b4c5e))
* **@clayui/css:** Alerts adds components `.alert-inline`, `alert-autofit-stacked`, `alert-autofit-stacked-sm-down`, `alert-autofit-stacked-xs-down`, `alert-indicator-start` ([7738e78](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7738e78))
* **@clayui/css:** Cadmin Alerts adds components `.alert-inline`, `alert-autofit-stacked`, `alert-autofit-stacked-sm-down`, `alert-autofit-stacked-xs-down`, `alert-indicator-start` ([b60b0c7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b60b0c7))
* **@clayui/css:** Cadmin Form Validation adds `$cadmin-input-danger`, `$cadmin-input-warning`, `$cadmin-input-success`, `$cadmin-input-danger-select`, `$cadmin-input-warning-select`, `$cadmin-input-success-select` Sass maps with `clay-form-control-variant` and `clay-select-variant` for more customization options ([df1e426](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/df1e426))
* **@clayui/css:** Form Validation adds `$input-danger`, `$input-warning`, `$input-success`, `$input-danger-select`, `$input-warning-select`, `$input-success-select` Sass maps with `clay-form-control-variant` and `clay-select-variant` for more customization options ([c23c8f5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c23c8f5))


### BREAKING CHANGES

* **@clayui/css:** `sticker-light` now has a light font color and `sticker-dark` has a dark font color. All instances of `sticker-light` should be updated to use `sticker-dark` and all instances of `sticker-dark` should be updated to use `sticker-light`. If you do not want to make this change in your markup, you can revert back to the original styles with:

```
$sticker-light-bg: $dark !default;
$sticker-light-color: $white !default;

$sticker-dark-bg: $dark !default;
$sticker-dark-color: $white !default;
```





# [3.36.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.35.3...v3.36.0) (2021-09-23)


### Bug Fixes

* **@clayui/css:** Atlas Global Variables define all global variables for easier copy and paste for those extending Clay CSS. This should help reduce undefined variable errors when reusing globals. ([acb598e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/acb598e))
* **@clayui/css:** Atlas removes Sassdoc comments. All documentation that gets generated should go in Base ([89dc333](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/89dc333)), closes [#4275](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4275)
* **@clayui/css:** Base Theme Global variables move settings toward the top of the file. ([b1b309d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b1b309d))
* **@clayui/css:** Buttons and Cadmin Buttons `.btn-monospaced` icons are off center by a pixel, use `display: inline-flex` to center and remove padding. If you need items to display inline in `.btn-monospaced` wrap them in a `span` tag. ([ece0b5b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ece0b5b))
* **@clayui/css:** Buttons create Sass placeholders for Clay CSS btn-* classes to allow theme devs to [@extend](https://github.com/extend) their button classes from it ([f7e50f0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f7e50f0)), closes [#4248](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4248)
* **@clayui/css:** Global Functions `clay-enable-transitions` should return `$transitions` instead of `$transition` ([ca2d59a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ca2d59a))
* **@clayui/css:** Global Functions `clay-enable-transitions` the variable `$enable-transitions` isn't available in Cadmin, use `$enable` instead ([bd4e1c5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bd4e1c5))
* **@clayui/css:** Mixins `clay-button-variant` adds option to style `:disabled:focus`, mostly for removing focus shadow on disabled `.btn` ([bb942f9](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bb942f9))
* **@clayui/css:** Mixins `clay-button-variant` c-inner should work if mobile sizes are enabled ([a0a005c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a0a005c))
* **@clayui/css:** Mixins `clay-button-variant` remove outputting `a.btn, button.btn { cursor: pointer; }` we can pass it in directly to `.btn` ([d5a1942](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d5a1942))
* **@clayui/css:** Mixins form-control-variant update hover, focus, disabled to accept nested placeholder maps ([05a85ca](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/05a85ca))


### Features

* **@clayui/css:** Buttons convert `.btn-lg` and `.btn-sm` to use `clay-button-variant` mixin ([f6b3e95](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f6b3e95))
* **@clayui/css:** Buttons convert `.btn-unstyled`, `.btn-monospaced`, `.btn-monospaced-lg`, `.btn-monospaced-sm`, `.btn-outline-borderless` to use `clay-button-variant` mixin ([4c16ce5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4c16ce5))
* **@clayui/css:** Buttons convert `.btn` to use `clay-button-variant` mixin ([617befc](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/617befc))
* **@clayui/css:** Cadmin Buttons convert `.btn`, `.btn-lg`, `.btn-sm`, `.btn-monospaced`, `.btn-monospaced-sm`, `.btn-monospaced-lg`, `.btn-unstyled`, and `.btn-outline-borderless` to use `clay-button-variant` mixin ([8481f19](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8481f19))
* **@clayui/css:** Cadmin Forms convert label and .form-control to use clay-css mixin ([4226e59](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4226e59))
* **@clayui/css:** Forms convert label and .form-control to use clay-css mixin ([6a8b9f0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6a8b9f0))
* **@clayui/css:** Global Functions adds `starts-with($str1, $str2)`. A function that determines whether the string `$str1` begins with the characters of the specified string `$str2`. ([6ddef3e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6ddef3e))
* **@clayui/css:** Mixins `clay-css` if transition has a value other than `null` or `none`, it should output a prefers-reduced-motion media query ([95b5c08](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/95b5c08))
* **@clayui/css:** Mixins `clay-css` should output any CSS Custom Properties passed into it. ([a78ddfa](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a78ddfa)), closes [#4252](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4252)
* **@clayui/css:** Move .hide from liferay-portal to clay-css ([0e25435](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0e25435))





## [3.35.3](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.35.2...v3.35.3) (2021-09-09)


### Bug Fixes

* **@clayui/css:** Forms use fixed value for $input-height-inner, $input-height-inner-half, $input-height-inner-quarter to reduce Sass errors with CSS custom properties in $input-line-height and $input-padding-y ([2fa8ca3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2fa8ca3)), closes [#4247](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4247)





## [3.35.2](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.35.1...v3.35.2) (2021-08-30)

**Note:** Version bump only for package @clayui/css





## [3.35.1](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.35.0...v3.35.1) (2021-08-30)

**Note:** Version bump only for package @clayui/css





# [3.35.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.34.0...v3.35.0) (2021-08-30)

**Note:** Version bump only for package @clayui/css





# [3.34.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.33.1...v3.34.0) (2021-08-25)


### Bug Fixes

* **@clayui/css:** Atlas Form readonly input with validation should use the background-color of the base readonly input ([f5580ac](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f5580ac))
* **@clayui/css:** Cadmin adds Timelines component, used in Asset Publisher Configuration Modals ([f7b473a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f7b473a))
* **@clayui/css:** Cadmin Modals allow adding cadmin directly to modal-header, modal-body, and modal-footer elements ([038f5be](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/038f5be))
* **@clayui/css:** Cadmin toggle-switch-check-bar should be 48px wide in larger screens ([5dee0f0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5dee0f0))
* **@clayui/css:** Cards deprecate Bootstrap 4 components `.card-header-tabs`, `.card-header-pills`, `.card-img-*`, `.card-deck`, `.card-group`, `.card-columns`, `.accordion`. Enable them again by setting `$enable-bs4-deprecate: true;`. ([4a05474](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4a05474))
* **@clayui/css:** Custom Forms deprecate Bootstrap 4 components `.custom-switch`, `.custom-select`, `.custom-select-lg`, `.custom-select-sm`, `.custom-file`, `.custom-range` ([bc2c5f5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bc2c5f5))
* **@clayui/css:** Custom Forms remove duplicates of custom-control-indicator-checked-border-color and dropdown-font-size ([f0e3212](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f0e3212))
* **@clayui/css:** Deprecate Bootstrap 4 component Jumbotron. Enable again by setting `$enable-bs4-deprecate: true;`. ([32d3fd1](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/32d3fd1))
* **@clayui/css:** Deprecate the Bootstrap 4 Carousel component. Enable them again by setting `$enable-bs4-deprecate: true;`. ([7026c40](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7026c40))
* **@clayui/css:** Form deprecate Bootstrap 4 components `.col-form-label`, `.col-form-label-lg`, `.col-form-label-sm`, `.form-row`, `.form-inline`. Enable them again by setting `$enable-bs4-deprecate: true;`. ([08da40a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/08da40a))
* **@clayui/css:** Form Validation deprecate Bootstrap 4 HTML5 Form Validation components `.was-validated`, `.invalid-feedback`, `.valid-feedback`, `.#{$state}-feedback`, `.#{$state}-tooltip` ([ed0e374](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ed0e374))
* **@clayui/css:** Globals adds `$enable-bs4-deprecated` setting to enable Bootstrap 4 components that we have deprecated ([7e9ac0d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7e9ac0d))
* **@clayui/css:** Globals set `$enable-bs4-deprecated: true !default;`. You can disable the deprecated Bootstrap 4 components by setting `$enable-bs4-deprecated: false !default;`. This will prevent the deprecated component CSS from being output. ([01f3ba6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/01f3ba6))
* **@clayui/css:** Mixins Timelines ignore timeline variables and use cadmin variables when compiling Cadmin Timelines ([2eebd4a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2eebd4a))
* **@clayui/css:** Nav deprecate Bootstrap 4 component `.nav-pills`. Enable again by setting `$enable-bs4-deprecate: true;`. ([d2c9027](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d2c9027))
* **@clayui/css:** Removes unused variables: ([32b1c4c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/32b1c4c))
* **@clayui/css:** Spinners deprecate Bootstrap 4 component. Enable again by setting `$enable-bs4-deprecate: true;`. ([3f8fe71](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3f8fe71))
* **@clayui/css:** Table remove unused components `.table-drag`, `.table-dragging`, `.table-clone` and remove maps `$table-drag`, `$table-dragging`, `$table-clone` ([e6adb42](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e6adb42))
* **@clayui/css:** Toasts deprecate Bootstrap 4 component. Enable again by setting `$enable-bs4-deprecate: true;`. ([02845eb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/02845eb))
* **@clayui/css:** Wrap *-theme-colors map keys in single quotes. Key names that match CSS colors makes Sass throw this warning without quotes: ([2a1fb6a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2a1fb6a)), closes [#4219](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4219)





## [3.33.1](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.33.0...v3.33.1) (2021-08-12)


### Bug Fixes

* **@clayui/css:** Globals move `$bg-theme-colors`, `$bg-gradient-theme-colors`, `$border-theme-colors`, `$text-theme-colors` maps to where they are used in Utilities ([07f4c9d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/07f4c9d)), closes [#4214](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4214)
* **@clayui/css:** Use fallback value for `$body-bg` when using variable inside a Sass color function. Sass color functions do not accept CSS custom property as a value. ([ae0dff6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ae0dff6))
* **@clayui/css:** Utilities Functional Important generate `.border-white` with `$border-theme-colors` map ([40131be](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/40131be)), closes [#4214](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4214)





# [3.33.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.32.1...v3.33.0) (2021-08-11)


### Bug Fixes

* **@clayui/css:** Cadmin Modal .modal.show should have display: block ([5876b9f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5876b9f)), closes [#4203](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4203)
* **@clayui/css:** Cadmin removes unused variables `$cadmin-body-moz-osx-font-smoothing`, `$cadmin-body-webkit-font-smoothing`, `$cadmin-body-text-align`. We don't provide a CSS reset in Cadmin. ([c3af64e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c3af64e))
* **@clayui/css:** Forms .form-control-select with long text shouldn't break to new line and should have overflow ellipsis, similar behavior to select.form-control ([44804d8](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/44804d8)), closes [#4206](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4206)
* **@clayui/css:** Forms remove Bootstrap's confusing way of setting an inset box-shadow on an input. This causes flickering on .btn.form-control-select on click. If you want a regular box-shadow and an inset box-shadow on an input define them both inside the $input-box-shadow variable. Example below: ([83d56d1](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/83d56d1)), closes [#4206](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4206)
* **@clayui/css:** Functions adds `_type-conversion-functions.scss` for converting colors of type string to type color. Sass doesn't provide a way to do this https://github.com/sass/sass/issues/3006. ([68be792](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/68be792)), closes [#4180](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4180)
* **@clayui/css:** Global Functions `clay-get-fallback` convert color string to type color ([68fd699](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/68fd699))
* **@clayui/css:** Removes the use of `$theme-colors` Sass map to generate utility properties (e.g., `bg-primary`, `text-primary`, `list-group-item-primary`, `table-primary`) and allow configuring separately. The new way also supports CSS variables. Adds new maps: ([78fb2d2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/78fb2d2))


### Features

* **@clayui/css:** Reboot `body` element should use clay-css mixin for generating properties ([c0b456e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c0b456e)), closes [#4194](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4194)





## [3.32.1](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.32.0...v3.32.1) (2021-07-30)


### Bug Fixes

* **@clayui/css:** Cadmin Treeview scope `component-action`, `component-expander`, `component-icon`, `component-text` so styles don't bleed into other components ([1ce70bd](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1ce70bd)), closes [#4198](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4198)





# [3.32.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.31.0...v3.32.0) (2021-07-28)


### Bug Fixes

* **@clayui/css:** Cadmin Links adds `component-text` and `component-icon`, generic names for reuse in other components ([ae49f03](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ae49f03))
* **@clayui/css:** Cadmin Treeview new component ([ea1568e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ea1568e))
* **@clayui/css:** Forms `form-group-sm div.form-control` should be 32px tall and grow to fix content inside, similar to a textarea element ([eb987a1](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/eb987a1)), closes [#4164](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4164)
* **@clayui/css:** Grid generating `container-max-width-*` classes should work with Custom Properties ([b12dbf5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b12dbf5))
* **@clayui/css:** Mixins update `clay-loading-animation-variant` to use `clay-css` pattern ([4280c6f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4280c6f)), closes [#3987](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3987)
* **@clayui/css:** Mixins update `sheet-footer-btn-block` to use `clay-css` pattern ([5523b67](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5523b67)), closes [#3987](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3987)
* **@clayui/css:** Sheet `$sheet-lg-max-width` should use fixed number instead of generating based on a `$container-max-widths` value ([5968bd5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5968bd5))
* **@clayui/css:** Utilities remove duplicate rounded utilities ([6687624](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6687624))


### Features

* **@clayui/css:** $container-max-widths Sass map should accept CSS Custom Properties ([3a8ffe2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3a8ffe2))
* **@clayui/css:** Buttons use nested property names in variables to stay as close as possible to the way our CSS is written ([89e3360](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/89e3360)), closes [#4176](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4176)
* **@clayui/css:** Functions adds `map-deep-get` for getting values of deeply nested Sass map items ([2b80302](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2b80302))





# [3.31.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.30.0...v3.31.0) (2021-06-30)


### Bug Fixes

* **@clayui/css:** Links convert variables to use nested Sass map pattern ([1a9d654](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1a9d654))
* **@clayui/css:** Mixin Links don't use nested setters. The setter function takes an Argslist now, we can pass any number of Sass maps with one function call ([dfa1ea2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/dfa1ea2))
* **@clayui/css:** Removes nested `setter` functions, only need to call it once. See https://github.com/liferay/clay/issues/4076. ([e2db591](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e2db591))


### Features

* **@clayui/css:** Add `square-hole-multi` SVG icon ([205046c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/205046c))
* **@clayui/css:** SVG Icons adds search-experiences.svg ([39ae51d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/39ae51d))





# [3.30.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.29.0...v3.30.0) (2021-06-16)


### Bug Fixes

* **@clayui/css:** Mixins `clay-panel-variant` updates mixin to use nested maps pattern ([ea0c66a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ea0c66a))
* **@clayui/css:** Modal and Cadmin Modal make `.modal-body.inline-scroller` `max-height: 320px` ([815d6d4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/815d6d4)), closes [#4113](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4113)
* **@clayui/css:** Panel adjust spacing for `panel-unstyled` to prevent visual jump on close. ([9dec5b6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9dec5b6))
* **@clayui/css:** Panel and Cadmin Panel update variables that use `clay-panel-variant` mixin to use newest keys, The old keys still work and will win over new keys. ([ea4bffb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ea4bffb))
* **@clayui/css:** Reboot and Cadmin Reboot removes negative tabindex rule that removes default focus outline due to keyboard navigation accessibility issues. `tabindex="-1"` can still be focused programmatically. ([9e52cfb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9e52cfb)), closes [#4124](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4124)





# [3.29.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.28.0...v3.29.0) (2021-05-28)


### Bug Fixes

* **@clayui/css:** Global Functions update `setter` to accept more than 2 variables (e.g., `setter($var1, $var2, $var3, $var4, $var5)`) ([2a923f0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2a923f0)), closes [#4076](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4076)
* **@clayui/css:** Mixins `clay-aspect-ratio-item-variant` and `clay-aspect-ratio-variant` convert to use new (easier to remember) Sass map keys. The old keys will still work and win over new keys. ([d4680a9](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d4680a9)), closes [#4085](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4085)
* **@clayui/css:** Mixins Card convert to use new (easier to remember) Sass map keys. The old keys will still work and win over new keys. ([a2e6d34](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a2e6d34)), closes [#4088](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4088)


### Features

* **@clayui/css:** Adds the `block` SVG icon ([96dabe4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/96dabe4))





# [3.28.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.27.0...v3.28.0) (2021-05-19)


### Bug Fixes

* **@clayui/css:** Cadmin Alert adds `.cadmin.alert-container` selector ([a104844](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a104844))
* **@clayui/css:** Cadmin Badges remove unused components `inline-item` and `badge-pill` ([46868c7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/46868c7))
* **@clayui/css:** Cadmin Button Groups remove unused components `dropdown-toggle-split` and `btn-group-toggle` ([3fef3d5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3fef3d5))
* **@clayui/css:** Cadmin Cards remove unused components `card-header-tabs`, `card-header-pills`, `card-deck`, `card-group`, `card-columns`, `accordion` ([06bdb00](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/06bdb00))
* **@clayui/css:** Cadmin Dropdown remove unused component dropdown in navbar ([e062006](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e062006))
* **@clayui/css:** Cadmin Form Validation remove unused components HTML 5 form validation ([8cb7a19](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8cb7a19))
* **@clayui/css:** Cadmin Forms remove unused components `col-form-label`, `col-form-label-lg`, `col-form-label-sm`, `form-row`, `form-inline` ([81e1f4f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/81e1f4f))
* **@clayui/css:** Cadmin Icons remove unused components `lexicon-icon-sm`, `lexicon-icon-lg`, `lexicon-icon-xl` ([f0ee8fc](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f0ee8fc))
* **@clayui/css:** Cadmin Input Group remove styles related to `custom-select`, `custom-file` ([cdf23e7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cdf23e7))
* **@clayui/css:** Cadmin Labels remove deprecated component `inline-item` ([9ed5291](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9ed5291))
* **@clayui/css:** Cadmin List Group remove unused component `list-group-horizontal` ([0b7f427](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0b7f427))
* **@clayui/css:** Cadmin merge Atlas variables with Cadmin base variables, we don't need two themes here ([0eb6d29](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0eb6d29))
* **@clayui/css:** Cadmin Modals remove unused component `modal-dialog-scrollable` ([130dc5c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/130dc5c))
* **@clayui/css:** Cadmin move _reboot out of scoping selector, attribution text is causing empty selector to be output ([ad36b85](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ad36b85))
* **@clayui/css:** Cadmin Navs remove unused component `nav-pills` ([d27a7a1](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d27a7a1))
* **@clayui/css:** Cadmin port changes to Clay CSS that were made before Cadmin got merged: [#3998](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3998), [#4002](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4002), [#4040](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4040), [#4055](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4055), [#4056](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4056), [#4060](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4060) ([240bbc4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/240bbc4)), closes [#4064](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4064)
* **@clayui/css:** Cadmin re-add widths for menubar and SF. Not sure what happened. ([9142345](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9142345))
* **@clayui/css:** Cadmin remove unused components `custom-switch`, `custom-select`, `custom-file`, `custom-range` ([fc447e2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/fc447e2))
* **@clayui/css:** Cadmin removes Atlas variables ([4af356f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4af356f))
* **@clayui/css:** Cadmin removes components _root, _carousel, _jumbotron, _spinners, _toasts, _media, _application-bar, _drilldown, and _timelines. They are not used for Admin controls. ([9ddeaed](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9ddeaed))
* **@clayui/css:** Cadmin removes Sass docs comments ([62e5541](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/62e5541))
* **@clayui/css:** Cadmin removes variables related to unused components ([7ec35dc](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7ec35dc))
* **@clayui/css:** Cadmin Side Navigation remove unused component `container-fluid-1280` ([41d8b50](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/41d8b50))
* **@clayui/css:** Cadmin theme use selector `.cadmin.component` for components that render inside react portals. It's too difficult to put `cadmin` on the parent element. ([640a662](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/640a662))
* **@clayui/css:** Cadmin update Sass maps that use `clay-select-variant` to use new keys ([c782615](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c782615))
* **@clayui/css:** Cadmin Utilities display utilities should also have `.cadmin.d-{display}` ([4bb7a0a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4bb7a0a))
* **@clayui/css:** Input Groups add `btn-monospaced` support for buttons inside `input-group-inset-item` ([0d31b54](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0d31b54)), closes [#4049](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4049)
* **@clayui/css:** Labels convert variables to use new Sass map keys ([dcfc7c3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/dcfc7c3))
* **@clayui/css:** Management Bar Search button should be properly aligned in mobile view ([1c3f583](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1c3f583))
* **@clayui/css:** Mixins `border-radius` shouldn't output the default radius if a null parameter is passed ([42241df](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/42241df)), closes [#4066](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4066)
* **@clayui/css:** Mixins `clay-label-size` and `clay-label-variant` convert to use new (easier to remember) Sass map keys. The old keys will still work and win over new keys. ([2123fdf](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2123fdf)), closes [#4069](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4069)
* **@clayui/css:** Mixins `clay-nav-variant` convert to use new (easier to remember) Sass map keys. The old keys will still work and win over new keys. ([3fa114a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3fa114a)), closes [#4071](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4071)
* **@clayui/css:** Mixins `clay-select-variant` update to use `clay-css` pattern, also deprecated keys should win over new keys ([65ad45e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/65ad45e))
* **@clayui/css:** Mixins border-radius should use custom value first ([5d30ab2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5d30ab2))
* **@clayui/css:** Restore default padding-left on ul, ol, dl that are undone by cadmin ([1db5db7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1db5db7))
* **@clayui/css:** Subnav Tbar labels should have $font-weight-normal by default ([e1e36a6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e1e36a6))
* **@clayui/css:** Toggle Switch should be 48px wide ([6735e54](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6735e54))


### Features

* **@clayui/css:** Add `form-extensions` SVG icon ([3061a9a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3061a9a))
* **@clayui/css:** Add SVG icons `chatbot` and `signature` ([7966c62](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7966c62))
* **@clayui/css:** Cadmin theme convert rem values to px ([2e33149](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2e33149))
* **@clayui/css:** Created scoped version of Clay CSS for admin style isolation and prefix variables with `$cadmin-` ([f1ae440](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f1ae440))
* **@clayui/css:** Functions and Mixins update to accept Clay CSS variables, Cadmin variables, or custom where applicable ([b1eb431](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b1eb431))





# [3.27.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.26.0...v3.27.0) (2021-05-05)


### Bug Fixes

* **@clayui/css:** Date Picker previous-month-date and next-month-date active should be lighter ([51a24f3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/51a24f3))
* **@clayui/css:** Menubar convert old Sass map keys to key names so older keys used by previous versions will win ([9a1a73a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9a1a73a))
* **@clayui/css:** Menubar update `$menubar-vertical-expand-md` and `$menubar-vertical-expand-lg` to use new keys. Older keys will still win over new keys to preserve backward compatibility. ([12b9636](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/12b9636))
* **@clayui/css:** Mixins `clay-form-control-variant` old keys should win over new keys ([8986a81](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8986a81)), closes [#3987](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3987)
* **@clayui/css:** Mixins `clay-menubar-vertical-expand` use `clay-css` mixin pattern ([6a9ba26](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6a9ba26))
* **@clayui/css:** Mixins `clay-menubar-vertical-variant` moves default styles to variables. The mixin should only output styles if values are given. ([703b76e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/703b76e))
* **@clayui/css:** Progress Bar sets a `min-width` on `progress-group-addon` to prevent resizing progress bar when numbers are changed to icons ([63e63c0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/63e63c0)), closes [#4024](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4024)
* **@clayui/css:** Sass maps passed into `clay-form-control-variant` mixin should use new keys. This allows variable theme overwrites using deprecated keys to still win. ([f3be2d6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f3be2d6)), closes [#3987](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3987)


### Features

* **@clayui/css:** SVG Icons add rotate ([0fec9ce](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0fec9ce))
* **@clayui/css:** SVG Icons adds `order-list-down` and `order-list-up` ([f80f8a0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f80f8a0)), closes [#4021](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/4021)





# [3.26.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.25.4...v3.26.0) (2021-04-21)


### Features

* **@clayui/css:** Alerts adds `alert-feedback` modifier ([51b57e6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/51b57e6)), closes [#3968](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3968)
* **@clayui/css:** Date Picker adds Date Range styles ([a385e6a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a385e6a))





## [3.25.3](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.25.2...v3.25.3) (2021-03-24)


### Bug Fixes

* **@clayui/css:** Atlas Menubar (Vertical Navigation) link active state should be more visible ([5a94cfd](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5a94cfd))
* **@clayui/css:** Menubar toggler with c-inner cuts off caret icon ([1932782](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1932782))
* **@clayui/css:** Mixins `clay-link` adds option to style `&.show, &[aria-expanded='true']` separately from `active-class` so we can style panel toggles ([8a1a148](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8a1a148))





## [3.25.2](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.25.1...v3.25.2) (2021-03-10)


### Bug Fixes

* **@clayui/css:** Dual List Box `form-control-inset` is too narrow caused by [#3972](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3972) ([637e65b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/637e65b)), closes [#3976](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3976)
* **@clayui/css:** Forms `.col-form-label-*` should use `$input-border-bottom-width` or `$input-border-top-width` to avoid invalid property value ([ade3649](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ade3649)), closes [#3946](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3946)





## [3.25.1](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.25.0...v3.25.1) (2021-03-05)


### Bug Fixes

* **@clayui/css:** Atlas Custom Checkbox use hr icon for indeterminate indicator ([a894c5b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a894c5bd1fe500894d55bfd656efde142ba81db6))
* **@clayui/css:** Forms `form-control-tag-group component-action` should be height 100% ([4b4b140](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4b4b140b87019d9fa4c00186219090524dce1fcd))
* **@clayui/css:** SVG Icons updates `hr` icon per Lexicon ([949944c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/949944ccaac1b21091628b15cedd3b7ea96287af))





# [3.25.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/v3.24.1...v3.25.0) (2021-02-23)


### Bug Fixes

* **@clayui/css:** Global Functions moves generated SVG icons Sass map to separate file `_lx-icons-generated.scss` ([7ffc523](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7ffc523))





## [3.24.1](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.24.0...@clayui/css@3.24.1) (2021-02-11)


### Bug Fixes

* **@clayui/css:** Atlas Alert close font-size should be 16px ([245eac5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/245eac5)), closes [#3877](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3877)
* **@clayui/css:** Atlas Clay Color change close button icon to be 16px ([2309d7a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2309d7a)), closes [#3878](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3878)
* **@clayui/css:** Atlas Select Element IE11 should hide default icon and use caret-double-l instead ([6623ff7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6623ff7)), closes [#3922](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3922)
* **@clayui/css:** Clay Color adjust spacing to be the same as Lexicon specs. See https://docs.google.com/document/d/1IUGl5VOWh6lqRa1baRoshVcytc8XbqVMkk30vRW4SM8/edit#heading=h.o2fss76woci2 ([704d25d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/704d25d))





# [3.24.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.23.0...@clayui/css@3.24.0) (2021-01-27)


### Bug Fixes

* **@clayui/css:** Absorb Bootstrap 4 variables into Clay CSS ([d4be0ec](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d4be0ec))
* **@clayui/css:** Atlas `color-yiq` function not useable in Atlas variables due to `$yiq-contrasted-threshold` undefined ([2035a8b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2035a8b)), closes [#3708](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3708)
* **@clayui/css:** Atlas Toggle Switch change checked state button icon color to primary ([de9ca0b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/de9ca0b)), closes [#3872](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3872)
* **@clayui/css:** List Group adds missing disabled styles for list-group-item ([bdc3acf](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bdc3acf))
* **@clayui/css:** Removes Bootstrap 4 variable overwrites, still keeping this file to prevent Sass import errors from custom imports ([1232870](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1232870))
* **@clayui/css:** Removes imports for Bootstrap 4 variables and variable overwrites ([bd0f614](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bd0f614))
* **@clayui/css:** Tables set background-color on thead, tbody, tfoot for Table and Table List. This is for a Chrome 87 bug. ([3b0badb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3b0badb)), closes [#3847](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3847)


### Features

* **@clayui/css:** Atlas Toggle Switch make it 40px by 24px in desktop views ([50c5c6d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/50c5c6d)), closes [#3835](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3835)
* **@clayui/css:** SVG Icons adds cursor.svg ([afbb1f0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/afbb1f0))





# [3.23.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.22.1...@clayui/css@3.23.0) (2021-01-13)


### Bug Fixes

* **@clayui/css:** Breadcrumbs match sizes to Lexicon specs ([0d471aa](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0d471aa))
* **@clayui/css:** Buttons shouldn't inherit `text-transform` from its parent ([a66dcba](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a66dcba))
* **@clayui/css:** Component Title used in Sheet should work ([c338b71](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c338b71))
* **@clayui/css:** Label use times-small icon and close button should be 16px by 16px ([c2270a9](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c2270a9))
* **@clayui/css:** run format ([19ee791](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/19ee791))
* **@clayui/css:** SVG Icons adds relationship.svg ([6253c68](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6253c68)), closes [#3873](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3873)


### Features

* **@clayui/css:** Sheet adds variants `.sheet-multiple-form` and `.sheet-dataset-content` ([cf4a4d1](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cf4a4d1))
* **@clayui/css:** SVG Icons adds google-drive ([3752c14](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3752c14)), closes [#3869](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3869)
* **@clayui/css:** Utilities adds `.autofit-padded-no-gutters-sm` and placeholder `%autofit-padded-no-gutters-sm` for smaller (4px) gutters between columns ([f0cc8f4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f0cc8f4))





## [3.22.1](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.22.0...@clayui/css@3.22.1) (2020-12-29)


### Bug Fixes

* **@clayui/css:** Atlas Theme change body background-color to #fff to match Classic and Admin themes ([04f0a02](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/04f0a02))
* **@clayui/css:** Management Bar set a min-height so swapping out contents via js doesn't resize the bar ([9a484d5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9a484d5))
* **@clayui/css:** Mixins clay-navbar-size adds option to configure min-height and min-height-mobile ([4236b13](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4236b13))
* **@clayui/css:** Navigation Bar Light should have 1px gray bottom border ([625e629](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/625e629))
* **@clayui/css:** SVG Icons adds `rectangle.svg` and `rectangle-split.svg` ([bb2556b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bb2556b))


### Reverts

* **@clayui.css): "feat(@clayui/css:** SVG Icons adds full-view.svg and split-view.svg" ([4bea06b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4bea06b))





# [3.22.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.20.0...@clayui/css@3.22.0) (2020-12-16)


### Bug Fixes

* **@clayui/css:** Mixin `clay-css` adds `-webkit-overflow-scrolling` and `fill` properties ([a18d2a6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a18d2a6)), closes [#3771](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3771)
* **@clayui/css:** Mixins clay-link active-class should also style `&[aria-expanded='true']` and `&.show` so we can style collapse plugin open state ([a559fd3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a559fd3)), closes [#3767](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3767)
* **@clayui/css:** SVG Icons adds dropdown.svg ([892d3ae](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/892d3ae))
* **@clayui/css:** Tables don't require the class `table-autofit` for `table-cell-expand`, `table-cell-expand-small`, `table-cell-expand-smaller`, and `table-cell-expand-smallest` to work. Also adds `table-cell-contract`. ([6f7f2bf](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6f7f2bf)), closes [#3818](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3818)
* **@clayui/css:** Tables moves caption styles from _reboot.scss to _tables.scss and change default to `caption-side: top` ([168abf4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/168abf4)), closes [#272833](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/272833)


### Features

* **@clayui/css:** Mixins `clay-button-variant` allow styling `.active` separately from `:active` with `active-class` ([d2370d3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d2370d3)), closes [#3797](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3797)
* **@clayui/css:** SVG Icons adds arrow-right-full.svg ([631e2d0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/631e2d0))
* **@clayui/css:** SVG Icons adds automatic-translate.svg ([03eba11](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/03eba11))
* **@clayui/css:** SVG Icons adds fieldset.svg ([1900c8d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1900c8d)), closes [#3828](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3828)
* **@clayui/css:** SVG Icons adds full-view.svg and split-view.svg ([bbd6ede](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bbd6ede))
* **@clayui/css:** SVG Icons adds icon for React ([8e09e97](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8e09e97))





# [3.21.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.20.0...@clayui/css@3.21.0) (2020-12-02)


### Bug Fixes

* **@clayui/css:** Tables don't require the class `table-autofit` for `table-cell-expand`, `table-cell-expand-small`, `table-cell-expand-smaller`, and `table-cell-expand-smallest` to work. Also adds `table-cell-contract`. ([6f7f2bf](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6f7f2bf)), closes [#3818](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3818)
* **@clayui/css:** Tables moves caption styles from _reboot.scss to _tables.scss and change default to `caption-side: top` ([168abf4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/168abf4)), closes [#272833](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/272833)


### Features

* **@clayui/css:** SVG Icons adds automatic-translate.svg ([03eba11](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/03eba11))
* **@clayui/css:** SVG Icons adds icon for React ([8e09e97](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8e09e97))





# [3.20.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.19.0...@clayui/css@3.20.0) (2020-11-16)


### Bug Fixes

* **@clayui/css:** Time Picker `clay-time-edit` use `display: flex` and don't rely on white-space for spacing ([e4ab83d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e4ab83d)), closes [#3783](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3783)


### Features

* **@clayui/css:** Absorb Bootstrap 4 mixins into Clay CSS ([27032c4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/27032c4))
* **@clayui/css:** Dropdown adds `.dropdown-menu-width-full`, `.dropdown-menu-width-sm`, `dropdown-menu-height-auto` modifier classes for larger dropdown menus with the Clay Drop Down plugin ([bab438c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bab438c)), closes [#3790](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3790)
* **@clayui/css:** Removes Bootstrap 4 mixins and functions imports ([cba11d0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cba11d0))





# [3.19.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.18.2...@clayui/css@3.19.0) (2020-10-22)


### Bug Fixes

* **@clayui/css:** `drilldown-item-indicator-text-*` click area should be larger ([bc53c65](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bc53c65)), closes [#3579](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3579)
* **@clayui/css:** Atlas fix custom radio button image, inline radio misaligned in Chrome ([ef1fc95](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ef1fc95))


### Features

* **@clayui/css:** SVG Icons adds shield-check ([5c1760c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5c1760c)), closes [#3755](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3755)





## [3.18.2](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.18.1...@clayui/css@3.18.2) (2020-10-01)


### Bug Fixes

* **@clayui.com:** Atlas Buttons `.btn-outline-secondary` should have color [#6](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/6)b6c7e, caused by [#3149](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3149) ([7418263](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7418263)), closes [#6b6c7](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/6b6c7)
* **@clayui/css:** Atlas Custom Radio don't use % for icon background-size. Chrome has trouble rendering it when whitespace is removed. ([5375e63](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5375e63)), closes [#3722](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3722)
* **@clayui/css:** Btn Group `.btn-monospaced.btn-sm` doesn't work inside `.btn-group-vertical` and same for `.btn-monospaced.btn-lg` ([750b061](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/750b061))
* **@clayui/css:** SVG Icons `display`, `display-content`, `product-menu-open`, `product-menu-closed`, and `hidden` updates anchor points, weights, and minor alignment issues ([2a01b38](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2a01b38))





## [3.18.1](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.18.0...@clayui/css@3.18.1) (2020-08-28)


### Bug Fixes

* **@clayui/css:** add font weight semibold ([f85a519](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f85a519))
* **@clayui/css:** Table Responsive re-add `margin-bottom` that was removed in [#3149](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3149) ([cef6b0f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cef6b0f))





# [3.18.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.17.1...@clayui/css@3.18.0) (2020-08-26)


### Features

* **@clayui/toolbar:** Add clayui/form to deps, Add low-level components to Toolbar ([719b71f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/719b71f))





## [3.17.1](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.17.0...@clayui/css@3.17.1) (2020-08-21)


### Bug Fixes

* **@clayui/css:** Table List use `border-collapse` and `border-width` instead of `box-shadow` hack for rounded corners ([82ecbda](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/82ecbda))





# [3.17.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.16.0...@clayui/css@3.17.0) (2020-08-11)


### Bug Fixes

* **@clayui/css:** `variables/_globals.scss` and `components/_reboot.scss` rename `$c-button` Sass map, added in [#3575](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3575), to `$c-button-base`. This namespace references a base element, in this case, `<button>`. This is to free up the variable namespace `$c-button` to refer to `.button` if we ever need it in the future. ([45c088a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/45c088a))
* **@clayui/css:** Alerts text in `alert-autofit-row` break to new line prematurely ([8b13ce3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8b13ce3))
* **@clayui/css:** Atlas Custom Checkbox use `check-small` instead of ([4e059fe](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4e059fe))
* **@clayui/css:** Atlas Drilldown header button is off by 1px ([4224a60](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4224a60))
* **@clayui/css:** C Kbd each key in a keyboard shortcut should be wrapped in its own `kbd` element ([36ec62e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/36ec62e)), closes [#3283](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3283)
* **@clayui/css:** Dropdown `.dropdown-item` should use `cursor: pointer` so `<a class="dropdown-item" role="button">` will still behave like a clickable element ([1311053](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1311053))
* **@clayui/css:** Mixins `clay-css` adds `-moz-appearance` and `-webkit-appearance` to the list of properties so we can pass them in independently when needed ([946bd9c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/946bd9c))
* **@clayui/css:** Mixins `clay-dropdown-item-variant` `active-class` should use `active` values unless it's overridden using the `active-class` map ([c521848](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c521848))
* **@clayui/css:** Reboot adds `cursor: pointer` to `button` CSS reset ([4eca62f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4eca62f))
* **@clayui/css:** Reboot go back to Bootstrap 4's styling `a` tag directly but omit styling placeholder anchors. Placeholders are styled the same as links now which makes it easier to use markup like `<a class="btn btn-primary" role="button" tabindex="0">` without having to add styles. ([170adfb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/170adfb))
* **@clayui/css:** SVG Icons update `check` path ([d24abf0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d24abf0))
* **@clayui/css:** SVG Icons update `times-small` ([0970c0f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0970c0f))
* **@clayui/css:** SVG Icons update `times` path ([31020e9](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/31020e9))
* **@clayui/css:** Table `.table` should have 1px borders ([ca0a17c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ca0a17c))
* **@clayui/css:** Update global functions ([d43ac9b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d43ac9b))


### Features

* **@clayui/css:** Clay Color `.clay-color-map` and `.clay-color-range` shouldn't highlight text and scroll viewport on touch devices when dragging ([0f670c4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0f670c4))
* **@clayui/css:** SVG Icons add `check-small` ([b88dbdb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b88dbdb))
* **@clayui/css:** SVG Icons add `theme` ([93f6efe](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/93f6efe))
* **@clayui/drop-down:** create DropDownWithDrilldown high-level component ([6b92a80](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6b92a80))


### Reverts

* **@clayui/css:** Atlas Alerts change `.alert .close` font-size to 12px ([862609a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/862609a))





# [3.16.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.15.0...@clayui/css@3.16.0) (2020-07-28)


### Bug Fixes

* **@clayui.css:** Mixins `clay-range-input-variant` hides `.clay-range-thumb` and styles thumb pseudo elements so we can offer a non JS based input[type="range"] ([6b5fa34](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6b5fa34))
* **@clayui/css:** Atlas Alerts adjust spacing to match Lexicon specs ([13905b7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/13905b7))
* **@clayui/css:** Atlas Alerts change `.alert .close` font-size to 12px ([486603a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/486603a))
* **@clayui/css:** Attribute `hidden` should hide elements ([a9e1e56](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a9e1e56))
* **@clayui/css:** Clay Color adds highlight for `.active` state ([1e2c2ad](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1e2c2ad))
* **@clayui/css:** Clay Color changes swatch size to 20px from 18px for small version ([acd3b89](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/acd3b89))
* **@clayui/css:** Clay Range adds `.clay-range-progress-none` modifier to hide progress indicator for non JS input range and update focus shadows due to focus artifact in Safari ([45b946b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/45b946b))
* **@clayui/css:** Form Validation raise specificity of `.has-{danger|warning|success} .input-group-inset-item` by a class. It is now `.has-{danger|warning|success} .input-group .input-group-inset-item`. ([9e906bd](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9e906bd))
* **@clayui/css:** Sorts (alphabetically) imports that are delimited by two new lines ([4548dad](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4548dad)), closes [#3529](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3529)
* **@clayui/css:** SVG Icons update `check-circle-full` path normalize thickness and size to other check icons ([6435f04](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6435f04))
* **@clayui/css:** SVG Icons update `check-circle` path normalize thickness and size to other check icons ([0e7d50d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0e7d50d))
* **@clayui/css:** SVG Icons update `check-square` path normalize thickness and size to other check icons ([3da4644](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3da4644))
* **@clayui/css:** SVG Icons update `check` path normalize thickness and size to other check icons ([fba13b6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/fba13b6))
* **@clayui/css:** Update global functions ([146bd4f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/146bd4f))


### Features

* **@clayui/css:** Add new spacers ([c6deb4e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c6deb4e))
* **@clayui/css:** Clay Color should support `.input-group-sm` and `.form-group-sm`. ([309a6c9](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/309a6c9))
* **@clayui/css:** Drilldown should work with Dropdown Menu, have dual click areas inside `dropdown-item`, and have `min-height` ([b7686a0](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b7686a0))
* **@clayui/css:** Dropdowns adds `.dropdown-item-indicator-start`, `.dropdown-item-indicator-text-start`, `.dropdown-item-indicator-end`, `.dropdown-item-indicator-text-end` to allow for separate actions inside a `dropdown-item` ([e76aa8e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e76aa8e))
* **@clayui/css:** Input Groups `.input-group-sm` and `.form-group-sm` should change the size of `.clay-color` ([6e5b4d1](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6e5b4d1))
* **@clayui/css:** SVG Icons add `closed-book` ([c461d19](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c461d19))





# [3.15.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.14.0...@clayui/css@3.15.0) (2020-07-14)


### Bug Fixes

* **@clayui/css:** Adds leading whitespace for License texts ([5566010](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5566010))
* **@clayui/css:** Cards change `.card-page-item-asset` `min-width: 193px` so 4 cards can fit in `sheet-lg` at maximum size ([95dca1c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/95dca1c))
* **@clayui/css:** Copy licenses from root directory into clay-css/LICENSES ([0d1ef58](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0d1ef58))
* **@clayui/css:** Input Group fix border radius issues due to reducing Bootstrap's selector specificity ([7e399ea](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7e399ea))
* **@clayui/css:** Modal max-width sizes should be declared before `.modal-full-screen` and add back `flex-grow: 1` to `.modal-body` ([b2722ea](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b2722ea))
* **@clayui/css:** Reboot makes `use[href]` inherit parent styles ([2504c62](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2504c62))
* **@clayui/css:** Reboot removes focus outline on negative `tabindex` elements. Chrome adds outline on focus to any element with a `tabindex` attribute. ([a5deefd](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a5deefd))
* **@clayui/css:** SVG Icons updates `picture`, reduce the anchors of the sun and the compound path can be placed tighten to viewbox ([5b83c6e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5b83c6e))
* **@clayui/css:** Update svg4everybody to 2.1.9 ([c4eb007](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c4eb007))
* **clay-css:** copy LICENSES to lib before publish ([e1122b3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e1122b3))
* **clay-css:** run 'gulp version' before commit ([6b7e181](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6b7e181))


### Features

* **@clayui/css:** SVG Icons adds `copy-rtl` ([bcc3f95](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bcc3f95))
* **@clayui/css:** SVG Icons adds `home-full` and simplifies `home` design ([d3b948e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d3b948e))
* **@clayui/css:** SVG Icons adds `low-vision` ([df440f7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/df440f7))
* **@clayui/css:** SVG Icons adds `paste-plaintext-rtl` ([ced1018](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ced1018)), closes [#3450](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3450)
* **@clayui/css:** SVG Icons adds `paste-plaintext` ([5bf397c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5bf397c))
* **@clayui/css:** SVG Icons adds `paste-word-rtl.svg` ([8d92075](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8d92075)), closes [#3448](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3448)





# [3.14.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.13.0...@clayui/css@3.14.0) (2020-07-07)


### Bug Fixes

* **@clayui/css:** Badges Variables forgot to remove some commented code ([8c7c71f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8c7c71f))
* **@clayui/css:** Completed absorbtion of Bootstrap 4 components, moves all imports from _bs4.scss to _components.scss ([9c21b33](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9c21b33))
* **@clayui/css:** Import `components/_reboot.scss` in `_bs4.scss` until we absorb all Bootstrap 4 components due to specificity issues ([58055cc](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/58055cc))
* **@clayui/css:** Mixins `clay-form-control-variant` and `clay-select-variant` should respect old keys `bg`, `bg-clip`, `bg-image`, `bg-position`, `bg-repeat`, `bg-size` ([3a1f230](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3a1f230))
* **@clayui/css:** Reboot combine `body` and `a` styles from Type ([c5c84c7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c5c84c7))
* **@clayui/css:** Reboot don't need `display: block` for `article`, `aside`, `figcaption`, `figure`, `footer`, `header`, `hgroup`, `nav`, `section` ([ecb2718](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ecb2718))
* **@clayui/css:** Reboot we don't need to set `font-family`, `line-height` on the `html` element already set on `body` ([bc95fb3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/bc95fb3))
* **@clayui/css:** Remove unused import `[@import](https://github.com/import) 'bootstrap/breadcrumb'` ([39fc48f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/39fc48f))
* **@clayui/css:** Remove unused import `[@import](https://github.com/import) 'bootstrap/nav'` ([37e2fd2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/37e2fd2))
* **@clayui/css:** SVG Icons `link` and `chain-broken` reduce anchor points ([d80adab](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d80adab))
* **@clayui/css:** SVG Icons adds license to `button`, `container`, `slideshow`, `tabs`, `tap-ahead`, `text-l` ([34a7e30](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/34a7e30))
* **@clayui/css:** SVG Icons fix xmlns declaration for `bold`, `cards2`, `decimal`. Icons aren't visible when converted to data uri and used in `background-image` ([e79e68d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e79e68d))
* **@clayui/css:** SVG Icons swap `indent-less` and `indent-more`. The arrows are pointing the wrong way ([6b4f1cf](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6b4f1cf))
* **@clayui/css:** SVG Icons update `expand` reduce anchor points ([55a0561](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/55a0561))
* **@clayui/css:** SVG Icons update `flag-empty` and `flag-full` reduce anchor points ([d3d6c3c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d3d6c3c))
* **@clayui/css:** SVG Icons updates `align-image-center`, `align-image-left`, and `align-image-right` with rounded borders ([b55c8d1](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b55c8d1))
* **@clayui/css:** SVG Icons updates `bold`, `italic`, and `underline` to be smaller ([5db734f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5db734f))
* **@clayui/css:** SVG Icons updates `subscript` and `superscript` icons ([36604f5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/36604f5))
* **@clayui/css:** SVG Icons updates `table2` adjust anchor points ([6afe9c9](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6afe9c9))


### Features

* **@clayui/css:** Absorb Bootstrap 4 _buttons.scss into Clay CSS _buttons.scss ([d2731ba](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d2731ba))
* **@clayui/css:** Absorb Bootstrap 4 _code.scss ([505938d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/505938d))
* **@clayui/css:** Absorb Bootstrap 4 _custom-forms.scss into Clay CSS _custom-forms.scss ([52cd5f8](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/52cd5f8))
* **@clayui/css:** Absorb Bootstrap 4 _dropdown.scss into Clay CSS _dropdown-menu.scss ([a486bc8](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a486bc8))
* **@clayui/css:** Absorb Bootstrap 4 _forms.scss into Clay CSS _forms.scss and _form-validation.scss ([e7e854f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e7e854f))
* **@clayui/css:** Absorb Bootstrap 4 _grid.scss into Clay CSS ([48143b2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/48143b2))
* **@clayui/css:** Absorb Bootstrap 4 _images.scss ([6e6ea9f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6e6ea9f))
* **@clayui/css:** Absorb Bootstrap 4 _input-group.scss into Clay CSS _input-groups.scss ([acba14c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/acba14c))
* **@clayui/css:** Absorb Bootstrap 4 _media.scss into Clay CSS _media.scss ([a685d6b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a685d6b))
* **@clayui/css:** Absorb Bootstrap 4 _nav.scss into Clay CSS _nav.scss ([e123acb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e123acb))
* **@clayui/css:** Absorb Bootstrap 4 _reboot.scss into Clay CSS ([89e5adb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/89e5adb))
* **@clayui/css:** Absorb Bootstrap 4 _transitions.scss ([469659b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/469659b))
* **@clayui/css:** Absorb Bootstrap 4 _type.scss into Clay CSS ([e6e4012](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e6e4012))
* **@clayui/css:** Absorb Bootstrap 4 Tables ([22e1f92](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/22e1f92))
* **@clayui/css:** Absorb Bootstrap 4's _root.scss into Clay CSS ([dd82ded](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/dd82ded))
* **@clayui/css:** Absorb Bootstrap's _alert.scss into Clay CSS _alerts.scss ([0869797](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0869797))
* **@clayui/css:** Absorb Bootstrap's _badge.scss into Clay CSS _badges.scss ([cfe46c7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cfe46c7))
* **@clayui/css:** Absorb Bootstrap's _breadcrumb.scss into Clay CSS _breadcrumbs.scss ([9d30cab](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9d30cab))
* **@clayui/css:** Absorb Bootstrap's _btn-group.scss into Clay CSS _btn-group.scss ([e802d1f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e802d1f))
* **@clayui/css:** Absorb Bootstrap's _card.scss into Clay CSS _cards.scss ([35620d3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/35620d3))
* **@clayui/css:** Absorb Bootstrap's _carousel.scss into Clay CSS _carousel.scss ([9e468b5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9e468b5))
* **@clayui/css:** Absorb Bootstrap's _close.scss into Clay CSS _utilities.scss ([c3026d5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c3026d5))
* **@clayui/css:** Absorb Bootstrap's _jumbotron.scss into Clay CSS ([dd38b93](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/dd38b93))
* **@clayui/css:** Absorb Bootstrap's _list-group.scss into Clay CSS _list-group.scss ([9f4a8b6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9f4a8b6))
* **@clayui/css:** Absorb Bootstrap's _modal.scss into Clay CSS _modals.scss ([c2a4de8](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/c2a4de8))
* **@clayui/css:** Absorb Bootstrap's _navbar.scss into Clay CSS _navbar.scss ([5b1fb4d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5b1fb4d))
* **@clayui/css:** Absorb Bootstrap's _pagination.scss into Clay CSS _pagination.scss ([e6eb67c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e6eb67c))
* **@clayui/css:** Absorb Bootstrap's _popover.scss into Clay CSS _popovers.scss ([8d43344](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8d43344))
* **@clayui/css:** Absorb Bootstrap's _print.scss into Clay CSS _print.scss ([5eb2f76](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5eb2f76))
* **@clayui/css:** Absorb Bootstrap's _progress.scss into Clay CSS _progress-bars.scss ([cad6f69](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cad6f69))
* **@clayui/css:** Absorb Bootstrap's _spinners.scss into Clay CSS _spinners.scss ([a00ec52](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a00ec52))
* **@clayui/css:** Absorb Bootstrap's _toasts.scss into Clay CSS _toasts.scss ([e484351](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e484351))
* **@clayui/css:** Absorb Bootstrap's _tooltip.scss into Clay CSS _tooltip.scss ([48696cd](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/48696cd))
* **@clayui/css:** Absorb Bootstrap's _utilities.scss into Clay CSS _utilities-functional-important.scss ([b1b7adb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b1b7adb))
* **@clayui/css:** Button adds placeholders `%clay-btn-monospaced-lg`, `%clay-btn-monospaced-sm` so we can extend with Sass `[@extend](https://github.com/extend)` without unnecessary selectors ([b704e7f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b704e7f))
* **@clayui/css:** Global Functions adds ` clay-enable-gradients`, `clay-enable-rounded`, `clay-enable-shadows`, `clay-enable-transitions` so we can support these Bootstrap settings in variables ([ac66e1f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ac66e1f))
* **@clayui/css:** Global Variables undeprecate `$clay-unset` and add alias `$c-unset` for unsetting values so they don't get output in the final css file ([e0e8b98](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e0e8b98))
* **@clayui/css:** Mixins `clay-button-variant` reduce selector specificity of `:not([disabled]):not(.disabled):active` to `:active` ([f16970f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f16970f))
* **@clayui/css:** Mixins `clay-close` removes Bootstrap 4.1.2 selector overwrites. We don't need them since we are removing Bootstrap 4 dependency. ([8318d9f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8318d9f))
* **@clayui/css:** Mixins `clay-css` check for keyword `clay-unset` and output `null` value if it is passed in ([fb5427f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/fb5427f))
* **@clayui/css:** Mixins `clay-link` `disabled` should set `outline: 0` and `box-shadow: none` by default so disabled anchors don't receive focus outline ([8b53b60](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8b53b60))
* **@clayui/css:** SVG Icons adds `align-image-full-width` ([26db99e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/26db99e))
* **@clayui/css:** SVG Icons adds `background-color` ([7ae3634](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7ae3634))
* **@clayui/css:** SVG Icons adds `button`, `tabs`, `slideshow`, `tap-ahead` ([5fc3af6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5fc3af6))
* **@clayui/css:** SVG Icons adds `container` ([49517bc](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/49517bc)), closes [#3343](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3343)
* **@clayui/css:** SVG Icons adds `emoji` ([8345faf](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/8345faf))
* **@clayui/css:** SVG Icons adds `flag-empty-rtl` and `flag-full-rtl` ([f5fa452](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f5fa452))
* **@clayui/css:** SVG Icons adds `list-ol-rtl` and updates `list-ol` ([007d5c8](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/007d5c8))
* **@clayui/css:** SVG Icons adds `list-ul-rtl` and updates `list-ul` reduces anchor points ([654cbc3](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/654cbc3))
* **@clayui/css:** SVG Icons adds `paste-word` ([9033e36](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9033e36))
* **@clayui/css:** SVG Icons adds `select-all` ([1db4f98](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1db4f98))
* **@clayui/css:** SVG Icons adds `special-character` ([18d5172](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/18d5172))
* **@clayui/css:** SVG Icons adds `text-color` ([0191409](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0191409))
* **@clayui/css:** SVG Icons changes `paste` to something more relevant and moves original `paste` to `copy` ([cdd96ab](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cdd96ab))
* **@clayui/css:** SVG Icons rename `text.svg` to `text-l.svg`, make `text.svg` icon larger ([31a1ad4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/31a1ad4))
* **@clayui/css:** SVG Icons updates `code` ([745911b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/745911b)), closes [#3344](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3344)


### Reverts

* **@clayui/css:** Mixins `clay-link` `disabled` should set `outline: 0` and `box-shadow: none` by default so disabled anchors don't receive focus outline ([1c3ace2](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1c3ace2))





# [3.13.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.12.0...@clayui/css@3.13.0) (2020-06-18)


### Features

* **@clayui/css:** Move components `type`, `icons`, `aspect-ratio`, and `buttons` earlier in the import chain so they are easier to overwrite ([6f69b82](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6f69b82)), closes [#3191](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3191)





# [3.12.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.11.0...@clayui/css@3.12.0) (2020-06-04)


### Bug Fixes

* **clay-css:** re-add file that was accidentally deleted ([ebc4d75](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ebc4d75))


### Features

* **@clayui/css:** Update search icon ([7e5bd9a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7e5bd9a))
* **@clayui/css:** Update search icon - trim the icon code ([b74e028](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b74e028)), closes [#3293](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3293)





# [3.11.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.10.0...@clayui/css@3.11.0) (2020-05-21)


### Bug Fixes

* **@clayui/card:** check for values before rendering container elements ([a732a8e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a732a8e))
* **@clayui/css:** `_global-functions` should be accessible to Portal's `_clay_variables.scss` without having to import it manually ([e76d56a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/e76d56a)), closes [#3193](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3193)
* **@clayui/css:** Buttons unset Bootstrap's `pointer-events: none;` on `a.btn.disabled` and set it on `.btn.disabled:active` ([63cfa7d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/63cfa7d)), closes [#3096](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3096)
* **@clayui/css:** Cards `card-interactive-primary` Chrome 81/83 hover transition artifact. Use any `transition-timing-function` other than `ease-in` or `ease-in-out` ([d7aa102](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/d7aa102)), closes [#3233](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3233)
* **@clayui/css:** Forms `input[type="range"].form-control` shadow in Chrome 81 caused by https://github.com/liferay/clay/issues/1179 and Chrome update ([101d566](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/101d566)), closes [#3249](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3249)
* **@clayui/css:** Links `link-outline` and `component-action` `.disabled` should have `cursor: not-allowed` and `.disabled:active` should have `pointer-events: none;` ([0f132a5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/0f132a5)), closes [#3096](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3096)
* **@clayui/css:** Mixin `clay-autofit-float` undeprecate `.autofit-col-end` ([9da6aa8](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9da6aa8)), closes [#3230](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3230)
* **@clayui/css:** Mixin `clay-close` deprecated keys should win to preserve backward compatibility ([3e3407e](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3e3407e)), closes [#3164](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3164)
* **@clayui/css:** Mixin `clay-sticker-variant` deprecated keys should win to preserve backward compatibility ([281696a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/281696a)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-css` should output the `content` CSS property without having to double quote ([dbc5260](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/dbc5260)), closes [#3233](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3233)
* **@clayui/css:** Prettier should format `_global-functions.scss` but ignore autogenerated svgs ([a796cf4](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a796cf4)), closes [#3250](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3250)
* **@clayui/css:** SVG Icons `thumbs-up` and `thumbs-down` reduce anchor points ([a03bfef](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a03bfef)), closes [#3203](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3203)
* **@clayui/css:** SVG Icons deprecate `desktop` and add `display-content` ([66c5ef7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/66c5ef7)), closes [#3200](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3200)
* **@clayui/css:** Utilities `.close` should have `cursor: not-allowed` and `.disabled:active` should have `pointer-events: none` ([92100aa](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/92100aa)), closes [#3096](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3096)


### Features

* **@clayui/css:** Create file `_bs4.scss` that imports Bootstrap 4 files separately so we can remove imports as we absorb BS4 components into Clay CSS ([f59c90c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f59c90c)), closes [#3192](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3192)
* **@clayui/css:** Mixin `clay-sticker-variant` should use `clay-css` mixin to generate properties ([ae2648d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/ae2648d)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** SVG Icons adds `angle-down-small`, `angle-up-small`, `angle-left-small`, and `angle-right-small` ([4e55feb](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4e55feb)), closes [#3156](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3156)
* **@clayui/css:** SVG Icons adds `thumbs-up-full` and `thumbs-down-full` ([55086ae](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/55086ae)), closes [#3208](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3208)
* **@clayui/css:** SVG Icons adds icon `display` ([2d0dac9](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2d0dac9)), closes [#3200](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3200)





# [3.10.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.9.0...@clayui/css@3.10.0) (2020-04-24)


### Bug Fixes

* **@clayui/css:** Button Group Vertical `.btn-monospaced` shouldn't shrink inside `autofit-col` ([5fcc7b5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5fcc7b5)), closes [#3063](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3063)
* **@clayui/css:** Forms `.form-control-sm` and `.form-control-lg` should have correct left and right padding ([21688d6](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/21688d6)), closes [#3110](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3110)
* **@clayui/css:** Forms small form elements should have 4px border-radius ([686c662](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/686c662)), closes [#3105](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3105)
* **@clayui/css:** Mixin `clay-autofit-row` deprecated keys should win to preserve backward compatibility ([9e4d297](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9e4d297)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-button-variant` deprecated keys should win to preserve backward compatibility ([411901c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/411901c)), closes [#3164](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3164)
* **@clayui/css:** Mixin `clay-modal-variant` deprecated keys should win to preserve backward compatibility ([f38eeaa](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f38eeaa)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-panel-variant` deprecated keys should win to preserve backward compatibility ([63ae6ee](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/63ae6ee)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-tbar-variant` deprecated keys should win to preserve backward compatibility ([cfc3727](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cfc3727)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-after-highlight-variant` deprecated keys should win to preserve backward compatibility ([7b519b7](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/7b519b7)), closes [#3164](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3164)
* **@clayui/css:** Mixins `clay-container` deprecated keys should win to preserve backward compatibility ([4b07121](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/4b07121)), closes [#3164](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3164)
* **@clayui/css:** Mixins `clay-dropdown-item-variant` and `clay-dropdown-menu-variant` deprecated keys should win to preserve backward compatibility ([815354a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/815354a)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-input-group-stacked` and `clay-input-group-text-variant` deprecated keys should win to preserve backward compatibility ([6da73e1](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/6da73e1)), closes [#3164](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3164)
* **@clayui/css:** Mixins `clay-link` and `clay-text-typography` deprecated keys should win to preserve backward compatibility ([5c9a20b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5c9a20b)), closes [#3164](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3164)
* **@clayui/css:** SVG Icons update cog.svg to new style for better contrast ([adc6580](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/adc6580)), closes [#3085](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3085)
* **@clayui/css:** SVG Icons updates `angle-down`, `angle-left`, `angle-right`, and `angle-up` by reducing anchor points in the SVG ([b040734](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b040734)), closes [#3131](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3131)


### Features

* **@clayui/css:** Mixin `clay-after-highlight-variant` use `clay-css` mixin to generate properties ([480b85b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/480b85b)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-autofit-row` should use `clay-css` mixin to generate properties ([1c12aac](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/1c12aac)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-close` should match `clay-link` to preserve compatibility between the two ([f44e459](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/f44e459)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-dropdown-item-variant` use `clay-css` mixin to generate properties ([9f63d87](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/9f63d87)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-dropdown-menu-variant` use `clay-css` mixin to generate properties ([2e66512](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/2e66512)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-input-group-text-variant` use `clay-css` mixin to generate properties ([08c0dd8](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/08c0dd8)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-modal-variant` should use `clay-css` mixin to generate properties ([15c4f3f](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/15c4f3f)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixin `clay-panel-variant` should use `clay-css` mixin to generate properties ([98fedd5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/98fedd5)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-button-variant` use `clay-css` mixin to generate properties ([3fcabd5](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/3fcabd5)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-close` use `clay-css` mixin to generate properties ([83ea47a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/83ea47a)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-container` use `clay-css` mixin to generate properties ([31b82d8](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/31b82d8)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-link` use `clay-css` mixin to generate properties ([32b2299](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/32b2299)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-row` should use `clay-css` mixin because it provides more options ([b15a98a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/b15a98a)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins `clay-text-typography` use `clay-css` mixin to generate properties ([cdd429c](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/cdd429c)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** Mixins adds `clay-table-drag-variant` with options `cell`, `c-drag`, `c-dragging-before`, `c-dragging-after`, `c-droppable-before`, `c-droppable-after` ([81622df](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/81622df)), closes [#2934](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2934)
* **@clayui/css:** Mixins map deprecated `clay-button-size` to `clay-button-variant` ([a98b49b](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/a98b49b)), closes [#3075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3075)
* **@clayui/css:** SVG Icons adds disk ([dbd2c5d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/dbd2c5d)), closes [#3080](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3080)
* **@clayui/css:** SVG Icons adds search-plus ([5859d71](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/5859d71)), closes [#3091](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3091)
* **@clayui/css:** SVG Icons update `disk`. we will change the corners to straight so that it matches the rest of the icons ([11e614d](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/11e614d)), closes [#3080](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3080)
* **@clayui/css:** Tables adds `.table-drag`, `.table-dragging`, `.table-clone` base styles for drag and drop table columns ([fff748a](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/fff748a)), closes [#2934](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2934)
* **clayui.com:** source md/mdx files from package directories ([fc6e798](https://github.com/liferay/clay/tree/master/packages/clay-css/commit/fc6e798))





# [3.9.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.8.0...@clayui/css@3.9.0) (2020-03-26)


### Bug Fixes

* **@clayui/css:** Atlas Custom Checkbox and Radio should be 16px x 16px ([7a16efa](https://github.com/liferay/clay/commit/7a16efa)), closes [#3026](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3026)
* **@clayui/css:** Forms `input[type="range"]` focus border artifact in Chrome and remove padding ([37c86d9](https://github.com/liferay/clay/commit/37c86d9)), closes [#1179](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/1179)
* **@clayui/css:** Mixins `clay-css` only loop through properties that are passed via Sass map instead of listing everything ([b2f5496](https://github.com/liferay/clay/commit/b2f5496)), closes [#2990](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2990)
* **@clayui/css:** override specific styles for rtl support ([dce5d81](https://github.com/liferay/clay/commit/dce5d81))


### Features

* **@clayui/css:** SVG Icons add Malaysian flag ([37e26c6](https://github.com/liferay/clay/commit/37e26c6)), closes [#3017](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/3017)


### Reverts

* **@clayui/css:** override specific styles for rtl support ([5125a62](https://github.com/liferay/clay/commit/5125a62))





# [3.8.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.7.0...@clayui/css@3.8.0) (2020-03-12)


### Bug Fixes

* **@clayui/css:** SVG Icons update the flag of Slovakia ([91d5cd0](https://github.com/liferay/clay/commit/91d5cd0)), closes [#2996](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2996)
* **clay-css:** Aspect Ratio `.aspect-ratio-item` should be aligned to the left when parent container has `text-align: center` ([bf2f992](https://github.com/liferay/clay/commit/bf2f992)), closes [#833](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/833)
* **clay-css:** Clay Base Form Select Element icon should display. Bootstrap changed the way they handle svg's as background-images at https://github.com/twbs/bootstrap/commit/c26e68427c06477cacdc4a75d92e5bd22476b4bb ([27241af](https://github.com/liferay/clay/commit/27241af)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Mixins `clay-button-variant` deprecate `hover-z-index`, `focus-z-index`, `disabled-z-index`, `active-z-index` and use the Sass maps instead ([96b650b](https://github.com/liferay/clay/commit/96b650b)), closes [#2903](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2903)
* **clay-css:** Mixins `clay-css` background-attachment should accept key `bg-attachment` or `background-attachment` ([b07e570](https://github.com/liferay/clay/commit/b07e570)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Mixins `clay-css` background-color should accept key `bg` or `background-color` ([b55e7bc](https://github.com/liferay/clay/commit/b55e7bc)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Removes Bootstrap 4's gnarly `select.form-control:not([multiple]):not([size])` selector overwrite. This selector was removed in Bootstrap 4.1.3. See https://github.com/twbs/bootstrap/commit/f426a67394010b5cc0235c845b744e2711f81e59 ([a209ac6](https://github.com/liferay/clay/commit/a209ac6)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** SVG Icons modify `tablet-landscape` and `tablet-portrait` they were off by a couple pixels ([9c3e266](https://github.com/liferay/clay/commit/9c3e266)), closes [#2970](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2970)


### Features

* **@clayui/css:** Labels adds `label-inverse-*` to invert label colors ([340ce27](https://github.com/liferay/clay/commit/340ce27)), closes [#2975](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2975)
* **@clayui/css:** Mixins `clay-label-variant` use `clay-css` mixin in each selector instead of individually declaring properties ([d456db6](https://github.com/liferay/clay/commit/d456db6)), closes [#2975](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2975)
* **clay-css:** Adds Clay Dual Listbox (Old Input Move Boxes) component ([18b3905](https://github.com/liferay/clay/commit/18b3905)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Adds Clay Reorder component. A `select[multiple]` element with buttons that rearrange `option`s inside `select[multiple]` ([7ba7584](https://github.com/liferay/clay/commit/7ba7584)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Adds Empty State component ([a159135](https://github.com/liferay/clay/commit/a159135)), closes [#833](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/833)
* **clay-css:** Adds images for Empty State in `src/images/images` ([df33ac1](https://github.com/liferay/clay/commit/df33ac1)), closes [#833](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/833)
* **clay-css:** Form Select Element use `clay-select-variant` mixin to generate styles and consolidate repeated selectors ([4a381a0](https://github.com/liferay/clay/commit/4a381a0)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Global Variables add `$component-focus-inset-box-shadow` for reusable focus inset box-shadows across components ([5008674](https://github.com/liferay/clay/commit/5008674)), closes [#2954](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2954)
* **clay-css:** Mixins `clay-button-variant` use `clay-css` mixin for applying `hover`, `focus`, `disabled`, `active`, `active-class-after`, `active-focus`. ([22a6be1](https://github.com/liferay/clay/commit/22a6be1)), closes [#2903](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2903)
* **clay-css:** Mixins `clay-css` adds option to pass in `scrollbar-width` for future proofing this property. It's available in Firefox 64+ ([4fbe1df](https://github.com/liferay/clay/commit/4fbe1df)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Mixins `clay-form-control-variant` use `clay-css` mixin in each selector instead of individually declaring properties ([f4ce3e1](https://github.com/liferay/clay/commit/f4ce3e1)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Mixins `clay-select-variant` use `clay-css` mixin in each selector instead of individually declaring properties ([485afb4](https://github.com/liferay/clay/commit/485afb4)), closes [#2896](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2896)
* **clay-css:** Mixins `clay-sidebar-variant` add option to configure `.sidebar`, `.sidebar-panel`, `.sidebar-header`, `.sidebar-body`, `.sidebar-footer`, `.nav-nested`, `.sidebar-list-group .list-group-item`, `.sidebar-list-group .sticker`, `.sidebar-list-group .sticker-secondary` via Sass maps and `clay-css` mixin ([994c7bd](https://github.com/liferay/clay/commit/994c7bd)), closes [#2903](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2903)
* **clay-css:** Mixins `clay-tbar-variant` use `clay-css` mixin for applying base `tbar`, `strong`, `.tbar-item`, `.tbar-section` styles ([a25959b](https://github.com/liferay/clay/commit/a25959b)), closes [#2903](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2903)
* **clay-css:** Mixins adds `clay-slideout-variant` with options to configure `c-slideout-shown`, `c-slideout-tbar-shown`, `c-slideout-tbar-shown-sidebar`, `sidebar`, `sidebar-c-slideout-show`, `sidebar-c-slideout-transition`, `tbar-stacked`, `tbar-stacked-c-slideout-show`, `tbar-stacked-c-slideout-transition` ([95ae58e](https://github.com/liferay/clay/commit/95ae58e)), closes [#2903](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2903)
* **clay-css:** Sidebar adds `.sidebar-dark` variant and Sass map `$sidebar-dark` which uses `clay-sidebar-variant` mixin ([df14c79](https://github.com/liferay/clay/commit/df14c79)), closes [#2903](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2903)
* **clay-css:** Slideout adds new component `.c-slideout`, `.c-slideout-transition-in`, `.c-slideout-transition-out`, `.c-slideout-fixed`, `.c-slideout-absolute`, `.c-slideout-start`, `.c-slideout-end` ([50491e2](https://github.com/liferay/clay/commit/50491e2)), closes [#2903](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2903)
* **clay-css:** Tbar adds `.tbar-stacked` for Lexicon's Vertical Bar Pattern and variants `.tbar-light`, `.tbar-dark-l2`, .tbar-dark-d1` ([7bd2ac6](https://github.com/liferay/clay/commit/7bd2ac6)), closes [#2903](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2903)
* **clay-css:** Utilities adds `.c-focus-inset` for inner focus styles ([33ca179](https://github.com/liferay/clay/commit/33ca179)), closes [#2954](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2954)





# 3.7.0 (2020-02-28)


### Bug Fixes

* **clay css:** Adds `clay-time` component (Time Picker) ([74b2326](https://github.com/liferay/clay/commit/74b2326)), closes [#1424](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/1424)
* **clay css:** Forms add `.disabled` to `.form-control` to style elements that use `div` ([5d36450](https://github.com/liferay/clay/commit/5d36450))
* **clay css:** Management Bar `.navbar-text` should break to new line when there is not enough space ([40ba156](https://github.com/liferay/clay/commit/40ba156)), closes [#2085](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2085)
* **clay css:** Mixin `clay-form-control-variant` add `align-items`, `flex-wrap`, `justify-content`, `max-width`, `min-height`, `text-transform` ([0b5cb01](https://github.com/liferay/clay/commit/0b5cb01))
* **clay-css:** Add border-spacing, border-collapse not working in IE ([9d12922](https://github.com/liferay/clay/commit/9d12922))
* **clay-css:** Adds `!optional` flag to `[@extend](https://github.com/extend)` for components that are extending selectors/placeholders outside of their respective component file ([403a0c2](https://github.com/liferay/clay/commit/403a0c2)), closes [#2881](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2881)
* **clay-css:** Atlas Custom Control disabled label color should be the same as `$input-label-disabled-color` ([a160132](https://github.com/liferay/clay/commit/a160132)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** Atlas Dropdown change `.dropdown-header` and `.dropdown-subheader` color to [#272833](https://github.com/liferay/clay/commit/f901ce8)), closes [#2812](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2812)
* **clay-css:** Atlas Form Validation `.form-feedback-item` and `.form-text` should be semi-bold ([798be68](https://github.com/liferay/clay/commit/798be68)), closes [#2328](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2328)
* **clay-css:** Atlas Globals tweak `$success`, `$success-d1`, `$success-l1`, `$danger-d` hex values to match Lexicon exactly ([5b50860](https://github.com/liferay/clay/commit/5b50860)), closes [#2820](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2820)
* **clay-css:** Atlas Nav Tabs and Nav Underline should use `$font-weight-semi-bold`. Nav Underline should be 32px tall and underline color should be `$primary-l1` ([6cdffef](https://github.com/liferay/clay/commit/6cdffef)), closes [#2388](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2388)
* **clay-css:** Badges `.badge > .c-inner` only set margins and overwrite inherited max-width property ([52ee10f](https://github.com/liferay/clay/commit/52ee10f)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Button `.btn-unstyled` should reset sizes for `.btn-sm` and `.btn-lg` ([896c21a](https://github.com/liferay/clay/commit/896c21a)), closes [#2475](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2475)
* **clay-css:** Buttons use `math-sign` function for calculating negative margins on `.btn .c-inner` to prevent invalid CSS output like `margin: - -;` ([1ca34e4](https://github.com/liferay/clay/commit/1ca34e4)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Custom Control add Sass maps `$custom-control-label`, `$custom-control-label-disabled`, `$custom-control-label-text` and map deprecated `$custom-control-description-*` to them so our namespace matches Bootstrap's. It was renamed toward end of Bootstrap beta in 6a54b4a ([e41dcf5](https://github.com/liferay/clay/commit/e41dcf5)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Deprecate `.sheet-lg` and `$sheet-lg-max-width` in favor of `.container .sheet` pattern ([2e1e82c](https://github.com/liferay/clay/commit/2e1e82c)), closes [#2655](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2655)
* **clay-css:** Dropdown Item `.disabled` should have `cursor: not-allowed` and move `pointer-events: none` to `.disabled:active` ([28cb857](https://github.com/liferay/clay/commit/28cb857)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** Form Validation Feedback space between icon and text should be 4px ([e1d0e09](https://github.com/liferay/clay/commit/e1d0e09)), closes [#2075](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2075)
* **clay-css:** Globals added `_globals-z-index.scss` to list z-index variables used in Bootstrap/ClayCSS ([e12ee48](https://github.com/liferay/clay/commit/e12ee48)), closes [#2339](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2339)
* **clay-css:** List Group double borders in `list-group-item-flex` caused by Bootstrap 4.4.1 22f6b37 ([1221279](https://github.com/liferay/clay/commit/1221279)), closes [#2785](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2785)
* **clay-css:** Mixin `clay-input-group-stacked` should use child combinator styles only apply direct descendants ([0f3d82e](https://github.com/liferay/clay/commit/0f3d82e)), closes [#2384](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2384)
* **clay-css:** Mixins `clay-button-size`, `clay-button-variant`, `clay-close`, `clay-label-size`, `clay-link`, `clay-menubar-vertical-expand`, `clay-navbar-size`, `clay-panel-variant`, `clay-tbar-variant` should only set margins for `c-inner` ([61ac029](https://github.com/liferay/clay/commit/61ac029)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-dropdown-item-variant` only set margins and overwrite inherited width property for `c-inner` ([be5d06c](https://github.com/liferay/clay/commit/be5d06c)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Modal Footer use `justify-content: flex-start` instead of Bootstrap's `flex-end` to work around IE11 rendering issues with `modal-item`'s ([2be40c2](https://github.com/liferay/clay/commit/2be40c2)), closes [#2873](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2873)
* **clay-css:** Modals Atlas change widths of `.modal-sm`, `modal`, and `modal-lg` to `320px`, `600px`, `896px` respectively ([3c0c7c9](https://github.com/liferay/clay/commit/3c0c7c9)), closes [#2367](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2367)
* **clay-css:** Nav `.nav-justified` should work with `button` ([fd5e3d0](https://github.com/liferay/clay/commit/fd5e3d0)), closes [#2237](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2237)
* **clay-css:** Navigation Bar and Management Bar focus styles should match across each component ([5d0ecf9](https://github.com/liferay/clay/commit/5d0ecf9)), closes [#2900](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2900)
* **clay-css:** New SVG Icon reset ([4c85071](https://github.com/liferay/clay/commit/4c85071)), closes [#2146](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2146)
* **clay-css:** SVG Icons add deprecation note to `announcement`, `sticky`, `urgent` ([3eaec3a](https://github.com/liferay/clay/commit/3eaec3a))
* broken markdown lists ([d1adc7e](https://github.com/liferay/clay/commit/d1adc7e))
* **clay-css:** SVG Icons deprecate `import-export` and `embed` in favor of `order-arrow` and `code` respectively ([956d668](https://github.com/liferay/clay/commit/956d668)), closes [#2419](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2419)
* **clay-css:** SVG Icons reduce the size by remove inessential attributes and comments ([e3d7120](https://github.com/liferay/clay/commit/e3d7120)), closes [#2309](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2309)
* **clay-css:** SVG Icons renamed `announcement`, `sticky`, and `urgent` to `megaphone-full`, `pin-full`, and `bell-full` respectively ([e89b1f0](https://github.com/liferay/clay/commit/e89b1f0)), closes [#2119](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2119)
* **clay-css:** Table Header (th) should be aligned left by default in Safari ([6a6c9a4](https://github.com/liferay/clay/commit/6a6c9a4)), closes [#2219](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2219)
* **clay-css:** Use `selector-unify` to combine parent selectors with nested element selectors in mixins and components ([cb8e0a2](https://github.com/liferay/clay/commit/cb8e0a2)), closes [#2392](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2392)
* **css:** allow newline characters to display properly for tooltips ([2265d10](https://github.com/liferay/clay/commit/2265d10))


### Features

* **@clayui/css:** add new SVG icons `arrow-end`, `arrow-join`, `arrow-split`, `arrow-start`, `arrow-xor`, `circle`, `diamond` and `square` ([3e69b1e](https://github.com/liferay/clay/commit/3e69b1e))
* **clay-css:** add new change-list-disabled SVG icon ([a02d20c](https://github.com/liferay/clay/commit/a02d20c))
* **clay-css:** Add usable mixins from bourbon under `_vendor-prefixes.scss` ([91feecb](https://github.com/liferay/clay/commit/91feecb))
* **clay-css:** Alert adds `.alert-btn`, `.alert-autofit-row`, `.alert-footer`, and `.alert .btn-group-item` ([5212f50](https://github.com/liferay/clay/commit/5212f50)), closes [#2765](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2765)
* **clay-css:** Aspect Ratio adds `.aspect-ratio-item-top-left` ([6981a23](https://github.com/liferay/clay/commit/6981a23)), closes [#2843](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2843)
* **clay-css:** Atlas change `$indigo` to [#7785](https://github.com/liferay/clay/commit/0be9e04)), closes [#2960](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2960)
* **clay-css:** Atlas Form Validation add styles for readonly input success, error, and warning states ([faf5748](https://github.com/liferay/clay/commit/faf5748)), closes [#2715](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2715)
* **clay-css:** Atlas Forms input readonly should have white background and no focus box shadow ([db77870](https://github.com/liferay/clay/commit/db77870)), closes [#2425](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2425)
* **clay-css:** Atlas Global Variables make `h1` - `h6` font sizes the same as 2.x ([0e0f9a0](https://github.com/liferay/clay/commit/0e0f9a0)), closes [#2864](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2864)
* **clay-css:** Atlas Globals adds `$enable-lexicon-flat-colors` to change base colors to match Lexicon Flat Color palette, set to `false` to revert back to old colors ([69fcdb2](https://github.com/liferay/clay/commit/69fcdb2)), closes [#E83E8](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/E83E8) [#2726](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2726)
* **clay-css:** Badge adds `.c-inner` pattern for `.badge`, `.badge-item`, and `.badge .close` ([01b7aee](https://github.com/liferay/clay/commit/01b7aee)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Buttons adds `.c-inner` pattern for `.btn`, `.btn-unstyled`, `.btn-monospaced`, `.btn-sm`, `.btn-lg` ([d810b02](https://github.com/liferay/clay/commit/d810b02)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Card add support for `.c-inner` ([5303bdf](https://github.com/liferay/clay/commit/5303bdf)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Card adds `.card-type-asset.product-card` ([c6be980](https://github.com/liferay/clay/commit/c6be980)), closes [#2843](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2843)
* **clay-css:** Card adds support for `.card` `.aspect-ratio-item-top-left`, `.aspect-ratio-item-top-center`, `.aspect-ratio-item-top-right`, `.aspect-ratio-item-right-middle`, `.aspect-ratio-item-bottom-right`, `.aspect-ratio-item-bottom-center`, `.aspect-ratio-item-bottom-left` ([930ee92](https://github.com/liferay/clay/commit/930ee92)), closes [#2843](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2843)
* **clay-css:** Clay Range add `clay-range-thumb` slider head overlay to make it easier to grab via js and position tooltip inside of it ([d3dbcbd](https://github.com/liferay/clay/commit/d3dbcbd))
* **clay-css:** Clay Time added focus styles for `.clay-time .form-control-inset` ([5c0c447](https://github.com/liferay/clay/commit/5c0c447)), closes [#2299](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2299)
* **clay-css:** Custom Control added `.custom-control-primary` to help increase visual hierarchy of a `custom-control` ([cc0275d](https://github.com/liferay/clay/commit/cc0275d)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Custom Control adds `$custom-control-description-font-weight` and sets font-weight to normal in Atlas ([3d2af5c](https://github.com/liferay/clay/commit/3d2af5c)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Custom Forms `.custom-control` should have `text-align: left` so text is next to input if parent container has `text-align: center` ([4615041](https://github.com/liferay/clay/commit/4615041)), closes [#2843](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2843)
* **clay-css:** Dropdown add `.c-inner` pattern for `.dropdown-item`, `.dropdown-menu-indicator-start`, and `.dropdown-menu-indicator-end` ([d9c40e6](https://github.com/liferay/clay/commit/d9c40e6)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Dropdown add styles for `.dropdown-item .c-kbd` ([8668050](https://github.com/liferay/clay/commit/8668050)), closes [#2906](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2906)
* **clay-css:** Dropdown Section add specific styles for nested `custom-control`s ([573a860](https://github.com/liferay/clay/commit/573a860)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** enable-c-inner: true by default ([81ea040](https://github.com/liferay/clay/commit/81ea040))
* **clay-css:** Forms Clay Multiselect `.form-control-tag-group` should have Clear All button and be aligned in the middle ([3df613c](https://github.com/liferay/clay/commit/3df613c)), closes [#2335](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2335)
* **clay-css:** Forms support `label` element without `for` attribute. `label` needs the class `.form-control-label` and text must be wrapped in an element with class `.form-control-label-text` ([d0fff7f](https://github.com/liferay/clay/commit/d0fff7f)), closes [#2242](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2242)
* **clay-css:** Global Functions added `clay-max` to return the maximum between two values and also accepts null values ([0852a9e](https://github.com/liferay/clay/commit/0852a9e))
* **clay-css:** Global Functions added `map-deep-merge()` that merges keys and values from deeply nested Sass maps ([1f21cac](https://github.com/liferay/clay/commit/1f21cac)), closes [#2403](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2403)
* **clay-css:** Icons add support for `.c-inner` in `.collapse-icon` ([679fcea](https://github.com/liferay/clay/commit/679fcea)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Input Group adds support for `.c-inner` to `.input-group-inset-item .btn` ([60fc69b](https://github.com/liferay/clay/commit/60fc69b)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Label adds `.c-inner` pattern for `.label`, `.label-lg`, and `.label-item` ([bbde2ec](https://github.com/liferay/clay/commit/bbde2ec)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Links `component-action` add support for `.c-inner`, declare properties from `%link-monospaced` in Sass map `$component-action` and remove `[@extend](https://github.com/extend) %link-monospaced` ([2f84f48](https://github.com/liferay/clay/commit/2f84f48)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Links `link-monospaced` should use `clay-link` mixin, add Sass map `$link-monospaced`, add support for `.c-inner` ([c9b3da3](https://github.com/liferay/clay/commit/c9b3da3)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Links `link-outline` should use `clay-link` mixin, add Sass map `$link-outline`, add support for `.c-inner` ([37e6598](https://github.com/liferay/clay/commit/37e6598)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** List Group `.list-group-item-action` should support `.c-inner` ([6add193](https://github.com/liferay/clay/commit/6add193)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** List Group add `.list-group-sm` modifier to make `.list-group-item` shorter ([edd8c40](https://github.com/liferay/clay/commit/edd8c40)), closes [#2423](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2423)
* **clay-css:** Menubar added `.menubar-vertical-expand-md.menubar-decorated` and `.menubar-vertical-expand-lg.menubar-decorated` ([e46b52c](https://github.com/liferay/clay/commit/e46b52c)), closes [#2822](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2822)
* **clay-css:** Mixin `clay-navbar-size` add `.c-inner` support for `.navbar-toggler`, `.navbar-toggler-link`, `.navbar-brand`, `.nav-btn`, `.nav-btn-monospaced`, `.nav-link`, `.nav-link-monospaced` ([95c8e1c](https://github.com/liferay/clay/commit/95c8e1c)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-button-size`, `clay-button-variant` add support for `.c-inner` and `.lexicon-icon` ([f37f31d](https://github.com/liferay/clay/commit/f37f31d)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-button-size`, `clay-button-variant`, `clay-close`, `clay-dropdown-item-variant`, `clay-label-size`, `clay-link` adds option to pass `$c-inner` through Sass map ([66d3827](https://github.com/liferay/clay/commit/66d3827)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-button-variant` adds configs `z-index`, `hover-z-index`, `focus-z-index`, `disabled-z-index` and `active-z-index` ([9f729d5](https://github.com/liferay/clay/commit/9f729d5)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-close` add `.c-inner` pattern ([8d355c8](https://github.com/liferay/clay/commit/8d355c8)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-dropdown-item-variant` adds options to configure `autofit-row`, `c-kbd-inline`, `hover-c-kbd-inline`, `focus-c-kbd-inline`, `active-c-kbd-inline`, `active-class-c-kbd-inline`, `disabled-c-kbd-inline` ([b2e743d](https://github.com/liferay/clay/commit/b2e743d)), closes [#2906](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2906)
* **clay-css:** Mixins `clay-form-control-variant` add options to configure `$selection-bg`, `$selection-color`, and should also output `.focus` styles ([ec5663c](https://github.com/liferay/clay/commit/ec5663c)), closes [#2299](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2299)
* **clay-css:** Mixins `clay-link` `.c-inner` should use parent's `max-width` ([0fe271d](https://github.com/liferay/clay/commit/0fe271d)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-link` add `.c-inner` pattern ([09c5628](https://github.com/liferay/clay/commit/09c5628)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-link` added position, padding, and disabled-active-pointer-events ([4d78c67](https://github.com/liferay/clay/commit/4d78c67)), closes [#2540](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2540)
* **clay-css:** Mixins `clay-link` adds config `margin`, `max-height`, `min-height`, `min-width` ([516c9e8](https://github.com/liferay/clay/commit/516c9e8)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins `clay-menubar-vertical-expand` adds support for `.menubar-toggler .c-inner` through Sass map `toggler-c-inner` ([cd81488](https://github.com/liferay/clay/commit/cd81488)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Mixins added `clay-autofit-row` for custom `.autofit-row` and `.autofit-col` spacing ([cf3bafa](https://github.com/liferay/clay/commit/cf3bafa)), closes [#2765](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2765)
* **clay-css:** Mixins added `clay-line-clamp` for truncating text based on number of lines ([525f3d1](https://github.com/liferay/clay/commit/525f3d1)), closes [#2058](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2058)
* **clay-css:** Mixins added `clay-range-input-variant` for creating `.clay-range-input` variants ([55e59eb](https://github.com/liferay/clay/commit/55e59eb))
* **clay-css:** Mixins added `mixins/_globals.scss` file and mixin `clay-css` for outputting any css property ([af0da9f](https://github.com/liferay/clay/commit/af0da9f)), closes [#2822](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2822)
* **clay-css:** Mixins clay-container adds option to configure cursor ([6f6fb78](https://github.com/liferay/clay/commit/6f6fb78))
* **clay-css:** Modals add `.modal-item-group`, `.modal-item-group-first`, `.modal-item-group-last`, `.modal-item-group-only`, `.modal-item-shrink`, and modify `.modal-item` to accommodate more use cases like truncating long text ([72d9083](https://github.com/liferay/clay/commit/72d9083)), closes [#2844](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2844)
* **clay-css:** Modals added fixed height modals `.modal-height-sm`, `.modal-height-md`, `.modal-height-lg`, `.modal-height-xl` that sets heights `250px`, `450px`, `650px`, `800px` respectively ([de5d10d](https://github.com/liferay/clay/commit/de5d10d)), closes [#2395](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2395)
* **clay-css:** Multi Step Nav add `.c-inner` support for `.multi-step-icon` ([81c4924](https://github.com/liferay/clay/commit/81c4924)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Nav add `.c-inner` support for `.nav-btn`, `.nav-btn-monospaced`, and `.nav-link-monospaced` ([e2ca2ea](https://github.com/liferay/clay/commit/e2ca2ea)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Nav add support for `.c-inner` in `.nav-link` ([f3d19f0](https://github.com/liferay/clay/commit/f3d19f0)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Nav add support for `.nav-link.btn-unstyled` ([3dcbf47](https://github.com/liferay/clay/commit/3dcbf47)), closes [#2540](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2540)
* **clay-css:** Navbar add support for `.nav-item .dropdown` so `.dropdown-toggle` is sized and positioned properly ([124ee8b](https://github.com/liferay/clay/commit/124ee8b)), closes [#2900](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2900)
* **clay-css:** new SVG Icon test ([acb9f57](https://github.com/liferay/clay/commit/acb9f57))
* **clay-css:** Pagination add `.c-inner` support for `.pagination-sm` and `.pagination-lg` ([7464fe3](https://github.com/liferay/clay/commit/7464fe3)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Panel add `.c-inner` support for `.panel-header`, `.panel-header.collapse-icon`, `.panel-group-flush .panel-header`, `.panel-group-flush .collapse-icon` ([507dfee](https://github.com/liferay/clay/commit/507dfee)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Range added `clay-range` component ([142700f](https://github.com/liferay/clay/commit/142700f)), closes [#2157](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2157)
* **clay-css:** Range added tooltip and fix styles in IE11 ([a9e6137](https://github.com/liferay/clay/commit/a9e6137))
* **clay-css:** Sheet add `.c-inner` support for `.sheet-subtitle`, `.sheet-subtitle.collapse-icon` ([9aafb11](https://github.com/liferay/clay/commit/9aafb11)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** SVG Icon added `device-check` ([80396b4](https://github.com/liferay/clay/commit/80396b4)), closes [#2757](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2757)
* **clay-css:** SVG Icon source format `change-list-disabled` ([dd8f2f2](https://github.com/liferay/clay/commit/dd8f2f2))
* **clay-css:** SVG Icons add `books.svg` ([5fb502d](https://github.com/liferay/clay/commit/5fb502d)), closes [#2905](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2905)
* **clay-css:** SVG Icons add `social-instagram` and `social-vimeo` ([a879b3d](https://github.com/liferay/clay/commit/a879b3d)), closes [#2695](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2695)
* **clay-css:** SVG Icons add briefcase ([0216f1c](https://github.com/liferay/clay/commit/0216f1c))
* **clay-css:** SVG Icons add Google ([4a34678](https://github.com/liferay/clay/commit/4a34678)), closes [#2581](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2581)
* **clay-css:** SVG Icons add hdd.svg ([5052c5f](https://github.com/liferay/clay/commit/5052c5f)), closes [#2582](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2582)
* **clay-css:** SVG Icons add sign-in ([1c31dbb](https://github.com/liferay/clay/commit/1c31dbb)), closes [#2580](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2580)
* **clay-css:** SVG Icons added `credit-card` and `catalog` ([0d8e359](https://github.com/liferay/clay/commit/0d8e359)), closes [#2739](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2739)
* **clay-css:** SVG Icons added `heart-full` ([38edecf](https://github.com/liferay/clay/commit/38edecf)), closes [#2690](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2690)
* **clay-css:** SVG Icons added `import` and `import-list` ([4cf09f1](https://github.com/liferay/clay/commit/4cf09f1)), closes [#2683](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2683)
* **clay-css:** SVG Icons added `liferay-ac` ([6c76834](https://github.com/liferay/clay/commit/6c76834)), closes [#2727](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2727)
* **clay-css:** SVG Icons added `order-arrow-left` and `order-arrow-right` ([4a86eac](https://github.com/liferay/clay/commit/4a86eac)), closes [#2688](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2688)
* **clay-css:** SVG Icons added `times-circle-full` and `times-small` ([9be9456](https://github.com/liferay/clay/commit/9be9456)), closes [#2691](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2691)
* **clay-css:** SVG Icons added `truck` ([76b19e0](https://github.com/liferay/clay/commit/76b19e0)), closes [#2689](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2689)
* **clay-css:** SVG Icons added cloud ([001e644](https://github.com/liferay/clay/commit/001e644)), closes [#2742](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2742)
* **clay-css:** SVG Icons adds `document-pending` ([24067d8](https://github.com/liferay/clay/commit/24067d8)), closes [#2724](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2724)
* **clay-css:** SVG Icons deprecate `twitter` and add `social-twitter` ([eb5e2c0](https://github.com/liferay/clay/commit/eb5e2c0)), closes [#2697](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2697)
* **clay-css:** SVG Icons update `times` to be thicker ([4632b83](https://github.com/liferay/clay/commit/4632b83))
* **clay-css:** Tbar add `.c-inner` support for `.tbar-link`, `.tbar-link-monospaced`, `.tbar-btn`, `.tbar-btn-monospaced` ([9560bef](https://github.com/liferay/clay/commit/9560bef)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Type adds `.c-kbd` to style `kbd` element with light/dark theme and sizes sm/lg ([26db8b6](https://github.com/liferay/clay/commit/26db8b6)), closes [#2906](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2906)
* **clay-css:** Update Bootstrap CSS to 4.4.1, Bootstrap JS 4.4.0, Popper.js 1.16.0 ([491620d](https://github.com/liferay/clay/commit/491620d)), closes [#2785](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2785)
* **clay-css:** Use `map-deep-merge` to merge Sass maps in Clay CSS ([d69858d](https://github.com/liferay/clay/commit/d69858d)), closes [#2403](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2403)
* **clay-css:** Utilities `.c-inner` should inherit sizing styles from parent ([7dd8f58](https://github.com/liferay/clay/commit/7dd8f58)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)
* **clay-css:** Utilities add duplicate of Bootstrap's spacing utilities prefixed with `c-` and without the `!important` flag ([e12e7b4](https://github.com/liferay/clay/commit/e12e7b4)), closes [#2725](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2725)
* **clay-css:** Utilities adds `.c-inner` wrapper for use inside interactive elements to have better control over focus styles on click ([9616e49](https://github.com/liferay/clay/commit/9616e49)), closes [#2763](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2763)





# [3.6.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.5.0...@clayui/css@3.6.0) (2020-02-13)


### Bug Fixes

* **clay-css:** Navigation Bar and Management Bar focus styles should match across each component ([5d0ecf9](https://github.com/liferay/clay/commit/5d0ecf9)), closes [#2900](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2900)


### Features

* **clay-css:** Aspect Ratio adds `.aspect-ratio-item-top-left` ([6981a23](https://github.com/liferay/clay/commit/6981a23)), closes [#2843](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2843)
* **clay-css:** Card adds `.card-type-asset.product-card` ([c6be980](https://github.com/liferay/clay/commit/c6be980)), closes [#2843](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2843)
* **clay-css:** Card adds support for `.card` `.aspect-ratio-item-top-left`, `.aspect-ratio-item-top-center`, `.aspect-ratio-item-top-right`, `.aspect-ratio-item-right-middle`, `.aspect-ratio-item-bottom-right`, `.aspect-ratio-item-bottom-center`, `.aspect-ratio-item-bottom-left` ([930ee92](https://github.com/liferay/clay/commit/930ee92)), closes [#2843](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2843)
* **clay-css:** Custom Forms `.custom-control` should have `text-align: left` so text is next to input if parent container has `text-align: center` ([4615041](https://github.com/liferay/clay/commit/4615041)), closes [#2843](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2843)
* **clay-css:** Modals add `.modal-item-group`, `.modal-item-group-first`, `.modal-item-group-last`, `.modal-item-group-only`, `.modal-item-shrink`, and modify `.modal-item` to accommodate more use cases like truncating long text ([72d9083](https://github.com/liferay/clay/commit/72d9083)), closes [#2844](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2844)
* **clay-css:** Navbar add support for `.nav-item .dropdown` so `.dropdown-toggle` is sized and positioned properly ([124ee8b](https://github.com/liferay/clay/commit/124ee8b)), closes [#2900](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2900)
* **clay-css:** SVG Icons add `books.svg` ([5fb502d](https://github.com/liferay/clay/commit/5fb502d)), closes [#2905](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2905)





# [3.5.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.2.0...@clayui/css@3.5.0) (2020-01-31)


### Bug Fixes

* **clay-css:** Adds `!optional` flag to `[@extend](https://github.com/extend)` for components that are extending selectors/placeholders outside of their respective component file ([403a0c2](https://github.com/liferay/clay/commit/403a0c2)), closes [#2881](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2881)
* **clay-css:** Atlas Custom Control disabled label color should be the same as `$input-label-disabled-color` ([a160132](https://github.com/liferay/clay/commit/a160132)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** Atlas Dropdown change `.dropdown-header` and `.dropdown-subheader` color to [#272833](https://github.com/liferay/clay/commit/f901ce8)), closes [#2812](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2812)
* **clay-css:** Atlas Globals tweak `$success`, `$success-d1`, `$success-l1`, `$danger-d` hex values to match Lexicon exactly ([5b50860](https://github.com/liferay/clay/commit/5b50860)), closes [#2820](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2820)
* **clay-css:** Custom Control add Sass maps `$custom-control-label`, `$custom-control-label-disabled`, `$custom-control-label-text` and map deprecated `$custom-control-description-*` to them so our namespace matches Bootstrap's. It was renamed toward end of Bootstrap beta in 6a54b4a ([e41dcf5](https://github.com/liferay/clay/commit/e41dcf5)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Deprecate `.sheet-lg` and `$sheet-lg-max-width` in favor of `.container .sheet` pattern ([2e1e82c](https://github.com/liferay/clay/commit/2e1e82c)), closes [#2655](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2655)
* **clay-css:** Dropdown Item `.disabled` should have `cursor: not-allowed` and move `pointer-events: none` to `.disabled:active` ([28cb857](https://github.com/liferay/clay/commit/28cb857)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** List Group double borders in `list-group-item-flex` caused by Bootstrap 4.4.1 22f6b37 ([1221279](https://github.com/liferay/clay/commit/1221279)), closes [#2785](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2785)
* **clay-css:** Modal Footer use `justify-content: flex-start` instead of Bootstrap's `flex-end` to work around IE11 rendering issues with `modal-item`'s ([2be40c2](https://github.com/liferay/clay/commit/2be40c2)), closes [#2873](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2873)
* **css:** allow newline characters to display properly for tooltips ([2265d10](https://github.com/liferay/clay/commit/2265d10))


### Features

* **clay-css:** Alert adds `.alert-btn`, `.alert-autofit-row`, `.alert-footer`, and `.alert .btn-group-item` ([5212f50](https://github.com/liferay/clay/commit/5212f50)), closes [#2765](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2765)
* **clay-css:** Atlas Form Validation add styles for readonly input success, error, and warning states ([faf5748](https://github.com/liferay/clay/commit/faf5748)), closes [#2715](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2715)
* **clay-css:** Atlas Global Variables make `h1` - `h6` font sizes the same as 2.x ([0e0f9a0](https://github.com/liferay/clay/commit/0e0f9a0)), closes [#2864](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2864)
* **clay-css:** Atlas Globals adds `$enable-lexicon-flat-colors` to change base colors to match Lexicon Flat Color palette, set to `false` to revert back to old colors ([69fcdb2](https://github.com/liferay/clay/commit/69fcdb2)), closes [#E83E8](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/E83E8) [#2726](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2726)
* **clay-css:** Custom Control added `.custom-control-primary` to help increase visual hierarchy of a `custom-control` ([cc0275d](https://github.com/liferay/clay/commit/cc0275d)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Custom Control adds `$custom-control-description-font-weight` and sets font-weight to normal in Atlas ([3d2af5c](https://github.com/liferay/clay/commit/3d2af5c)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Dropdown Section add specific styles for nested `custom-control`s ([573a860](https://github.com/liferay/clay/commit/573a860)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** Forms support `label` element without `for` attribute. `label` needs the class `.form-control-label` and text must be wrapped in an element with class `.form-control-label-text` ([d0fff7f](https://github.com/liferay/clay/commit/d0fff7f)), closes [#2242](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2242)
* **clay-css:** Menubar added `.menubar-vertical-expand-md.menubar-decorated` and `.menubar-vertical-expand-lg.menubar-decorated` ([e46b52c](https://github.com/liferay/clay/commit/e46b52c)), closes [#2822](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2822)
* **clay-css:** Mixins added `clay-autofit-row` for custom `.autofit-row` and `.autofit-col` spacing ([cf3bafa](https://github.com/liferay/clay/commit/cf3bafa)), closes [#2765](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2765)
* **clay-css:** Mixins added `mixins/_globals.scss` file and mixin `clay-css` for outputting any css property ([af0da9f](https://github.com/liferay/clay/commit/af0da9f)), closes [#2822](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2822)
* **clay-css:** Mixins clay-container adds option to configure cursor ([6f6fb78](https://github.com/liferay/clay/commit/6f6fb78))
* **clay-css:** SVG Icon added `device-check` ([80396b4](https://github.com/liferay/clay/commit/80396b4)), closes [#2757](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2757)
* **clay-css:** SVG Icons added `credit-card` and `catalog` ([0d8e359](https://github.com/liferay/clay/commit/0d8e359)), closes [#2739](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2739)
* **clay-css:** SVG Icons added `liferay-ac` ([6c76834](https://github.com/liferay/clay/commit/6c76834)), closes [#2727](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2727)
* **clay-css:** SVG Icons added cloud ([001e644](https://github.com/liferay/clay/commit/001e644)), closes [#2742](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2742)
* **clay-css:** SVG Icons adds `document-pending` ([24067d8](https://github.com/liferay/clay/commit/24067d8)), closes [#2724](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2724)
* **clay-css:** Update Bootstrap CSS to 4.4.1, Bootstrap JS 4.4.0, Popper.js 1.16.0 ([491620d](https://github.com/liferay/clay/commit/491620d)), closes [#2785](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2785)
* **clay-css:** Utilities add duplicate of Bootstrap's spacing utilities prefixed with `c-` and without the `!important` flag ([e12e7b4](https://github.com/liferay/clay/commit/e12e7b4)), closes [#2725](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2725)





# [3.4.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.2.0...@clayui/css@3.4.0) (2020-01-20)


### Bug Fixes

* **clay-css:** Atlas Custom Control disabled label color should be the same as `$input-label-disabled-color` ([a160132](https://github.com/liferay/clay/commit/a160132)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** Atlas Dropdown change `.dropdown-header` and `.dropdown-subheader` color to [#272833](https://github.com/liferay/clay/commit/f901ce8)), closes [#2812](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2812)
* **clay-css:** Atlas Globals tweak `$success`, `$success-d1`, `$success-l1`, `$danger-d` hex values to match Lexicon exactly ([5b50860](https://github.com/liferay/clay/commit/5b50860)), closes [#2820](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2820)
* **clay-css:** Custom Control add Sass maps `$custom-control-label`, `$custom-control-label-disabled`, `$custom-control-label-text` and map deprecated `$custom-control-description-*` to them so our namespace matches Bootstrap's. It was renamed toward end of Bootstrap beta in 6a54b4a ([e41dcf5](https://github.com/liferay/clay/commit/e41dcf5)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Deprecate `.sheet-lg` and `$sheet-lg-max-width` in favor of `.container .sheet` pattern ([2e1e82c](https://github.com/liferay/clay/commit/2e1e82c)), closes [#2655](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2655)
* **clay-css:** Dropdown Item `.disabled` should have `cursor: not-allowed` and move `pointer-events: none` to `.disabled:active` ([28cb857](https://github.com/liferay/clay/commit/28cb857)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** List Group double borders in `list-group-item-flex` caused by Bootstrap 4.4.1 22f6b37 ([1221279](https://github.com/liferay/clay/commit/1221279)), closes [#2785](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2785)
* **css:** allow newline characters to display properly for tooltips ([2265d10](https://github.com/liferay/clay/commit/2265d10))


### Features

* **clay-css:** Alert adds `.alert-btn`, `.alert-autofit-row`, `.alert-footer`, and `.alert .btn-group-item` ([5212f50](https://github.com/liferay/clay/commit/5212f50)), closes [#2765](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2765)
* **clay-css:** Atlas Form Validation add styles for readonly input success, error, and warning states ([faf5748](https://github.com/liferay/clay/commit/faf5748)), closes [#2715](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2715)
* **clay-css:** Atlas Global Variables make `h1` - `h6` font sizes the same as 2.x ([0e0f9a0](https://github.com/liferay/clay/commit/0e0f9a0)), closes [#2864](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2864)
* **clay-css:** Atlas Globals adds `$enable-lexicon-flat-colors` to change base colors to match Lexicon Flat Color palette, set to `false` to revert back to old colors ([69fcdb2](https://github.com/liferay/clay/commit/69fcdb2)), closes [#E83E8](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/E83E8) [#2726](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2726)
* **clay-css:** Custom Control added `.custom-control-primary` to help increase visual hierarchy of a `custom-control` ([cc0275d](https://github.com/liferay/clay/commit/cc0275d)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Custom Control adds `$custom-control-description-font-weight` and sets font-weight to normal in Atlas ([3d2af5c](https://github.com/liferay/clay/commit/3d2af5c)), closes [#2813](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2813)
* **clay-css:** Dropdown Section add specific styles for nested `custom-control`s ([573a860](https://github.com/liferay/clay/commit/573a860)), closes [#2811](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2811)
* **clay-css:** Forms support `label` element without `for` attribute. `label` needs the class `.form-control-label` and text must be wrapped in an element with class `.form-control-label-text` ([d0fff7f](https://github.com/liferay/clay/commit/d0fff7f)), closes [#2242](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2242)
* **clay-css:** Menubar added `.menubar-vertical-expand-md.menubar-decorated` and `.menubar-vertical-expand-lg.menubar-decorated` ([e46b52c](https://github.com/liferay/clay/commit/e46b52c)), closes [#2822](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2822)
* **clay-css:** Mixins added `clay-autofit-row` for custom `.autofit-row` and `.autofit-col` spacing ([cf3bafa](https://github.com/liferay/clay/commit/cf3bafa)), closes [#2765](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2765)
* **clay-css:** Mixins added `mixins/_globals.scss` file and mixin `clay-css` for outputting any css property ([af0da9f](https://github.com/liferay/clay/commit/af0da9f)), closes [#2822](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2822)
* **clay-css:** Mixins clay-container adds option to configure cursor ([6f6fb78](https://github.com/liferay/clay/commit/6f6fb78))
* **clay-css:** SVG Icon added `device-check` ([80396b4](https://github.com/liferay/clay/commit/80396b4)), closes [#2757](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2757)
* **clay-css:** SVG Icons added `credit-card` and `catalog` ([0d8e359](https://github.com/liferay/clay/commit/0d8e359)), closes [#2739](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2739)
* **clay-css:** SVG Icons added `liferay-ac` ([6c76834](https://github.com/liferay/clay/commit/6c76834)), closes [#2727](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2727)
* **clay-css:** SVG Icons added cloud ([001e644](https://github.com/liferay/clay/commit/001e644)), closes [#2742](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2742)
* **clay-css:** SVG Icons adds `document-pending` ([24067d8](https://github.com/liferay/clay/commit/24067d8)), closes [#2724](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2724)
* **clay-css:** Update Bootstrap CSS to 4.4.1, Bootstrap JS 4.4.0, Popper.js 1.16.0 ([491620d](https://github.com/liferay/clay/commit/491620d)), closes [#2785](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2785)
* **clay-css:** Utilities add duplicate of Bootstrap's spacing utilities prefixed with `c-` and without the `!important` flag ([e12e7b4](https://github.com/liferay/clay/commit/e12e7b4)), closes [#2725](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2725)





# [3.3.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.2.0...@clayui/css@3.3.0) (2019-12-05)


### Bug Fixes

* **clay-css:** Deprecate `.sheet-lg` and `$sheet-lg-max-width` in favor of `.container .sheet` pattern ([2e1e82c](https://github.com/liferay/clay/commit/2e1e82c)), closes [#2655](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2655)


### Features

* **clay-css:** Atlas Form Validation add styles for readonly input success, error, and warning states ([faf5748](https://github.com/liferay/clay/commit/faf5748)), closes [#2715](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2715)
* **clay-css:** Atlas Globals adds `$enable-lexicon-flat-colors` to change base colors to match Lexicon Flat Color palette, set to `false` to revert back to old colors ([69fcdb2](https://github.com/liferay/clay/commit/69fcdb2)), closes [#E83E8](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/E83E8) [#2726](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2726)
* **clay-css:** SVG Icon added `device-check` ([80396b4](https://github.com/liferay/clay/commit/80396b4)), closes [#2757](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2757)
* **clay-css:** SVG Icons added `credit-card` and `catalog` ([0d8e359](https://github.com/liferay/clay/commit/0d8e359)), closes [#2739](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2739)
* **clay-css:** SVG Icons added `liferay-ac` ([6c76834](https://github.com/liferay/clay/commit/6c76834)), closes [#2727](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2727)
* **clay-css:** SVG Icons added cloud ([001e644](https://github.com/liferay/clay/commit/001e644)), closes [#2742](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2742)
* **clay-css:** SVG Icons adds `document-pending` ([24067d8](https://github.com/liferay/clay/commit/24067d8)), closes [#2724](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2724)
* **clay-css:** Utilities add duplicate of Bootstrap's spacing utilities prefixed with `c-` and without the `!important` flag ([e12e7b4](https://github.com/liferay/clay/commit/e12e7b4)), closes [#2725](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2725)





# [3.2.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.1.0...@clayui/css@3.2.0) (2019-11-07)


### Features

* **clay-css:** SVG Icons add `social-instagram` and `social-vimeo` ([a879b3d](https://github.com/liferay/clay/commit/a879b3d)), closes [#2695](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2695)
* **clay-css:** SVG Icons added `heart-full` ([38edecf](https://github.com/liferay/clay/commit/38edecf)), closes [#2690](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2690)
* **clay-css:** SVG Icons added `import` and `import-list` ([4cf09f1](https://github.com/liferay/clay/commit/4cf09f1)), closes [#2683](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2683)
* **clay-css:** SVG Icons added `order-arrow-left` and `order-arrow-right` ([4a86eac](https://github.com/liferay/clay/commit/4a86eac)), closes [#2688](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2688)
* **clay-css:** SVG Icons added `times-circle-full` and `times-small` ([9be9456](https://github.com/liferay/clay/commit/9be9456)), closes [#2691](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2691)
* **clay-css:** SVG Icons added `truck` ([76b19e0](https://github.com/liferay/clay/commit/76b19e0)), closes [#2689](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2689)
* **clay-css:** SVG Icons deprecate `twitter` and add `social-twitter` ([eb5e2c0](https://github.com/liferay/clay/commit/eb5e2c0)), closes [#2697](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2697)
* **clay-css:** SVG Icons update `times` to be thicker ([4632b83](https://github.com/liferay/clay/commit/4632b83))





# [3.1.0](https://github.com/liferay/clay/tree/master/packages/clay-css/compare/@clayui/css@3.0.1...@clayui/css@3.1.0) (2019-10-28)


### Bug Fixes

* broken markdown lists ([d1adc7e](https://github.com/liferay/clay/commit/d1adc7e))


### Features

* **clay-css:** SVG Icons add briefcase ([0216f1c](https://github.com/liferay/clay/commit/0216f1c))
* **clay-css:** SVG Icons add hdd.svg ([5052c5f](https://github.com/liferay/clay/commit/5052c5f)), closes [#2582](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2582)
* **clay-css:** SVG Icons add sign-in ([1c31dbb](https://github.com/liferay/clay/commit/1c31dbb)), closes [#2580](https://github.com/liferay/clay/tree/master/packages/clay-css/issues/2580)





### v3.0.0-alpha.1
