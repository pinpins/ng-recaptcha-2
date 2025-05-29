# 20.0.0 (2025-05-29)


### Bug Fixes

* **build:** fix AoT builds ([921be50](https://github.com/pinpins/ng-recaptcha-2/commit/921be508abd085a8ff5e5fa92c3014b4935d0e20)), closes [#57](https://github.com/pinpins/ng-recaptcha-2/issues/57) [#65](https://github.com/pinpins/ng-recaptcha-2/issues/65)
* **component-v3:** fix a potential metadata error in v3 service ([ed885b5](https://github.com/pinpins/ng-recaptcha-2/commit/ed885b59ece675fd714f999550336d0c259cc2a5))
* **component:** catch and propagate grecaptcha errors, closes [#175](https://github.com/pinpins/ng-recaptcha-2/issues/175) ([075edd0](https://github.com/pinpins/ng-recaptcha-2/commit/075edd052f4b419602680a1d481059ff4f3dd7c1))
* **component:** correct type when using strict mode ([a687d13](https://github.com/pinpins/ng-recaptcha-2/commit/a687d13e2874f38738002ffba598f5892cb60959)), closes [#211](https://github.com/pinpins/ng-recaptcha-2/issues/211)
* **component:** correctly emit `resolved` event ([25d4246](https://github.com/pinpins/ng-recaptcha-2/commit/25d4246ce286447ac6b4fe7818a3b8bdc3f9a72d))
* **component:** correctly reset captcha during `ngOnDestroy` ([b31d57f](https://github.com/pinpins/ng-recaptcha-2/commit/b31d57f85d3a676eb3d0428f19effb2e3cc74e8a)), closes [#12](https://github.com/pinpins/ng-recaptcha-2/issues/12)
* **component:** delay invisible recaptcha execution until it's rendered ([99292b7](https://github.com/pinpins/ng-recaptcha-2/commit/99292b77568a7e0a949c8e679f0eabe21d1c6cca)), closes [#127](https://github.com/pinpins/ng-recaptcha-2/issues/127)
* **component:** emit `resolved(null)` event when recaptcha expires ([491d99a](https://github.com/pinpins/ng-recaptcha-2/commit/491d99ae36139398b23e7d039f404dd62c360def)), closes [#11](https://github.com/pinpins/ng-recaptcha-2/issues/11)
* **component:** ensure that component is destroyed safely ([1e51d56](https://github.com/pinpins/ng-recaptcha-2/commit/1e51d565bdd11f01f90b7f7962a8822945b523bf)), closes [#46](https://github.com/pinpins/ng-recaptcha-2/issues/46)
* **component:** fix a potential error during recaptcha rendering ([1c395b5](https://github.com/pinpins/ng-recaptcha-2/commit/1c395b5a356bf64f57ad25c341115e40a3f9af8f))
* **component:** fix custom languages for reCAPTCHA v3 ([a2b145d](https://github.com/pinpins/ng-recaptcha-2/commit/a2b145ded798954aa5253ee6948a1c66fc4df765)), closes [#174](https://github.com/pinpins/ng-recaptcha-2/issues/174)
* **component:** fix server-side rendering ([7a5bc6c](https://github.com/pinpins/ng-recaptcha-2/commit/7a5bc6c3570f533d003954b2cebc1c23cedd07f0)), closes [#34](https://github.com/pinpins/ng-recaptcha-2/issues/34)
* **component:** fix the injection error when using slandalone `RecaptchaV3Module` ([c93b99c](https://github.com/pinpins/ng-recaptcha-2/commit/c93b99c1fdda1284dd9523a45835892968913ba3))
* **component:** handle id input parameter correctly ([b578fe5](https://github.com/pinpins/ng-recaptcha-2/commit/b578fe5db9d541b5cf11d2a1d6029688ce1d3825))
* **component:** handle top-level `execute` errors for reCAPTCHA v3 ([c7d02ce](https://github.com/pinpins/ng-recaptcha-2/commit/c7d02ce89da98fde93ffa87e76b9ff63a604b3dd)), closes [#194](https://github.com/pinpins/ng-recaptcha-2/issues/194)
* **component:** improve reCAPTCHA v2 and v3 interoperability ([79fc85b](https://github.com/pinpins/ng-recaptcha-2/commit/79fc85b41b51c0f816536b5ea97f3926c0087e0a)), closes [#152](https://github.com/pinpins/ng-recaptcha-2/issues/152)
* **component:** mark `forRoot()` method as deprecated ([dea31e5](https://github.com/pinpins/ng-recaptcha-2/commit/dea31e52c902fb37bdcb743c6ce51e4a6c3e5b07))
* **component:** Replace `OpaqueToken` with `InjectionToken` ([2b7db9b](https://github.com/pinpins/ng-recaptcha-2/commit/2b7db9b24ce133e6a4a9cefd8e1e8c0178cee69b))
* **component:** reset form-bound captcha value after component destruction ([9e5c5e7](https://github.com/pinpins/ng-recaptcha-2/commit/9e5c5e7e9e6a2929462d4b5e586aa9eb0bf38ad6)), closes [#201](https://github.com/pinpins/ng-recaptcha-2/issues/201)
* **component:** reset form-bound captcha value after component destruction ([0e550c4](https://github.com/pinpins/ng-recaptcha-2/commit/0e550c4a3e4c0aac40085da37a35c1928eebd0cf)), closes [#201](https://github.com/pinpins/ng-recaptcha-2/issues/201)
* **component:** reset the captcha when the component is destroyed ([e1441c8](https://github.com/pinpins/ng-recaptcha-2/commit/e1441c8b73f9d0e99850aba00f4e7bcf74450433)), closes [#10](https://github.com/pinpins/ng-recaptcha-2/issues/10)
* **component:** set CSP nonce as attribute ([abcb9a6](https://github.com/pinpins/ng-recaptcha-2/commit/abcb9a6e4571f17e8d9fb304c8f47fd082595d9e))
* **component:** unblock protractor tests after <re-captcha> destruction ([a5f2fe9](https://github.com/pinpins/ng-recaptcha-2/commit/a5f2fe906a35b4d02cc05b668ee50ef673457f16))
* **component:** use ElementRef to access component's native element ([d3a8409](https://github.com/pinpins/ng-recaptcha-2/commit/d3a8409cc6578258c1f0d6e0e153c5bb77a583e4)), closes [#48](https://github.com/pinpins/ng-recaptcha-2/issues/48) [#68](https://github.com/pinpins/ng-recaptcha-2/issues/68)
* **demo:** re-add a missing systemjs config file ([b51694a](https://github.com/pinpins/ng-recaptcha-2/commit/b51694af99cd1e260168d48a2f99b137c53d3694))
* **module:** Adding the value accessor directive to the forms barrel, which was missing. ([ad73e2e](https://github.com/pinpins/ng-recaptcha-2/commit/ad73e2e1be5a7008ec24aa8455cd4e7a4317c842))
* **package:** convert the `README.md` file back to a proper symlink ([e0c5c99](https://github.com/pinpins/ng-recaptcha-2/commit/e0c5c9903ed6b1927774ff657f5b3ca216a12664))
* **package:** fix publishing empty package ([e4685fe](https://github.com/pinpins/ng-recaptcha-2/commit/e4685fe0ff83a14b2d56d88455a76e0d11e62d9c))
* **package:** make `@types/grecaptcha` a non-optional dependency ([bc5ad51](https://github.com/pinpins/ng-recaptcha-2/commit/bc5ad516cda6c39d12f5804330b1be02936f5283)), closes [#205](https://github.com/pinpins/ng-recaptcha-2/issues/205)
* **rxjs:** change import of `of` operator ([3e0bda6](https://github.com/pinpins/ng-recaptcha-2/commit/3e0bda60684bd731a58f35485dca686a0e227144)), closes [#95](https://github.com/pinpins/ng-recaptcha-2/issues/95)


### Features

* **component:** *deprecate* `error` output in favor of `errored` ([6b002bb](https://github.com/pinpins/ng-recaptcha-2/commit/6b002bb7e42fa941ae5096c8417a9672b42bf28c))
* **component:** add `exportAs` annotation ([3e2e217](https://github.com/pinpins/ng-recaptcha-2/commit/3e2e217e3980bdf567a6328520dbbd5d3cb0d276))
* **component:** add a new `RECAPTCHA_LOADER_OPTIONS` injection token as a way of manipulating script load parameters (such as base URL, language, trusted types, WAF, etc) ([b3c7213](https://github.com/pinpins/ng-recaptcha-2/commit/b3c721321221a6047ed914d76ad93169f91a9299))
* **component:** Add Angular 11 support ([918fe90](https://github.com/pinpins/ng-recaptcha-2/commit/918fe909685953082698635e1c64aa9223bc56ba))
* **component:** add support for `badge` property ([5a16430](https://github.com/pinpins/ng-recaptcha-2/commit/5a16430149534ecaa7ef921c80e0383f4ac787aa)), closes [#30](https://github.com/pinpins/ng-recaptcha-2/issues/30)
* **component:** add support for invisible reCAPTCHA ([c19489d](https://github.com/pinpins/ng-recaptcha-2/commit/c19489d2668f89c0277a5985920d3db299a78703)), closes [#18](https://github.com/pinpins/ng-recaptcha-2/issues/18)
* **component:** add support for reCAPTCHA v3 ([4a083c6](https://github.com/pinpins/ng-recaptcha-2/commit/4a083c638e7395b982a1cfc95a8d187107d14e21)), closes [#129](https://github.com/pinpins/ng-recaptcha-2/issues/129)
* **component:** add the ability to handle reCAPTCHA errors ([80c9e6e](https://github.com/pinpins/ng-recaptcha-2/commit/80c9e6e36c3b8dced1a5e5db591118bcd2bc72f7)), closes [#199](https://github.com/pinpins/ng-recaptcha-2/issues/199)
* **component:** add the ability to provide `nonce` to the script tag ([8f55b19](https://github.com/pinpins/ng-recaptcha-2/commit/8f55b19b15edfa7da76387a9b4521e8d0f08bc93)), closes [#100](https://github.com/pinpins/ng-recaptcha-2/issues/100)
* **component:** add the ability to specify component props globally ([d9c5f55](https://github.com/pinpins/ng-recaptcha-2/commit/d9c5f55b6d75314cb2939699fc9b1f76f18f7171)), closes [#45](https://github.com/pinpins/ng-recaptcha-2/issues/45)
* **component:** adjust dependencies for Angular 6 support ([736c7ae](https://github.com/pinpins/ng-recaptcha-2/commit/736c7ae764b619dbbb559a568b5455d65b779bec))
* **component:** allow to specify a base url for loading recaptcha ([df505fd](https://github.com/pinpins/ng-recaptcha-2/commit/df505fd0476bb3d268c3d6084e0ded5053fa8e49)), closes [#101](https://github.com/pinpins/ng-recaptcha-2/issues/101)
* **component:** change component and directive selectors ([58a01b4](https://github.com/pinpins/ng-recaptcha-2/commit/58a01b460671c23c88735911d30fd8a520a00729))
* **component:** load recaptcha script using code compatible with trusted types ([88d257b](https://github.com/pinpins/ng-recaptcha-2/commit/88d257b08255b59ca5e517871413e0a59a626a3f)), closes [#304](https://github.com/pinpins/ng-recaptcha-2/issues/304)
* **component:** make Angular 10.0.0 a supported peer dependency ([3d7756b](https://github.com/pinpins/ng-recaptcha-2/commit/3d7756bfdf75dad4a359577142908fd9b7d9a80d)), closes [#177](https://github.com/pinpins/ng-recaptcha-2/issues/177)
* **component:** make Angular 8.0.0 a supported peer dependency ([f003ff2](https://github.com/pinpins/ng-recaptcha-2/commit/f003ff22f5cdd93730bb6d957c7ad4cbafabfdb3))
* **component:** make Angular 9.0.0 a supported peer dependency ([98edce6](https://github.com/pinpins/ng-recaptcha-2/commit/98edce685bfb458a048408e4709f2265c5626776)), closes [#168](https://github.com/pinpins/ng-recaptcha-2/issues/168)
* **component:** remove deprecated `forRoot` method ([514beaf](https://github.com/pinpins/ng-recaptcha-2/commit/514beaf066eceae7d5a976e4259641ac8f24244e))
* **misc:** Annotating a static field with nocollapse so that we doesn't have issues closure compiler in advanced mode. ([55e5932](https://github.com/pinpins/ng-recaptcha-2/commit/55e593239fb3e9a551887787bd9c34065088fe8e))
* **module:** change the way recaptcha modules work ([6e13389](https://github.com/pinpins/ng-recaptcha-2/commit/6e13389d0a5909ad529f2231464826f6e6570851))
* **module:** skip `forRoot()` when importing `RecaptchaModule` ([7fb97fb](https://github.com/pinpins/ng-recaptcha-2/commit/7fb97fb04049dd058a2394ecef297dac7c6104d1)), closes [#113](https://github.com/pinpins/ng-recaptcha-2/issues/113) [#116](https://github.com/pinpins/ng-recaptcha-2/issues/116)
* **package management:** add `@types/grecaptcha` as optional dependency ([85fbfba](https://github.com/pinpins/ng-recaptcha-2/commit/85fbfbadbaafe4443393383726a303fc246e725f))
* **package:** add Angular 12 support ([a212a21](https://github.com/pinpins/ng-recaptcha-2/commit/a212a218d7c9c019855ef6566c2d105f0d9952ea))
* **package:** add Angular 14 support ([eac6858](https://github.com/pinpins/ng-recaptcha-2/commit/eac685866af880d75974ead66cefd11dc45949cf))
* **package:** add Angular 15 support ([6c62634](https://github.com/pinpins/ng-recaptcha-2/commit/6c626347630f775a9c16bf08c942c3f43935e206)), closes [#275](https://github.com/pinpins/ng-recaptcha-2/issues/275)
* **package:** add Angular 16 support ([77a7d1f](https://github.com/pinpins/ng-recaptcha-2/commit/77a7d1fa37993fad98f2f07dc0b6dc54bf8a96b0)), closes [#288](https://github.com/pinpins/ng-recaptcha-2/issues/288)
* **package:** add Angular 17 support ([83714aa](https://github.com/pinpins/ng-recaptcha-2/commit/83714aab5f751de29aa408bf82c614c5a1d0918c)), closes [#310](https://github.com/pinpins/ng-recaptcha-2/issues/310)
* **package:** implement Angular Package format ([71340c4](https://github.com/pinpins/ng-recaptcha-2/commit/71340c49ed52ce6cfeb4b46eb85c0987f3770410))
* **package:** update `"@types/grecaptcha"` optional dependency version to ^3 ([e1ee7b9](https://github.com/pinpins/ng-recaptcha-2/commit/e1ee7b96748f07a2c6093b49d6013470b70a87cd))
* **package:** update peer dependencies to include Angular 7 ([929ef7a](https://github.com/pinpins/ng-recaptcha-2/commit/929ef7a0a46a64be3b402b02f4506b4bafdddbcc))
* **package:** update peer dependencies to include Angular v4 ([b2f04e8](https://github.com/pinpins/ng-recaptcha-2/commit/b2f04e8847ff3c3f68d4566f4fbd7ff7906842a7))
* **package:** upgrade to Angular 13 ([af08641](https://github.com/pinpins/ng-recaptcha-2/commit/af08641e7097f8ec0dec5f489227bea22082ba89)), closes [#245](https://github.com/pinpins/ng-recaptcha-2/issues/245)


### BREAKING CHANGES

* **package:** - Angular v16 is no longer supported with this version. Pin `ng-recaptcha` to `v12.x.x` to retain support for a previous Angular version
* **package:** - Angular v15 is no longer supported with this version. Pin `ng-recaptcha` to `v11.x.x` to retain support for a previous Angular version
* **component:** Support for previous versions of Angular has been dropped. Starting from v7 only one version of Angular will be supported.
* **component:** The `RecaptchaModule.forRoot()` method has been obsolete since v4.1.0 (since it has no longer been required). It is now removed. To migrate your code, simply use `RecaptchaModule` where you previously used `RecaptchaModule.forRoot()`
* **package:** * `ng-recaptcha/forms` entry point has been removed. `RecaptchaFormsModule` and `RecaptchaValueAccessorDirective` should now be imported directly from `ng-recaptcha`
* `tslib` is now a package dependency to ensure minimum possible bundle size. If your project doesn't yet have a dependency on `tslib`, run `npm install -D tslib@^1.9.0` (or `yarn add -D tslib@^1.9.0` if you use yarn)
* **component:** The peer dependency for `@angular/core` has been bumped to `^6.0.0`
* **component:** Angular v2.x.x is no longer supported due to dependency on Platform capabilities that were added in [v4.0.0-rc.1](https://github.com/angular/angular/blob/master/CHANGELOG.md#features-20)
* **component:** component selector changed from `recaptcha` to `re-captcha`
* **module:** module handling has changed.
Users of `RecaptchaNoFormsModule` should instead use `import { RecaptchaModule } from 'ng-recaptcha'`. Users of v1 `RecaptchaModule` should also `import { RecaptchaFormsModule } from 'ng-recaptcha/forms'`. SystemJS users must also re-setup module "main" file to `index.js`



<a name="14.0.0"></a>

# 14.0.0 (2024-05-25)

### Bug Fixes

- **build:** fix AoT builds ([921be50](https://github.com/LakhveerChahal/ng-recaptcha/commit/921be50)), closes [#57](https://github.com/LakhveerChahal/ng-recaptcha/issues/57) [#65](https://github.com/LakhveerChahal/ng-recaptcha/issues/65)
- **component-v3:** fix a potential metadata error in v3 service ([ed885b5](https://github.com/LakhveerChahal/ng-recaptcha/commit/ed885b5))
- **component:** catch and propagate grecaptcha errors, closes [#175](https://github.com/LakhveerChahal/ng-recaptcha/issues/175) ([075edd0](https://github.com/LakhveerChahal/ng-recaptcha/commit/075edd0))
- **component:** correct type when using strict mode ([a687d13](https://github.com/LakhveerChahal/ng-recaptcha/commit/a687d13)), closes [#211](https://github.com/LakhveerChahal/ng-recaptcha/issues/211)
- **component:** correctly emit `resolved` event ([25d4246](https://github.com/LakhveerChahal/ng-recaptcha/commit/25d4246))
- **component:** correctly reset captcha during `ngOnDestroy` ([b31d57f](https://github.com/LakhveerChahal/ng-recaptcha/commit/b31d57f)), closes [#12](https://github.com/LakhveerChahal/ng-recaptcha/issues/12)
- **component:** delay invisible recaptcha execution until it's rendered ([99292b7](https://github.com/LakhveerChahal/ng-recaptcha/commit/99292b7)), closes [#127](https://github.com/LakhveerChahal/ng-recaptcha/issues/127)
- **component:** emit `resolved(null)` event when recaptcha expires ([491d99a](https://github.com/LakhveerChahal/ng-recaptcha/commit/491d99a)), closes [#11](https://github.com/LakhveerChahal/ng-recaptcha/issues/11)
- **component:** ensure that component is destroyed safely ([1e51d56](https://github.com/LakhveerChahal/ng-recaptcha/commit/1e51d56)), closes [#46](https://github.com/LakhveerChahal/ng-recaptcha/issues/46)
- **component:** fix a potential error during recaptcha rendering ([1c395b5](https://github.com/LakhveerChahal/ng-recaptcha/commit/1c395b5))
- **component:** fix custom languages for reCAPTCHA v3 ([a2b145d](https://github.com/LakhveerChahal/ng-recaptcha/commit/a2b145d)), closes [#174](https://github.com/LakhveerChahal/ng-recaptcha/issues/174)
- **component:** fix server-side rendering ([7a5bc6c](https://github.com/LakhveerChahal/ng-recaptcha/commit/7a5bc6c)), closes [#34](https://github.com/LakhveerChahal/ng-recaptcha/issues/34) [/github.com/angular/angular/blob/master/CHANGELOG.md#features-20](https://github.com//github.com/angular/angular/blob/master/CHANGELOG.md/issues/features-20)
- **component:** fix the injection error when using slandalone `RecaptchaV3Module` ([c93b99c](https://github.com/LakhveerChahal/ng-recaptcha/commit/c93b99c))
- **component:** handle id input parameter correctly ([b578fe5](https://github.com/LakhveerChahal/ng-recaptcha/commit/b578fe5))
- **component:** handle top-level `execute` errors for reCAPTCHA v3 ([c7d02ce](https://github.com/LakhveerChahal/ng-recaptcha/commit/c7d02ce)), closes [#194](https://github.com/LakhveerChahal/ng-recaptcha/issues/194)
- **component:** improve reCAPTCHA v2 and v3 interoperability ([79fc85b](https://github.com/LakhveerChahal/ng-recaptcha/commit/79fc85b)), closes [#152](https://github.com/LakhveerChahal/ng-recaptcha/issues/152)
- **component:** mark `forRoot()` method as deprecated ([dea31e5](https://github.com/LakhveerChahal/ng-recaptcha/commit/dea31e5))
- **component:** Replace `OpaqueToken` with `InjectionToken` ([2b7db9b](https://github.com/LakhveerChahal/ng-recaptcha/commit/2b7db9b))
- **component:** reset form-bound captcha value after component destruction ([9e5c5e7](https://github.com/LakhveerChahal/ng-recaptcha/commit/9e5c5e7)), closes [#201](https://github.com/LakhveerChahal/ng-recaptcha/issues/201)
- **component:** reset form-bound captcha value after component destruction ([0e550c4](https://github.com/LakhveerChahal/ng-recaptcha/commit/0e550c4)), closes [#201](https://github.com/LakhveerChahal/ng-recaptcha/issues/201)
- **component:** reset the captcha when the component is destroyed ([e1441c8](https://github.com/LakhveerChahal/ng-recaptcha/commit/e1441c8)), closes [#10](https://github.com/LakhveerChahal/ng-recaptcha/issues/10)
- **component:** set CSP nonce as attribute ([abcb9a6](https://github.com/LakhveerChahal/ng-recaptcha/commit/abcb9a6))
- **component:** unblock protractor tests after <re-captcha> destruction ([a5f2fe9](https://github.com/LakhveerChahal/ng-recaptcha/commit/a5f2fe9))
- **component:** use ElementRef to access component's native element ([d3a8409](https://github.com/LakhveerChahal/ng-recaptcha/commit/d3a8409)), closes [#48](https://github.com/LakhveerChahal/ng-recaptcha/issues/48) [#68](https://github.com/LakhveerChahal/ng-recaptcha/issues/68)
- **demo:** re-add a missing systemjs config file ([b51694a](https://github.com/LakhveerChahal/ng-recaptcha/commit/b51694a))
- **module:** Adding the value accessor directive to the forms barrel, which was missing. ([ad73e2e](https://github.com/LakhveerChahal/ng-recaptcha/commit/ad73e2e))
- **package:** convert the `README.md` file back to a proper symlink ([e0c5c99](https://github.com/LakhveerChahal/ng-recaptcha/commit/e0c5c99))
- **package:** fix publishing empty package ([e4685fe](https://github.com/LakhveerChahal/ng-recaptcha/commit/e4685fe))
- **package:** make `[@types](https://github.com/types)/grecaptcha` a non-optional dependency ([bc5ad51](https://github.com/LakhveerChahal/ng-recaptcha/commit/bc5ad51)), closes [#205](https://github.com/LakhveerChahal/ng-recaptcha/issues/205)
- **rxjs:** change import of `of` operator ([3e0bda6](https://github.com/LakhveerChahal/ng-recaptcha/commit/3e0bda6)), closes [#95](https://github.com/LakhveerChahal/ng-recaptcha/issues/95)

### Features

- **component:** _deprecate_ `error` output in favor of `errored` ([6b002bb](https://github.com/LakhveerChahal/ng-recaptcha/commit/6b002bb))
- **component:** add `exportAs` annotation ([3e2e217](https://github.com/LakhveerChahal/ng-recaptcha/commit/3e2e217))
- **component:** add a new `RECAPTCHA_LOADER_OPTIONS` injection token as a way of manipulating script load parameters (such as base URL, language, trusted types, WAF, etc) ([b3c7213](https://github.com/LakhveerChahal/ng-recaptcha/commit/b3c7213))
- **component:** Add Angular 11 support ([918fe90](https://github.com/LakhveerChahal/ng-recaptcha/commit/918fe90))
- **component:** add support for `badge` property ([5a16430](https://github.com/LakhveerChahal/ng-recaptcha/commit/5a16430)), closes [#30](https://github.com/LakhveerChahal/ng-recaptcha/issues/30)
- **component:** add support for invisible reCAPTCHA ([c19489d](https://github.com/LakhveerChahal/ng-recaptcha/commit/c19489d)), closes [#18](https://github.com/LakhveerChahal/ng-recaptcha/issues/18)
- **component:** add support for reCAPTCHA v3 ([4a083c6](https://github.com/LakhveerChahal/ng-recaptcha/commit/4a083c6)), closes [#129](https://github.com/LakhveerChahal/ng-recaptcha/issues/129)
- **component:** add the ability to handle reCAPTCHA errors ([80c9e6e](https://github.com/LakhveerChahal/ng-recaptcha/commit/80c9e6e)), closes [#199](https://github.com/LakhveerChahal/ng-recaptcha/issues/199)
- **component:** add the ability to provide `nonce` to the script tag ([8f55b19](https://github.com/LakhveerChahal/ng-recaptcha/commit/8f55b19)), closes [#100](https://github.com/LakhveerChahal/ng-recaptcha/issues/100)
- **component:** add the ability to specify component props globally ([d9c5f55](https://github.com/LakhveerChahal/ng-recaptcha/commit/d9c5f55)), closes [#45](https://github.com/LakhveerChahal/ng-recaptcha/issues/45)
- **component:** adjust dependencies for Angular 6 support ([736c7ae](https://github.com/LakhveerChahal/ng-recaptcha/commit/736c7ae))
- **component:** allow to specify a base url for loading recaptcha ([df505fd](https://github.com/LakhveerChahal/ng-recaptcha/commit/df505fd)), closes [#101](https://github.com/LakhveerChahal/ng-recaptcha/issues/101)
- **component:** change component and directive selectors ([58a01b4](https://github.com/LakhveerChahal/ng-recaptcha/commit/58a01b4))
- **component:** load recaptcha script using code compatible with trusted types ([88d257b](https://github.com/LakhveerChahal/ng-recaptcha/commit/88d257b)), closes [#304](https://github.com/LakhveerChahal/ng-recaptcha/issues/304)
- **component:** make Angular 10.0.0 a supported peer dependency ([3d7756b](https://github.com/LakhveerChahal/ng-recaptcha/commit/3d7756b)), closes [#177](https://github.com/LakhveerChahal/ng-recaptcha/issues/177)
- **component:** make Angular 8.0.0 a supported peer dependency ([f003ff2](https://github.com/LakhveerChahal/ng-recaptcha/commit/f003ff2))
- **component:** make Angular 9.0.0 a supported peer dependency ([98edce6](https://github.com/LakhveerChahal/ng-recaptcha/commit/98edce6)), closes [#168](https://github.com/LakhveerChahal/ng-recaptcha/issues/168)
- **component:** remove deprecated `forRoot` method ([514beaf](https://github.com/LakhveerChahal/ng-recaptcha/commit/514beaf))
- **misc:** Annotating a static field with nocollapse so that we doesn't have issues closure compiler in advanced mode. ([55e5932](https://github.com/LakhveerChahal/ng-recaptcha/commit/55e5932))
- **module:** change the way recaptcha modules work ([6e13389](https://github.com/LakhveerChahal/ng-recaptcha/commit/6e13389))
- **module:** skip `forRoot()` when importing `RecaptchaModule` ([7fb97fb](https://github.com/LakhveerChahal/ng-recaptcha/commit/7fb97fb)), closes [#113](https://github.com/LakhveerChahal/ng-recaptcha/issues/113) [#116](https://github.com/LakhveerChahal/ng-recaptcha/issues/116)
- **package management:** add `[@types](https://github.com/types)/grecaptcha` as optional dependency ([85fbfba](https://github.com/LakhveerChahal/ng-recaptcha/commit/85fbfba))
- **package:** add Angular 12 support ([a212a21](https://github.com/LakhveerChahal/ng-recaptcha/commit/a212a21))
- **package:** add Angular 14 support ([eac6858](https://github.com/LakhveerChahal/ng-recaptcha/commit/eac6858))
- **package:** add Angular 15 support ([6c62634](https://github.com/LakhveerChahal/ng-recaptcha/commit/6c62634)), closes [#275](https://github.com/LakhveerChahal/ng-recaptcha/issues/275)
- **package:** add Angular 16 support ([77a7d1f](https://github.com/LakhveerChahal/ng-recaptcha/commit/77a7d1f)), closes [#288](https://github.com/LakhveerChahal/ng-recaptcha/issues/288)
- **package:** add Angular 17 support ([83714aa](https://github.com/LakhveerChahal/ng-recaptcha/commit/83714aa)), closes [#310](https://github.com/LakhveerChahal/ng-recaptcha/issues/310)
- **package:** implement Angular Package format ([71340c4](https://github.com/LakhveerChahal/ng-recaptcha/commit/71340c4))
- **package:** update `"[@types](https://github.com/types)/grecaptcha"` optional dependency version to ^3 ([e1ee7b9](https://github.com/LakhveerChahal/ng-recaptcha/commit/e1ee7b9))
- **package:** update peer dependencies to include Angular 7 ([929ef7a](https://github.com/LakhveerChahal/ng-recaptcha/commit/929ef7a))
- **package:** update peer dependencies to include Angular v4 ([b2f04e8](https://github.com/LakhveerChahal/ng-recaptcha/commit/b2f04e8))
- **package:** upgrade to Angular 13 ([af08641](https://github.com/LakhveerChahal/ng-recaptcha/commit/af08641)), closes [#245](https://github.com/LakhveerChahal/ng-recaptcha/issues/245)

### BREAKING CHANGES

- **package:** - Angular v16 is no longer supported with this version. Pin `ng-recaptcha` to `v12.x.x` to retain support for a previous Angular version
- **package:** - Angular v15 is no longer supported with this version. Pin `ng-recaptcha` to `v11.x.x` to retain support for a previous Angular version
- **component:** Support for previous versions of Angular has been dropped. Starting from v7 only one version of Angular will be supported.
- **component:** The `RecaptchaModule.forRoot()` method has been obsolete since v4.1.0 (since it has no longer been required). It is now removed. To migrate your code, simply use `RecaptchaModule` where you previously used `RecaptchaModule.forRoot()`
- **package:** \* `ng-recaptcha/forms` entry point has been removed. `RecaptchaFormsModule` and `RecaptchaValueAccessorDirective` should now be imported directly from `ng-recaptcha`
- `tslib` is now a package dependency to ensure minimum possible bundle size. If your project doesn't yet have a dependency on `tslib`, run `npm install -D tslib@^1.9.0` (or `yarn add -D tslib@^1.9.0` if you use yarn)
- **component:** The peer dependency for `@angular/core` has been bumped to `^6.0.0`
- **component:**
- **component:** component selector changed from `recaptcha` to `re-captcha`
- **module:** module handling has changed.
  Users of `RecaptchaNoFormsModule` should instead use `import { RecaptchaModule } from 'ng-recaptcha'`. Users of v1 `RecaptchaModule` should also `import { RecaptchaFormsModule } from 'ng-recaptcha/forms'`. SystemJS users must also re-setup module "main" file to `index.js`

<a name="13.2.1"></a>

## [13.2.1](https://github.com/DethAriel/ng-recaptcha/compare/v13.2.0...v13.2.1) (2023-11-25)

### Bug Fixes

- **component:** fix the injection error when using slandalone `RecaptchaV3Module` ([c93b99c](https://github.com/DethAriel/ng-recaptcha/commit/c93b99c))

<a name="13.2.0"></a>

# [13.2.0](https://github.com/DethAriel/ng-recaptcha/compare/v13.1.0...v13.2.0) (2023-11-25)

### Features

- **component:** add a new `RECAPTCHA_LOADER_OPTIONS` injection token as a way of manipulating script load parameters (such as base URL, language, trusted types, WAF, etc) ([b3c7213](https://github.com/DethAriel/ng-recaptcha/commit/b3c7213))

<a name="13.1.0"></a>

# [13.1.0](https://github.com/DethAriel/ng-recaptcha/compare/v13.0.0...v13.1.0) (2023-11-24)

### Features

- **component:** load recaptcha script using code compatible with trusted types ([88d257b](https://github.com/DethAriel/ng-recaptcha/commit/88d257b)), closes [#304](https://github.com/DethAriel/ng-recaptcha/issues/304)

<a name="13.0.0"></a>

# [13.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v12.0.2...v13.0.0) (2023-11-23)

### Features

- **package:** add Angular 17 support ([83714aa](https://github.com/DethAriel/ng-recaptcha/commit/83714aa)), closes [#310](https://github.com/DethAriel/ng-recaptcha/issues/310)

### BREAKING CHANGES

- **package:** - Angular v16 is no longer supported with this version. Pin `ng-recaptcha` to `v12.x.x` to retain support for a previous Angular version

<a name="12.0.2"></a>

## [12.0.2](https://github.com/DethAriel/ng-recaptcha/compare/v12.0.1...v12.0.2) (2023-07-31)

### Bug Fixes

- **component:** set CSP nonce as attribute ([abcb9a6](https://github.com/DethAriel/ng-recaptcha/commit/abcb9a6))

<a name="12.0.1"></a>

## [12.0.1](https://github.com/DethAriel/ng-recaptcha/compare/v12.0.0...v12.0.1) (2023-05-24)

### Bug Fixes

- **package:** convert the `README.md` file back to a proper symlink ([e0c5c99](https://github.com/DethAriel/ng-recaptcha/commit/e0c5c99))

<a name="12.0.0"></a>

# [12.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v11.0.0...v12.0.0) (2023-05-24)

### Features

- **package:** add Angular 16 support ([77a7d1f](https://github.com/DethAriel/ng-recaptcha/commit/77a7d1f)), closes [#288](https://github.com/DethAriel/ng-recaptcha/issues/288)

### BREAKING CHANGES

- **package:** - Angular v15 is no longer supported with this version. Pin `ng-recaptcha` to `v11.x.x` to retain support for a previous Angular version

<a name="11.0.0"></a>

# [11.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v10.0.0...v11.0.0) (2022-11-30)

### Features

- **component:** _deprecate_ `error` output in favor of `errored` ([6b002bb](https://github.com/DethAriel/ng-recaptcha/commit/6b002bb))
- **package:** add Angular 15 support ([6c62634](https://github.com/DethAriel/ng-recaptcha/commit/6c62634)), closes [#275](https://github.com/DethAriel/ng-recaptcha/issues/275)

<a name="10.0.0"></a>

# [10.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v9.0.0...v10.0.0) (2022-06-25)

### Features

- **package:** add Angular 14 support ([eac6858](https://github.com/DethAriel/ng-recaptcha/commit/eac6858))

<a name="9.0.0"></a>

# [9.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v7.0.2...v9.0.0) (2021-11-16)

### Features

- **package:** upgrade to Angular 13 ([af08641](https://github.com/DethAriel/ng-recaptcha/commit/af08641)), closes [#245](https://github.com/DethAriel/ng-recaptcha/issues/245)

<a name="8.0.1"></a>

## [8.0.1](https://github.com/DethAriel/ng-recaptcha/compare/v8.0.0...v8.0.1) (2021-07-22)

### Bug Fixes

- **component:** reset form-bound captcha value after component destruction ([0e550c4](https://github.com/DethAriel/ng-recaptcha/commit/0e550c4)), closes [#201](https://github.com/DethAriel/ng-recaptcha/issues/201)

<a name="8.0.0"></a>

# [8.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v7.0.1...v8.0.0) (2021-05-14)

### Features

- **package:** add Angular 12 support ([a212a21](https://github.com/DethAriel/ng-recaptcha/commit/a212a21))

<a name="7.0.2"></a>

## [7.0.2](https://github.com/DethAriel/ng-recaptcha/compare/v7.0.1...v7.0.2) (2021-07-22)

### Bug Fixes

- **component:** reset form-bound captcha value after component destruction ([9e5c5e7](https://github.com/DethAriel/ng-recaptcha/commit/9e5c5e7)), closes [#201](https://github.com/DethAriel/ng-recaptcha/issues/201)

<a name="7.0.1"></a>

## [7.0.1](https://github.com/DethAriel/ng-recaptcha/compare/v7.0.0...v7.0.1) (2021-01-07)

### Bug Fixes

- **component:** fix component usages for Typescript strict mode ([a687d13](https://github.com/DethAriel/ng-recaptcha/commit/a687d13)), closes [#211](https://github.com/DethAriel/ng-recaptcha/issues/211)

<a name="7.0.0"></a>

# [7.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v6.1.0...v7.0.0) (2020-12-22)

### Bug Fixes

- **package:** make `@types/grecaptcha` a non-optional dependency ([bc5ad51](https://github.com/DethAriel/ng-recaptcha/commit/bc5ad51)), closes [#205](https://github.com/DethAriel/ng-recaptcha/issues/205)

### Features

- **component:** Add Angular 11 support ([918fe90](https://github.com/DethAriel/ng-recaptcha/commit/918fe90))
- **component:** remove deprecated `forRoot` method ([514beaf](https://github.com/DethAriel/ng-recaptcha/commit/514beaf))
- **package:** update `"@types/grecaptcha"` optional dependency version to ^3 ([e1ee7b9](https://github.com/DethAriel/ng-recaptcha/commit/e1ee7b9))

### BREAKING CHANGES

- **component:** Support for previous versions of Angular has been dropped. Starting from v7 only one version of Angular will be supported.
- **component:** The `RecaptchaModule.forRoot()` method has been obsolete since v4.1.0 (since it has no longer been required). It is now removed. To migrate your code, simply use `RecaptchaModule` where you previously used `RecaptchaModule.forRoot()`

<a name="6.1.0"></a>

# [6.1.0](https://github.com/DethAriel/ng-recaptcha/compare/v6.0.2...v6.1.0) (2020-12-01)

### Bug Fixes

- **component:** handle top-level `execute` errors for reCAPTCHA v3 ([c7d02ce](https://github.com/DethAriel/ng-recaptcha/commit/c7d02ce)), closes [#194](https://github.com/DethAriel/ng-recaptcha/issues/194)
- **component:** mark `forRoot()` method as deprecated ([dea31e5](https://github.com/DethAriel/ng-recaptcha/commit/dea31e5))

### Features

- **component:** add the ability to handle reCAPTCHA errors ([80c9e6e](https://github.com/DethAriel/ng-recaptcha/commit/80c9e6e)), closes [#199](https://github.com/DethAriel/ng-recaptcha/issues/199)

<a name="6.0.2"></a>

## [6.0.2](https://github.com/DethAriel/ng-recaptcha/compare/v6.0.1...v6.0.2) (2020-09-14)

### Bug Fixes

- **component:** fix custom languages for reCAPTCHA v3 ([a2b145d](https://github.com/DethAriel/ng-recaptcha/commit/a2b145d)), closes [#174](https://github.com/DethAriel/ng-recaptcha/issues/174)
- **component:** improve reCAPTCHA v2 and v3 interoperability ([79fc85b](https://github.com/DethAriel/ng-recaptcha/commit/79fc85b)), closes [#152](https://github.com/DethAriel/ng-recaptcha/issues/152)

<a name="6.0.1"></a>

## [6.0.1](https://github.com/DethAriel/ng-recaptcha/compare/v6.0.0...v6.0.1) (2020-09-12)

### Bug Fixes

- **component:** catch and propagate grecaptcha errors, closes [#175](https://github.com/DethAriel/ng-recaptcha/issues/175) ([075edd0](https://github.com/DethAriel/ng-recaptcha/commit/075edd0))

<a name="6.0.0"></a>

# [6.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v5.0.0...v6.0.0) (2020-09-10)

### Features

- **component:** make Angular 10.0.0 a supported peer dependency ([3d7756b](https://github.com/DethAriel/ng-recaptcha/commit/3d7756b)), closes [#177](https://github.com/DethAriel/ng-recaptcha/issues/177)
- **component:** make Angular 9.0.0 a supported peer dependency ([98edce6](https://github.com/DethAriel/ng-recaptcha/commit/98edce6)), closes [#168](https://github.com/DethAriel/ng-recaptcha/issues/168)

<a name="5.0.0"></a>

# [5.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v4.3.0...v5.0.0) (2019-08-09)

### Features

- **component:** make Angular 8.0.0 a supported peer dependency ([f003ff2](https://github.com/DethAriel/ng-recaptcha/commit/f003ff2))
- **package:** implement Angular Package format ([71340c4](https://github.com/DethAriel/ng-recaptcha/commit/71340c4))

### BREAKING CHANGES

- **package:** \* `ng-recaptcha/forms` entry point has been removed. `RecaptchaFormsModule` and `RecaptchaValueAccessorDirective` should now be imported directly from `ng-recaptcha`
- `tslib` is now a package dependency to ensure minimum possible bundle size. If your project doesn't yet have a dependency on `tslib`, run `npm install -D tslib@^1.9.0` (or `yarn add -D tslib@^1.9.0` if you use yarn)

<a name="4.3.0"></a>

# [4.3.0](https://github.com/DethAriel/ng-recaptcha/compare/v4.3.0-beta.1...v4.3.0) (2019-06-04)

### Bug Fixes

- **component-v3:** fix a potential metadata error in v3 service ([ed885b5](https://github.com/DethAriel/ng-recaptcha/commit/ed885b5))

<a name="4.3.0-beta.1"></a>

# [4.3.0-beta.1](https://github.com/DethAriel/ng-recaptcha/compare/v4.2.1...v4.3.0-beta.1) (2019-02-08)

### Features

- **component:** add support for reCAPTCHA v3 ([4a083c6](https://github.com/DethAriel/ng-recaptcha/commit/4a083c6)), closes [#129](https://github.com/DethAriel/ng-recaptcha/issues/129)

<a name="4.2.1"></a>

## [4.2.1](https://github.com/DethAriel/ng-recaptcha/compare/v4.2.0...v4.2.1) (2018-10-24)

### Bug Fixes

- **package:** fix publishing empty package ([e4685fe](https://github.com/DethAriel/ng-recaptcha/commit/e4685fe))

<a name="4.2.0"></a>

# [4.2.0](https://github.com/DethAriel/ng-recaptcha/compare/v4.1.1...v4.2.0) (2018-10-24)

### Features

- **component:** add the ability to provide `nonce` to the script tag ([8f55b19](https://github.com/DethAriel/ng-recaptcha/commit/8f55b19)), closes [#100](https://github.com/DethAriel/ng-recaptcha/issues/100)
- **component:** allow to specify a base url for loading recaptcha ([df505fd](https://github.com/DethAriel/ng-recaptcha/commit/df505fd)), closes [#101](https://github.com/DethAriel/ng-recaptcha/issues/101)

<a name="4.1.1"></a>

## [4.1.1](https://github.com/DethAriel/ng-recaptcha/compare/v4.1.0...v4.1.1) (2018-10-24)

### Bug Fixes

- **component:** delay invisible recaptcha execution until it's rendered ([99292b7](https://github.com/DethAriel/ng-recaptcha/commit/99292b7)), closes [#127](https://github.com/DethAriel/ng-recaptcha/issues/127)

<a name="4.1.0"></a>

# [4.1.0](https://github.com/DethAriel/ng-recaptcha/compare/v4.0.0...v4.1.0) (2018-10-24)

### Bug Fixes

- **component:** fix a potential error during recaptcha rendering ([1c395b5](https://github.com/DethAriel/ng-recaptcha/commit/1c395b5))

### Features

- **module:** skip `forRoot()` when importing `RecaptchaModule` ([7fb97fb](https://github.com/DethAriel/ng-recaptcha/commit/7fb97fb)), closes [#113](https://github.com/DethAriel/ng-recaptcha/issues/113) [#116](https://github.com/DethAriel/ng-recaptcha/issues/116)
- **package:** update peer dependencies to include Angular 7 ([929ef7a](https://github.com/DethAriel/ng-recaptcha/commit/929ef7a))

<a name="4.0.0"></a>

# [4.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v4.0.0-beta.1...v4.0.0) (2018-09-29)

<a name="4.0.0-beta.1"></a>

# [4.0.0-beta.1](https://github.com/DethAriel/ng-recaptcha/compare/v3.0.5...v4.0.0-beta.1) (2018-05-17)

### Features

- **component:** adjust dependencies for Angular 6 support ([736c7ae](https://github.com/DethAriel/ng-recaptcha/commit/736c7ae))

### BREAKING CHANGES

- **component:** The peer dependency for `@angular/core` has been bumped to `^6.0.0`

<a name="3.0.5"></a>

## [3.0.5](https://github.com/DethAriel/ng-recaptcha/compare/v3.0.3...v3.0.5) (2018-04-27)

### Bug Fixes

- **rxjs:** change import of `of` operator ([3e0bda6](https://github.com/DethAriel/ng-recaptcha/commit/3e0bda6)), closes [#95](https://github.com/DethAriel/ng-recaptcha/issues/95)

<a name="3.0.3"></a>

## [3.0.3](https://github.com/DethAriel/ng-recaptcha/compare/v3.0.2...v3.0.3) (2017-12-26)

### Bug Fixes

- **component:** use ElementRef to access component's native element ([d3a8409](https://github.com/DethAriel/ng-recaptcha/commit/d3a8409)), closes [#48](https://github.com/DethAriel/ng-recaptcha/issues/48) [#68](https://github.com/DethAriel/ng-recaptcha/issues/68)

<a name="3.0.2"></a>

## [3.0.2](https://github.com/DethAriel/ng-recaptcha/compare/v3.0.1...v3.0.2) (2017-10-18)

### Bug Fixes

- **build:** fix AoT builds ([921be50](https://github.com/DethAriel/ng-recaptcha/commit/921be50)), closes [#57](https://github.com/DethAriel/ng-recaptcha/issues/57) [#65](https://github.com/DethAriel/ng-recaptcha/issues/65)

<a name="3.0.1"></a>

## [3.0.1](https://github.com/DethAriel/ng-recaptcha/compare/v3.0.0...v3.0.1) (2017-09-29)

### Bug Fixes

- **component:** Replace `OpaqueToken` with `InjectionToken` ([2b7db9b](https://github.com/DethAriel/ng-recaptcha/commit/2b7db9b))

<a name="3.0.0"></a>

# [3.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v2.2.0...v3.0.0) (2017-08-30)

### Bug Fixes

- **component:** fix server-side rendering ([7a5bc6c](https://github.com/DethAriel/ng-recaptcha/commit/7a5bc6c)), closes [#34](https://github.com/DethAriel/ng-recaptcha/issues/34)

### BREAKING CHANGES

- **component:** Angular v2.x.x is no longer supported due to dependency on Platform capabilities that were added in [v4.0.0-rc.1](https://github.com/angular/angular/blob/master/CHANGELOG.md#features-20)

<a name="2.2.0"></a>

# [2.2.0](https://github.com/DethAriel/ng-recaptcha/compare/v2.1.1...v2.2.0) (2017-08-18)

### Bug Fixes

- **component:** ensure that component is destroyed safely ([1e51d56](https://github.com/DethAriel/ng-recaptcha/commit/1e51d56)), closes [#46](https://github.com/DethAriel/ng-recaptcha/issues/46)

### Features

- **component:** add the ability to specify component props globally ([8a7b22d](https://github.com/DethAriel/ng-recaptcha/commit/8a7b22d)), closes [#45](https://github.com/DethAriel/ng-recaptcha/issues/45)

<a name="2.1.1"></a>

## [2.1.1](https://github.com/DethAriel/ng-recaptcha/compare/v2.1.0...v2.1.1) (2017-05-02)

### Bug Fixes

- **component:** unblock protractor tests after `<re-captcha>` destruction ([a5f2fe9](https://github.com/DethAriel/ng-recaptcha/commit/a5f2fe9))

<a name="2.1.0"></a>

# [2.1.0](https://github.com/DethAriel/ng-recaptcha/compare/v2.0.2...v2.1.0) (2017-05-01)

### Features

- **component:** add support for `badge` property ([5a16430](https://github.com/DethAriel/ng-recaptcha/commit/5a16430)), closes [#30](https://github.com/DethAriel/ng-recaptcha/issues/30)

### Bug Fixes

- **demo:** re-add a missing systemjs config file ([b51694a](https://github.com/DethAriel/ng-recaptcha/commit/b51694a))

<a name="2.0.2"></a>

## [2.0.2](https://github.com/DethAriel/ng-recaptcha/compare/v2.0.1...v2.0.2) (2017-03-26)

### Features

- **package:** update peer dependencies to include Angular v4 ([b2f04e8](https://github.com/DethAriel/ng-recaptcha/commit/b2f04e8))

<a name="2.0.1"></a>

## [2.0.1](https://github.com/DethAriel/ng-recaptcha/compare/v2.0.0...v2.0.1) (2017-03-17)

### Bug Fixes

- **module:** Adding the value accessor directive to the forms barrel, which was missing. ([ad73e2e](https://github.com/DethAriel/ng-recaptcha/commit/ad73e2e))

### Features

- **misc:** Annotating a static field with `@nocollapse` to avoid issues with closure compiler in advanced mode. ([55e5932](https://github.com/DethAriel/ng-recaptcha/commit/55e5932))

<a name="2.0.0"></a>

# [2.0.0](https://github.com/DethAriel/ng-recaptcha/compare/v1.7.0...v2.0.0) (2017-03-14)

### Features

- **component:** change component and directive selectors ([58a01b4](https://github.com/DethAriel/ng-recaptcha/commit/58a01b4))
- **module:** change the way recaptcha modules work ([6e13389](https://github.com/DethAriel/ng-recaptcha/commit/6e13389))

### BREAKING CHANGES

- component: component selector changed from `recaptcha` to `re-captcha`
- module: module handling has changed.
  Users of `RecaptchaNoFormsModule` should instead use `import { RecaptchaModule } from 'ng-recaptcha'`. Users of v1 `RecaptchaModule` should also `import { RecaptchaFormsModule } from 'ng-recaptcha/forms'`. SystemJS users must also re-setup module "main" file to `index.js`

<a name="1.7.0"></a>

# [1.7.0](https://github.com/DethAriel/ng2-recaptcha/compare/v1.6.1...v1.7.0) (2017-03-13)

### Bug Fixes

- **component:** handle id input parameter correctly ([b578fe5](https://github.com/DethAriel/ng2-recaptcha/commit/b578fe5))

### Features

- **component:** add `exportAs` annotation ([3e2e217](https://github.com/DethAriel/ng2-recaptcha/commit/3e2e217))
- **component:** add support for invisible reCAPTCHA ([c19489d](https://github.com/DethAriel/ng2-recaptcha/commit/c19489d)), closes [#18](https://github.com/DethAriel/ng2-recaptcha/issues/18)

<a name="1.6.1"></a>

## [1.6.1](https://github.com/DethAriel/ng2-recaptcha/compare/v1.6.0...v1.6.1) (2017-03-10)

### Enhancements

- **package:** expand wildcard exports to better support Google Closure Compiler ([8dd1a59](https://github.com/DethAriel/ng2-recaptcha/commit/8dd1a59))

<a name="1.6.0"></a>

# [1.6.0](https://github.com/DethAriel/ng2-recaptcha/compare/v1.5.4...v1.6.0) (2017-02-17)

### Features

- **package management:** add `[@types](https://github.com/types)/grecaptcha` as optional dependency ([85fbfba](https://github.com/DethAriel/ng2-recaptcha/commit/85fbfba))

<a name="1.5.4"></a>

## [1.5.4](https://github.com/DethAriel/ng2-recaptcha/compare/v1.5.3...v1.5.4) (2017-02-02)

### Bug Fixes

- **component:** correctly reset captcha during `ngOnDestroy` ([b31d57f](https://github.com/DethAriel/ng2-recaptcha/commit/b31d57f)), closes [#12](https://github.com/DethAriel/ng2-recaptcha/issues/12)

<a name="1.5.3"></a>

## [1.5.3](https://github.com/DethAriel/ng2-recaptcha/compare/v1.5.2...v1.5.3) (2017-02-01)

### Bug Fixes

- **component:** emit `resolved(null)` event when recaptcha expires ([491d99a](https://github.com/DethAriel/ng2-recaptcha/commit/491d99a)), closes [#11](https://github.com/DethAriel/ng2-recaptcha/issues/11)

<a name="1.5.2"></a>

## [1.5.2](https://github.com/DethAriel/ng2-recaptcha/compare/v1.5.1...v1.5.2) (2017-01-31)

### Bug Fixes

- **component:** reset the captcha when the component is destroyed ([e1441c8](https://github.com/DethAriel/ng2-recaptcha/commit/e1441c8)), closes [#10](https://github.com/DethAriel/ng2-recaptcha/issues/10)

<a name="1.5.1"></a>

## [1.5.1](https://github.com/DethAriel/ng2-recaptcha/compare/v1.5.0...v1.5.1) (2017-01-27)

<a name="1.5.0"></a>

# [1.5.0](https://github.com/DethAriel/ng2-recaptcha/compare/v1.4.0...v1.5.0) (2017-01-24)

### Bug Fixes

- **component:** correctly emit `resolved` event ([25d4246](https://github.com/DethAriel/ng2-recaptcha/commit/25d4246))

<a name="1.4.0"></a>

# [1.4.0](https://github.com/DethAriel/ng2-recaptcha/compare/v1.3.2...v1.4.0) (2016-10-28)

Added AoT compilation support
