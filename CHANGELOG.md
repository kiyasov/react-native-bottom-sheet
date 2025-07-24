

# 5.2.0 (2025-07-24)


### Bug Fixes

* **#1035,#1043:** updated default animatedNextPositionIndex to INITIAL_VALUE ([#1960](https://github.com/gorhom/react-native-bottom-sheet/issues/1960))(by [@dfalling](https://github.com/dfalling)) ([1cf3e41](https://github.com/gorhom/react-native-bottom-sheet/commit/1cf3e4167f2ffacf36c7abebb527f79048754121)), closes [#1035](https://github.com/gorhom/react-native-bottom-sheet/issues/1035) [#1043](https://github.com/gorhom/react-native-bottom-sheet/issues/1043)
* **#1119:** fixed race condition between onmount and keyboard animations ([a1ec74d](https://github.com/gorhom/react-native-bottom-sheet/commit/a1ec74dbbc85476bb39f3637e9a97214e0cad9a0))
* **#1968:** moved the flashlist optional import into the component body ([ab33e21](https://github.com/gorhom/react-native-bottom-sheet/commit/ab33e2132f8e6fdb4a3c36e34c0f2ff04e09f11f)), closes [#1968](https://github.com/gorhom/react-native-bottom-sheet/issues/1968)
* **#1983:** updated shared values access as hook dependancies ([ae41b2d](https://github.com/gorhom/react-native-bottom-sheet/commit/ae41b2da650d2be614d840fbdfe1d29db6d7a575)), closes [#1983](https://github.com/gorhom/react-native-bottom-sheet/issues/1983)
* **#1983:** updated shared values access as hook dependancies ([#1992](https://github.com/gorhom/react-native-bottom-sheet/issues/1992))(by [@pinpong](https://github.com/pinpong)) ([9757bd2](https://github.com/gorhom/react-native-bottom-sheet/commit/9757bd251cba67cf26489640f20fd1557b1a426e)), closes [#1983](https://github.com/gorhom/react-native-bottom-sheet/issues/1983) [#1983](https://github.com/gorhom/react-native-bottom-sheet/issues/1983)
* **#1987:** updated provided style handling for bottom sheet view ([4c8ae25](https://github.com/gorhom/react-native-bottom-sheet/commit/4c8ae252b8ec0bb420b60f8314cc7f04ed12b519)), closes [#1987](https://github.com/gorhom/react-native-bottom-sheet/issues/1987)
* **#2043:** handle unnecessary invocation of index side effect ([#2073](https://github.com/gorhom/react-native-bottom-sheet/issues/2073))(inspired by @IslamRustamov) ([2164c02](https://github.com/gorhom/react-native-bottom-sheet/commit/2164c02e63177f9ac69acc05722c85e8d55cd931)), closes [#2043](https://github.com/gorhom/react-native-bottom-sheet/issues/2043)
* **#2129:** fixed initial isAnimatedOnMount value ([0850cb8](https://github.com/gorhom/react-native-bottom-sheet/commit/0850cb864819f79189592cb66c2b6d179957ba61))
* **#2163:** restart closing animation when container height get updated ([4ed9f3c](https://github.com/gorhom/react-native-bottom-sheet/commit/4ed9f3cb542316a984893efa2025ca5384ffe89a)), closes [#2163](https://github.com/gorhom/react-native-bottom-sheet/issues/2163)
* **#2177:** set absolute fill to backdrop default style ([979ba7c](https://github.com/gorhom/react-native-bottom-sheet/commit/979ba7ce0b9d69abfaefd169ee692bf818fa4d0d)), closes [#2177](https://github.com/gorhom/react-native-bottom-sheet/issues/2177)
* **#2237:** fixed node handle lookup for virtualized list on web (by [@btoo](https://github.com/btoo)) ([6442b0e](https://github.com/gorhom/react-native-bottom-sheet/commit/6442b0ea54a38d8dcb82f63aade077ead29d382b))
* **#2237:** fixed recursive loop in findNodeHandle.web (by @TNAJanssen) ([3556ba8](https://github.com/gorhom/react-native-bottom-sheet/commit/3556ba8e1445a78dfc6cfc93997500d52a03368e))
* **#2237:** updated findNodeHandle for web to support React 19 ([47a95f5](https://github.com/gorhom/react-native-bottom-sheet/commit/47a95f517ab5b4680d0f5a45b09464911aafd35e)), closes [#2237](https://github.com/gorhom/react-native-bottom-sheet/issues/2237)
* **#2267:** early exit when attempting to snap to index while layout is not ready ([0715f03](https://github.com/gorhom/react-native-bottom-sheet/commit/0715f0384a187cdb1df903d693666ac4b12db807)), closes [#2267](https://github.com/gorhom/react-native-bottom-sheet/issues/2267)
* **#2278:** removed flashlist for web ([e17096f](https://github.com/gorhom/react-native-bottom-sheet/commit/e17096feade145f9e6349815398f8aaae758d554)), closes [#2278](https://github.com/gorhom/react-native-bottom-sheet/issues/2278)
* **#2288:** added unique id to the root bottom sheet modal portal ([711ea7a](https://github.com/gorhom/react-native-bottom-sheet/commit/711ea7a5290ef485b9ba5c65eb45e28d6e495b43)), closes [#2288](https://github.com/gorhom/react-native-bottom-sheet/issues/2288)
* **1887:** updated the keyboard handling for Android with keyboard input mode resize ([08db4ab](https://github.com/gorhom/react-native-bottom-sheet/commit/08db4ab4b0058955e9ee2d55f87da8fefb5390ad))
* added a fixed position for the container on web ([ce5115a](https://github.com/gorhom/react-native-bottom-sheet/commit/ce5115a2abd2ddc7140eb3037274b2c5bb3ff10a))
* added BottomSheetFlashList mock ([#1988](https://github.com/gorhom/react-native-bottom-sheet/issues/1988))(by @Fadikk367) ([13c7d47](https://github.com/gorhom/react-native-bottom-sheet/commit/13c7d47beae6f2451968d30e862f0ea49b7199b6))
* added BottomSheetTextInput to the mock file ([#1698](https://github.com/gorhom/react-native-bottom-sheet/issues/1698))(by [@ghorbani-m](https://github.com/ghorbani-m)) ([dee95e5](https://github.com/gorhom/react-native-bottom-sheet/commit/dee95e5b161d78b0aae34d85abea3d8042417892))
* added children type to containerComponent prop type ([#1971](https://github.com/gorhom/react-native-bottom-sheet/issues/1971))(by @Nodonisko) ([203e52f](https://github.com/gorhom/react-native-bottom-sheet/commit/203e52fa5be3e167522776f184d79511bdf35344))
* added error message when dynamic sizing enabled with a wrong children type ([8b62dca](https://github.com/gorhom/react-native-bottom-sheet/commit/8b62dca06752a3c047162a693a75173a7c701e3e))
* added footer height to content height when using dynamic sizing ([#1725](https://github.com/gorhom/react-native-bottom-sheet/issues/1725)) ([5009085](https://github.com/gorhom/react-native-bottom-sheet/commit/50090859f9e50932c641df5b0d6f91cc9f3b5bad))
* added missing mock of Touchables ([#1700](https://github.com/gorhom/react-native-bottom-sheet/issues/1700))(by [@jaworek](https://github.com/jaworek)) ([a6f44c0](https://github.com/gorhom/react-native-bottom-sheet/commit/a6f44c01ef8f1b9154ce2313614daf075567f641))
* added positions to onAnimate, and prevent index to be negative with keyboard animations ([#2271](https://github.com/gorhom/react-native-bottom-sheet/issues/2271))(by [@souyahia](https://github.com/souyahia)) ([898270e](https://github.com/gorhom/react-native-bottom-sheet/commit/898270e62e0f83c8f8df671a60d6aabe749d890e))
* added support for web without Babel/SWC ([#1741](https://github.com/gorhom/react-native-bottom-sheet/issues/1741))(by [@joshsmith](https://github.com/joshsmith)) ([d620494](https://github.com/gorhom/react-native-bottom-sheet/commit/d620494877e98f4331d8c0a1cb7d375abb06db60))
* addressed an edge case with scrollview content sizing on initial rendering on safari ([d1226b7](https://github.com/gorhom/react-native-bottom-sheet/commit/d1226b70ac2405b4a98c8e5be6cee94ae110a35b))
* allow backdrop style prop to override internal style ([#211](https://github.com/gorhom/react-native-bottom-sheet/issues/211)) ([3ffd34b](https://github.com/gorhom/react-native-bottom-sheet/commit/3ffd34b21fb99a6b7b18ee689bb076f6883705c0))
* allow bottom sheet view to resize it self when its content resized ([5397478](https://github.com/gorhom/react-native-bottom-sheet/commit/53974786a18aceab1cc15def1b29c94ef93002e3))
* allow content to be accessible [#619](https://github.com/gorhom/react-native-bottom-sheet/issues/619) ([f1baf0e](https://github.com/gorhom/react-native-bottom-sheet/commit/f1baf0e4748fd84110d905f82404a86fd697c936))
* allow user to override showsVerticalScrollIndicator value on scrollables ([11cdc34](https://github.com/gorhom/react-native-bottom-sheet/commit/11cdc344e029200435280389b291441c1c363e97))
* allowed content max height be applied for dynamic sizing ([57c196c](https://github.com/gorhom/react-native-bottom-sheet/commit/57c196cfdf2f63622fb5ea8d6d32cf21b9dd9367))
* allowed keyboard height to be recalculated when it changes ([#931](https://github.com/gorhom/react-native-bottom-sheet/issues/931)) ([2f33bbe](https://github.com/gorhom/react-native-bottom-sheet/commit/2f33bbe8ddee66b959100fbe06c54eaf097138df))
* always update container height to avoid races. ([#919](https://github.com/gorhom/react-native-bottom-sheet/issues/919))(by [@elan](https://github.com/elan)) ([3245b23](https://github.com/gorhom/react-native-bottom-sheet/commit/3245b23653a38da2057f28d02f6d2bf1168864d0))
* always update handle height to avoid races.(related [#919](https://github.com/gorhom/react-native-bottom-sheet/issues/919)) ([dbf8945](https://github.com/gorhom/react-native-bottom-sheet/commit/dbf894591db8c72c4a0a4a5f1c2986f07ed4b1fb))
* animateToPoint callback dependencies ([468f920](https://github.com/gorhom/react-native-bottom-sheet/commit/468f9204d30fc327e5e6a3e1c43976a0afe13e51))
* apply additional panGH props to handle's gesture handler ([#152](https://github.com/gorhom/react-native-bottom-sheet/issues/152)) ([9321b00](https://github.com/gorhom/react-native-bottom-sheet/commit/9321b0057cecde065e7674cce28a9825d157521d))
* backdrop random appearance ([#378](https://github.com/gorhom/react-native-bottom-sheet/issues/378)) ([9ff77d0](https://github.com/gorhom/react-native-bottom-sheet/commit/9ff77d0924fab506a9b1b89aba7e2998fc7c887c))
* bottom sheet container layout measuring ([1c348bf](https://github.com/gorhom/react-native-bottom-sheet/commit/1c348bf68fe7a72c5d6c0cc9e73d6541d9f3a869))
* bottom sheet not appearing for users that have reduced motion turned on ([#1743](https://github.com/gorhom/react-native-bottom-sheet/issues/1743))(by [@fobos531](https://github.com/fobos531)) ([9b4ef4d](https://github.com/gorhom/react-native-bottom-sheet/commit/9b4ef4dabb7ce1f846ae90e2bab39fa9354ff125))
* **bottom-sheet-modal:** added container component prop to modal ([#1309](https://github.com/gorhom/react-native-bottom-sheet/issues/1309))(by [@magrinj](https://github.com/magrinj)) ([67e1e09](https://github.com/gorhom/react-native-bottom-sheet/commit/67e1e09acbc0e96e435a0c2247fa1e0bc19f91aa))
* **BottomSheetContainer:** cannot add new property 'value' ([#1808](https://github.com/gorhom/react-native-bottom-sheet/issues/1808))(by @MoritzCooks) ([ccd6bb5](https://github.com/gorhom/react-native-bottom-sheet/commit/ccd6bb540884f35fb9c0dcd5527ed8bac0c1be91))
* **BottomSheetScrollView:** updated scroll responders props type ([#1335](https://github.com/gorhom/react-native-bottom-sheet/issues/1335))(by [@eps1lon](https://github.com/eps1lon)) ([e42fafc](https://github.com/gorhom/react-native-bottom-sheet/commit/e42fafcc492d01665c296bf551a6a264eb866fc5))
* **BottomSheetTextInput:** reset shouldHandleKeyboardEvents on unmount ([#1495](https://github.com/gorhom/react-native-bottom-sheet/issues/1495))(by [@koplyarov](https://github.com/koplyarov)) ([81cd66f](https://github.com/gorhom/react-native-bottom-sheet/commit/81cd66f9c49843e43231d1d81ec4aa518a9f1b95))
* check if next and current indices are different before animating to a snap position ([#1095](https://github.com/gorhom/react-native-bottom-sheet/issues/1095))(by [@itsramiel](https://github.com/itsramiel)) ([3b75d5d](https://github.com/gorhom/react-native-bottom-sheet/commit/3b75d5d84e0a02933ef2b01d855d9f6036c756b2))
* clipped views when keyboard is closing ([2320a81](https://github.com/gorhom/react-native-bottom-sheet/commit/2320a81f95e696e22debe5a823740f51fadae0f6))
* closed bottom sheet snap point (by [@eastroot1590](https://github.com/eastroot1590)) ([#1043](https://github.com/gorhom/react-native-bottom-sheet/issues/1043), [#1035](https://github.com/gorhom/react-native-bottom-sheet/issues/1035)) ([c7f2ce2](https://github.com/gorhom/react-native-bottom-sheet/commit/c7f2ce26fdaf525951b70b76cd857e0b63cb4865))
* correctly check for non-null object ([#1122](https://github.com/gorhom/react-native-bottom-sheet/issues/1122))(by [@stropho](https://github.com/stropho)) ([54abf0c](https://github.com/gorhom/react-native-bottom-sheet/commit/54abf0c0832d1451dfe11be212fc5f938ff5c5fd))
* crash on swipe down ([#1367](https://github.com/gorhom/react-native-bottom-sheet/issues/1367))(by [@beqramo](https://github.com/beqramo)) ([3ccbefc](https://github.com/gorhom/react-native-bottom-sheet/commit/3ccbefc4d16558867d518f7e0306fbb4d1dbdbeb))
* crash when last snap point get removed ([31311f9](https://github.com/gorhom/react-native-bottom-sheet/commit/31311f920edf4b69ddecef20ece8d7943826e68b))
* dismiss all action for modals ([#1529](https://github.com/gorhom/react-native-bottom-sheet/issues/1529))(by [@david-gomes5](https://github.com/david-gomes5)) ([17269f1](https://github.com/gorhom/react-native-bottom-sheet/commit/17269f1f55b91f33cec24870ebe00f2510888a4b))
* dismiss keyboard when sheet position change on Android ([8f34990](https://github.com/gorhom/react-native-bottom-sheet/commit/8f34990436f8cc8c1ec1c545488d77db5845166c))
* don't react to snap point changes if height is 0 ([#855](https://github.com/gorhom/react-native-bottom-sheet/issues/855))(by [@simon-abbott](https://github.com/simon-abbott)) ([29af238](https://github.com/gorhom/react-native-bottom-sheet/commit/29af238d9eed31f0d9cad39ade8a43cf37ca2e72))
* dynamic sizing with detached static views ([b72e275](https://github.com/gorhom/react-native-bottom-sheet/commit/b72e27519c36671d84973f8b0b9cd1f8a7a8b8c1))
* exp easing flickers on android ([#175](https://github.com/gorhom/react-native-bottom-sheet/issues/175)) ([6223a4c](https://github.com/gorhom/react-native-bottom-sheet/commit/6223a4c8272fbc28a2f09d8cdf94f490e39c5e3a))
* fixed animated reaction for animated callback nodes ([#150](https://github.com/gorhom/react-native-bottom-sheet/issues/150)) ([72c2738](https://github.com/gorhom/react-native-bottom-sheet/commit/72c2738b49506f4aa4126383e7dc214cc7e1e27c))
* fixed dynamic scrollables content size with footer in place ([ace0da7](https://github.com/gorhom/react-native-bottom-sheet/commit/ace0da7475d68d4f27d386ead9f71c2eb19fbe31))
* fixed extracting paddingBottom in scrollable components ([945104a](https://github.com/gorhom/react-native-bottom-sheet/commit/945104ab532eb3cf63ea16cec348f3ef2ad6c584))
* fixed extracting paddingBottom in scrollable components ([64cef61](https://github.com/gorhom/react-native-bottom-sheet/commit/64cef618cd654486174cc6a8179a76c80ef5d497))
* fixed handling dynamic snap point on mount snapping ([35b2fcb](https://github.com/gorhom/react-native-bottom-sheet/commit/35b2fcb7d4eb1a2b953280a56396459b43b8767e))
* fixed initial content height calculation on web ([4db946e](https://github.com/gorhom/react-native-bottom-sheet/commit/4db946e4af331bb2d3a80002ee6051da9f3593eb))
* fixed interaction glitch ([#135](https://github.com/gorhom/react-native-bottom-sheet/issues/135)) ([a342fe6](https://github.com/gorhom/react-native-bottom-sheet/commit/a342fe6ac11e55bebc514cc0b90edf8cc1019226))
* fixed keyboard dismissing issue with Reanimated v3 ([#1346](https://github.com/gorhom/react-native-bottom-sheet/issues/1346))(by [@janicduplessis](https://github.com/janicduplessis)) ([1d1a464](https://github.com/gorhom/react-native-bottom-sheet/commit/1d1a46489bede1d3f119df2fb6f467e778461c39))
* fixed native projects to allow release builds ([516db83](https://github.com/gorhom/react-native-bottom-sheet/commit/516db837ab7ee3626905785d1210f8c23e42d4ce))
* fixed over-drag implementation ([#186](https://github.com/gorhom/react-native-bottom-sheet/issues/186)) ([78c7333](https://github.com/gorhom/react-native-bottom-sheet/commit/78c733353ab8d4e127c3c9f8995aa103bc446daa))
* fixed position x index sequencing with container resizing ([#1675](https://github.com/gorhom/react-native-bottom-sheet/issues/1675)) ([f0ec705](https://github.com/gorhom/react-native-bottom-sheet/commit/f0ec705cd74ea6e31614ab12c0b4fdc097d3820d))
* fixed reattach events onfocus ([#1](https://github.com/gorhom/react-native-bottom-sheet/issues/1)) ([fe3c56b](https://github.com/gorhom/react-native-bottom-sheet/commit/fe3c56bbce66b8cac5e7beb8c2ab5c90fd59292e))
* fixed sheet visibility when handle provided null ([#223](https://github.com/gorhom/react-native-bottom-sheet/issues/223)) ([5a1582e](https://github.com/gorhom/react-native-bottom-sheet/commit/5a1582e5ff1158e7178878b9758e1eff03254ae0))
* fixed shouldMeasureHandleHeight evaluation ([#157](https://github.com/gorhom/react-native-bottom-sheet/issues/157)) ([db2de5b](https://github.com/gorhom/react-native-bottom-sheet/commit/db2de5b6d78ebfcdc514b8abfb7f144ea9ff5941))
* fixed the backdrop tap gesture on web ([#1446](https://github.com/gorhom/react-native-bottom-sheet/issues/1446)) ([b0792de](https://github.com/gorhom/react-native-bottom-sheet/commit/b0792dea5ec605b449d40037cbecfd35bf0ff066))
* fixed the mount animation with reduce motion enabled ([#1560](https://github.com/gorhom/react-native-bottom-sheet/issues/1560), [#1674](https://github.com/gorhom/react-native-bottom-sheet/issues/1674)) ([6efd8ae](https://github.com/gorhom/react-native-bottom-sheet/commit/6efd8aeb0e312555fa77609869eedbf46a4a04b3))
* fixed the multiline issue on BottomSheetTextInput [#411](https://github.com/gorhom/react-native-bottom-sheet/issues/411) ([e21d676](https://github.com/gorhom/react-native-bottom-sheet/commit/e21d6762a929c6eaaf64e95d8af2934cc8b3a703))
* handle initial closed sheet ([4bc40d9](https://github.com/gorhom/react-native-bottom-sheet/commit/4bc40d93da05dcff664ce939a9944416b9e91359))
* hide the bottom sheet on closed ([#690](https://github.com/gorhom/react-native-bottom-sheet/issues/690)) ([9f04d55](https://github.com/gorhom/react-native-bottom-sheet/commit/9f04d557d202ab8570b1b409332bfdd129e5efa4))
* improve modal dismissing ([#346](https://github.com/gorhom/react-native-bottom-sheet/issues/346)) ([fd9ae1c](https://github.com/gorhom/react-native-bottom-sheet/commit/fd9ae1c0c1bdd8aec4485b1739299107d887aee8))
* on mount flicker on fixed sheet ([48c4988](https://github.com/gorhom/react-native-bottom-sheet/commit/48c49888b95dc88abf320d4d7590f43806e0bd59))
* pass correct params to animateToPosition ([#610](https://github.com/gorhom/react-native-bottom-sheet/issues/610)) ([01883fb](https://github.com/gorhom/react-native-bottom-sheet/commit/01883fb9575574c228cd40ec4a43658a6ea831c9))
* prevent animated content height value from getting below zero ([d9b417f](https://github.com/gorhom/react-native-bottom-sheet/commit/d9b417f703ceb69a959b0ce59600e53d75560d1e))
* prevent animatedIndex from flickering caused by content resizing ([7fef5d0](https://github.com/gorhom/react-native-bottom-sheet/commit/7fef5d03c0edef5945dc0bd825ce9081b90e7402))
* prevent animatedPosition from becoming undefined ([400d7b9](https://github.com/gorhom/react-native-bottom-sheet/commit/400d7b93caa0a46f678db2978e7e5f95cc87ee99))
* prevent animation to same position ([9636f84](https://github.com/gorhom/react-native-bottom-sheet/commit/9636f847d53ff99d801753254876722050cc3e13))
* prevent backdrop from blocking touchability ([#391](https://github.com/gorhom/react-native-bottom-sheet/issues/391)) ([d3a5c12](https://github.com/gorhom/react-native-bottom-sheet/commit/d3a5c12685326e0ba9ddb5cdb3948359223fffa6))
* prevent canceling touchmove events when not cancelable ([#2244](https://github.com/gorhom/react-native-bottom-sheet/issues/2244))(by [@erickreutz](https://github.com/erickreutz)) ([14d5d1e](https://github.com/gorhom/react-native-bottom-sheet/commit/14d5d1e89f22b5101445799fd0cb836ecb7c4882))
* prevent crash when resizing container height on Android ([#253](https://github.com/gorhom/react-native-bottom-sheet/issues/253)) ([759baa8](https://github.com/gorhom/react-native-bottom-sheet/commit/759baa84207a94b20665bad5eb79edb6c0e560bc))
* prevent default backdrop from blocking ui behind ([#246](https://github.com/gorhom/react-native-bottom-sheet/issues/246)) ([ea6affe](https://github.com/gorhom/react-native-bottom-sheet/commit/ea6affe27642fb5f923eabd871100f72e32e330e))
* prevent hiding bottom sheet container on platforms other than Android ([#719](https://github.com/gorhom/react-native-bottom-sheet/issues/719)) ([3da1a2e](https://github.com/gorhom/react-native-bottom-sheet/commit/3da1a2e6f33fb886e53606d4bbcd06938d839008))
* prevent keyboard change to snap sheet while user is interacting ([dd632b0](https://github.com/gorhom/react-native-bottom-sheet/commit/dd632b04651d37ab6a8a2aba2be13d9633e677e4))
* prevent scrollable glitches ([#142](https://github.com/gorhom/react-native-bottom-sheet/issues/142)) ([ac1c8ff](https://github.com/gorhom/react-native-bottom-sheet/commit/ac1c8ff09602805bd720a6cdc2775d74311756d5)), closes [#144](https://github.com/gorhom/react-native-bottom-sheet/issues/144)
* prevent sheet from being stuck on close ([#389](https://github.com/gorhom/react-native-bottom-sheet/issues/389)) ([18f27b9](https://github.com/gorhom/react-native-bottom-sheet/commit/18f27b980fe48f134bab54e166cae63d5500e6f9))
* prevent sheet from stucking on close state ([63a1891](https://github.com/gorhom/react-native-bottom-sheet/commit/63a189134cdc9f73c3bb495412ac3633197886c5))
* prevent snap points lower than 0 ([95ea72a](https://github.com/gorhom/react-native-bottom-sheet/commit/95ea72a459f96d40ad583c5579cc72f0e128e5dd))
* prevent stuck state when animation is interrupted ([01e1e87](https://github.com/gorhom/react-native-bottom-sheet/commit/01e1e8716477aa904bedbda2aa08642f8a0c3c9c))
* prevent the sheet from snapping while layout being calculated ([445a964](https://github.com/gorhom/react-native-bottom-sheet/commit/445a9645366af04931f4464d1befb1bc8e1dbbed))
* prevent unstable mounting for modals ([#697](https://github.com/gorhom/react-native-bottom-sheet/issues/697)) ([657505a](https://github.com/gorhom/react-native-bottom-sheet/commit/657505a65b01a1ccd7e2027b12fe1953967aa875))
* prevent updating backdrop state when unmounting ([#1657](https://github.com/gorhom/react-native-bottom-sheet/issues/1657))(by [@christophby](https://github.com/christophby)) ([d746d85](https://github.com/gorhom/react-native-bottom-sheet/commit/d746d85b92e2bdb4351ea4d3fde140e3199ac671))
* prevented animatedSnapPoints reaction from running randomly ([bf4e461](https://github.com/gorhom/react-native-bottom-sheet/commit/bf4e461e2cb9b5cb90a7de105637fc43d3947525))
* provide dynamic initial snap points while layout is calculating  ([#584](https://github.com/gorhom/react-native-bottom-sheet/issues/584)) ([98fb8d2](https://github.com/gorhom/react-native-bottom-sheet/commit/98fb8d24a55c064f0072c74c0bf2e1af079be819))
* provide the portal host name with use portal ([67e9097](https://github.com/gorhom/react-native-bottom-sheet/commit/67e909711164aba900c2764034723c8b0e051704))
* re-snap to current position when snap points get updated ([bb8e202](https://github.com/gorhom/react-native-bottom-sheet/commit/bb8e202af05dc6beeb108cfa1680401374ac58ad))
* refactored snap points reaction to handle keyboard state ([#497](https://github.com/gorhom/react-native-bottom-sheet/issues/497)) ([f8f2417](https://github.com/gorhom/react-native-bottom-sheet/commit/f8f2417454480207ae7a5a481b9fcd1483043e23))
* **regression:** updated keyboard handling reaction (by [@yusufyildirim](https://github.com/yusufyildirim)) ([#979](https://github.com/gorhom/react-native-bottom-sheet/issues/979)) ([1811239](https://github.com/gorhom/react-native-bottom-sheet/commit/1811239202f7dac2b55bb42cd1155d092f1c5694))
* remove 'removeListener' as it is now deprecated ([#635](https://github.com/gorhom/react-native-bottom-sheet/issues/635))(by [@brianathere](https://github.com/brianathere)) ([f03b05b](https://github.com/gorhom/react-native-bottom-sheet/commit/f03b05bbc39bf62f7d97422e717f2998f2e1fada))
* remove jumping on Android while starting scrolling ([#141](https://github.com/gorhom/react-native-bottom-sheet/issues/141)) ([b7b99ca](https://github.com/gorhom/react-native-bottom-sheet/commit/b7b99ca3bb4f82814b0db5320d406233c999da8a))
* removed disableIntervalMomentum animated value ([#13](https://github.com/gorhom/react-native-bottom-sheet/issues/13)) ([ca0d8cd](https://github.com/gorhom/react-native-bottom-sheet/commit/ca0d8cd1cd65e6b62fdf0c32e68aa2e6226baad6))
* removed flex style from draggable view ([29152fb](https://github.com/gorhom/react-native-bottom-sheet/commit/29152fb65672a07ff91249a882f0fc0f3d9b796c))
* removed keyboard height setting from hide event ([61473b5](https://github.com/gorhom/react-native-bottom-sheet/commit/61473b56c3389e5ac9edfeb1dc4b93907e3b5d05))
* removed redundant dependency ([3ffc7f7](https://github.com/gorhom/react-native-bottom-sheet/commit/3ffc7f70e8769fc1ecc39754111754b53d12bff8))
* removed rounding on evaluating position ([#201](https://github.com/gorhom/react-native-bottom-sheet/issues/201)) ([f028c3e](https://github.com/gorhom/react-native-bottom-sheet/commit/f028c3ec313ada02024ea1952aef01e2dd457701))
* removed rounding up from useNormalizedSnapPoints hook. ([#169](https://github.com/gorhom/react-native-bottom-sheet/issues/169)) ([1257c46](https://github.com/gorhom/react-native-bottom-sheet/commit/1257c462f68f4a0550211dddaffeecdd7d7c56a3)), closes [#168](https://github.com/gorhom/react-native-bottom-sheet/issues/168)
* replace getRefNativeTag with findNodeHandle ([#1823](https://github.com/gorhom/react-native-bottom-sheet/issues/1823))(by @AndreiCalazans) ([866b4ee](https://github.com/gorhom/react-native-bottom-sheet/commit/866b4ee570fc345d59053561c26af67144e8fd6f))
* replaced deprecated reanimated Extrapolate with Extrapolation ([#1875](https://github.com/gorhom/react-native-bottom-sheet/issues/1875))(by [@cenksari](https://github.com/cenksari)) ([5af3e80](https://github.com/gorhom/react-native-bottom-sheet/commit/5af3e803b0313154f42fbadba7dae6d32719c01c))
* resume animation on interruption ([#769](https://github.com/gorhom/react-native-bottom-sheet/issues/769)) ([f2a9332](https://github.com/gorhom/react-native-bottom-sheet/commit/f2a933274c88004357700bf728c1c3d1fde48d20))
* resume close animation when container gets resized ([#1374](https://github.com/gorhom/react-native-bottom-sheet/issues/1374)) ([#1392](https://github.com/gorhom/react-native-bottom-sheet/issues/1392)) ([1f69625](https://github.com/gorhom/react-native-bottom-sheet/commit/1f69625e180fcec4d8d3dec436f8d5bb4eba476b))
* return flipper back to make example working ([#70](https://github.com/gorhom/react-native-bottom-sheet/issues/70)) ([cadb22c](https://github.com/gorhom/react-native-bottom-sheet/commit/cadb22c3f10fa99d347c40762702e3882f2c8d31))
* revert changes on BottomSheetModal that blocked stack behavour ([15225ae](https://github.com/gorhom/react-native-bottom-sheet/commit/15225aef40fb5cb789fb077505edb5d710ab9e91))
* scrollble container style crash ([a4b9b93](https://github.com/gorhom/react-native-bottom-sheet/commit/a4b9b933268a670fbf6dd1198de61d899abde738))
* sheet positioning on modals ([ee573e9](https://github.com/gorhom/react-native-bottom-sheet/commit/ee573e9463836301d9736c3e5d86b2b363f9fb14))
* stabilise animated callback node variables ([#256](https://github.com/gorhom/react-native-bottom-sheet/issues/256)) ([0498e8c](https://github.com/gorhom/react-native-bottom-sheet/commit/0498e8c7f44f0a318d97e11a26a8f7f43bdeab25))
* stablise `animateToPoint` worklet callback ([4e15615](https://github.com/gorhom/react-native-bottom-sheet/commit/4e1561584b27c524c39a3b8f0bd3139a2afcf58e))
* stablise animated index when reacting to keyboard status ([26132c1](https://github.com/gorhom/react-native-bottom-sheet/commit/26132c14871af82eda7adf63ea98ab7a9f7d95e3))
* unmounting modals with navigation ([#315](https://github.com/gorhom/react-native-bottom-sheet/issues/315)) ([35ffee4](https://github.com/gorhom/react-native-bottom-sheet/commit/35ffee48e594c5b4a1209f32aa50aa04c5bd0b28))
* updated android keyboard handling ([f53306d](https://github.com/gorhom/react-native-bottom-sheet/commit/f53306d8d214d7dc605eb5ecb343f08f011c3ae2))
* updated animated closed position value on detached ([833879f](https://github.com/gorhom/react-native-bottom-sheet/commit/833879f3f703b80fb5bc591a823d86f3c56cc7ee))
* updated animation sequencing to respect force closing by user ([#1941](https://github.com/gorhom/react-native-bottom-sheet/issues/1941)) ([e4f3fe3](https://github.com/gorhom/react-native-bottom-sheet/commit/e4f3fe339b20a28d8573fa31f0d1b85be3ef2085))
* updated asigning velocity in animate worklet ([#650](https://github.com/gorhom/react-native-bottom-sheet/issues/650)) ([38b635e](https://github.com/gorhom/react-native-bottom-sheet/commit/38b635ec03d749cc0b7258ae2972ece722e0bb4a))
* updated BottomSheetBackdrop "falsey" default props ([#793](https://github.com/gorhom/react-native-bottom-sheet/issues/793))(by [@jakobo](https://github.com/jakobo)) ([7e00dd2](https://github.com/gorhom/react-native-bottom-sheet/commit/7e00dd2e30808a122d28ca1e37eebe19e450b884)), closes [#779](https://github.com/gorhom/react-native-bottom-sheet/issues/779)
* updated BottomSheetContainer measuring on android ([d0e5227](https://github.com/gorhom/react-native-bottom-sheet/commit/d0e52270076617242010b08f73fe09ab8ede69d1))
* updated BottomSheetModal mock, add createBottomSheetScrollableComponent and enum mocks ([#2265](https://github.com/gorhom/react-native-bottom-sheet/issues/2265))(by [@gabimoncha](https://github.com/gabimoncha)) ([a77904a](https://github.com/gorhom/react-native-bottom-sheet/commit/a77904ac935278bec4e086700e1e93baa54282b6))
* updated containerOffset top value to default to 0 ([#1420](https://github.com/gorhom/react-native-bottom-sheet/issues/1420))(by [@beqramo](https://github.com/beqramo)) ([b81cb93](https://github.com/gorhom/react-native-bottom-sheet/commit/b81cb9368b55c24703a9c000a76e89a2d253e141))
* updated default backdrop handling ([#126](https://github.com/gorhom/react-native-bottom-sheet/issues/126)) ([23c1b99](https://github.com/gorhom/react-native-bottom-sheet/commit/23c1b99b0451cd0fdab915b8da7ee2fe4a998e88))
* updated detached bottom sheet handling ([603f492](https://github.com/gorhom/react-native-bottom-sheet/commit/603f49294e572716d7eaf517a2adde01681c56c6))
* updated footer container export name ([a887141](https://github.com/gorhom/react-native-bottom-sheet/commit/a88714153a780395337b84efe00e3d410702c1d9))
* updated gesture props to be optional ([#380](https://github.com/gorhom/react-native-bottom-sheet/issues/380)) ([62f82a4](https://github.com/gorhom/react-native-bottom-sheet/commit/62f82a4f3ff735c75ecf0a49140cdbcbc363241d))
* updated initial position to screen height ([#657](https://github.com/gorhom/react-native-bottom-sheet/issues/657)) ([dc56417](https://github.com/gorhom/react-native-bottom-sheet/commit/dc56417c912b068d0ed2487517ae8f2ad2334b57))
* updated keyboard handling for Android ([2d74ab0](https://github.com/gorhom/react-native-bottom-sheet/commit/2d74ab069357f0ba430ff9f059dad0c6305eef48))
* updated keyboard height in container calculation ([2599f6c](https://github.com/gorhom/react-native-bottom-sheet/commit/2599f6cf46af0f95812e34670de5a7cae5d44fd9))
* updated reduce motion handling, to respeact user setting and allow overriding ([1ef05c7](https://github.com/gorhom/react-native-bottom-sheet/commit/1ef05c7fee821c356220452ccf61d33d29483c00))
* updated scrollables mocks with ReactNative list equivalent ([#1394](https://github.com/gorhom/react-native-bottom-sheet/issues/1394))(by [@gkueny](https://github.com/gkueny)) ([630f87f](https://github.com/gorhom/react-native-bottom-sheet/commit/630f87ff6bd19c4dfc071783139c938eda3baf6c))
* updated the enable content panning gesture logic ([2962a2d](https://github.com/gorhom/react-native-bottom-sheet/commit/2962a2d5326e517a48fe11d0e0d762beacca890d))
* updated the scrollable locking logic while scrolling ([#1939](https://github.com/gorhom/react-native-bottom-sheet/issues/1939)) ([d2b959c](https://github.com/gorhom/react-native-bottom-sheet/commit/d2b959c1f25f1aaeed1b30d21c43809c72490ef3))
* updated types for styles ([#616](https://github.com/gorhom/react-native-bottom-sheet/issues/616)) ([7fa1453](https://github.com/gorhom/react-native-bottom-sheet/commit/7fa14531fe2fe28ba9385fdcb22e4ca5e6aacf9e))
* updated typings for sectionlist to mirror rn core types ([#475](https://github.com/gorhom/react-native-bottom-sheet/issues/475)) ([dd9dbdc](https://github.com/gorhom/react-native-bottom-sheet/commit/dd9dbdc8d9fbeb5d557cee37841c5ca187c1b5fb))
* updated useStableCallback to set callback in ref without useEffect ([#2010](https://github.com/gorhom/react-native-bottom-sheet/issues/2010))(by [@pavel-krasnov](https://github.com/pavel-krasnov)) ([e898859](https://github.com/gorhom/react-native-bottom-sheet/commit/e89885936391f5ce106983d8aac814bcb422e82c))
* useStableCallback implementation ([87a73c5](https://github.com/gorhom/react-native-bottom-sheet/commit/87a73c59b83ef0b3868c12403a467ea3aebf0dd5))
* **web:** replace setNativeProps with useState ([#1076](https://github.com/gorhom/react-native-bottom-sheet/issues/1076))(by @RobertSasak) ([625049f](https://github.com/gorhom/react-native-bottom-sheet/commit/625049f47b266819b0b8a7d96b32e12e46837b37))
* **web:** use absolute positioning for BottomSheetContainer in web ([#1597](https://github.com/gorhom/react-native-bottom-sheet/issues/1597)) ([d6e3dc9](https://github.com/gorhom/react-native-bottom-sheet/commit/d6e3dc9b327b840895c875dcf016fb5c80a62915))


### Features

* add backdrop handling ([#124](https://github.com/gorhom/react-native-bottom-sheet/issues/124)) ([9650a48](https://github.com/gorhom/react-native-bottom-sheet/commit/9650a487b1139bca8895261fefacfeef6bdfa3fd))
* add third party gestures integration ([#143](https://github.com/gorhom/react-native-bottom-sheet/issues/143)) ([aa329d7](https://github.com/gorhom/react-native-bottom-sheet/commit/aa329d72169079fa55babe52a19656d3e7569e14))
* added a new bottom sheet stack behaviour `replace` ([#1897](https://github.com/gorhom/react-native-bottom-sheet/issues/1897))(with [@janodetzel](https://github.com/janodetzel)) ([997d794](https://github.com/gorhom/react-native-bottom-sheet/commit/997d794ccffe8739268ec50dfecca624e10f8752))
* added a prop to control flashing scrollable on expand ([#146](https://github.com/gorhom/react-native-bottom-sheet/issues/146)) ([025942c](https://github.com/gorhom/react-native-bottom-sheet/commit/025942c24e422e2b1f5f142ed3c3b19407fc80e4))
* added accessibility overrides support ([#1288](https://github.com/gorhom/react-native-bottom-sheet/issues/1288))(by @Mahmoud-SK) ([6203c18](https://github.com/gorhom/react-native-bottom-sheet/commit/6203c18acc9f8dc3a31af5bf5ad80e368deceb52))
* added animateOnMount prop ([#121](https://github.com/gorhom/react-native-bottom-sheet/issues/121)) ([e14374b](https://github.com/gorhom/react-native-bottom-sheet/commit/e14374b7c2585580067de06f0f876dd48f3dd034))
* added backgroundStyle, handleStyle & handleIndicatorStyle to bottom sheet ([2211765](https://github.com/gorhom/react-native-bottom-sheet/commit/221176546fd59ed0c9d79fe7f0350eda24dd8550))
* added bottom sheet modal ([#125](https://github.com/gorhom/react-native-bottom-sheet/issues/125)) ([4fe2f39](https://github.com/gorhom/react-native-bottom-sheet/commit/4fe2f39a8db24c2fa82b8d3d5007f3e3413b51e2))
* added data to present modal api ([#942](https://github.com/gorhom/react-native-bottom-sheet/issues/942)) ([8a3d138](https://github.com/gorhom/react-native-bottom-sheet/commit/8a3d13871a40e08e0c3deb302b60bbb2bcffd9f3))
* added default dynamic sizing ([#1513](https://github.com/gorhom/react-native-bottom-sheet/issues/1513))(with @Eli-Nathan & [@ororsatti](https://github.com/ororsatti)) ([#1683](https://github.com/gorhom/react-native-bottom-sheet/issues/1683)) ([8017fb6](https://github.com/gorhom/react-native-bottom-sheet/commit/8017fb6b02088d3c66c64a8a23e0f63f22884d36))
* added detached bottom sheet  ([#487](https://github.com/gorhom/react-native-bottom-sheet/issues/487)) ([3aa5fdb](https://github.com/gorhom/react-native-bottom-sheet/commit/3aa5fdbce75acf47f534e69b3a898abbf7dfca46))
* added enable pan down to close ([#437](https://github.com/gorhom/react-native-bottom-sheet/issues/437)) ([1f103b0](https://github.com/gorhom/react-native-bottom-sheet/commit/1f103b0d2c0a1661213b8c63af1db24cb0c191f7))
* added enableBlurKeyboardOnGesture prop to handle blurring keyboard on gesture ([1c31aca](https://github.com/gorhom/react-native-bottom-sheet/commit/1c31acad50a7c171548ea7f4594a4d1d563cf40f))
* added expand & collapse methods ([#8](https://github.com/gorhom/react-native-bottom-sheet/issues/8)) ([65af6f1](https://github.com/gorhom/react-native-bottom-sheet/commit/65af6f1e8a20ba8c07e2e4192027819bb46f6f96))
* added expo compatibility support ([2c3d545](https://github.com/gorhom/react-native-bottom-sheet/commit/2c3d545a10e6125fb66829a6784069b1b62f6798))
* added flashlist as a scrollable ([9bf39ed](https://github.com/gorhom/react-native-bottom-sheet/commit/9bf39ed08d7377937b0e8b8af65791b178c06492))
* added footer component ([#457](https://github.com/gorhom/react-native-bottom-sheet/issues/457)) ([46fb883](https://github.com/gorhom/react-native-bottom-sheet/commit/46fb88398ec7625c258cd62cb8560d72f3537fcb))
* added handling for keyboard height change ([#656](https://github.com/gorhom/react-native-bottom-sheet/issues/656))(by @Ferossgp) ([3c5fc57](https://github.com/gorhom/react-native-bottom-sheet/commit/3c5fc571e6442bd56712e9f4dbba89bbcd93dda1))
* added keyboard handling ([#334](https://github.com/gorhom/react-native-bottom-sheet/issues/334)) ([e024c73](https://github.com/gorhom/react-native-bottom-sheet/commit/e024c73729a819dfa4c2dc49b8d884ef96bcf2c4))
* added keyboard input mode for android ([069c4b6](https://github.com/gorhom/react-native-bottom-sheet/commit/069c4b6742630dc5fa7d4763a5c4dc6bfec439cc))
* added more gesture handler props ([#148](https://github.com/gorhom/react-native-bottom-sheet/issues/148)) ([33d226c](https://github.com/gorhom/react-native-bottom-sheet/commit/33d226c1fb4d23de6819d0454e8100e4659ba971))
* added onAnimate callback ([#127](https://github.com/gorhom/react-native-bottom-sheet/issues/127)) ([aeeb9a2](https://github.com/gorhom/react-native-bottom-sheet/commit/aeeb9a2d46152f35a2dd4a7439abf51d6cab4880))
* added onClose callback to BottomSheet ([ee64545](https://github.com/gorhom/react-native-bottom-sheet/commit/ee64545ce0e7609fb383f1473773c8481a0bc7aa))
* added over drag support ([#139](https://github.com/gorhom/react-native-bottom-sheet/issues/139)) ([36c2993](https://github.com/gorhom/react-native-bottom-sheet/commit/36c29935ba49a4e4e479aab33a14eb2f7aafed87))
* added over scroll and bouncing support ([#137](https://github.com/gorhom/react-native-bottom-sheet/issues/137)) ([d689731](https://github.com/gorhom/react-native-bottom-sheet/commit/d689731a4f18073181038aca6f03f0bed4619336))
* added pre-integrated VirtualizedList component ([2d4d69d](https://github.com/gorhom/react-native-bottom-sheet/commit/2d4d69d8881a3cbe452f5e46157e2b9702528206))
* added pull to refresh implementaion ([016a01f](https://github.com/gorhom/react-native-bottom-sheet/commit/016a01f3705c83c9903a3e28c875e7b90424a128))
* added Reanimated v2 compatibility ([#15](https://github.com/gorhom/react-native-bottom-sheet/issues/15) by [@sa8ab](https://github.com/sa8ab)) ([#24](https://github.com/gorhom/react-native-bottom-sheet/issues/24)) ([f38c6c6](https://github.com/gorhom/react-native-bottom-sheet/commit/f38c6c6ff8ccdac3ee9a35c91b02a70f81d0b00b))
* added snap to position ([#443](https://github.com/gorhom/react-native-bottom-sheet/issues/443)) ([9ca5f29](https://github.com/gorhom/react-native-bottom-sheet/commit/9ca5f29b200e1192712859dd9fe31f8c411fadf1))
* added stack behavior to bottom sheet modal ([#140](https://github.com/gorhom/react-native-bottom-sheet/issues/140)) ([84e06df](https://github.com/gorhom/react-native-bottom-sheet/commit/84e06dfa5cdaf0f9fea32e8823e19000272afd02))
* added style prop ([#189](https://github.com/gorhom/react-native-bottom-sheet/issues/189)) ([9ffd4e8](https://github.com/gorhom/react-native-bottom-sheet/commit/9ffd4e8b1883476ea4b75d95648d96a2eda005db))
* added web support ([#1150](https://github.com/gorhom/react-native-bottom-sheet/issues/1150)) ([a996b4a](https://github.com/gorhom/react-native-bottom-sheet/commit/a996b4aa68139136ec75e0921025d235471c838d)), closes [#1126](https://github.com/gorhom/react-native-bottom-sheet/issues/1126)
* allow control panning gestures ([#123](https://github.com/gorhom/react-native-bottom-sheet/issues/123)) ([3454fdd](https://github.com/gorhom/react-native-bottom-sheet/commit/3454fddddbb10624f61830bf0fe6fec9875b8bcb))
* allow custom pan gesture and scroll handler customisation  ([#525](https://github.com/gorhom/react-native-bottom-sheet/issues/525)) (by [@vonovak](https://github.com/vonovak)) ([4c32da7](https://github.com/gorhom/react-native-bottom-sheet/commit/4c32da7c0bb7e902883f009f10909286ad65042c))
* allow handle to drag sheet without effecting the scrollable ([580b763](https://github.com/gorhom/react-native-bottom-sheet/commit/580b7632e656403b0797c4e969a35d30f0ec5cb3))
* allow modify animation configs ([#333](https://github.com/gorhom/react-native-bottom-sheet/issues/333)) ([f78a663](https://github.com/gorhom/react-native-bottom-sheet/commit/f78a663e894da8641b756de6377cf7bbabe3b040))
* allow scrollable events ([#1019](https://github.com/gorhom/react-native-bottom-sheet/issues/1019)) ([2be6498](https://github.com/gorhom/react-native-bottom-sheet/commit/2be6498e3c564bd446a92f80df5de5ba6ce5f533))
* allow unsafe usage for useBottomSheetInternal & useBottomSheetModalInternal ([#740](https://github.com/gorhom/react-native-bottom-sheet/issues/740))(by [@jembach](https://github.com/jembach)) ([1bf6139](https://github.com/gorhom/react-native-bottom-sheet/commit/1bf613997cb7a7c8d1fd14f8253701e511a145c7))
* allow view scrollble to over-drag sheet ([2c2ca4e](https://github.com/gorhom/react-native-bottom-sheet/commit/2c2ca4ec17587689c2e38fcb0aad87a172251b55))
* introduced more stable handling for dynamic snap points ([3edb2d1](https://github.com/gorhom/react-native-bottom-sheet/commit/3edb2d1f9a9a8b1ba2e04803cd12306e4353199b))
* react to index prop changes ([55af54b](https://github.com/gorhom/react-native-bottom-sheet/commit/55af54bd772ff312f91891d7c88f33afa02f1efe))
* rewrite bottom sheet from scratch 🎉 ([#2](https://github.com/gorhom/react-native-bottom-sheet/issues/2)) ([a58a29f](https://github.com/gorhom/react-native-bottom-sheet/commit/a58a29fc0f9a8f92ce72dc59fefe83a86c6c8091))
* rewrite gesture apis with gesture handler 2 ([#1126](https://github.com/gorhom/react-native-bottom-sheet/issues/1126)) ([6a4d296](https://github.com/gorhom/react-native-bottom-sheet/commit/6a4d2967684b01e28f23b1b35afbb4cc4dabaf1d))
* support dynamic snap points ([#122](https://github.com/gorhom/react-native-bottom-sheet/issues/122)) ([d88f545](https://github.com/gorhom/react-native-bottom-sheet/commit/d88f545cf0b5177771bde173df00210b31452c03))
* support new prop for BottomSheetBackdrop, "pressBehavior" ([#361](https://github.com/gorhom/react-native-bottom-sheet/issues/361)) ([fa7ce63](https://github.com/gorhom/react-native-bottom-sheet/commit/fa7ce6338f336b97475b27461bd18af1f5ed85a3))
* updated reanimated to rc3 ([#268](https://github.com/gorhom/react-native-bottom-sheet/issues/268)) ([bb35274](https://github.com/gorhom/react-native-bottom-sheet/commit/bb35274ef4b13fdbc8f31106e0d23e60b4677754))


### Reverts

* **8b62dca:** added error message when dynamic sizing enabled with a wrong children type ([5714c1c](https://github.com/gorhom/react-native-bottom-sheet/commit/5714c1c850b66da9c9a0e8d08522a66076b35793))
* updated animate method parameter default value ([#1757](https://github.com/gorhom/react-native-bottom-sheet/issues/1757))(by [@jeongshin](https://github.com/jeongshin)) ([2784fa1](https://github.com/gorhom/react-native-bottom-sheet/commit/2784fa1415d461fd761f2bf29610bcbae1e0f8bb))

## [5.1.6](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.1.5...v5.1.6) (2025-06-03)


### Bug Fixes

* **#2267:** early exit when attempting to snap to index while layout is not ready ([0715f03](https://github.com/gorhom/react-native-bottom-sheet/commit/0715f0384a187cdb1df903d693666ac4b12db807)), closes [#2267](https://github.com/gorhom/react-native-bottom-sheet/issues/2267)
* **#2278:** removed flashlist for web ([e17096f](https://github.com/gorhom/react-native-bottom-sheet/commit/e17096feade145f9e6349815398f8aaae758d554)), closes [#2278](https://github.com/gorhom/react-native-bottom-sheet/issues/2278)
* added positions to onAnimate, and prevent index to be negative with keyboard animations ([#2271](https://github.com/gorhom/react-native-bottom-sheet/issues/2271))(by [@souyahia](https://github.com/souyahia)) ([898270e](https://github.com/gorhom/react-native-bottom-sheet/commit/898270e62e0f83c8f8df671a60d6aabe749d890e))
* allow bottom sheet view to resize it self when its content resized ([5397478](https://github.com/gorhom/react-native-bottom-sheet/commit/53974786a18aceab1cc15def1b29c94ef93002e3))
* updated BottomSheetModal mock, add createBottomSheetScrollableComponent and enum mocks ([#2265](https://github.com/gorhom/react-native-bottom-sheet/issues/2265))(by [@gabimoncha](https://github.com/gabimoncha)) ([a77904a](https://github.com/gorhom/react-native-bottom-sheet/commit/a77904ac935278bec4e086700e1e93baa54282b6))

## [5.1.5](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.1.4...v5.1.5) (2025-05-26)


### Bug Fixes

* **#2237:** fixed node handle lookup for virtualized list on web (by [@btoo](https://github.com/btoo)) ([6442b0e](https://github.com/gorhom/react-native-bottom-sheet/commit/6442b0ea54a38d8dcb82f63aade077ead29d382b))
* **#2288:** added unique id to the root bottom sheet modal portal ([711ea7a](https://github.com/gorhom/react-native-bottom-sheet/commit/711ea7a5290ef485b9ba5c65eb45e28d6e495b43)), closes [#2288](https://github.com/gorhom/react-native-bottom-sheet/issues/2288)
* fixed initial content height calculation on web ([4db946e](https://github.com/gorhom/react-native-bottom-sheet/commit/4db946e4af331bb2d3a80002ee6051da9f3593eb))
* prevent canceling touchmove events when not cancelable ([#2244](https://github.com/gorhom/react-native-bottom-sheet/issues/2244))(by [@erickreutz](https://github.com/erickreutz)) ([14d5d1e](https://github.com/gorhom/react-native-bottom-sheet/commit/14d5d1e89f22b5101445799fd0cb836ecb7c4882))
* provide the portal host name with use portal ([67e9097](https://github.com/gorhom/react-native-bottom-sheet/commit/67e909711164aba900c2764034723c8b0e051704))

## [5.1.4](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.1.3...v5.1.4) (2025-05-04)


### Bug Fixes

* **#2237:** fixed recursive loop in findNodeHandle.web (by @TNAJanssen) ([3556ba8](https://github.com/gorhom/react-native-bottom-sheet/commit/3556ba8e1445a78dfc6cfc93997500d52a03368e))

## [5.1.3](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.1.2...v5.1.3) (2025-05-04)


### Bug Fixes

* **#2237:** updated findNodeHandle for web to support React 19 ([47a95f5](https://github.com/gorhom/react-native-bottom-sheet/commit/47a95f517ab5b4680d0f5a45b09464911aafd35e)), closes [#2237](https://github.com/gorhom/react-native-bottom-sheet/issues/2237)

## [5.1.2](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.1.1...v5.1.2) (2025-03-09)


### Bug Fixes

* **#2163:** restart closing animation when container height get updated ([4ed9f3c](https://github.com/gorhom/react-native-bottom-sheet/commit/4ed9f3cb542316a984893efa2025ca5384ffe89a)), closes [#2163](https://github.com/gorhom/react-native-bottom-sheet/issues/2163)
* **#2177:** set absolute fill to backdrop default style ([979ba7c](https://github.com/gorhom/react-native-bottom-sheet/commit/979ba7ce0b9d69abfaefd169ee692bf818fa4d0d)), closes [#2177](https://github.com/gorhom/react-native-bottom-sheet/issues/2177)

## [5.1.1](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.1.0...v5.1.1) (2025-02-09)


### Bug Fixes

* **#2043:** handle unnecessary invocation of index side effect ([#2073](https://github.com/gorhom/react-native-bottom-sheet/issues/2073))(inspired by @IslamRustamov) ([2164c02](https://github.com/gorhom/react-native-bottom-sheet/commit/2164c02e63177f9ac69acc05722c85e8d55cd931)), closes [#2043](https://github.com/gorhom/react-native-bottom-sheet/issues/2043)

# [5.1.0](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.0.6...v5.1.0) (2025-02-06)


### Bug Fixes

* **#2129:** fixed initial isAnimatedOnMount value ([0850cb8](https://github.com/gorhom/react-native-bottom-sheet/commit/0850cb864819f79189592cb66c2b6d179957ba61))


### Features

* added enableBlurKeyboardOnGesture prop to handle blurring keyboard on gesture ([1c31aca](https://github.com/gorhom/react-native-bottom-sheet/commit/1c31acad50a7c171548ea7f4594a4d1d563cf40f))

## [5.0.6](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.0.5...v5.0.6) (2024-11-17)


### Bug Fixes

* clipped views when keyboard is closing ([2320a81](https://github.com/gorhom/react-native-bottom-sheet/commit/2320a81f95e696e22debe5a823740f51fadae0f6))
* removed keyboard height setting from hide event ([61473b5](https://github.com/gorhom/react-native-bottom-sheet/commit/61473b56c3389e5ac9edfeb1dc4b93907e3b5d05))
* updated useStableCallback to set callback in ref without useEffect ([#2010](https://github.com/gorhom/react-native-bottom-sheet/issues/2010))(by [@pavel-krasnov](https://github.com/pavel-krasnov)) ([e898859](https://github.com/gorhom/react-native-bottom-sheet/commit/e89885936391f5ce106983d8aac814bcb422e82c))
* useStableCallback implementation ([87a73c5](https://github.com/gorhom/react-native-bottom-sheet/commit/87a73c59b83ef0b3868c12403a467ea3aebf0dd5))

## [5.0.5](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.0.4...v5.0.5) (2024-10-26)


### Bug Fixes

* **#1983:** updated shared values access as hook dependancies ([#1992](https://github.com/gorhom/react-native-bottom-sheet/issues/1992))(by [@pinpong](https://github.com/pinpong)) ([9757bd2](https://github.com/gorhom/react-native-bottom-sheet/commit/9757bd251cba67cf26489640f20fd1557b1a426e)), closes [#1983](https://github.com/gorhom/react-native-bottom-sheet/issues/1983) [#1983](https://github.com/gorhom/react-native-bottom-sheet/issues/1983)
* added BottomSheetFlashList mock ([#1988](https://github.com/gorhom/react-native-bottom-sheet/issues/1988))(by @Fadikk367) ([13c7d47](https://github.com/gorhom/react-native-bottom-sheet/commit/13c7d47beae6f2451968d30e862f0ea49b7199b6))

## [5.0.4](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.0.3...v5.0.4) (2024-10-20)


### Bug Fixes

* **#1983:** updated shared values access as hook dependancies ([ae41b2d](https://github.com/gorhom/react-native-bottom-sheet/commit/ae41b2da650d2be614d840fbdfe1d29db6d7a575)), closes [#1983](https://github.com/gorhom/react-native-bottom-sheet/issues/1983)
* **#1987:** updated provided style handling for bottom sheet view ([4c8ae25](https://github.com/gorhom/react-native-bottom-sheet/commit/4c8ae252b8ec0bb420b60f8314cc7f04ed12b519)), closes [#1987](https://github.com/gorhom/react-native-bottom-sheet/issues/1987)

## [5.0.3](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.0.2...v5.0.3) (2024-10-20)


### Bug Fixes

* added children type to containerComponent prop type ([#1971](https://github.com/gorhom/react-native-bottom-sheet/issues/1971))(by @Nodonisko) ([203e52f](https://github.com/gorhom/react-native-bottom-sheet/commit/203e52fa5be3e167522776f184d79511bdf35344))
* dynamic sizing with detached static views ([b72e275](https://github.com/gorhom/react-native-bottom-sheet/commit/b72e27519c36671d84973f8b0b9cd1f8a7a8b8c1))
* fixed dynamic scrollables content size with footer in place ([ace0da7](https://github.com/gorhom/react-native-bottom-sheet/commit/ace0da7475d68d4f27d386ead9f71c2eb19fbe31))
* updated reduce motion handling, to respeact user setting and allow overriding ([1ef05c7](https://github.com/gorhom/react-native-bottom-sheet/commit/1ef05c7fee821c356220452ccf61d33d29483c00))

## [5.0.2](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.0.1...v5.0.2) (2024-10-14)


### Bug Fixes

* **#1035,#1043:** updated default animatedNextPositionIndex to INITIAL_VALUE ([#1960](https://github.com/gorhom/react-native-bottom-sheet/issues/1960))(by [@dfalling](https://github.com/dfalling)) ([1cf3e41](https://github.com/gorhom/react-native-bottom-sheet/commit/1cf3e4167f2ffacf36c7abebb527f79048754121)), closes [#1035](https://github.com/gorhom/react-native-bottom-sheet/issues/1035) [#1043](https://github.com/gorhom/react-native-bottom-sheet/issues/1043)
* **#1968:** moved the flashlist optional import into the component body ([ab33e21](https://github.com/gorhom/react-native-bottom-sheet/commit/ab33e2132f8e6fdb4a3c36e34c0f2ff04e09f11f)), closes [#1968](https://github.com/gorhom/react-native-bottom-sheet/issues/1968)

## [5.0.1](https://github.com/gorhom/react-native-bottom-sheet/compare/v5.0.0...v5.0.1) (2024-10-14)


### Bug Fixes

* removed redundant dependency ([3ffc7f7](https://github.com/gorhom/react-native-bottom-sheet/commit/3ffc7f70e8769fc1ecc39754111754b53d12bff8))

# [5.0.0](https://github.com/gorhom/react-native-bottom-sheet/compare/v4.6.4...v5.0.0) (2024-10-13)

### Features

* added web support (#1150) ([`a996b4a`](https://github.com/gorhom/react-native-bottom-sheet/commit/a996b4aa68139136ec75e0921025d235471c838d))
* added flashlist as a scrollable ([9bf39ed](https://github.com/gorhom/react-native-bottom-sheet/commit/9bf39ed08d7377937b0e8b8af65791b178c06492))
* rewrite gesture apis with gesture handler 2 (#1126) ([`6a4d296`](https://github.com/gorhom/react-native-bottom-sheet/commit/6a4d2967684b01e28f23b1b35afbb4cc4dabaf1d))
* added accessibility overrides support ([#1288](https://github.com/gorhom/react-native-bottom-sheet/issues/1288))(by @Mahmoud-SK) ([6203c18](https://github.com/gorhom/react-native-bottom-sheet/commit/6203c18acc9f8dc3a31af5bf5ad80e368deceb52))
* added default dynamic sizing ([#1513](https://github.com/gorhom/react-native-bottom-sheet/issues/1513))(with @Eli-Nathan & [@ororsatti](https://github.com/ororsatti)) ([#1683](https://github.com/gorhom/react-native-bottom-sheet/issues/1683)) ([8017fb6](https://github.com/gorhom/react-native-bottom-sheet/commit/8017fb6b02088d3c66c64a8a23e0f63f22884d36))
* added a new bottom sheet stack behaviour `replace` ([#1897](https://github.com/gorhom/react-native-bottom-sheet/issues/1897))(with [@janodetzel](https://github.com/janodetzel)) ([997d794](https://github.com/gorhom/react-native-bottom-sheet/commit/997d794ccffe8739268ec50dfecca624e10f8752))

### Bug Fixes

* addressed an edge case with scrollview content sizing on initial rendering on safari ([d1226b7](https://github.com/gorhom/react-native-bottom-sheet/commit/d1226b70ac2405b4a98c8e5be6cee94ae110a35b))
* replaced deprecated reanimated Extrapolate with Extrapolation ([#1875](https://github.com/gorhom/react-native-bottom-sheet/issues/1875))(by [@cenksari](https://github.com/cenksari)) ([5af3e80](https://github.com/gorhom/react-native-bottom-sheet/commit/5af3e803b0313154f42fbadba7dae6d32719c01c))
* updated animation sequencing to respect force closing by user ([#1941](https://github.com/gorhom/react-native-bottom-sheet/issues/1941)) ([e4f3fe3](https://github.com/gorhom/react-native-bottom-sheet/commit/e4f3fe339b20a28d8573fa31f0d1b85be3ef2085))
* updated the enable content panning gesture logic ([2962a2d](https://github.com/gorhom/react-native-bottom-sheet/commit/2962a2d5326e517a48fe11d0e0d762beacca890d))
* updated the scrollable locking logic while scrolling ([#1939](https://github.com/gorhom/react-native-bottom-sheet/issues/1939)) ([d2b959c](https://github.com/gorhom/react-native-bottom-sheet/commit/d2b959c1f25f1aaeed1b30d21c43809c72490ef3))
* updated the keyboard handling for Android with keyboard input mode resize ([08db4ab](https://github.com/gorhom/react-native-bottom-sheet/commit/08db4ab4b0058955e9ee2d55f87da8fefb5390ad))
* replace getRefNativeTag with findNodeHandle ([#1823](https://github.com/gorhom/react-native-bottom-sheet/issues/1823))(by @AndreiCalazans) ([866b4ee](https://github.com/gorhom/react-native-bottom-sheet/commit/866b4ee570fc345d59053561c26af67144e8fd6f))
* **BottomSheetContainer:** cannot add new property 'value' ([#1808](https://github.com/gorhom/react-native-bottom-sheet/issues/1808))(by @MoritzCooks) ([ccd6bb5](https://github.com/gorhom/react-native-bottom-sheet/commit/ccd6bb540884f35fb9c0dcd5527ed8bac0c1be91))
* added error message when dynamic sizing enabled with a wrong children type ([8b62dca](https://github.com/gorhom/react-native-bottom-sheet/commit/8b62dca06752a3c047162a693a75173a7c701e3e))
* bottom sheet not appearing for users that have reduced motion turned on ([#1743](https://github.com/gorhom/react-native-bottom-sheet/issues/1743))(by [@fobos531](https://github.com/fobos531)) ([9b4ef4d](https://github.com/gorhom/react-native-bottom-sheet/commit/9b4ef4dabb7ce1f846ae90e2bab39fa9354ff125))
* fixed the mount animation with reduce motion enabled ([#1560](https://github.com/gorhom/react-native-bottom-sheet/issues/1560), [#1674](https://github.com/gorhom/react-native-bottom-sheet/issues/1674)) ([6efd8ae](https://github.com/gorhom/react-native-bottom-sheet/commit/6efd8aeb0e312555fa77609869eedbf46a4a04b3))
* added BottomSheetTextInput to the mock file ([#1698](https://github.com/gorhom/react-native-bottom-sheet/issues/1698))(by [@ghorbani-m](https://github.com/ghorbani-m)) ([dee95e5](https://github.com/gorhom/react-native-bottom-sheet/commit/dee95e5b161d78b0aae34d85abea3d8042417892))
* added footer height to content height when using dynamic sizing ([#1725](https://github.com/gorhom/react-native-bottom-sheet/issues/1725)) ([5009085](https://github.com/gorhom/react-native-bottom-sheet/commit/50090859f9e50932c641df5b0d6f91cc9f3b5bad))
* added missing mock of Touchables ([#1700](https://github.com/gorhom/react-native-bottom-sheet/issues/1700))(by [@jaworek](https://github.com/jaworek)) ([a6f44c0](https://github.com/gorhom/react-native-bottom-sheet/commit/a6f44c01ef8f1b9154ce2313614daf075567f641))
* added support for web without Babel/SWC ([#1741](https://github.com/gorhom/react-native-bottom-sheet/issues/1741))(by [@joshsmith](https://github.com/joshsmith)) ([d620494](https://github.com/gorhom/react-native-bottom-sheet/commit/d620494877e98f4331d8c0a1cb7d375abb06db60))
* fixed the backdrop tap gesture on web ([#1446](https://github.com/gorhom/react-native-bottom-sheet/issues/1446)) ([b0792de](https://github.com/gorhom/react-native-bottom-sheet/commit/b0792dea5ec605b449d40037cbecfd35bf0ff066))
* allowed content max height be applied for dynamic sizing ([57c196c](https://github.com/gorhom/react-native-bottom-sheet/commit/57c196cfdf2f63622fb5ea8d6d32cf21b9dd9367))
* dismiss all action for modals ([#1529](https://github.com/gorhom/react-native-bottom-sheet/issues/1529))(by [@david-gomes5](https://github.com/david-gomes5)) ([17269f1](https://github.com/gorhom/react-native-bottom-sheet/commit/17269f1f55b91f33cec24870ebe00f2510888a4b))
* fixed position x index sequencing with container resizing ([#1675](https://github.com/gorhom/react-native-bottom-sheet/issues/1675)) ([f0ec705](https://github.com/gorhom/react-native-bottom-sheet/commit/f0ec705cd74ea6e31614ab12c0b4fdc097d3820d))
* prevent updating backdrop state when unmounting ([#1657](https://github.com/gorhom/react-native-bottom-sheet/issues/1657))(by [@christophby](https://github.com/christophby)) ([d746d85](https://github.com/gorhom/react-native-bottom-sheet/commit/d746d85b92e2bdb4351ea4d3fde140e3199ac671))
* **web:** use absolute positioning for BottomSheetContainer in web ([#1597](https://github.com/gorhom/react-native-bottom-sheet/issues/1597)) ([d6e3dc9](https://github.com/gorhom/react-native-bottom-sheet/commit/d6e3dc9b327b840895c875dcf016fb5c80a62915))
* (BottomSheetTextInput): reset shouldHandleKeyboardEvents on unmount (#1495)(by @koplyarov) ([`81cd66f`](https://github.com/gorhom/react-native-bottom-sheet/commit/81cd66f9c49843e43231d1d81ec4aa518a9f1b95))
* updated containerOffset top value to default to 0 (#1420)(by @beqramo) ([`b81cb93`](https://github.com/gorhom/react-native-bottom-sheet/commit/b81cb9368b55c24703a9c000a76e89a2d253e141))
* resume close animation when container gets resized (#1374) (#1392) ([`1f69625`](https://github.com/gorhom/react-native-bottom-sheet/commit/1f69625e180fcec4d8d3dec436f8d5bb4eba476b))
* (bottom-sheet-modal): added container component prop to modal (#1309)(by @magrinj) ([`67e1e09`](https://github.com/gorhom/react-native-bottom-sheet/commit/67e1e09acbc0e96e435a0c2247fa1e0bc19f91aa))
* updated scrollables mocks with ReactNative list equivalent (#1394)(by @gkueny) ([`630f87f`](https://github.com/gorhom/react-native-bottom-sheet/commit/630f87ff6bd19c4dfc071783139c938eda3baf6c))
* crash on swipe down (#1367)(by @beqramo) ([`3ccbefc`](https://github.com/gorhom/react-native-bottom-sheet/commit/3ccbefc4d16558867d518f7e0306fbb4d1dbdbeb))
* (BottomSheetScrollView): updated scroll responders props type (#1335)(by @eps1lon) ([`e42fafc`](https://github.com/gorhom/react-native-bottom-sheet/commit/e42fafcc492d01665c296bf551a6a264eb866fc5))
* fixed keyboard dismissing issue with Reanimated v3 (#1346)(by @janicduplessis) ([`1d1a464`](https://github.com/gorhom/react-native-bottom-sheet/commit/1d1a46489bede1d3f119df2fb6f467e778461c39))
- (#1119): fixed race condition between onmount and keyboard animations ([`a1ec74d`](https://github.com/gorhom/react-native-bottom-sheet/commit/a1ec74dbbc85476bb39f3637e9a97214e0cad9a0))

#### Chores And Housekeeping

* updated expo and react native deps (#1445) ([`f6f2304`](https://github.com/gorhom/react-native-bottom-sheet/commit/f6f2304235c05f92d86ce8083caf910b9297a10a))
* updated react native and other deps (#1412) ([`549e461`](https://github.com/gorhom/react-native-bottom-sheet/commit/549e461530a91e1d7c95a5178bd2238ebf84df86))
* fixed types (#1123)(by @stropho) ([`b440964`](https://github.com/gorhom/react-native-bottom-sheet/commit/b44096451d4fed81be7f08b0edf638e4a1c42ccd))
* updated reanimated to v3 (#1324) ([`4829316`](https://github.com/gorhom/react-native-bottom-sheet/commit/4829316beeff95c9e2efa5fbfdfcf7ef37b4af60))
