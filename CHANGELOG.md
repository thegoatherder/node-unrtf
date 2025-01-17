# Changelog

All notable changes to this project will be documented in this file.

## [2.0.0](https://www.github.com/Fdawgs/node-unrtf/compare/v1.1.1...v2.0.0) (2021-04-29)


### ⚠ BREAKING CHANGES

* remove support for nodejs v10, as it is EOL as of 2021-04-30

### Dependencies

* **deps:** bump actions/github-script from v3.1.0 to v3.1.1 ([eff3805](https://www.github.com/Fdawgs/node-unrtf/commit/eff380528a5ec8cdbd270a51824ac508be533557))


### Miscellaneous

* remove support for nodejs v10 ([2ae95c7](https://www.github.com/Fdawgs/node-unrtf/commit/2ae95c7d64e74019ce2f89dc89a5dfc9e53f4bb5))


### Documentation

* grammar and readability fixes ([35e9d0c](https://www.github.com/Fdawgs/node-unrtf/commit/35e9d0c88f8fcaed7c611251a8d27ed8dd97acee))


### Continuous Integration

* add cleanup-run job ([37eda95](https://www.github.com/Fdawgs/node-unrtf/commit/37eda951536b2a4373b5c3bd68a62130969c33b7))
* add nodejs v16 to unit test matrix ([eac6377](https://www.github.com/Fdawgs/node-unrtf/commit/eac63778c91030edaee86a0a2f02b617bb5c3b4e))
* do not run coveralls steps/jobs on forks ([cb9a6f8](https://www.github.com/Fdawgs/node-unrtf/commit/cb9a6f8d2d8fcb23d3f03b52f0ea3bcfe9b4fa35))
* **link-check:** fix skip regex ([be010ea](https://www.github.com/Fdawgs/node-unrtf/commit/be010ea51fa1942045ab20425ed4aca60411bd9b))
* **link-check:** ignore links to lib binaries ([822a03a](https://www.github.com/Fdawgs/node-unrtf/commit/822a03a03784162ddaf81f2b2e90173f45ef525a))

### [1.1.1](https://www.github.com/Fdawgs/node-unrtf/compare/v1.1.0...v1.1.1) (2021-03-29)


### Miscellaneous

* **husky:** move doc step to pre-commit hook ([bbca3e5](https://www.github.com/Fdawgs/node-unrtf/commit/bbca3e5a4101e391bd8a48062cab48444e4637aa))
* **index:** make version param optional ([3476ad0](https://www.github.com/Fdawgs/node-unrtf/commit/3476ad06099abb55ab1895797016baaeeb513979))
* **prettierignore:** add `api.md` ([15ec35e](https://www.github.com/Fdawgs/node-unrtf/commit/15ec35ef6eb2263196cd133b0fac2aaa2a66d264))


### Dependencies

* **deps-dev:** bump husky from 4.3.8 to 6.0.0 ([3832a5b](https://www.github.com/Fdawgs/node-unrtf/commit/3832a5ba4fcb6d24ec8a76641e5000cb6926beec))
* **deps:** bump GoogleCloudPlatform/release-please-action ([387d34b](https://www.github.com/Fdawgs/node-unrtf/commit/387d34b4c41a1db2a29be1a382ba67d3531c7f89))
* **deps:** bump typoci/spellcheck-action from v0.3.0 to v0.4.0 ([13fd1b3](https://www.github.com/Fdawgs/node-unrtf/commit/13fd1b3c2dbcc59e500a8d5b2140c06ff2aa4def))


### Continuous Integration

* **automerge:** move automerge job into new workflow ([1f6c64c](https://www.github.com/Fdawgs/node-unrtf/commit/1f6c64c39ef0f8a58472ce49f6054575ca88c37b))
* **ci:** ignore dependabot prs for commit message linting ([4db8bdc](https://www.github.com/Fdawgs/node-unrtf/commit/4db8bdc0459c247d3f7adb9baf803c95b808ca1a))
* **stale:** shorten workflow name ([84f86ae](https://www.github.com/Fdawgs/node-unrtf/commit/84f86aed55f86388f5a0aa10c6190fdd2b24793a))
* **workflows:** run only on push and pulls to master branch ([d993574](https://www.github.com/Fdawgs/node-unrtf/commit/d99357417fff0f073a4569f0f686761a2ddfd8e0))

## [1.1.0](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.8...v1.1.0) (2021-03-08)


### Features

* **index:** add binary version checking for options ([3e91223](https://www.github.com/Fdawgs/node-unrtf/commit/3e91223aba763abd8be5d3775f2c0443cd24423b))


### Bug Fixes

* **index:** correct misspelling of `received` in error string ([cda01e6](https://www.github.com/Fdawgs/node-unrtf/commit/cda01e6f1a2e460dd9b86b9cd9438e2f3c5936f0))


### Continuous Integration

* **workflows:** move release steps into `cd` workflow ([#45](https://www.github.com/Fdawgs/node-unrtf/issues/45)) ([7713848](https://www.github.com/Fdawgs/node-unrtf/commit/7713848037ff066bca84665cc358328ba8681cca))


### Documentation

* **changelog:** add compare links ([8b51b55](https://www.github.com/Fdawgs/node-unrtf/commit/8b51b5529f3bc923987492ab9277750f674fe7a6))
* **changelog:** add h1 header ([ec72246](https://www.github.com/Fdawgs/node-unrtf/commit/ec7224681d629ce5d45faf526553a685d29aaf64))


### Miscellaneous

* **package:** move prettier config to separate file ([8a20a35](https://www.github.com/Fdawgs/node-unrtf/commit/8a20a35bb4582d2da9a121186885b83ab1e10dd4))
* **prettier:** create .prettierignore ([0fbe516](https://www.github.com/Fdawgs/node-unrtf/commit/0fbe5160ba88664869789cafb2db530734391fec))
* **workflows:** rename ci and perf sections ([7674345](https://www.github.com/Fdawgs/node-unrtf/commit/7674345fd82c737413322164232d68f31874dbe0))


### Dependencies

* **deps:** add semver dependency ([a1e8467](https://www.github.com/Fdawgs/node-unrtf/commit/a1e8467f2b8768380fadfc504f920161b4fd90f1))
* **deps:** bump actions/stale from v3.0.17 to v3.0.18 ([0e95561](https://www.github.com/Fdawgs/node-unrtf/commit/0e95561bf0d796e4266037008ea394c0fcf39977))
* **deps:** bump fastify/github-action-merge-dependabot ([733272f](https://www.github.com/Fdawgs/node-unrtf/commit/733272f0e5d3288fbed109847f09a4a653dcfe3f))
* **deps:** bump GoogleCloudPlatform/release-please-action ([f5bfb06](https://www.github.com/Fdawgs/node-unrtf/commit/f5bfb0655c1a78027ef31045b8cc685d1dfc693b))
* **deps:** bump wagoid/commitlint-github-action from v3.0.1 to v3.0.6 ([fa23fec](https://www.github.com/Fdawgs/node-unrtf/commit/fa23fec20eab9aafad9e5e17eb2b19f8b16011f6))

### [1.0.8](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.7...v1.0.8) (2021-03-02)

### Documentation

-   bump coc from v1.4.0 to v2.0.0 ([3f1a367](https://www.github.com/Fdawgs/node-unrtf/commit/3f1a36790321cd9d95ef4c7d3cc4d846b40cac1f))
-   **contributing:** add documentation style ([17b373b](https://www.github.com/Fdawgs/node-unrtf/commit/17b373b54dd75f2b72f1c2585ef9025fb9f4254d))
-   **readme:** fix broken link ([a0d360f](https://www.github.com/Fdawgs/node-unrtf/commit/a0d360fa8c7e495b6cc5164a2417d74b532098cd))
-   **readme:** grammar ([68aba60](https://www.github.com/Fdawgs/node-unrtf/commit/68aba60fe2400dbab646bca4a0c7c0018a9a1278))
-   **readme:** revamp intro section ([86edaa3](https://www.github.com/Fdawgs/node-unrtf/commit/86edaa3fd33309f4d684bf92a09022cda5bd4380))
-   **readme:** shorten links ([bb80196](https://www.github.com/Fdawgs/node-unrtf/commit/bb801961d63b4de98c1662185822a3f70e02ba2c))

### Dependencies

-   **dependabot:** set commit message prefix; lower pull limit ([26cac51](https://www.github.com/Fdawgs/node-unrtf/commit/26cac5147257b317c053e930284d4e4c34be8673))
-   **deps-dev:** add husky for git hook handling ([537497c](https://www.github.com/Fdawgs/node-unrtf/commit/537497c3bc112f2b2e3d6c9467235ea94c2cb8c1))
-   **deps-dev:** bump @commitlint/cli from 11.0.0 to 12.0.1 ([#41](https://www.github.com/Fdawgs/node-unrtf/issues/41)) ([9b2d9b4](https://www.github.com/Fdawgs/node-unrtf/commit/9b2d9b4bd5289caf24a9f988ea03b2b4719244f2))
-   **deps-dev:** bump @commitlint/config-conventional ([e1b6506](https://www.github.com/Fdawgs/node-unrtf/commit/e1b6506710a5d30b539cdf4cde15161251e325b7))
-   **deps-dev:** bump eslint-config-prettier from 7.2.0 to 8.1.0 ([cd7a091](https://www.github.com/Fdawgs/node-unrtf/commit/cd7a091622e740040a6915b0ee5b23f3b6be5c74))
-   **deps-dev:** bump eslint-plugin-jsdoc from 31.6.1 to 32.0.1 ([#37](https://www.github.com/Fdawgs/node-unrtf/issues/37)) ([5fa4c1f](https://www.github.com/Fdawgs/node-unrtf/commit/5fa4c1fb81d1cd990703fbe2d601ad9801a65824))
-   **deps-dev:** bump jsdoc-to-markdown from 6.0.1 to 7.0.0 ([#40](https://www.github.com/Fdawgs/node-unrtf/issues/40)) ([00306f0](https://www.github.com/Fdawgs/node-unrtf/commit/00306f0728251860f15ac9bb8b8e785d414663fc))
-   **deps-dev:** pin husky major version ([994c53b](https://www.github.com/Fdawgs/node-unrtf/commit/994c53b8ad4e5211998723c4293edb861b45bcad))
-   **deps-dev:** remove coveralls, replaced by github action ([d602daf](https://www.github.com/Fdawgs/node-unrtf/commit/d602daf8258389f54be800520989fdfd740e438a))
-   **deps-dev:** remove jsinspect ([ddb0e60](https://www.github.com/Fdawgs/node-unrtf/commit/ddb0e60a40c68d08f02f4ebb763d2f884d6ca42b))
-   **deps:** bump wagoid/commitlint-github-action from v2.0.3 to v2.2.3 ([eab0134](https://www.github.com/Fdawgs/node-unrtf/commit/eab01346c6e655a56ad14796a69511e673070f93))
-   **deps:** bump wagoid/commitlint-github-action from v2.2.3 to v3.0.1 ([4226100](https://www.github.com/Fdawgs/node-unrtf/commit/42261005af9c3df7f94b1cf33e7aa698f4de505c))
-   **deps:** specify minor and hotfix versions ([57bcbd1](https://www.github.com/Fdawgs/node-unrtf/commit/57bcbd19e299a461c46f6db48c166137be114675))

### Miscellaneous

-   add commit-lint job ([b2842b4](https://www.github.com/Fdawgs/node-unrtf/commit/b2842b4601d3a9a63feb90cccafa711041688871))
-   add commitlint husky `commit-msg` hook ([47b8438](https://www.github.com/Fdawgs/node-unrtf/commit/47b843828fc76dc6d2fdf08e3d82eaa6b475332a))
-   add link check workflow ([d56c153](https://www.github.com/Fdawgs/node-unrtf/commit/d56c1539a97831d47bfd89058c66ae9989331727))
-   add pull request template ([41593f5](https://www.github.com/Fdawgs/node-unrtf/commit/41593f5b02a9a5147fd020d64844798653d1a382))
-   automate release and changelog generation ([84113f7](https://www.github.com/Fdawgs/node-unrtf/commit/84113f718879320e4a7b3b4fec791c7d25640a88))
-   capitalise headings correctly ([3c302f8](https://www.github.com/Fdawgs/node-unrtf/commit/3c302f890cf60e07d66be9ce81d816272832d936))
-   **ci:** capitalise jobs and job step names ([e4fb8d1](https://www.github.com/Fdawgs/node-unrtf/commit/e4fb8d1be1f20fd56c91ca46ce25746958a353d2))
-   **codeql:** remove autobuild action ([27d7e86](https://www.github.com/Fdawgs/node-unrtf/commit/27d7e8665e868aed22ee1649a8d9a4c14d08e60e))
-   **dependabot:** ignore husky updates ([234088c](https://www.github.com/Fdawgs/node-unrtf/commit/234088cf875367eb36a7de71e00d67526b776021))
-   disable long running homebrew cleanup tasks ([812de48](https://www.github.com/Fdawgs/node-unrtf/commit/812de481769a4697f0b72bccd55cf28cce9c08b0))
-   **github-actions:** set `flag-name` for parallel coverage tests ([7dccf38](https://www.github.com/Fdawgs/node-unrtf/commit/7dccf38f1049a7b13aa41ba61ad79d9d17353a10))
-   **github-actions:** set semver for coverallsapp ([723b833](https://www.github.com/Fdawgs/node-unrtf/commit/723b83368798e4528674570e2d197211c62eb256))
-   ignore test wmf file ([550287f](https://www.github.com/Fdawgs/node-unrtf/commit/550287f72b0fcefa664fccb46dc387e33f3612d7))
-   **jest:** enable resetmocks option ([c7bb98c](https://www.github.com/Fdawgs/node-unrtf/commit/c7bb98cfd60d72410594ead53eb24421efe6f6bc))
-   **linkcheck:** extend ignored urls ([c8b7162](https://www.github.com/Fdawgs/node-unrtf/commit/c8b716299a2f72b21248ccb40ee837df43e85be5))
-   **lint-check:** compress patterns ([5f1d76c](https://www.github.com/Fdawgs/node-unrtf/commit/5f1d76cfee0fbf144b878df489fef6c4cf677a0c))
-   **readme:** add linebreaks between badges ([07af20d](https://www.github.com/Fdawgs/node-unrtf/commit/07af20d688a150de69813c9b61d8dbf596a32368))
-   **readme:** capitalise headings correctly ([ef91208](https://www.github.com/Fdawgs/node-unrtf/commit/ef9120895eaa5af667d2d35734720ba209f900ba))
-   **readme:** prettier badge shape ([ea67e5c](https://www.github.com/Fdawgs/node-unrtf/commit/ea67e5c457c27babe56496dff7ab9f87afc1520f))
-   remove cache actions as they use lock file ([c8ca340](https://www.github.com/Fdawgs/node-unrtf/commit/c8ca34057f5e91cf5d651e19d4074b2a33b6f034))
-   replace stalebot with github action ([2d9339b](https://www.github.com/Fdawgs/node-unrtf/commit/2d9339b3802e9457f3b030bf3086ff21bfe04ff5))
-   replace typo ci app with action ([8c5f4f9](https://www.github.com/Fdawgs/node-unrtf/commit/8c5f4f9e3e78effd7cd60430d703e1de87b0a4db))
-   revert linux os to `ubuntu-latest` from `20.04` ([cfe6b9f](https://www.github.com/Fdawgs/node-unrtf/commit/cfe6b9fc4faa56eddc197a99f9b508d3561f19ef))
-   **scripts:** rename `jest-coverage` to `jest:coverage` ([093e365](https://www.github.com/Fdawgs/node-unrtf/commit/093e365df746efe86fb6114b155ff9db52a485c4))
-   shorten husky pre-push script ([5e03f99](https://www.github.com/Fdawgs/node-unrtf/commit/5e03f99a37f166b0f36e7ea59d12415ef680ac26))
-   stop excess coverage files being generated ([15be36a](https://www.github.com/Fdawgs/node-unrtf/commit/15be36ae88c9b67f902e215a29ea51688eebe5d9))
-   **tests:** use apa header style for describe name params ([78eef74](https://www.github.com/Fdawgs/node-unrtf/commit/78eef74fe7fbe16f8b11b57592e804a02697f35b))
-   **vscode:** add `redhat.vscode-yaml` as recommended extension ([aeb9a16](https://www.github.com/Fdawgs/node-unrtf/commit/aeb9a168ad12e66f793a43bb0b6e1a035e10158e))
-   **vscode:** add `updateImportsOnFileMove` setting ([bcf3342](https://www.github.com/Fdawgs/node-unrtf/commit/bcf3342f05f202ed4d98a434e284ba9676072879))
-   **vscode:** add workspace settings and extensions ([0704d1d](https://www.github.com/Fdawgs/node-unrtf/commit/0704d1d4e0bff12e6ed229268ad93408df6a0927))
-   **vscode:** remove conflicting prettier ext setting ([cb2fe3d](https://www.github.com/Fdawgs/node-unrtf/commit/cb2fe3db555bb31af20790fba9b014ad46f17eaa))
-   **workflows:** fix release types to account for bots ([477dae4](https://www.github.com/Fdawgs/node-unrtf/commit/477dae4e6485ff6147595c4427557ca7d0432d95))
-   **workflows:** rename spellcheck workflow ([f8a2de7](https://www.github.com/Fdawgs/node-unrtf/commit/f8a2de727acff05772f604c3a9f3f1e9b7d219e3))
-   **workflows:** tidy node-version syntax ([5ff6186](https://www.github.com/Fdawgs/node-unrtf/commit/5ff61868b093b3d6df9c9f45d5fc13d4c31f638b))

### [1.0.7](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.6...v1.0.7) (2021-01-18)

-   build: add typoci config file ([673d667](https://github.com/Fdawgs/node-unrtf/commit/673d667))
-   build: remove `yarn` as package manager, revert to `npm` ([92bfa05](https://github.com/Fdawgs/node-unrtf/commit/92bfa05))
-   build(deps-dev): bump eslint-plugin-jsdoc from 30.7.13 to 31.0.7 (#26) ([3a385b0](https://github.com/Fdawgs/node-unrtf/commit/3a385b0)), closes [#26](https://github.com/Fdawgs/node-unrtf/issues/26)
-   fix: remove lockfile ([3f1f06f](https://github.com/Fdawgs/node-unrtf/commit/3f1f06f))
-   fix: script calls ([92c1d12](https://github.com/Fdawgs/node-unrtf/commit/92c1d12))
-   ci: ignore scripts on publish ([51bbc50](https://github.com/Fdawgs/node-unrtf/commit/51bbc50))
-   ci: remove redundant javascript dictionary ([5bb970f](https://github.com/Fdawgs/node-unrtf/commit/5bb970f))
-   ci(typo-ci): add `ydh` to list of excluded words ([ce0dd7d](https://github.com/Fdawgs/node-unrtf/commit/ce0dd7d))
-   chore(package): add homepage and bug urls ([0296e85](https://github.com/Fdawgs/node-unrtf/commit/0296e85))
-   docs: update contact email ([b1ab606](https://github.com/Fdawgs/node-unrtf/commit/b1ab606))
-   docs(contributing): update yarn link ([e1c4bc0](https://github.com/Fdawgs/node-unrtf/commit/e1c4bc0))

### [1.0.6](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.5...v1.0.6) (2021-01-03)

-   build(deps-dev): bump eslint from 7.16.0 to 7.17.0 (#23) ([906057f](https://github.com/Fdawgs/node-unrtf/commit/906057f)), closes [#23](https://github.com/Fdawgs/node-unrtf/issues/23)
-   build(deps-dev): bump eslint-plugin-jsdoc from 30.7.9 to 30.7.13 (#22) ([3a6a54c](https://github.com/Fdawgs/node-unrtf/commit/3a6a54c)), closes [#22](https://github.com/Fdawgs/node-unrtf/issues/22)
-   build(deps-dev): remove cross-env ([3fb81e4](https://github.com/Fdawgs/node-unrtf/commit/3fb81e4))
-   ci: refactor `codeql-analysis.yml` ([ed2cf30](https://github.com/Fdawgs/node-unrtf/commit/ed2cf30))
-   ci: use yarn cache of node dependencies if present ([fe7171a](https://github.com/Fdawgs/node-unrtf/commit/fe7171a))
-   ci(codeql): specify more query suites ([0bf1d99](https://github.com/Fdawgs/node-unrtf/commit/0bf1d99))
-   chore: remove old .env files from gitignore ([1fcc8dd](https://github.com/Fdawgs/node-unrtf/commit/1fcc8dd))
-   docs(readme): update examples ([22d5943](https://github.com/Fdawgs/node-unrtf/commit/22d5943))
-   test(index): function with no options param passed ([72c97af](https://github.com/Fdawgs/node-unrtf/commit/72c97af))
-   refactor(index): remove unused default branch ([aee6c76](https://github.com/Fdawgs/node-unrtf/commit/aee6c76))
-   style(ci): tidy job names ([78bc55e](https://github.com/Fdawgs/node-unrtf/commit/78bc55e))

### [1.0.5](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.4...v1.0.5) (2020-12-28)

-   build: update github-actions with dependabot ([e905020](https://github.com/Fdawgs/node-unrtf/commit/e905020))
-   build(deps-dev): bump cross-env from 7.0.2 to 7.0.3 ([3c99ec3](https://github.com/Fdawgs/node-unrtf/commit/3c99ec3))
-   build(deps-dev): bump eslint from 7.14.0 to 7.16.0 ([96b903f](https://github.com/Fdawgs/node-unrtf/commit/96b903f))
-   build(deps-dev): bump eslint-config-prettier from 6.15.0 to 7.1.0 ([a9c02e6](https://github.com/Fdawgs/node-unrtf/commit/a9c02e6))
-   build(deps-dev): bump eslint-plugin-jsdoc from 30.7.8 to 30.7.9 (#14) ([ff9c9d2](https://github.com/Fdawgs/node-unrtf/commit/ff9c9d2)), closes [#14](https://github.com/Fdawgs/node-unrtf/issues/14)
-   build(deps-dev): bump typescript from 4.1.2 to 4.1.3 (#16) ([372bd4b](https://github.com/Fdawgs/node-unrtf/commit/372bd4b)), closes [#16](https://github.com/Fdawgs/node-unrtf/issues/16)
-   build(deps-dev): remove eslint-plugin-json ([ae41058](https://github.com/Fdawgs/node-unrtf/commit/ae41058))
-   build(deps): bump fastify/github-action-merge-dependabot (#13) ([dbda5ae](https://github.com/Fdawgs/node-unrtf/commit/dbda5ae)), closes [#13](https://github.com/Fdawgs/node-unrtf/issues/13)
-   build(typescript): enable strict option ([4c5344a](https://github.com/Fdawgs/node-unrtf/commit/4c5344a))
-   docs(contributing): update prettier script ([c2df110](https://github.com/Fdawgs/node-unrtf/commit/c2df110))
-   docs(readme): remove abbreviation ([cca9eb4](https://github.com/Fdawgs/node-unrtf/commit/cca9eb4))
-   ci: add linting job; expand scope of jobs ([2abbfc1](https://github.com/Fdawgs/node-unrtf/commit/2abbfc1))
-   ci: automatically merge dependabot pull requests on pass build stage ([3c7b40a](https://github.com/Fdawgs/node-unrtf/commit/3c7b40a))
-   ci: bump actions/setup-node from v1 to v2 ([3ec3d8b](https://github.com/Fdawgs/node-unrtf/commit/3ec3d8b))
-   ci: freeze yarn lockfile on publish ([65135d6](https://github.com/Fdawgs/node-unrtf/commit/65135d6))
-   ci: merge unit test jobs ([4fe02c8](https://github.com/Fdawgs/node-unrtf/commit/4fe02c8))
-   ci: move dependency installs to correct step ([5bf2bd9](https://github.com/Fdawgs/node-unrtf/commit/5bf2bd9))
-   ci: require lint job on automerge ([ab41541](https://github.com/Fdawgs/node-unrtf/commit/ab41541))
-   style: use default prettier options for trailing commas and quotes ([c4f9fad](https://github.com/Fdawgs/node-unrtf/commit/c4f9fad))
-   fix(scripts): test script ([b5a59e0](https://github.com/Fdawgs/node-unrtf/commit/b5a59e0))
-   chore: add stale confg ([777a58e](https://github.com/Fdawgs/node-unrtf/commit/777a58e))
-   chore(scripts): rename test scripts ([e0cee9f](https://github.com/Fdawgs/node-unrtf/commit/e0cee9f))

### [1.0.4](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.3...v1.0.4) (2020-12-01)

-   build(deps-dev): bump dev dependencies ([25a4bb4](https://github.com/Fdawgs/node-unrtf/commit/25a4bb4))
-   chore: add security.md ([821352e](https://github.com/Fdawgs/node-unrtf/commit/821352e))
-   ci: add cd action to publish to npm ([709bef7](https://github.com/Fdawgs/node-unrtf/commit/709bef7))
-   ci: replace travis-ci with github actions ([70d23d8](https://github.com/Fdawgs/node-unrtf/commit/70d23d8))

### [1.0.3](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.2...v1.0.3) (2020-11-10)

-   build(deps-dev): bump dev dependencies ([2e96ea0](https://github.com/Fdawgs/node-unrtf/commit/2e96ea0))
-   fix(index): return promise objects ([863d9f7](https://github.com/Fdawgs/node-unrtf/commit/863d9f7))
-   docs(index): correct return jsdoc tag for parseoptions function ([59bb581](https://github.com/Fdawgs/node-unrtf/commit/59bb581))
-   refactor(index): concat invalid args provided into error object ([dd1084e](https://github.com/Fdawgs/node-unrtf/commit/dd1084e))
-   chore(index): rename const to reflect functionality ([a0624e9](https://github.com/Fdawgs/node-unrtf/commit/a0624e9))

### [1.0.2](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.1...v1.0.2) (2020-10-29)

-   build(deps-dev): bump dev dependencies ([79e05f9](https://github.com/Fdawgs/node-unrtf/commit/79e05f9))
-   docs: grammar and spelling fixes ([f5fb9e3](https://github.com/Fdawgs/node-unrtf/commit/f5fb9e3))
-   fix(index): check file exists before attempting to parse ([41daf30](https://github.com/Fdawgs/node-unrtf/commit/41daf30))

### [1.0.1](https://www.github.com/Fdawgs/node-unrtf/compare/v1.0.0...v1.0.1) (2020-10-27)

-   build(deps-dev): bump dev dependencies ([cf5cd8b](https://github.com/Fdawgs/node-unrtf/commit/cf5cd8b))
-   ci(travis): add npm deploy stage ([d194055](https://github.com/Fdawgs/node-unrtf/commit/d194055))
-   fix(index): catch empty file vars before unrtf parses them ([789afbd](https://github.com/Fdawgs/node-unrtf/commit/789afbd))

## [1.0.0](https://www.github.com/Fdawgs/node-unrtf/compare/v0.0.2...v1.0.0) (2020-10-26)

-   build(deps-dev): bump dev dependencies ([dd3f926](https://github.com/Fdawgs/node-unrtf/commit/dd3f926))
-   refactor(index): move optional option param for convert function to end ([02b95a9](https://github.com/Fdawgs/node-unrtf/commit/02b95a9))
-   chore(scripts): do not lint ts and tsx files ([f40b335](https://github.com/Fdawgs/node-unrtf/commit/f40b335))
-   feat(index): add typescript definitions ([e2203a6](https://github.com/Fdawgs/node-unrtf/commit/e2203a6))

### BREAKING CHANGE

-   `usage of convert(option, file) should be replaced with convert(file, option)`

### 0.0.2 (2020-10-21)

-   docs: add api docs and examples ([59f1fc3](https://github.com/Fdawgs/node-unrtf/commit/59f1fc3))
-   docs(index): add note to jsdoc tags about select options errors ([d1d9964](https://github.com/Fdawgs/node-unrtf/commit/d1d9964))
-   docs(index): clarify on required unrtf binary version ([2c74019](https://github.com/Fdawgs/node-unrtf/commit/2c74019))
-   docs(readme): add osx usage instructions ([2b64327](https://github.com/Fdawgs/node-unrtf/commit/2b64327))
-   tests: add more complex test rtf file ([20ed0c6](https://github.com/Fdawgs/node-unrtf/commit/20ed0c6))
-   tests(index): extend tests ([9386e78](https://github.com/Fdawgs/node-unrtf/commit/9386e78))
-   tests(index): remove broken vt test ([a7ac427](https://github.com/Fdawgs/node-unrtf/commit/a7ac427))
-   build(deps-dev): add is-html to test html responses ([c03e25d](https://github.com/Fdawgs/node-unrtf/commit/c03e25d))
-   ci(travis): add osx test stage ([53f9c34](https://github.com/Fdawgs/node-unrtf/commit/53f9c34))
-   chore: move travis file to root ([6158b29](https://github.com/Fdawgs/node-unrtf/commit/6158b29))
-   feat(index): add support for output for ps and wpml formats ([df88f2b](https://github.com/Fdawgs/node-unrtf/commit/df88f2b))
