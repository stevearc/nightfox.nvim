# Changelog

## [4.0.0](https://github.com/stevearc/nightfox.nvim/compare/v3.6.1...v4.0.0) (2023-09-29)


### ⚠ BREAKING CHANGES

* **palette:** rework dayfox ([#285](https://github.com/stevearc/nightfox.nvim/issues/285))
* **treesitter:** `TS*` highlight groups are removed.
* **group:** `groups` options now takes options per style + `all`

### Features

* Add `NightfoxLoad` command with completion ([c1ba098](https://github.com/stevearc/nightfox.nvim/commit/c1ba0987f832fdc86035a74056df36ee93a9db73))
* Add `reset()` cmd to clear overrides and config ([5d2581a](https://github.com/stevearc/nightfox.nvim/commit/5d2581a71510c319d128a8b02a21181abc611202))
* Add base dayfox theme ([62b2500](https://github.com/stevearc/nightfox.nvim/commit/62b2500a187cfb2518ecd63eea04a343c16c7d3c))
* Add color override option to config ([1a61db5](https://github.com/stevearc/nightfox.nvim/commit/1a61db502fccdc72a03f41b604cee59d5b92b90b))
* Add colorscheme for lualine and lightline ([3909e17](https://github.com/stevearc/nightfox.nvim/commit/3909e177474459f8223ef6069e1e0b720011d5aa))
* add CurSearch highlight group ([#143](https://github.com/stevearc/nightfox.nvim/issues/143)) ([de12896](https://github.com/stevearc/nightfox.nvim/commit/de12896bc40461377adf9dfbabab89aad991f399))
* Add dayfox to extras ([069d15c](https://github.com/stevearc/nightfox.nvim/commit/069d15c0bebc4a4d81619dc7a374a0c117878c72))
* Add hardfox colorscheme ([1bb7947](https://github.com/stevearc/nightfox.nvim/commit/1bb79479ad52a263be11d6a59a2565ee55031bad))
* Add internal _colorscheme_load func ([d5a15a4](https://github.com/stevearc/nightfox.nvim/commit/d5a15a4eb28bdbcae54a54b73197a1ce8ec2fa38))
* Add inverse selection options to config ([2b3ee99](https://github.com/stevearc/nightfox.nvim/commit/2b3ee999e293933646f80855eb4f1b51fd496325)), closes [#31](https://github.com/stevearc/nightfox.nvim/issues/31)
* Add light boolean value to colors object ([bd3b11f](https://github.com/stevearc/nightfox.nvim/commit/bd3b11fd58a96b77551ec7a767f5827c7c2da435))
* Add name to color style ([c2a00bf](https://github.com/stevearc/nightfox.nvim/commit/c2a00bff72216c88b0ee59fc82ca424a6d9a0ba3))
* add new DiagnosticOk highlight ([#378](https://github.com/stevearc/nightfox.nvim/issues/378)) ([fe2fc7b](https://github.com/stevearc/nightfox.nvim/commit/fe2fc7b93d66349eff2c5baa6cec922ee3958f56))
* add new lsp semantic token highlight groups ([#318](https://github.com/stevearc/nightfox.nvim/issues/318)) ([a8044b0](https://github.com/stevearc/nightfox.nvim/commit/a8044b084e0114609ec2c59cc4fa94c709a457d4))
* Add nordfox colorscheme style ([175d7df](https://github.com/stevearc/nightfox.nvim/commit/175d7df35d4fcb11af26c5c45b857ec6e9dd0962))
* Add palefox ([ea4815b](https://github.com/stevearc/nightfox.nvim/commit/ea4815b7bc9f1099362cc98a42cecfa2b0d7f7c8))
* Add plugin support ([25651a7](https://github.com/stevearc/nightfox.nvim/commit/25651a7f10c3871d0bf330beed2064f4d9b4d778))
* Add randfox as a style option ([e2a53a7](https://github.com/stevearc/nightfox.nvim/commit/e2a53a7e0f2e893f81272efc96e9157ab6a19f2e))
* Add string style config option ([1462a29](https://github.com/stevearc/nightfox.nvim/commit/1462a298ae06f027669196c6055b1c31f88d4b9e))
* add support for ts-rainbow2 ([#301](https://github.com/stevearc/nightfox.nvim/issues/301)) ([97e66df](https://github.com/stevearc/nightfox.nvim/commit/97e66dfaaecdc81f1dd7da00f8d4a6033f3bf6b2))
* Add Telescope selection colors ([2466368](https://github.com/stevearc/nightfox.nvim/commit/2466368383f65985c5135d9022329129080f9314))
* Add terminal color options ([2e177d2](https://github.com/stevearc/nightfox.nvim/commit/2e177d21e0ca37affb94d04e29f96aad8581c58d))
* add vim/neovim test on ubuntu/macos/windows ([#320](https://github.com/stevearc/nightfox.nvim/issues/320)) ([8bb6713](https://github.com/stevearc/nightfox.nvim/commit/8bb6713c56458aae339575b205234d820ec2046a))
* Change TSField to blue ([13928d9](https://github.com/stevearc/nightfox.nvim/commit/13928d9db2cfea7f77cb13e654a8e3ef526b779c))
* **ci:** add github action to autogenerate extra files ([#327](https://github.com/stevearc/nightfox.nvim/issues/327)) ([727a0ea](https://github.com/stevearc/nightfox.nvim/commit/727a0ea9d2dde7f8cfd4ae0f2e5570c365638227))
* **color:** add WCAG AA contrast validation ([12e0ca7](https://github.com/stevearc/nightfox.nvim/commit/12e0ca70e978f58318e7f0279bb7b243ababbd49))
* **colors:** Add dawn and dusk colorschemes ([9762d29](https://github.com/stevearc/nightfox.nvim/commit/9762d2939e0fd35b98f9115eb61e206f167cb2c4))
* **colors:** Warn when style not found ([1d423fa](https://github.com/stevearc/nightfox.nvim/commit/1d423faa652907b3d9211ac1e44aee8adfbe210d))
* **compiler:** handle errors in compiled results ([#263](https://github.com/stevearc/nightfox.nvim/issues/263)) ([e6a0d98](https://github.com/stevearc/nightfox.nvim/commit/e6a0d98dc1b4751b4d999d3dffd87b1af4f4873e))
* **compiler:** write compile lua file if debug set ([f32eef4](https://github.com/stevearc/nightfox.nvim/commit/f32eef468a98e73d5a87daa8db873dd1a94e021e))
* **compile:** simplify cache check ([#268](https://github.com/stevearc/nightfox.nvim/issues/268)) ([e29a913](https://github.com/stevearc/nightfox.nvim/commit/e29a91388d5a90109bf7c268782cd2301b7f3ed1))
* **config:** Add missing syntax styles ([#129](https://github.com/stevearc/nightfox.nvim/issues/129)) ([a85405b](https://github.com/stevearc/nightfox.nvim/commit/a85405b775a0a6a197556545359af0e9bcb13691))
* **config:** Default module config option ([#239](https://github.com/stevearc/nightfox.nvim/issues/239)) ([0731d09](https://github.com/stevearc/nightfox.nvim/commit/0731d0980afead7a6fffd55334b6bbe396801ab1))
* **cvd:** support colorblind mode with daltonization ([#281](https://github.com/stevearc/nightfox.nvim/issues/281)) ([f093297](https://github.com/stevearc/nightfox.nvim/commit/f093297145e917f7ae4d0e09fc9c07ac40620361))
* **extra:** Add border colors to kitty conf ([#118](https://github.com/stevearc/nightfox.nvim/issues/118)) ([958cc9f](https://github.com/stevearc/nightfox.nvim/commit/958cc9f7cee333aec60e8dddb78e43043c6ace91))
* **extra:** Add Konsole extra module ([#96](https://github.com/stevearc/nightfox.nvim/issues/96)) ([ba29285](https://github.com/stevearc/nightfox.nvim/commit/ba29285dca9740609f05b9674e3de7708e2ecfc9))
* **extra:** Add url reference to extra templates ([07043e3](https://github.com/stevearc/nightfox.nvim/commit/07043e311947de9df2ec81c374d9aa2db350ebb5))
* **extra:** add zellij theme file ([789b302](https://github.com/stevearc/nightfox.nvim/commit/789b3029d5058e925436ac29eb0521aa4e042b36))
* **extras:** Add dawn and dusk fox extras ([9d8f9d5](https://github.com/stevearc/nightfox.nvim/commit/9d8f9d5c6caa98520ceb55cd3ac6ed89d16fc874))
* **extras:** Add fish config ([009b1f5](https://github.com/stevearc/nightfox.nvim/commit/009b1f54d0a5e771aa59ce3b3110ab92900f1db2))
* **extras:** Add kitty config ([edda71a](https://github.com/stevearc/nightfox.nvim/commit/edda71afa33eed69d1fbcc53cf802034302fc392))
* **extras:** Add tmux config ([1b4269a](https://github.com/stevearc/nightfox.nvim/commit/1b4269a3cb0342f5988ce09bd926ab1224378808))
* **extras:** Add wezterm config ([7d77e2d](https://github.com/stevearc/nightfox.nvim/commit/7d77e2da770ac55c9eb7e3e25ec81b35191e148b))
* **extras:** Add Xresources extras ([7750734](https://github.com/stevearc/nightfox.nvim/commit/775073486b9b13311c4aeceb53258256b1bcdb0b))
* **extras:** Generate base alacritty conf all styles ([ec5cc39](https://github.com/stevearc/nightfox.nvim/commit/ec5cc39a3cc37dfc2cfa37c24140819e92905b79))
* **extras:** Generate Iterm2 colorscheme ([8500494](https://github.com/stevearc/nightfox.nvim/commit/85004941357cca2f34096a8489a37a068206f092)), closes [#14](https://github.com/stevearc/nightfox.nvim/issues/14)
* **extra:** Update wezterm with retro tab ([#196](https://github.com/stevearc/nightfox.nvim/issues/196)) ([631abad](https://github.com/stevearc/nightfox.nvim/commit/631abad762e9afc7d0cf70b749b5994be5570400))
* fingerprint ([#254](https://github.com/stevearc/nightfox.nvim/issues/254)) ([de9b4c5](https://github.com/stevearc/nightfox.nvim/commit/de9b4c51039b2449db3fe4109eb96564b2efcf49))
* **groups:** Add `WinBar` highlight group ([#162](https://github.com/stevearc/nightfox.nvim/issues/162)) ([b37efa5](https://github.com/stevearc/nightfox.nvim/commit/b37efa583fe7edbf347a25ff5ce07514c9316c88))
* **module:** add alpha support ([4b73c9d](https://github.com/stevearc/nightfox.nvim/commit/4b73c9d0995eb1a43e284534b97a543ca21c5c77))
* **module:** Add dap-ui as a module ([#151](https://github.com/stevearc/nightfox.nvim/issues/151)) ([2bb5195](https://github.com/stevearc/nightfox.nvim/commit/2bb5195ced102508a0ac10048e8e5fef0a5617f3))
* **module:** add highlight support for nvim-navic ([#283](https://github.com/stevearc/nightfox.nvim/issues/283)) ([0f94892](https://github.com/stevearc/nightfox.nvim/commit/0f948925ec435f2fa115522a991ac84efed0045a))
* **module:** Add inlay hint for coc and lsp ([#205](https://github.com/stevearc/nightfox.nvim/issues/205)) ([e07db0f](https://github.com/stevearc/nightfox.nvim/commit/e07db0f668ab9678a2fc1a4c73c58115e202f52a))
* **module:** Add nvim-notify ([#122](https://github.com/stevearc/nightfox.nvim/issues/122)) ([2fd6871](https://github.com/stevearc/nightfox.nvim/commit/2fd687137adb9fd9dc46f2e9db2d0a4e53ce32b0))
* **module:** add signify support ([#279](https://github.com/stevearc/nightfox.nvim/issues/279)) ([07174bf](https://github.com/stevearc/nightfox.nvim/commit/07174bfe0ad15a4c25ef908872904edb09069e94))
* **module:** Implement all relevant neotree hl's ([242f9ab](https://github.com/stevearc/nightfox.nvim/commit/242f9ab0975cc6eba3ef949ef1cbba0ebdff1c6f))
* **modules:** add indent_blankline ([#347](https://github.com/stevearc/nightfox.nvim/issues/347)) ([5472a3e](https://github.com/stevearc/nightfox.nvim/commit/5472a3e2bae6f381b603cd7998fc131f8134755c))
* **modules:** Add modes.nvim support ([#80](https://github.com/stevearc/nightfox.nvim/issues/80)) ([b742de6](https://github.com/stevearc/nightfox.nvim/commit/b742de61587c8213e00426a12c1a44be3281d2bd))
* **modules:** Add module pounce support ([#94](https://github.com/stevearc/nightfox.nvim/issues/94)) ([fce6585](https://github.com/stevearc/nightfox.nvim/commit/fce658599bc11cca3e71063405ee09aeec2a92d1))
* Nightfox inital colors ([c4179cb](https://github.com/stevearc/nightfox.nvim/commit/c4179cb18bf22d02d5e5f20f145c722f958cc946))
* Nushell Extra Theme Config ([#298](https://github.com/stevearc/nightfox.nvim/issues/298)) ([23a678f](https://github.com/stevearc/nightfox.nvim/commit/23a678f47722801f70fe64df39a1fa29f6abf297))
* **nvim:** Add FocusedSymbol from symbols-outline ([3413370](https://github.com/stevearc/nightfox.nvim/commit/341337035a706091e12c30263b2d5577e6e0f895))
* **pallet:** Add initial terafox ([#102](https://github.com/stevearc/nightfox.nvim/issues/102)) ([140136d](https://github.com/stevearc/nightfox.nvim/commit/140136d7a5fe872ecbfe2a70bed3162e658a5c13))
* Reproducible configuration minimal_init file ([2a77c05](https://github.com/stevearc/nightfox.nvim/commit/2a77c05c5562cade6a50ce82e86691cec51e3a39))
* **semantic_tokens:** add injected highlights ([#321](https://github.com/stevearc/nightfox.nvim/issues/321)) ([3802464](https://github.com/stevearc/nightfox.nvim/commit/380246446a359f7faf2f0ccb865658ec0a295bd0))
* **semantic_tokens:** link default library to function builtin ([53cdaa5](https://github.com/stevearc/nightfox.nvim/commit/53cdaa583138698f4a0a4a9d2abaf761c8960407))
* support bit for lua 5.1 ([#267](https://github.com/stevearc/nightfox.nvim/issues/267)) ([0bb05da](https://github.com/stevearc/nightfox.nvim/commit/0bb05daa5f4741d38378591ef502cfec53bbe13d))
* Support lightline again ([#144](https://github.com/stevearc/nightfox.nvim/issues/144)) ([9cd98ed](https://github.com/stevearc/nightfox.nvim/commit/9cd98eded6dfd499e2c6b2e4bb9666bf6a83d73a))
* support Lightline for Vim ([#63](https://github.com/stevearc/nightfox.nvim/issues/63)) ([3b0483f](https://github.com/stevearc/nightfox.nvim/commit/3b0483f6440e4f72ae58a8e1730df518f00b70df))
* TablineSel rev bg/fg ([e2f9618](https://github.com/stevearc/nightfox.nvim/commit/e2f961859cbfb2ba38147dc59fdd2314992c8b62))
* **theme:** Add `LspCodeLens` hlgroup ([f8ac476](https://github.com/stevearc/nightfox.nvim/commit/f8ac4764f12dca3f1f608843423ac9d914d37994)), closes [#10](https://github.com/stevearc/nightfox.nvim/issues/10)
* **theme:** Add alt bg option for unfocused bufs ([47d48c6](https://github.com/stevearc/nightfox.nvim/commit/47d48c617148bd09387dac1bf38c227f7580be65))
* **theme:** Add color_delimiter option ([dc66ecd](https://github.com/stevearc/nightfox.nvim/commit/dc66ecd736948939d0f5eccb138a9d73d37efbf6))
* **theme:** Uri now ornage ([e4a590a](https://github.com/stevearc/nightfox.nvim/commit/e4a590a9cc39c4fb86e58077e7096a352fcc8547))
* **treesitter:** add checked and unchecked highlight ([#273](https://github.com/stevearc/nightfox.nvim/issues/273)) ([0903c48](https://github.com/stevearc/nightfox.nvim/commit/0903c4886535d97e6e62f710ab97119d2e09aa0b))
* Update tabline colors ([c73a7be](https://github.com/stevearc/nightfox.nvim/commit/c73a7be0dc0a696c37a68c7197cdafc852c9da0a))
* Update theme file with correct colors ([2130ed9](https://github.com/stevearc/nightfox.nvim/commit/2130ed93f6ca3b327ea153253968d463a90e6419))
* Update to latest treesitter highlight format ([6585499](https://github.com/stevearc/nightfox.nvim/commit/65854998c139822ef0a8874364840b3fe80ea624))
* warp themes ([#252](https://github.com/stevearc/nightfox.nvim/issues/252)) ([120629a](https://github.com/stevearc/nightfox.nvim/commit/120629a6f0df0288a070ebbbc7c51f99004f7df0))


### Bug Fixes

* [@property](https://github.com/property) is linking to the old TSField highlight group ([#219](https://github.com/stevearc/nightfox.nvim/issues/219)) ([a168b80](https://github.com/stevearc/nightfox.nvim/commit/a168b80af33d0200f324ec6d928b79fd0295bf95))
* `bg_alt` is correctly darkened ([bb5449a](https://github.com/stevearc/nightfox.nvim/commit/bb5449abe5805fcdb933d8785dbcf9096ff0ef60))
* `colors_name` is reflected in variant used ([9a42ede](https://github.com/stevearc/nightfox.nvim/commit/9a42ede26b82830b883670f00f2bc2d03895fc9b))
* Add missing tag highlight group links ([#220](https://github.com/stevearc/nightfox.nvim/issues/220)) ([28eeaae](https://github.com/stevearc/nightfox.nvim/commit/28eeaaea2e9fafc1c6b22eef6b9a6e2b53fa02a8))
* **autocmd:** Do autocmd `ColorScheme` after load ([483422c](https://github.com/stevearc/nightfox.nvim/commit/483422c4bc25781e376e0e09d81d6bfeb6a5dda9))
* Avoid nvim specific lua function ([3d8040f](https://github.com/stevearc/nightfox.nvim/commit/3d8040f0e61ebb55e25ec1bffabb382cb77c20f9))
* **cache:** append user setup filename to user stat ([#257](https://github.com/stevearc/nightfox.nvim/issues/257)) ([e70d2d6](https://github.com/stevearc/nightfox.nvim/commit/e70d2d61284eec26c3a00075c43ca2f425f9257a))
* **cache:** move setup guard before load call ([#331](https://github.com/stevearc/nightfox.nvim/issues/331)) ([88182d4](https://github.com/stevearc/nightfox.nvim/commit/88182d48373be8ff1933bfd5fabc4c4aa55bf726))
* Change NonText to the comment colour ([f653802](https://github.com/stevearc/nightfox.nvim/commit/f65380298326eeaafc4aafb52618e653a16f976a))
* Change rustTSField to use fg_alt ([925b9cf](https://github.com/stevearc/nightfox.nvim/commit/925b9cf360b5c57eae08275fafafe124a26663a7))
* Clear and reset syntax when colorscheme is sourced ([8afc1dc](https://github.com/stevearc/nightfox.nvim/commit/8afc1dc81d598c660a3195d1840f8210df4c26a2))
* Clear default cterm style for vim ([fdb987a](https://github.com/stevearc/nightfox.nvim/commit/fdb987ac64ced0ae64184da4c109de95764e5385))
* Clear highlight groups on colorscheme load ([f268cff](https://github.com/stevearc/nightfox.nvim/commit/f268cffa893f59da7b7837c5115c17e67719adc0))
* **cmd:** Clean compiled files when enabling interactive mode ([8473b3a](https://github.com/stevearc/nightfox.nvim/commit/8473b3a56df9c557c38a77ff14ebeca1d159b0f7))
* **color:** Darken bg of dayfox by very small % ([22f158c](https://github.com/stevearc/nightfox.nvim/commit/22f158ccf961ada2d5bad40684b88aefb91d39a4))
* **color:** Nightfox adds missing dim colors ([3664208](https://github.com/stevearc/nightfox.nvim/commit/366420894d9c087496a91647a6a6597a86760ebc))
* **color:** Nightfox dim colors norm to lower case ([efbda18](https://github.com/stevearc/nightfox.nvim/commit/efbda186463d0ab60c866a50d13c623b8f948056))
* colors.meta are correct values ([f92bd6f](https://github.com/stevearc/nightfox.nvim/commit/f92bd6fc0ff0688917f5f998dabd1e56b7020673))
* **colors:** Add green for Dawn and Dusk ([acfbb1f](https://github.com/stevearc/nightfox.nvim/commit/acfbb1f7f6db64856a56f8cfe9175e1ed8e5fdc0)), closes [#48](https://github.com/stevearc/nightfox.nvim/issues/48)
* **colors:** Remove override of black value ([f7dc36c](https://github.com/stevearc/nightfox.nvim/commit/f7dc36c93b925fb7252647483fa4bd573d5aaa7b))
* **compile:** `sp` option applies to nvim highlights ([#168](https://github.com/stevearc/nightfox.nvim/issues/168)) ([b85c5c3](https://github.com/stevearc/nightfox.nvim/commit/b85c5c3a0e3b309ffa7d0a6ca33e430c91532ba0))
* **compile:** Add missing required bit functions ([#269](https://github.com/stevearc/nightfox.nvim/issues/269)) ([c610099](https://github.com/stevearc/nightfox.nvim/commit/c610099cc65a8e29898d3cd524ebf2b73f86dda0))
* **compile:** bit error on aarch64 with hash func ([#270](https://github.com/stevearc/nightfox.nvim/issues/270)) ([ae7474e](https://github.com/stevearc/nightfox.nvim/commit/ae7474ea078cb76d81517d30bece4a5a41770ef0))
* **compile:** Compile checks if link is empty before link ([#161](https://github.com/stevearc/nightfox.nvim/issues/161)) ([289f3d8](https://github.com/stevearc/nightfox.nvim/commit/289f3d81a753155158b132b549b3f1fa788d3950))
* **compile:** correct call to set background for vim ([5aeb0e7](https://github.com/stevearc/nightfox.nvim/commit/5aeb0e730755b3007029b51dda094d4e0e6e9291))
* **compile:** Guard missing opts ([#134](https://github.com/stevearc/nightfox.nvim/issues/134)) ([a8f50dd](https://github.com/stevearc/nightfox.nvim/commit/a8f50dd814a0a77ef3ca69ec3ecd0604b37bbc3c))
* **compiler:** add file permission error ([#368](https://github.com/stevearc/nightfox.nvim/issues/368)) ([e886e39](https://github.com/stevearc/nightfox.nvim/commit/e886e39e592e89f316536a6f070365a9d88901c9))
* **compile:** Update compile files ([1554f82](https://github.com/stevearc/nightfox.nvim/commit/1554f82ad1cf84a5a2fe7ad35e92ff039731d06e))
* **config:** Config options now given correct table ([#246](https://github.com/stevearc/nightfox.nvim/issues/246)) ([c2a0494](https://github.com/stevearc/nightfox.nvim/commit/c2a0494480c9ad44f0fb31885f320a37cc09dbdd))
* **config:** Multi calls to `setup` correctly override ([3bbc821](https://github.com/stevearc/nightfox.nvim/commit/3bbc821246a5135ea226182fcaa8d793d5fb99da))
* **config:** Treesitter and lsp modules default only in nvim ([#225](https://github.com/stevearc/nightfox.nvim/issues/225)) ([6a4a819](https://github.com/stevearc/nightfox.nvim/commit/6a4a819fd129c8b41e1e3fccf63f77227ff19b02))
* Darken DiffText to make readable ([22a85fc](https://github.com/stevearc/nightfox.nvim/commit/22a85fcb3e025b667857bb2d1e6d26c7cddf5d83)), closes [#9](https://github.com/stevearc/nightfox.nvim/issues/9)
* **dawnfox:** Update `bg_search` and `bg_visual` ([79401a4](https://github.com/stevearc/nightfox.nvim/commit/79401a417518a889af65779c36e44a8f6917f07d))
* **dayfox:** Another round of darkening yellow ([4b5f2dd](https://github.com/stevearc/nightfox.nvim/commit/4b5f2dd7ae0fb6361ba8e492adee8fb5db1496d9))
* **dayfox:** Darken dayfox colors for readability ([2ad6982](https://github.com/stevearc/nightfox.nvim/commit/2ad6982736c1c5215ab39f72ea2e3e6c3a2d3bf9)), closes [#47](https://github.com/stevearc/nightfox.nvim/issues/47)
* **dayfox:** Slightly lighten background ([21935c2](https://github.com/stevearc/nightfox.nvim/commit/21935c25fe681d43e381d49b0a44c9298d204841))
* **debug:** Remove config reload when debug mode ([883dabe](https://github.com/stevearc/nightfox.nvim/commit/883dabe0418e4d32bb39830c3dec18207fe52eff))
* **duskfox:** Increase contrast for bright and dim ([46cd263](https://github.com/stevearc/nightfox.nvim/commit/46cd263e49b22d21062043853005311ccb93b8a9))
* **dustfox:** Update `bg_search` and `bg_visual` ([1a0fd49](https://github.com/stevearc/nightfox.nvim/commit/1a0fd498444f98318dc8dd7bb51d54d6b942bdf5))
* **editor:** Update TabLine and VertSplit ([f8d61de](https://github.com/stevearc/nightfox.nvim/commit/f8d61de2a097b08f06db4c757d07d154bccfdf60))
* **extra:** Add cursor and selection for windows term ([#150](https://github.com/stevearc/nightfox.nvim/issues/150)) ([25b3f3e](https://github.com/stevearc/nightfox.nvim/commit/25b3f3e46c87c51e4d8075d2e11f481628716363))
* **extra:** Kitty does not like trailing comments ([1fa9739](https://github.com/stevearc/nightfox.nvim/commit/1fa9739a2ee45f5a0048e18bac43f90d1edb77ed))
* **extras:** Extras use new color api ([9959531](https://github.com/stevearc/nightfox.nvim/commit/9959531b20f2c0b64a8d7a9adf39879eeb3c9a06))
* **extras:** Generate extras with correct colors ([6b5acb8](https://github.com/stevearc/nightfox.nvim/commit/6b5acb818d187d8bc75d7e9ddb68834315858a6e))
* **extras:** Remove debugging line from iterm ([6c33b6d](https://github.com/stevearc/nightfox.nvim/commit/6c33b6dbdd65d2ebddf5f9ece2847ccf7c7fecea))
* **extra:** switch from fg3 to fg2 for white ([e54427a](https://github.com/stevearc/nightfox.nvim/commit/e54427a1bfea55c9ab0c21ac7e9d07b22156d0f0))
* **extra:** Use correct keys for bg and fg ([#197](https://github.com/stevearc/nightfox.nvim/issues/197)) ([b47c9b0](https://github.com/stevearc/nightfox.nvim/commit/b47c9b09b693e8d362cf2d7134b857f4e5135d47))
* **extra:** zellij black and white set to bg3/fg3 ([#336](https://github.com/stevearc/nightfox.nvim/issues/336)) ([409d646](https://github.com/stevearc/nightfox.nvim/commit/409d646bd15989241e0a71e4da513434c49cad10))
* **group:** Change whitespace from bg2 to bg3 ([b502287](https://github.com/stevearc/nightfox.nvim/commit/b502287ba7f250a1893f04f69e78ef3ea6a9c3dc))
* **group:** Character was linked to itself ([8b7f820](https://github.com/stevearc/nightfox.nvim/commit/8b7f820004c4dad44c01f2dd78a759d838b76c64))
* **group:** Comment out `MsgArea` ([#99](https://github.com/stevearc/nightfox.nvim/issues/99)) ([5c900d2](https://github.com/stevearc/nightfox.nvim/commit/5c900d27f2a52ce03f729d7fb42575a535e83398))
* **group:** Set `IncSearch` fg `sel1` -&gt; `sel0` ([fbd8210](https://github.com/stevearc/nightfox.nvim/commit/fbd821014b82b1c14529d1973204461edd5b5b2b))
* **group:** Swap link of `CursorLine` and `CursorColumn` ([#91](https://github.com/stevearc/nightfox.nvim/issues/91)) ([10c8f38](https://github.com/stevearc/nightfox.nvim/commit/10c8f38ddec8808c16d56034b4703fa6d4f986de))
* **indent_blankline:** style wasn't set correctly ([#351](https://github.com/stevearc/nightfox.nvim/issues/351)) ([77aa745](https://github.com/stevearc/nightfox.nvim/commit/77aa7458d2b725c2d9ff55a18befe1b891ac473e))
* **kitty:** add "cursor_text_color" parameter ([#325](https://github.com/stevearc/nightfox.nvim/issues/325)) ([4a291f8](https://github.com/stevearc/nightfox.nvim/commit/4a291f83297b42026fdbe245378d579f33c0b106))
* **lib:** `highlight` takes inverse for nvim api call ([#81](https://github.com/stevearc/nightfox.nvim/issues/81)) ([d78e39c](https://github.com/stevearc/nightfox.nvim/commit/d78e39c02b334e9df66c88bdc534e6426366a14c))
* **lib:** Change inverse to reverse ([#137](https://github.com/stevearc/nightfox.nvim/issues/137)) ([fb2f8f1](https://github.com/stevearc/nightfox.nvim/commit/fb2f8f1eab62a7f0a4fc0de07bf0fec24916fedb))
* **lib:** Fix guard for nightly hl command ([#88](https://github.com/stevearc/nightfox.nvim/issues/88)) ([c9568a2](https://github.com/stevearc/nightfox.nvim/commit/c9568a2de48762ca51a36ef659e3f4a69ea22640))
* **lib:** Hackly workaround for neovim core bug ([#141](https://github.com/stevearc/nightfox.nvim/issues/141)) ([32a007b](https://github.com/stevearc/nightfox.nvim/commit/32a007ba7a217dd55063945df6eff11561477d8a))
* **lightline:** Add missing autoload function ([aa27dc0](https://github.com/stevearc/nightfox.nvim/commit/aa27dc09fcd1ba110199166f64cb3d8f69339156))
* **lightline:** Define correct `tabline` fields ([#188](https://github.com/stevearc/nightfox.nvim/issues/188)) ([4899a16](https://github.com/stevearc/nightfox.nvim/commit/4899a1680e5b41436dc92a1f6e5f2a5bbc0b9454))
* **load:** add setup guard ([9b6e3a4](https://github.com/stevearc/nightfox.nvim/commit/9b6e3a470ac12fb2ce3de2162bb80bd0b47736f6))
* **log:** agnostic log with vim.notify ([b4aa477](https://github.com/stevearc/nightfox.nvim/commit/b4aa4774fd9bdfa9ce64a0461ad75ea8dd7cc557))
* **lualine:** Define theme for each style ([#84](https://github.com/stevearc/nightfox.nvim/issues/84)) ([4bf99cf](https://github.com/stevearc/nightfox.nvim/commit/4bf99cfb7c29d3a2fdab8ec088d973f321225f71))
* **lualine:** Explicitly make table instead of generating ([#243](https://github.com/stevearc/nightfox.nvim/issues/243)) ([b3f6915](https://github.com/stevearc/nightfox.nvim/commit/b3f691534ebc60986d44d0ac113621e6e2e61314))
* **lualine:** Inactive `c` fg set to fg3 ([#228](https://github.com/stevearc/nightfox.nvim/issues/228)) ([9df01a3](https://github.com/stevearc/nightfox.nvim/commit/9df01a3fb3d41e1e388ded7a34fe97a19146a283)), closes [#216](https://github.com/stevearc/nightfox.nvim/issues/216)
* **main:** Remove accidental debug line ([10e5aa5](https://github.com/stevearc/nightfox.nvim/commit/10e5aa5d10f03c2d9dbf6a14a0e1a7fef36985f1))
* **mini:** Fix packer issue with remote plugins ([b30bcab](https://github.com/stevearc/nightfox.nvim/commit/b30bcabc443ee606f6fe3745d59a56f29c915f22))
* **module:** Change context to bg2 ([f4bea6a](https://github.com/stevearc/nightfox.nvim/commit/f4bea6a7b3d476cb174456ab32e250764446666e))
* **module:** Default html tags moved to builtin0 ([#230](https://github.com/stevearc/nightfox.nvim/issues/230)) ([db26a92](https://github.com/stevearc/nightfox.nvim/commit/db26a92fc0175c9ffaa27db489308e306823ed3f))
* **module:** Nvim-tree image set to black for light ([#235](https://github.com/stevearc/nightfox.nvim/issues/235)) ([c0b9a96](https://github.com/stevearc/nightfox.nvim/commit/c0b9a96dc07f5238b650b05e9be04e8150af6aa1))
* **module:** remove `TS` prefix from cmp links ([669b0ce](https://github.com/stevearc/nightfox.nvim/commit/669b0ce7d02d511c06ceae6201392dc29906dfc0))
* **module:** Remove reference to `bufferline` ([#140](https://github.com/stevearc/nightfox.nvim/issues/140)) ([f0d0162](https://github.com/stevearc/nightfox.nvim/commit/f0d0162a5649b856bcb82a5bc08dc02b582ddce4))
* **modules:** Implement all git hl groups for nvimtree ([2b19e2a](https://github.com/stevearc/nightfox.nvim/commit/2b19e2ad758f078b607408b15bdaf39f3beafac6))
* **modules:** Spelling mistake for git.conflict ([0931345](https://github.com/stevearc/nightfox.nvim/commit/09313453ecda3e509d6309fcf6da8e3cbb71b33c))
* **modules:** Update dap-ui with title changes ([55bb3ba](https://github.com/stevearc/nightfox.nvim/commit/55bb3ba6e02f7cd6047158f6f623655384d0390c))
* **module:** use correct group names for illuminate.vim ([#286](https://github.com/stevearc/nightfox.nvim/issues/286)) ([c88664b](https://github.com/stevearc/nightfox.nvim/commit/c88664b18e593319aea1ded731dd252d4f9e0f9a))
* **module:** use treesitter links only if module enabled ([#296](https://github.com/stevearc/nightfox.nvim/issues/296)) ([07332c1](https://github.com/stevearc/nightfox.nvim/commit/07332c1c62aba0c8f80ad677d44ca15009353bde))
* **nightfox:** Change bright black for nightfox ([d5052a0](https://github.com/stevearc/nightfox.nvim/commit/d5052a0d54a3d140557ce6bb2cb7fe4a474adaef))
* **nix:** install pre-commit in shell hooks ([30fb114](https://github.com/stevearc/nightfox.nvim/commit/30fb11405ab6f35eee230d8c2fb25de59898f8de))
* NvimTree colors ([3384b1d](https://github.com/stevearc/nightfox.nvim/commit/3384b1d7581e45db6118d619a83b2fd093d88c83))
* **palette:** Increase contrast for `duskfox` folds ([#121](https://github.com/stevearc/nightfox.nvim/issues/121)) ([093ceb8](https://github.com/stevearc/nightfox.nvim/commit/093ceb8da0d0ff4033703a838d19af1db090d96a))
* **palette:** Increase contrast for diff text `terafox` ([79ca2a5](https://github.com/stevearc/nightfox.nvim/commit/79ca2a56749aa197f55ad5c5379610171ec784ca))
* **palette:** Only set string to base if key is color value ([c0090b2](https://github.com/stevearc/nightfox.nvim/commit/c0090b22334c2b4003f923361c9cd18072ce6e22))
* **palette:** Update `duskfox` and `terafox` `sel1` ([#117](https://github.com/stevearc/nightfox.nvim/issues/117)) ([cd37c29](https://github.com/stevearc/nightfox.nvim/commit/cd37c29b2dcafd35d063a03bc57b0911222c4f5a))
* **pallet:** Brighen bg4 `value` by 3 ([#87](https://github.com/stevearc/nightfox.nvim/issues/87)) ([920b129](https://github.com/stevearc/nightfox.nvim/commit/920b1294ed311d5f7d974646ae660493c54345e4))
* **pallet:** Use bg1 as base blend for bg colors ([e75c7b5](https://github.com/stevearc/nightfox.nvim/commit/e75c7b56d31614d55a04fd43c60d0cd02805780d))
* Quickfix line numbers change to yellow ([37545af](https://github.com/stevearc/nightfox.nvim/commit/37545af545013c0d2df44e52d0bb87c8723ad0fa))
* **release:** rename "branch" -&gt; "branches" ([#328](https://github.com/stevearc/nightfox.nvim/issues/328)) ([b9a3385](https://github.com/stevearc/nightfox.nvim/commit/b9a3385d4814d7c8aa6a9a68f42c6a8bc05282f4))
* reload precompiled modules ([#103](https://github.com/stevearc/nightfox.nvim/issues/103)) ([f9b0f96](https://github.com/stevearc/nightfox.nvim/commit/f9b0f96f61a4aa136f9fd6a04e60829f50eda9b0))
* Rename invalid autoload variable ([#207](https://github.com/stevearc/nightfox.nvim/issues/207)) ([83f6ee9](https://github.com/stevearc/nightfox.nvim/commit/83f6ee9e646c803aa14c7293ad7775900f24ea1a))
* Revert back to using tokyonight `hl clear` ([49b7839](https://github.com/stevearc/nightfox.nvim/commit/49b7839649166b3d3accb3f2627ba9a7152c0234))
* Search highlighting and visual selection ([9a60616](https://github.com/stevearc/nightfox.nvim/commit/9a60616b7ef824ab6c1e92a24c951556994977ab))
* Set Inc and Cur Search foreground to black/white ([#215](https://github.com/stevearc/nightfox.nvim/issues/215)) ([15f3b58](https://github.com/stevearc/nightfox.nvim/commit/15f3b5837a8d07f45cbe16753fbf13630bc167a3)), closes [#214](https://github.com/stevearc/nightfox.nvim/issues/214)
* **setup:** `group` override defaults `link` to '' ([#160](https://github.com/stevearc/nightfox.nvim/issues/160)) ([803d4ae](https://github.com/stevearc/nightfox.nvim/commit/803d4aecc624c37f4ebbf9dd16dc67727c21b5e2))
* **setup:** ORIG_HEAD doesn't exist in Detached HEAD ([d4a615a](https://github.com/stevearc/nightfox.nvim/commit/d4a615a015451e12b7f13886aa25512a02bd5cab))
* **spec:** Use correct name to apply override ([#194](https://github.com/stevearc/nightfox.nvim/issues/194)) ([733b853](https://github.com/stevearc/nightfox.nvim/commit/733b85350b56dce3b84af792081f396876ac1530))
* **statusline:** Add missing terafox to lualine ([034b21b](https://github.com/stevearc/nightfox.nvim/commit/034b21b4066b62651fa138e0329e85d871e3f85c))
* **syntax:** Fix highlight for json labels ([#363](https://github.com/stevearc/nightfox.nvim/issues/363)) ([a48f6d9](https://github.com/stevearc/nightfox.nvim/commit/a48f6d9a0273101df76eb25d2f5477baa277f935))
* **syntax:** Move diff* highlight groups under syntax ([#195](https://github.com/stevearc/nightfox.nvim/issues/195)) ([c6a5258](https://github.com/stevearc/nightfox.nvim/commit/c6a5258ba4aa70e458405df2c55d1ad4b93695e3))
* **template:** Correctly call `to_css` ([#165](https://github.com/stevearc/nightfox.nvim/issues/165)) ([e602aca](https://github.com/stevearc/nightfox.nvim/commit/e602acaad91a546be2250e026f0bdc6be8c8a44c)), closes [#163](https://github.com/stevearc/nightfox.nvim/issues/163)
* **terminal:** Resolve issue with terminal cursor ([7b37243](https://github.com/stevearc/nightfox.nvim/commit/7b37243e673e5e89f25080a91bd145f365eafc6b)), closes [#7](https://github.com/stevearc/nightfox.nvim/issues/7)
* **theme:** Add `Struct` kind to cmp ([6fd7a48](https://github.com/stevearc/nightfox.nvim/commit/6fd7a48ccbbe8c23c98270a9f79c6a738e7fcefc))
* **theme:** Add TSConstant change to match orange ([1708a50](https://github.com/stevearc/nightfox.nvim/commit/1708a50462c855ac50f92ff4a71af616c0610b87))
* **theme:** Change rust fields to dark white ([6811252](https://github.com/stevearc/nightfox.nvim/commit/6811252ad5a27a6363c7266893c122afe011d721))
* **theme:** Neogit notification hl's ([6b6cf94](https://github.com/stevearc/nightfox.nvim/commit/6b6cf94c588c9aba2f0bf65c175f54ddceb3aa85))
* **theme:** Remove all references to fg_dark ([b6bcd70](https://github.com/stevearc/nightfox.nvim/commit/b6bcd703434b522f3831835c22eb71aaa7a31fbd))
* **theme:** Remove subtle for Conceal & SpecialKey ([27a4742](https://github.com/stevearc/nightfox.nvim/commit/27a4742d176bef8ba7d932a892600b45bb7ba84a)), closes [#45](https://github.com/stevearc/nightfox.nvim/issues/45)
* **theme:** Set style for TS groups ([d6939df](https://github.com/stevearc/nightfox.nvim/commit/d6939dfe1def8ce8b56755a472fdae2a274b78ab))
* **theme:** Tabline only fg and bg variants ([51c1f74](https://github.com/stevearc/nightfox.nvim/commit/51c1f74dbd8dc0736bfef87ecdc99513962d77fd))
* **theme:** Toml properties changed to blue ([a25486c](https://github.com/stevearc/nightfox.nvim/commit/a25486c95d28b9281d87e1af5d1612e8a6c9af2c))
* **theme:** Update bracket delimiter and punctuation ([9027295](https://github.com/stevearc/nightfox.nvim/commit/90272951c757381873542732c3edc1017aea4899))
* **theme:** Update GlyphPalette to full group ([cf7c438](https://github.com/stevearc/nightfox.nvim/commit/cf7c43822200201e6f9270924813521fdbaa5a85))
* **theme:** Update neogit's highlights ([57ef9b5](https://github.com/stevearc/nightfox.nvim/commit/57ef9b52e015530090d9b9c49558197ae413cc19))
* **theme:** Update Pmenu select bg ([1bceb47](https://github.com/stevearc/nightfox.nvim/commit/1bceb4769a65e652abc435cab531c009c07259cd))
* **theme:** vim.lsp.diagnostic to vim.diagnostic ([bc5c018](https://github.com/stevearc/nightfox.nvim/commit/bc5c0180886ecca708ca9586aa1c228f9b26df3d))
* **transparent:** remove `NormalNC` link to `Normal` ([773fd00](https://github.com/stevearc/nightfox.nvim/commit/773fd00919fdd737569906948a9a527fd0127465))
* Treesitter text fg mapped to fg1 ([#221](https://github.com/stevearc/nightfox.nvim/issues/221)) ([73bb745](https://github.com/stevearc/nightfox.nvim/commit/73bb745cd459732e247ee81027ffeea4c63a7cf8))
* **treesitter:** correct yaml field ([#276](https://github.com/stevearc/nightfox.nvim/issues/276)) ([d2e0888](https://github.com/stevearc/nightfox.nvim/commit/d2e088812abba833d1e94f9fd1eea476cfda6a1f))
* **treesitter:** link correct hl group for diff ([a201f5f](https://github.com/stevearc/nightfox.nvim/commit/a201f5fc008fc1c12d68f1dbe855d3f29bb2a4c9))
* Update Dashboard colors ([e8d3002](https://github.com/stevearc/nightfox.nvim/commit/e8d3002043b8c887c60c9e87f7ce0907ab04080b))
* **util:** Deprication warning not checking for all ([63a8eb6](https://github.com/stevearc/nightfox.nvim/commit/63a8eb64e8559e4c910e91025a2959c4b50b8c54))
* **vim:** loadstring (5.1) vs load (5.2&gt;=) ([#375](https://github.com/stevearc/nightfox.nvim/issues/375)) ([4ab4dda](https://github.com/stevearc/nightfox.nvim/commit/4ab4ddae66f21b57251b03fd74437c6e2de9f2b1))
* **vim:** resolve deprecation of nested `[[` ([#373](https://github.com/stevearc/nightfox.nvim/issues/373)) ([e45f802](https://github.com/stevearc/nightfox.nvim/commit/e45f80288c0af7f30d785676a0d89c9dcc3e390a))
* write cache files in binary mode ([c9c4d6a](https://github.com/stevearc/nightfox.nvim/commit/c9c4d6aee2895b5fadc76b6197c3a889790813f0))
* Yaml Fields to blue ([87f88f6](https://github.com/stevearc/nightfox.nvim/commit/87f88f6e399d1a09df0af3f0ef3dc17043700a03))


### Performance Improvements

* **compile:** remove table overhead for better performance ([#312](https://github.com/stevearc/nightfox.nvim/issues/312)) ([4cf5680](https://github.com/stevearc/nightfox.nvim/commit/4cf56808775d4f2d4c83fa01401ff2c5c509484d))
* **compiler:** remove `require` call to write compiled file ([#311](https://github.com/stevearc/nightfox.nvim/issues/311)) ([14489df](https://github.com/stevearc/nightfox.nvim/commit/14489dfa8c4241a919845ed9101fae074234f35b))
* **setup:** cache only opt table passed to setup ([ae5df67](https://github.com/stevearc/nightfox.nvim/commit/ae5df67b091b8c0198975e6d776e65e36c92c09e))


### Code Refactoring

* **group:** `groups` now per style ([#154](https://github.com/stevearc/nightfox.nvim/issues/154)) ([9604c15](https://github.com/stevearc/nightfox.nvim/commit/9604c159010ad2b8f122f6087a0e73533fb2654c))
* **palette:** rework dayfox ([#285](https://github.com/stevearc/nightfox.nvim/issues/285)) ([4f6eff4](https://github.com/stevearc/nightfox.nvim/commit/4f6eff46463e248c3bd952a82fc7250dc87b91d8))
* **treesitter:** Support current format only ([#251](https://github.com/stevearc/nightfox.nvim/issues/251)) ([bb70a64](https://github.com/stevearc/nightfox.nvim/commit/bb70a6489c6055f445a86a0290ead288732477df))

## [3.6.1](https://github.com/EdenEast/nightfox.nvim/compare/v3.6.0...v3.6.1) (2023-09-20)


### Bug Fixes

* **vim:** loadstring (5.1) vs load (5.2&gt;=) ([#375](https://github.com/EdenEast/nightfox.nvim/issues/375)) ([4ab4dda](https://github.com/EdenEast/nightfox.nvim/commit/4ab4ddae66f21b57251b03fd74437c6e2de9f2b1))

## [3.6.0](https://github.com/EdenEast/nightfox.nvim/compare/v3.5.1...v3.6.0) (2023-09-19)


### Features

* **modules:** add indent_blankline ([#347](https://github.com/EdenEast/nightfox.nvim/issues/347)) ([5472a3e](https://github.com/EdenEast/nightfox.nvim/commit/5472a3e2bae6f381b603cd7998fc131f8134755c))


### Bug Fixes

* **compiler:** add file permission error ([#368](https://github.com/EdenEast/nightfox.nvim/issues/368)) ([e886e39](https://github.com/EdenEast/nightfox.nvim/commit/e886e39e592e89f316536a6f070365a9d88901c9))
* **indent_blankline:** style wasn't set correctly ([#351](https://github.com/EdenEast/nightfox.nvim/issues/351)) ([77aa745](https://github.com/EdenEast/nightfox.nvim/commit/77aa7458d2b725c2d9ff55a18befe1b891ac473e))
* **syntax:** Fix highlight for json labels ([#363](https://github.com/EdenEast/nightfox.nvim/issues/363)) ([a48f6d9](https://github.com/EdenEast/nightfox.nvim/commit/a48f6d9a0273101df76eb25d2f5477baa277f935))
* **vim:** resolve deprecation of nested `[[` ([#373](https://github.com/EdenEast/nightfox.nvim/issues/373)) ([e45f802](https://github.com/EdenEast/nightfox.nvim/commit/e45f80288c0af7f30d785676a0d89c9dcc3e390a))

## [3.5.1](https://github.com/EdenEast/nightfox.nvim/compare/v3.5.0...v3.5.1) (2023-04-21)


### Bug Fixes

* **extra:** switch from fg3 to fg2 for white ([e54427a](https://github.com/EdenEast/nightfox.nvim/commit/e54427a1bfea55c9ab0c21ac7e9d07b22156d0f0))
* **extra:** zellij black and white set to bg3/fg3 ([#336](https://github.com/EdenEast/nightfox.nvim/issues/336)) ([409d646](https://github.com/EdenEast/nightfox.nvim/commit/409d646bd15989241e0a71e4da513434c49cad10))
* **module:** remove `TS` prefix from cmp links ([669b0ce](https://github.com/EdenEast/nightfox.nvim/commit/669b0ce7d02d511c06ceae6201392dc29906dfc0))

## [3.5.0](https://github.com/EdenEast/nightfox.nvim/compare/v3.4.0...v3.5.0) (2023-04-11)


### Features

* **ci:** add github action to autogenerate extra files ([#327](https://github.com/EdenEast/nightfox.nvim/issues/327)) ([727a0ea](https://github.com/EdenEast/nightfox.nvim/commit/727a0ea9d2dde7f8cfd4ae0f2e5570c365638227))


### Bug Fixes

* **cache:** move setup guard before load call ([#331](https://github.com/EdenEast/nightfox.nvim/issues/331)) ([88182d4](https://github.com/EdenEast/nightfox.nvim/commit/88182d48373be8ff1933bfd5fabc4c4aa55bf726))
* **release:** rename "branch" -&gt; "branches" ([#328](https://github.com/EdenEast/nightfox.nvim/issues/328)) ([b9a3385](https://github.com/EdenEast/nightfox.nvim/commit/b9a3385d4814d7c8aa6a9a68f42c6a8bc05282f4))

## [3.4.0](https://github.com/EdenEast/nightfox.nvim/compare/v3.3.0...v3.4.0) (2023-04-04)


### Features

* add new lsp semantic token highlight groups ([#318](https://github.com/EdenEast/nightfox.nvim/issues/318)) ([a8044b0](https://github.com/EdenEast/nightfox.nvim/commit/a8044b084e0114609ec2c59cc4fa94c709a457d4))
* add vim/neovim test on ubuntu/macos/windows ([#320](https://github.com/EdenEast/nightfox.nvim/issues/320)) ([8bb6713](https://github.com/EdenEast/nightfox.nvim/commit/8bb6713c56458aae339575b205234d820ec2046a))
* **module:** add alpha support ([4b73c9d](https://github.com/EdenEast/nightfox.nvim/commit/4b73c9d0995eb1a43e284534b97a543ca21c5c77))
* **semantic_tokens:** add injected highlights ([#321](https://github.com/EdenEast/nightfox.nvim/issues/321)) ([3802464](https://github.com/EdenEast/nightfox.nvim/commit/380246446a359f7faf2f0ccb865658ec0a295bd0))
* **semantic_tokens:** link default library to function builtin ([53cdaa5](https://github.com/EdenEast/nightfox.nvim/commit/53cdaa583138698f4a0a4a9d2abaf761c8960407))


### Bug Fixes

* **kitty:** add "cursor_text_color" parameter ([#325](https://github.com/EdenEast/nightfox.nvim/issues/325)) ([4a291f8](https://github.com/EdenEast/nightfox.nvim/commit/4a291f83297b42026fdbe245378d579f33c0b106))
* **load:** add setup guard ([9b6e3a4](https://github.com/EdenEast/nightfox.nvim/commit/9b6e3a470ac12fb2ce3de2162bb80bd0b47736f6))
* **setup:** ORIG_HEAD doesn't exist in Detached HEAD ([d4a615a](https://github.com/EdenEast/nightfox.nvim/commit/d4a615a015451e12b7f13886aa25512a02bd5cab))

## [3.3.0](https://github.com/EdenEast/nightfox.nvim/compare/v3.2.0...v3.3.0) (2023-02-17)


### Features

* **extra:** add zellij theme file ([789b302](https://github.com/EdenEast/nightfox.nvim/commit/789b3029d5058e925436ac29eb0521aa4e042b36))


### Bug Fixes

* **compile:** correct call to set background for vim ([5aeb0e7](https://github.com/EdenEast/nightfox.nvim/commit/5aeb0e730755b3007029b51dda094d4e0e6e9291))


### Performance Improvements

* **compile:** remove table overhead for better performance ([#312](https://github.com/EdenEast/nightfox.nvim/issues/312)) ([4cf5680](https://github.com/EdenEast/nightfox.nvim/commit/4cf56808775d4f2d4c83fa01401ff2c5c509484d))
* **compiler:** remove `require` call to write compiled file ([#311](https://github.com/EdenEast/nightfox.nvim/issues/311)) ([14489df](https://github.com/EdenEast/nightfox.nvim/commit/14489dfa8c4241a919845ed9101fae074234f35b))

## [3.2.0](https://github.com/EdenEast/nightfox.nvim/compare/v3.1.0...v3.2.0) (2023-01-24)


### Features

* add support for ts-rainbow2 ([#301](https://github.com/EdenEast/nightfox.nvim/issues/301)) ([97e66df](https://github.com/EdenEast/nightfox.nvim/commit/97e66dfaaecdc81f1dd7da00f8d4a6033f3bf6b2))
* **cvd:** support colorblind mode with daltonization ([#281](https://github.com/EdenEast/nightfox.nvim/issues/281)) ([f093297](https://github.com/EdenEast/nightfox.nvim/commit/f093297145e917f7ae4d0e09fc9c07ac40620361))


### Bug Fixes

* **transparent:** remove `NormalNC` link to `Normal` ([773fd00](https://github.com/EdenEast/nightfox.nvim/commit/773fd00919fdd737569906948a9a527fd0127465))

## [3.1.0](https://github.com/EdenEast/nightfox.nvim/compare/v3.0.0...v3.1.0) (2023-01-18)


### Features

* **color:** add WCAG AA contrast validation ([12e0ca7](https://github.com/EdenEast/nightfox.nvim/commit/12e0ca70e978f58318e7f0279bb7b243ababbd49))
* Nushell Extra Theme Config ([#298](https://github.com/EdenEast/nightfox.nvim/issues/298)) ([23a678f](https://github.com/EdenEast/nightfox.nvim/commit/23a678f47722801f70fe64df39a1fa29f6abf297))


### Bug Fixes

* **module:** use treesitter links only if module enabled ([#296](https://github.com/EdenEast/nightfox.nvim/issues/296)) ([07332c1](https://github.com/EdenEast/nightfox.nvim/commit/07332c1c62aba0c8f80ad677d44ca15009353bde))

## [3.0.0](https://github.com/EdenEast/nightfox.nvim/compare/v2.1.0...v3.0.0) (2023-01-05)


### ⚠ BREAKING CHANGES

* **palette:** rework dayfox ([#285](https://github.com/EdenEast/nightfox.nvim/issues/285))

### Features

* **module:** add highlight support for nvim-navic ([#283](https://github.com/EdenEast/nightfox.nvim/issues/283)) ([0f94892](https://github.com/EdenEast/nightfox.nvim/commit/0f948925ec435f2fa115522a991ac84efed0045a))


### Bug Fixes

* **module:** use correct group names for illuminate.vim ([#286](https://github.com/EdenEast/nightfox.nvim/issues/286)) ([c88664b](https://github.com/EdenEast/nightfox.nvim/commit/c88664b18e593319aea1ded731dd252d4f9e0f9a))


### Code Refactoring

* **palette:** rework dayfox ([#285](https://github.com/EdenEast/nightfox.nvim/issues/285)) ([4f6eff4](https://github.com/EdenEast/nightfox.nvim/commit/4f6eff46463e248c3bd952a82fc7250dc87b91d8))

## [2.1.0](https://github.com/EdenEast/nightfox.nvim/compare/v2.0.0...v2.1.0) (2022-12-27)


### Features

* **compiler:** write compile lua file if debug set ([f32eef4](https://github.com/EdenEast/nightfox.nvim/commit/f32eef468a98e73d5a87daa8db873dd1a94e021e))
* **module:** add signify support ([#279](https://github.com/EdenEast/nightfox.nvim/issues/279)) ([07174bf](https://github.com/EdenEast/nightfox.nvim/commit/07174bfe0ad15a4c25ef908872904edb09069e94))


### Bug Fixes

* **log:** agnostic log with vim.notify ([b4aa477](https://github.com/EdenEast/nightfox.nvim/commit/b4aa4774fd9bdfa9ce64a0461ad75ea8dd7cc557))
* **treesitter:** correct yaml field ([#276](https://github.com/EdenEast/nightfox.nvim/issues/276)) ([d2e0888](https://github.com/EdenEast/nightfox.nvim/commit/d2e088812abba833d1e94f9fd1eea476cfda6a1f))


### Performance Improvements

* **setup:** cache only opt table passed to setup ([ae5df67](https://github.com/EdenEast/nightfox.nvim/commit/ae5df67b091b8c0198975e6d776e65e36c92c09e))
