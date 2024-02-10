## [2.0.0](https://github.com/ivangabriele/tsconfig/compare/v1.2.2...v2.0.0) (2024-02-10)


### ⚠ BREAKING CHANGES

* **peer-deps:** Require Next.js v14.
* **node:** Set module & moduleResolution to Node16 instead of ESNext & Node.
* **next:** Set moduleResolution to Bundler instead of Node.
* Enable noImplicitReturns compiler option.
* Remove ts-node config.
* Enable exactOptionalPropertyTypes compiler option.
* Enable verbatimModuleSyntax compiler option.
* Migrate to ESM.
* **semantic-release:** Require Typescript v5.
* **npm:** Require Node.js v20+.

### Features

* enable exactOptionalPropertyTypes compiler option ([86884af](https://github.com/ivangabriele/tsconfig/commit/86884afca39ac91867bc451153566cf96820b0d3))
* enable noImplicitReturns compiler option ([d63182b](https://github.com/ivangabriele/tsconfig/commit/d63182bc10dbfceaaae531c72b15410cc4037d42))
* enable verbatimModuleSyntax compiler option ([69a63b5](https://github.com/ivangabriele/tsconfig/commit/69a63b5a3feaf3928f2cfa256b320a9816ea34b8))
* **next:** set moduleResolution to Bundler instead of Node ([4c3b72b](https://github.com/ivangabriele/tsconfig/commit/4c3b72ba23426b9f93b210d4e32012f0abedfe5c))
* **node:** set module & moduleResolution to Node16 instead of ESNext & Node ([b2265ad](https://github.com/ivangabriele/tsconfig/commit/b2265ade02959a7ae32a683beaf8dd305b2d5e64))
* remove ts-node config ([f1f4ba0](https://github.com/ivangabriele/tsconfig/commit/f1f4ba0225b2ca6008de87f9e549307ad713dfad))


### Build System

* **dev-deps:** update all non-major dependencies ([#21](https://github.com/ivangabriele/tsconfig/issues/21)) ([39bc5f1](https://github.com/ivangabriele/tsconfig/commit/39bc5f1022b2401a6f67d2403283ddc753d2a2b2))
* **dev-deps:** update commitlint monorepo to v18 ([#24](https://github.com/ivangabriele/tsconfig/issues/24)) ([303d4bf](https://github.com/ivangabriele/tsconfig/commit/303d4bfb649111a0d22b405976a236d9aa1574cf))
* **dev-deps:** update dependency @ivangabriele/commitlint-config to v2 ([#28](https://github.com/ivangabriele/tsconfig/issues/28)) ([3131011](https://github.com/ivangabriele/tsconfig/commit/3131011908a9da3790e96a92435236b2eaf99887))
* **dev-deps:** update dependency @ivangabriele/prettier-config to v5 ([#29](https://github.com/ivangabriele/tsconfig/issues/29)) ([501eff9](https://github.com/ivangabriele/tsconfig/commit/501eff98da27e7afe5adf436ca7e4c9748785dec))
* **dev-deps:** update dependency husky to v9 ([#27](https://github.com/ivangabriele/tsconfig/issues/27)) ([d24b5e6](https://github.com/ivangabriele/tsconfig/commit/d24b5e6a27c5749a5cfa36ce60c0221aa3098039))
* **dev-deps:** update dependency prettier to v3 ([#22](https://github.com/ivangabriele/tsconfig/issues/22)) ([fa53812](https://github.com/ivangabriele/tsconfig/commit/fa538121528b1349af6bbecdff25f2d2d216c70e))
* migrate to ESM ([c8d45f6](https://github.com/ivangabriele/tsconfig/commit/c8d45f62182420fd19194e567b4b7c8d8c874cd0))
* **npm:** migrate to Node.js v20 ([25579b0](https://github.com/ivangabriele/tsconfig/commit/25579b098a5467e88417d9dac442ae152e7274ca))
* **peer-deps:** require Next.js v14 ([7d5b249](https://github.com/ivangabriele/tsconfig/commit/7d5b24923e588a68157fe8883d60c6c1797b0ba7))
* **yarn:** update lockfile ([43ca799](https://github.com/ivangabriele/tsconfig/commit/43ca7999ed22ddfe892a3933a681864b56774ae7))
* **yarn:** upgrade to v4 ([c4fad65](https://github.com/ivangabriele/tsconfig/commit/c4fad65e20e8bedde41caa84ffb97000803b1b77))


### Continuous Integration

* **semantic-release:** setup ([1f2d451](https://github.com/ivangabriele/tsconfig/commit/1f2d4511e811c0c2e0247bdf12bc119d7b3c568d))
