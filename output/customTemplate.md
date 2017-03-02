<img width="300px" src="https://github.com/rafinskipg/git-changelog/raw/master/images/git-changelog-logo.png" />

# Custom Template

_This changelog is generated with a custom template_

## squeezy potatoe v0.0.1 ( Thu Mar 02 2017 16:18:32 GMT+0100 (CET) )


## Bug Fixes
  - fix error messages (ee5068bffdbb9c0e45c8ce9ce0c2f790440f19e3
  - Fix generation of logs (cddb2408fa3017be704acac51dabbba9f477a547
  - correctly get branch name from the command line (4baa075bd93f878ee708817f911fe89c102dec02
  - correctly detect when running under grunt on Windows (4205ea49a893e4d1807a39268739c13754d40cf2
  - fixed tests (2e60172a4666c70d27e66d15dad297b89fff9583
  - Stream didn't close properly (99f228cfa5cb26c46ef9e3b00171a5e3d38fd844
  - Github commit url (c186f2d877e7907305953610bcaaef331406178a
  - **checkpath**
    - add missing require('path') (e5dab826062bd22dd37c8c3d3c24a4d9b4701f6d)
  - **generate**
    - create path to file if it does not already exist (62f6210f6895bcf5f9984b26948178b1a93cbc9e)
  - **git log**
    - Ignores letter case (d4cff0a86c5ce46405f3c0dd03f9c49a7d620792, Closes: [#54](https://github.com/Treyone/git-changelog/issues/54))
  - **git tag**
    - get latest tag, regardless of branch for workflows that rely on git-flow releases (48800306fa5ac19b7e9a4c6d7f2f432ee8ae4d84)
  - **git_changelog_generate**
    - pass tag if it exists to gitReadLog (7c801927672792fc9a818653b74c78d77c7bff9e, Closes: [#5](https://github.com/Treyone/git-changelog/issues/5))
  - **nested lists**
    - nested list fix. Closes #9 (2285551810919bd4d8a749ae3ddd88f9cedcdd0e, Closes: [#9](https://github.com/Treyone/git-changelog/issues/9))
  - **options**
    - Use version_name instead of version (43fdac855bfd2f67a43acc93ecc8ef2e7a81f45c)    - use repo_url instead of url (346b39491923a49a3421f174a566b204d5fc7db9)
  - **package.json**
    - move q to dependancies since it is required to run (257119cf2bb6d8f341a5d65a2f47bcf803dff205)
  - **params**
    - Restores versionName in CLI (1d97f952bd5d37f67c1febdf161f4ce9b310eebf)
  - **provider**
    - Added provider option in the command (8f3b3fef0d123e4fd11ea79bb9552285befc6689)
  - **template**
    - Fixes missing space in version_name output in template (f494f4a93a3c4a245f706cfb65f735a5ccccb2ce, Closes: [#72](https://github.com/Treyone/git-changelog/issues/72))
  - **travis**
    - Removed 0.12 nodejs version, addd 7.3.0 (1819083690e70e0af28d0c155b6fa67cbeb1dfb3)



## Features
  - Show pull requests merged (65f5504ce8e92fa39ced7da308e471cc85f750b5
  - improve `git log` synthax command to use the branch name (4ce6128103ece64b44695ac196b457e63649229b
  - CLI option with git-changelog (50af9f0aeba14e88254aaf1bfd6433c4c6bc9fbe
  - Working on new API (121b99285d2a04f9159951fa0e3f849d0d618fef
  - **bootstrap**
    - creating initial structure (dea45d68ce9555e876680bf7c0778add2f367a30)
  - **grunt-plugin**
    - Commit for research purposes (5afbb7a95c9f0e985f78666e7e231967524a8928)    - Now it is ready to be a grunt plugin (6422e0552b30f6e94d11b03310a23c1342aa5965)
  - **options**
    - Added ignore tags option (95362e8b57a673e810ffe54ff3337de1ea5109a8)
  - **output**
    - added logo in printHeader (6b489450a90172dc57059d7fd55fb4c6110152b2)
  - **package**
    - Added global install so you can run via command (86eae3f013ace1c5c23afc32b2e8f878a69629f1)
  - **providers**
    - possiblity to override issue URL when using an external issue tracker (d831bb1a1e05fae8dd5f932e1f3b1ffef0c4f456)    - Add possibility to set providers in the options (14da6fee8aa8b1fcec198ea26812aa1871008438)
  - **template**
    - Load default template if no custom template is found (41d5128b922efe3ced883a37bb4e170410160f4f)



## Documentation
  - updating documentation with template info (70fb97742ea2182a9d25ca92d6eeab081b44cc63
  - Updated readme with the correct specification (ec2de4bf599dfc77c24c9b86ee9c0d86fe37e5b8
  - Updated options and tagging info (1ad3b6bedc6431b70e3a2e93e5967bad9a7830ee
  - added documentation for explaining the commit message (d516c2fb464072fc1f4c86ec71a910eeab3e830c
  - Added docs (e0ba50c0bb0b13e9b39a59b8f4dda96e86d55644
  - **readme**
    - Updated readme (2d7b17625b9783532ee9ba655651cf8d475aa4ce)    - Unuseful commit (4373f4726eedad6d450c8255f5e57036a3e5e223)    - fix link to the `.changelogrc` section (2975171d89e1823253399bbe87a184e9164e9799)    - Follow proper style in example commits (6fef01ba8a71bb5cd779ddb84f52b8f75296618d)    - Reorder contents (14e8a772c3a05c32bc9fba6f75565132025d4942)    - TOC (d6338ab45f6e45e5562e5e6f4f1db86f39ca458d)    - Added more information on the new specification (f984eedde6be5db804d0b6bf2e238ab2e7ca15fb)    - added more commit examples and npm versioning usage (51341b7aae082c6c1a1caaa77dfdbfdc2622a56f)    - add logo (1af36c9b0dad5cc0c2a321e3f280a89d76a8fb2b)    - Final readme Fixes #1 Closes #1 (e725d8f4bf477b517ca6185a75fdfa0aa660b3be, Closes: [#1](https://github.com/Treyone/git-changelog/issues/1))



## Refactor
  - Refactor branch name (8774b963fd5e15de1cc1066c91034f9b1d34c4bc
  - added debug messages and refactored some additional code (70e48caf330b7f76fdea474ce58bcf96cb11ccbc
  - modified the task using a factory pattern to improve testability (1a0f25d3d9bbedd029c810c4dd2d35419cbb9276
  - Removed ignore tags and updated documentation (cb17b55de2ba0b597147fe4ce15e6883feb82a88
  - removed deprecated options (7d05b632af6be3db2c00925b7cf28cd990c19a71
  - **delete**
    - deleted some files (b9c72f57c4920420fef8c486bfccf5798870e06b)
  - **docs**
    - Angular document commits (01e8c1ba4c29fcddcfc237f4e6185682b9ced67d)    - Added docs (0a1558458c46574c5b0e6ec3749668fad1c8647a)
  - **generate**
    - replace `#getStream` with `fse#createOutputStream` (2d252d89017a70008896497e36f03e9d2add2c97)
  - **lib**
    - simplify methods and refactor into separate files (7a3600bf9a5487cb26e3eb4b65ac774a68b6b91e)
  - **writechangelog**
    - method now returns a promise (69fa1b0b11a603683342a9e0626cb69550b92002)



## Style
  - **jshint**
    - Fixed style (217bdf588729e8dba5739bd6edb424523e48b001)
  - **message**
    - Added a message on the changelog for referencing the github (d20031a9dc6fd92cba205903b2fd9d25feae6ea7)



## Test
  - Tests fixed (b9edae3bfc64f2a8c2320f6f27326225bd586cc7
  - added test for .init(), .getPreviousTag(), getRepoUrl(), .log() and .warn() (fd099a858b44e67e28f4e18f07c520803f3ac55e
  - removed unnecessary debug setting (was using for "debugging") (83cd52b1e8b79dd6bff13dc0d2003e802f8e45e6
  - updated test to cover promise return from .generate() (c182ee47a4ec36a453420f8cc04358ec6e98e381
  - ensure changelog has default setting at the beginning of spec (31f81e262440aa10efafd90c74d98569df418795
  - changed spy on changelog.generate() to stub, to avoid polluting following tests (0aa35588cf944b2f84b842d66220d50e8f5d96a8
  - added test for .writeChageLog() and .organizeCommits() (b07f28e1e92bdf20be669596651b344d2f70855e
  - added default mocha options (595c8347fd4e2b697ceac247babe7ece7c90c4fa
  - added missing done() callback on .catch() (0da53e9c8ad8a967753ac06dc1c23302c7956017
  - added tests for tag option equals to false (1fc1e809dcca7d499f870c314d2860121fcb6bab
  - Added unit tests for commit parsing (504a61a715ed541feee4570810c2153ba8984420
  - **writechangelog**
    - updated test to reflect changes to method (b999948f2c38f5d002fa0dc535429a80acdf2d75)



## Chore
  - updated grunt contrib clean (e28c0c763b7953861c05bcbedf04c3d6d48f8243
  - Remove grunt from peer dependencies (f6111d31f0c70f8368d2a57ea708bf58990f6bfd
  - Updated jshint (1d5f6b1d471e9d48ac2b4c7c8b78e3e5a8021ff4
  - typos and grammar (5ae2ee52d1f096d375d077299047684eae2cd5e2
  - a couple of spelling corrections [ci skip] (1486a84537c5fd2d7997721820981c7949487af2
  - minor edits to README (481c6c80d49e5e11c72d8378976d5d3ee1d581d2
  - fixing lint errors (3a8e8d486a2b89b9f04d01200fe4f9f7851d0123
  - added chai-as-promise to handle methods that return promises (1d3842576839b763b28a777e96b061dbd4d01a80
  - updated travis config (d6a7ef945f600ec787b515486bd3abfa2f86a25b
  - stopped tracking test output files (1d12bccb9f7dce07ff45318304dc5ab82620b6f1
  - added istanbul configuration file (88c945e6d8ddddfe6ee3bdf808ae2c749b4eabf3
  - updated travis configuration for code climate (fbd651dd765a1ee26293dd03543e578181462e3f
  - fixed lint issues in tests (2edb019910a421cd94868397a0f5881e90af4ed5
  - add tests to lint task (1d789792143d2f68820c16426e772857e45ba181
  - add lint rules for mocha test (bbea9341acb37f729e7f83d59d784cb4ff7969e1
  - ignore files generated by tests (3ccbff47ee2dd655da95ea3a9b95cb156f8f6956
  - update dependencies (3036d8037f4af6aa34fb137037a9eb9d0ce34297
  - removed unused dependency (cdd9f0d5623f839eaaf646d4de0cf72816cf00af
  - fixed typo (081a8f963104711b5f15bb8468489ee13927e226
  - added commits fixture for tests (b7d16b682a8167cd4a90e59c4f511774f6572ce1
  - added missing development dependencies (e52e3ec6234db4cc9055c6e0abd5f32b587f67d6
  - adding missing newline at the end of file (da4b54920e1be490fb47a25906eece63229b0094
  - removed testing from grunt file (causing recursion issues during some tests) (8e94e8ac23e73709495cf0c6851fbaf1a84c0c9b
  - install mocha before travis scripts (9be62aaeb7d50959cff870e0cabb08277d1c512b
  - updated npm scripts and added debug (aa4f2a2d7b834484f65239ceccdf4f973dbe0cee
  - moved fixtures to the test folder (e59d429b032451f75ef986e2d1b3c63fb8672a1c
  - removed unused test/hacky.js (500fdf3c37e72c98f4809806e85926035eb46792
  - rename changelog.spec.js to match file being tested (417578507b39aeffe826922ad3eccfcc13ad6ed0
  - fixed lint errors (71a5eae2212e7abf87c97a569f8251a56b5474a6
  - added grunt coverage task (ef6cf2cf14b69fe4200eb0eeb9319fb4bcdffcc2
  - added node.js `0.12` to travis-ci config (24d9c58a0a4ea349709719c431ca9878a2f01bc4
  - Updated readme (fca6ecbac686661ece15acdb41d23e86011457f2
  - package json version 1.1.3 (9d6003868e352ae21383913f671bc091afc9d8c7
  - **cleanup**
    - remove unnecessary code [skip ci] (80dbe3ec7a28e7c20d99e89009856c70138350b0)    - remove `#getStream` and `#checkPath` (cd75ebc44e39242b7e9c8ef2363c86d3f1cabc0e)
  - **deps**
    - install fs-extra@0.18.4 (7c8e257b81f0daeba7e347d175583af1a7a9bfa0)
  - **images**
    - add logo in JPEG format (50338b9a8b5540e42273857448e803d8b85c689d)    - add logo in PNG format (bb5fbbdba7ef2b9466c185c12ef426d82fe25bcf)
  - **lint**
    - add missing semicolon (2888af4803f85da1afbb8c9832314f53cc4ca131)    - fix indentation (4cf9b6e69a1426d48f18da45614f8f01994707b7)    - have jshint ignore false positives (ed8e9df48720c42086186fa4219262a351bbc3e4)    - fixing jshint errors (987366f02517c9cfdb62264d0f6ea7d0b20d6634)
  - **package**
    - Package json version (990b8ea04ca04f3c907653b0fa89ae6ddd601092)
  - **package.json**
    - Added preversion script (b3f1e44a900b00bda1facaee5354ba1ff58166aa)
  - **release**
    - 1.1.0 codename(christmas-templates) (d7d37854f9bcf6a885be278d05bf78651d493b1d)    - 1.0.0 codename(magnificent-goldman) (6b836fbea9405727bfc6d8e83349ea5cf8965b05)    - 0.1.8 codename(furious-stallman) (b943231854ffd6cb0c5f32e5482cadd99c96f3e9)
  - **task**
    - cleanup unused requires (8a41d4e7b245b2698749279765bcef4748e18ac7)




---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>
