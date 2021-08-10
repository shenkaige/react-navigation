# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.0.1](https://github.com/shenkaige/react-navigation/compare/@react-navigation/example@6.0.0...@react-navigation/example@6.0.1) (2021-08-10)

**Note:** Version bump only for package @react-navigation/example





# [6.0.0](https://github.com/shenkaige/react-navigation/compare/@react-navigation/example@5.1.0...@react-navigation/example@6.0.0) (2021-08-10)


### Bug Fixes

* automatically set top inset on Android in native stack ([2cb44a5](https://github.com/shenkaige/react-navigation/commit/2cb44a566315cc29243227f4289e42ee02e0aa42))
* don't hide child header automatically in stack ([8f0efc8](https://github.com/shenkaige/react-navigation/commit/8f0efc8db534297a95ea8a2bcb6d2e387c1fea53))
* drop dangerously prefix from getState and getParent ([227f133](https://github.com/shenkaige/react-navigation/commit/227f133536af85dc5ff85eeb269b76ed80cd3f05))
* fix error with type definitions. closes [#8511](https://github.com/shenkaige/react-navigation/issues/8511) ([d1210a8](https://github.com/shenkaige/react-navigation/commit/d1210a861b37201827c333a5c012c4f0ebd9bb6a))
* fix false warning due to change in Object.assign in metro preset ([5e358b3](https://github.com/shenkaige/react-navigation/commit/5e358b3aadac7bb186521872d515fff2e571a940)), closes [#8584](https://github.com/shenkaige/react-navigation/issues/8584)
* fix incorrect name for headerTransparent ([1da575e](https://github.com/shenkaige/react-navigation/commit/1da575e0e74c9510d6a57d473500cf84668c3824))
* fix integration tests ([211f1f2](https://github.com/shenkaige/react-navigation/commit/211f1f2c0eea71aa1e3d78bb6265e1d3f03363e8))
* fix modal animation not being set properly ([08e74af](https://github.com/shenkaige/react-navigation/commit/08e74af54529582dcbc8d91e77bfed70f006f00d))
* fix type error when passing unannotated navigation ref ([dc4ffc0](https://github.com/shenkaige/react-navigation/commit/dc4ffc0171b4535fe1b6e839b9d54350121bcf55))
* make sure disabling react-native-screens works ([a369ba3](https://github.com/shenkaige/react-navigation/commit/a369ba36451ddc2bb5b247e61b725bce1e3fb5e5))
* make sure new state events are emitted when new navigators mount ([af8b274](https://github.com/shenkaige/react-navigation/commit/af8b27414c8628570d946003f4fdff3341cb8954))
* make sure the wildcard pattern catches nested unmatched routes ([c3bd349](https://github.com/shenkaige/react-navigation/commit/c3bd349d77688011c9c55027edd66c6f39de2ade))
* make transparent modal work with modal presentation ([c90bff0](https://github.com/shenkaige/react-navigation/commit/c90bff08d54d1c7151737a43d4f73abe7d364366))
* relatively position float Header if !headerTransparent ([#8285](https://github.com/shenkaige/react-navigation/issues/8285)) ([78afbff](https://github.com/shenkaige/react-navigation/commit/78afbffe976b14bb60666a2b1230127db0dc24f6))
* set statusbar to translucent on Android ([3e67f64](https://github.com/shenkaige/react-navigation/commit/3e67f64ea575bdfb68d812f728075a1ef56d3fca))
* show a missing icon symbol instead of empty area in bottom tab bar ([2bc4882](https://github.com/shenkaige/react-navigation/commit/2bc4882692be9f02d781639892e1f98b891811c4))
* show error when beforeRemove is used to prevent action in naive stack ([6d518a4](https://github.com/shenkaige/react-navigation/commit/6d518a46b89496f4a3bfd2da24245fe344f97290))
* update ci image for playwright ([2b58c52](https://github.com/shenkaige/react-navigation/commit/2b58c52f70e0b391caa8657a4b440364eb61e950))
* use safe area context in material bottom tabs ([80cdc88](https://github.com/shenkaige/react-navigation/commit/80cdc88588584cfab0c122a77fecde1610229961))


### Code Refactoring

* drop mode prop in favor of animationPresentation option ([9ac709e](https://github.com/shenkaige/react-navigation/commit/9ac709ea1e5a63c3a48abfa334ff6a6925095a72))
* drop support for tabBarVisible option ([a97a43a](https://github.com/shenkaige/react-navigation/commit/a97a43aa1d2a615074ade93f1addebcee1dbfb65))
* move drawerContentOptions to options ([15e5678](https://github.com/shenkaige/react-navigation/commit/15e5678037bc6656d891724b4262cb542d6aad0d))
* move headerMode to options ([aacc1b5](https://github.com/shenkaige/react-navigation/commit/aacc1b525d86f0e0b1bad8016fd85e82024f16e9))
* simplify props for stack and drawer headers ([4cad132](https://github.com/shenkaige/react-navigation/commit/4cad132c2c3daa6370a6916977f1f1db0036d4e4))


### Features

* add 'transparentModal' presentation to JS stack ([3d14740](https://github.com/shenkaige/react-navigation/commit/3d147401e8ca98ec2d51d5e11c09cd1271d448d1))
* add a `beforeRemove` event ([6925e92](https://github.com/shenkaige/react-navigation/commit/6925e92dc3e9885e3f552ca5e5eb51ae1521e54e))
* add a Background component ([cbaabc1](https://github.com/shenkaige/react-navigation/commit/cbaabc1288e780698e499a00b9ca06ab9746a0da))
* add a getComponent prop to lazily specify components ([f418029](https://github.com/shenkaige/react-navigation/commit/f4180295bf22e32c65f6a7ab7089523cb2de58fb))
* add a hook to update document title ([13c9d1e](https://github.com/shenkaige/react-navigation/commit/13c9d1e281b4626199671bce11ba62d83767564f))
* add a NavigatorScreenParams type. closes [#6931](https://github.com/shenkaige/react-navigation/issues/6931) ([e3e58c2](https://github.com/shenkaige/react-navigation/commit/e3e58c2d890e7fab75d78371e349aea55a402fcd))
* add a new component to group multiple screens with common options ([1a6aebe](https://github.com/shenkaige/react-navigation/commit/1a6aebefcb77ea708687475c55742407d69808ce))
* add a slide animation for modals on Android ([6f326cf](https://github.com/shenkaige/react-navigation/commit/6f326cf0c5098a722176aedd2051d29e12c95592))
* add a tabBarBackground option to bottom tabs ([2f282f1](https://github.com/shenkaige/react-navigation/commit/2f282f107053a65b69f80edb5d9c858cfa569aa2))
* add ability to specify root param list ([b28bfdd](https://github.com/shenkaige/react-navigation/commit/b28bfddc17cbf3996fac04a34b2a7085ecf88be5))
* add devtools package ([#8436](https://github.com/shenkaige/react-navigation/issues/8436)) ([95b044e](https://github.com/shenkaige/react-navigation/commit/95b044ecf95939f40ced4da740a365140b3952b7))
* add helper and hook for container ref ([0ecd112](https://github.com/shenkaige/react-navigation/commit/0ecd112ec9786a26261ada3d33ef44dc1ec84da0))
* add helper to get focused route name from nested state ([#8435](https://github.com/shenkaige/react-navigation/issues/8435)) ([f51f9c8](https://github.com/shenkaige/react-navigation/commit/f51f9c8493e079f73688adaf9dc43a2171c3e44a))
* add option to show a header in drawer navigator screens ([dbe961b](https://github.com/shenkaige/react-navigation/commit/dbe961ba5bb243e8da4d889c3c7dd6ed1de287c4))
* add support for badges to bottom tab bar ([96c7b68](https://github.com/shenkaige/react-navigation/commit/96c7b688ce773b3dd1f1cf7775367cd7080c94a2))
* add wildcard patterns for paths ([4fe72e3](https://github.com/shenkaige/react-navigation/commit/4fe72e3ce7bae9120d04e490401f3bad58ebdf5c)), closes [#8019](https://github.com/shenkaige/react-navigation/issues/8019)
* associate path with the route it opens when deep linking ([#9384](https://github.com/shenkaige/react-navigation/issues/9384)) ([86e64fd](https://github.com/shenkaige/react-navigation/commit/86e64fdcd81a57cf3f3bdab4c9035b52984e7009)), closes [#9102](https://github.com/shenkaige/react-navigation/issues/9102)
* automatically hide header in nested stacks ([e0e0f79](https://github.com/shenkaige/react-navigation/commit/e0e0f79793be552e5532cd0afe9444000d21341e))
* automatically set headerMode if it's modal presentation style ([4bb0b43](https://github.com/shenkaige/react-navigation/commit/4bb0b43f1a0f27c96843415de6eaa37edebfb561))
* initial implementation of a flipper plugin ([d6f6f5f](https://github.com/shenkaige/react-navigation/commit/d6f6f5f94db85bd9166a5a97889c37690846d519))
* rework linking configuration to be more strict ([#8502](https://github.com/shenkaige/react-navigation/issues/8502)) ([a021cfb](https://github.com/shenkaige/react-navigation/commit/a021cfb8af4afd50f785f6ee9b51d361e25704ca))
* support mixing regular and modal presentation in same stack ([60fa3b9](https://github.com/shenkaige/react-navigation/commit/60fa3b9be976a73a5b04b632b4b37672674c956b))
* support navigate-like object in Link ([1478659](https://github.com/shenkaige/react-navigation/commit/14786594c004d8176570f1a4ab013b57b3180665))
* update react-native-safe-area-context to 1.0.0 ([#8182](https://github.com/shenkaige/react-navigation/issues/8182)) ([d62fbfe](https://github.com/shenkaige/react-navigation/commit/d62fbfe255140f16b182e8b54b276a7c96f2aec6))
* upgrade to latest react-native-tab-view using ViewPager ([2261001](https://github.com/shenkaige/react-navigation/commit/22610014b3b1e649b368a63fd021362235ee585d))
* use modal presentation style for modals on iOS by default ([8a63f19](https://github.com/shenkaige/react-navigation/commit/8a63f193bf26c35546aa45af01d89b7a7216657d))


### BREAKING CHANGES

* This drops the mode prop on the navigator in favor of a per-screen option animationPresentation
* headerMode is now moved to options instead of props
* This commit moves options from `drawerContentOptions` to regular `options` in order to reduce confusion between the two, as well as to make it more flexible to configure the drawer on a per screen basis.
* We need to add support for specifying style for tab bar in options to support the use cases which need this.
* Previously, the stack header accepted scene and previous scene which contained things such as descriptor, navigation prop, progress etc. The commit simplifies them to pass `route`, `navigation`, `options` and `progress` directly to the header. Similaryly, the `previous` argument now contains `options`, `route` and `progress`.





# [5.1.0](https://github.com/react-navigation/react-navigation/compare/@react-navigation/example@5.0.0-alpha.23...@react-navigation/example@5.1.0) (2020-05-20)


### Bug Fixes

* add config to enable redux devtools integration ([c9c825b](https://github.com/react-navigation/react-navigation/commit/c9c825bee61426635a28ee149eeeff3d628171cd))
* clamp interpolated styles ([67798af](https://github.com/react-navigation/react-navigation/commit/67798af869dcbbf323629fc7e7cc9062d1e12c29))
* disable screens when mode is modal on older expo versions ([94d7b28](https://github.com/react-navigation/react-navigation/commit/94d7b28c0b2ce0d56c99b224610f305be6451626))
* dispatch pop early when screen is closed with gesture ([#336](https://github.com/react-navigation/react-navigation/issues/336)) ([3d937d1](https://github.com/react-navigation/react-navigation/commit/3d937d1e6571cd613e830d64f7b2e7426076d371)), closes [#267](https://github.com/react-navigation/react-navigation/issues/267)
* provide initial values for safe area to prevent blank screen ([#238](https://github.com/react-navigation/react-navigation/issues/238)) ([77b7570](https://github.com/react-navigation/react-navigation/commit/77b757091c0451e20bca01138629669c7da544a8))
* render fallback only if linking is enabled. closes [#8161](https://github.com/react-navigation/react-navigation/issues/8161) ([1c075ff](https://github.com/react-navigation/react-navigation/commit/1c075ffb169d233ed0515efea264a5a69b4de52e))
* return onPress instead of onClick for useLinkProps ([ae5442e](https://github.com/react-navigation/react-navigation/commit/ae5442ebe812b91fa1f12164f27d1aeed918ab0e))
* rtl in native app example ([50b366e](https://github.com/react-navigation/react-navigation/commit/50b366e7341f201d29a44f20b7771b3a832b0045))
* screens integration on Android ([#294](https://github.com/react-navigation/react-navigation/issues/294)) ([9bfb295](https://github.com/react-navigation/react-navigation/commit/9bfb29562020c61b4d5c9bee278bcb1c7bdb8b67))
* spread parent params to children in compat navigator ([24febf6](https://github.com/react-navigation/react-navigation/commit/24febf6ea99be2e5f22005fdd2a82136d647255c)), closes [#6785](https://github.com/react-navigation/react-navigation/issues/6785)
* update screens for native stack ([5411816](https://github.com/react-navigation/react-navigation/commit/54118161885738a6d20b062c7e6679f3bace8424))
* wrap navigators in gesture handler root ([41a5e1a](https://github.com/react-navigation/react-navigation/commit/41a5e1a385aa5180abc3992a4c67077c37b998b9))


### Features

* add `animationTypeForReplace` option ([#297](https://github.com/react-navigation/react-navigation/issues/297)) ([6262f72](https://github.com/react-navigation/react-navigation/commit/6262f7298bff843571fb4b1a677d3beabe29833e))
* add `screens` prop for nested configs ([#308](https://github.com/react-navigation/react-navigation/issues/308)) ([b931ae6](https://github.com/react-navigation/react-navigation/commit/b931ae62dfb2c5253c94ea5ace73e9070ec17c4a))
* add `useLinkBuilder` hook to build links ([2792f43](https://github.com/react-navigation/react-navigation/commit/2792f438fe45428fe193e3708fee7ad61966cbf4))
* add a useLinkProps hook ([f2291d1](https://github.com/react-navigation/react-navigation/commit/f2291d110faa2aa8e10c9133c1c0c28d54af7917))
* add action prop to Link ([942d2be](https://github.com/react-navigation/react-navigation/commit/942d2be2c72720469475ce12ec8df23825994dbf))
* add custom theme support ([#211](https://github.com/react-navigation/react-navigation/issues/211)) ([00fc616](https://github.com/react-navigation/react-navigation/commit/00fc616de0572bade8aa85052cdc8290360b1d7f))
* add deeplinking to native example ([#309](https://github.com/react-navigation/react-navigation/issues/309)) ([e55e866](https://github.com/react-navigation/react-navigation/commit/e55e866af2f2163ee89bc527997cda13ffeb2abe))
* add headerStatusBarHeight option to stack ([b201fd2](https://github.com/react-navigation/react-navigation/commit/b201fd20716a2f03cb9373c72281f5d396a9356d))
* add Link component as useLinkTo hook for navigating to links ([2573b5b](https://github.com/react-navigation/react-navigation/commit/2573b5beaac1240434e52f3f57bb29da2f541c88))
* add openByDefault option to drawer ([36689e2](https://github.com/react-navigation/react-navigation/commit/36689e24c21b474692bb7ecd0b901c8afbbe9a20))
* add permanent drawer type ([#7818](https://github.com/react-navigation/react-navigation/issues/7818)) ([6a5d0a0](https://github.com/react-navigation/react-navigation/commit/6a5d0a035afae60d91aef78401ec8826295746fe))
* add preventDefault functionality in material bottom tabs ([3dede31](https://github.com/react-navigation/react-navigation/commit/3dede316ccab3b2403a475f60ce20b5c4e4cc068))
* emit appear and dismiss events for native stack ([f1df4a0](https://github.com/react-navigation/react-navigation/commit/f1df4a080877b3642e748a41a5ffc2da8c449a8c))
* initialState should take priority over deep link ([039017b](https://github.com/react-navigation/react-navigation/commit/039017bc2af69120d2d10e8f2c8a62919c37eb65))
* integrate with history API on web ([5a3f835](https://github.com/react-navigation/react-navigation/commit/5a3f8356b05bff7ed20893a5db6804612da3e568))
