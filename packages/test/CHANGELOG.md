# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [8.9.0](https://github.com/IBM/kui/compare/v4.5.0...v8.9.0) (2020-06-09)

### Bug Fixes

- about should show breadcrumbs ([99dc401](https://github.com/IBM/kui/commit/99dc401)), closes [#4730](https://github.com/IBM/kui/issues/4730)
- allow user to disable table title by feature flags, and disable table pagination ([5450512](https://github.com/IBM/kui/commit/5450512)), closes [#4640](https://github.com/IBM/kui/issues/4640) [#4655](https://github.com/IBM/kui/issues/4655)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- avoid recomputing tabs when switching back and forth ([cf5e41f](https://github.com/IBM/kui/commit/cf5e41f)), closes [#4666](https://github.com/IBM/kui/issues/4666)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- hitting escape on initial page load toggles open empty sidecar ([8fbdce5](https://github.com/IBM/kui/commit/8fbdce5)), closes [#4487](https://github.com/IBM/kui/issues/4487)
- improve alignment of icons ([221d0f9](https://github.com/IBM/kui/commit/221d0f9)), closes [#4555](https://github.com/IBM/kui/issues/4555)
- improve error reporting for kubectl apply ([fe21671](https://github.com/IBM/kui/commit/fe21671)), closes [#4605](https://github.com/IBM/kui/issues/4605)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Input element throws react error ([e6bb21b](https://github.com/IBM/kui/commit/e6bb21b)), closes [#4765](https://github.com/IBM/kui/issues/4765)
- kubectl edit apply twice does not work ([1976134](https://github.com/IBM/kui/commit/1976134)), closes [#4797](https://github.com/IBM/kui/issues/4797)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- sidecar toolbar can't due justice to longer error messages ([e67e0c9](https://github.com/IBM/kui/commit/e67e0c9)), closes [#4789](https://github.com/IBM/kui/issues/4789)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **plugin-kubectl:** k get pods --all-namespaces has a title with "default" as the namespace ([2f95129](https://github.com/IBM/kui/commit/2f95129)), closes [#4466](https://github.com/IBM/kui/issues/4466)
- **plugins/plugin-client-common:** stop using Carbon's TooltipIcon for DropDown ([be04d20](https://github.com/IBM/kui/commit/be04d20)), closes [#4767](https://github.com/IBM/kui/issues/4767)
- kubectl api-resources has duplicate rows and odd pagination behavior ([e740270](https://github.com/IBM/kui/commit/e740270)), closes [#4626](https://github.com/IBM/kui/issues/4626)
- remove config.d/version.json in favor of using the version field from package.json ([1e296c7](https://github.com/IBM/kui/commit/1e296c7)), closes [#4300](https://github.com/IBM/kui/issues/4300)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- sidecar back/forward should be ordered by visitation rather than insertion ([fba613a](https://github.com/IBM/kui/commit/fba613a)), closes [#4746](https://github.com/IBM/kui/issues/4746)
- sidecar Toolbar component renders empty if there is no Toolbar content ([14c27ba](https://github.com/IBM/kui/commit/14c27ba)), closes [#4229](https://github.com/IBM/kui/issues/4229)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)
- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)

### Features

- add button to WatchPane to show table back in terminal ([dc22591](https://github.com/IBM/kui/commit/dc22591)), closes [#4530](https://github.com/IBM/kui/issues/4530)
- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- add Stop Watching capability to WatchPane ([09043c1](https://github.com/IBM/kui/commit/09043c1)), closes [#4554](https://github.com/IBM/kui/issues/4554)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl edit via kui's editor ([414e813](https://github.com/IBM/kui/commit/414e813)), closes [#762](https://github.com/IBM/kui/issues/762)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- port kubectl get ns to RadioTable ([be0eabf](https://github.com/IBM/kui/commit/be0eabf)), closes [#4510](https://github.com/IBM/kui/issues/4510) [#4511](https://github.com/IBM/kui/issues/4511)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- split screen Terminal ([3a6b422](https://github.com/IBM/kui/commit/3a6b422)), closes [#4814](https://github.com/IBM/kui/issues/4814) [#4821](https://github.com/IBM/kui/issues/4821)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- target kubectl logs and kubectl exec to Logs and Terminal tabs ([409e632](https://github.com/IBM/kui/commit/409e632)), closes [#4762](https://github.com/IBM/kui/issues/4762)
- top tab buttons ([ff8cfba](https://github.com/IBM/kui/commit/ff8cfba)), closes [#4434](https://github.com/IBM/kui/issues/4434)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- watcher panel for open-ended watch jobs ([6dfe7df](https://github.com/IBM/kui/commit/6dfe7df)), closes [#4503](https://github.com/IBM/kui/issues/4503)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

# [8.7.0](https://github.com/IBM/kui/compare/v4.5.0...v8.7.0) (2020-05-08)

### Bug Fixes

- hitting escape on initial page load toggles open empty sidecar ([8fbdce5](https://github.com/IBM/kui/commit/8fbdce5)), closes [#4487](https://github.com/IBM/kui/issues/4487)
- **plugin-kubectl:** k get pods --all-namespaces has a title with "default" as the namespace ([2f95129](https://github.com/IBM/kui/commit/2f95129)), closes [#4466](https://github.com/IBM/kui/issues/4466)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- remove config.d/version.json in favor of using the version field from package.json ([1e296c7](https://github.com/IBM/kui/commit/1e296c7)), closes [#4300](https://github.com/IBM/kui/issues/4300)
- sidecar Toolbar component renders empty if there is no Toolbar content ([14c27ba](https://github.com/IBM/kui/commit/14c27ba)), closes [#4229](https://github.com/IBM/kui/issues/4229)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl edit via kui's editor ([414e813](https://github.com/IBM/kui/commit/414e813)), closes [#762](https://github.com/IBM/kui/issues/762)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- top tab buttons ([ff8cfba](https://github.com/IBM/kui/commit/ff8cfba)), closes [#4434](https://github.com/IBM/kui/issues/4434)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

## [8.6.1](https://github.com/IBM/kui/compare/v4.5.0...v8.6.1) (2020-04-25)

### Bug Fixes

- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- remove config.d/version.json in favor of using the version field from package.json ([1e296c7](https://github.com/IBM/kui/commit/1e296c7)), closes [#4300](https://github.com/IBM/kui/issues/4300)
- sidecar Toolbar component renders empty if there is no Toolbar content ([14c27ba](https://github.com/IBM/kui/commit/14c27ba)), closes [#4229](https://github.com/IBM/kui/issues/4229)
- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

# [8.6.0](https://github.com/IBM/kui/compare/v4.5.0...v8.6.0) (2020-04-23)

### Bug Fixes

- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- remove config.d/version.json in favor of using the version field from package.json ([1e296c7](https://github.com/IBM/kui/commit/1e296c7)), closes [#4300](https://github.com/IBM/kui/issues/4300)
- sidecar Toolbar component renders empty if there is no Toolbar content ([14c27ba](https://github.com/IBM/kui/commit/14c27ba)), closes [#4229](https://github.com/IBM/kui/issues/4229)
- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

# [8.5.0](https://github.com/IBM/kui/compare/v4.5.0...v8.5.0) (2020-04-19)

### Bug Fixes

- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- remove config.d/version.json in favor of using the version field from package.json ([1e296c7](https://github.com/IBM/kui/commit/1e296c7)), closes [#4300](https://github.com/IBM/kui/issues/4300)
- sidecar Toolbar component renders empty if there is no Toolbar content ([14c27ba](https://github.com/IBM/kui/commit/14c27ba)), closes [#4229](https://github.com/IBM/kui/issues/4229)
- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

## [8.4.2](https://github.com/IBM/kui/compare/v4.5.0...v8.4.2) (2020-04-10)

### Bug Fixes

- sidecar Toolbar component renders empty if there is no Toolbar content ([14c27ba](https://github.com/IBM/kui/commit/14c27ba)), closes [#4229](https://github.com/IBM/kui/issues/4229)
- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

## [8.4.1](https://github.com/IBM/kui/compare/v4.5.0...v8.4.1) (2020-04-10)

### Bug Fixes

- sidecar Toolbar component renders empty if there is no Toolbar content ([14c27ba](https://github.com/IBM/kui/commit/14c27ba)), closes [#4229](https://github.com/IBM/kui/issues/4229)
- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

# [8.4.0](https://github.com/IBM/kui/compare/v4.5.0...v8.4.0) (2020-04-10)

### Bug Fixes

- sidecar Toolbar component renders empty if there is no Toolbar content ([14c27ba](https://github.com/IBM/kui/commit/14c27ba)), closes [#4229](https://github.com/IBM/kui/issues/4229)
- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

# [8.1.0](https://github.com/IBM/kui/compare/v4.5.0...v8.1.0) (2020-04-04)

### Bug Fixes

- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- add labels to summary mode ([95f731d](https://github.com/IBM/kui/commit/95f731d)), closes [#4041](https://github.com/IBM/kui/issues/4041) [#4040](https://github.com/IBM/kui/issues/4040)
- add Show Owner Reference button for kube resources ([80ea40f](https://github.com/IBM/kui/commit/80ea40f)), closes [#4106](https://github.com/IBM/kui/issues/4106)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- improve pagination and toolbar UIs of PaginatedTable ([08062e9](https://github.com/IBM/kui/commit/08062e9)), closes [#1456](https://github.com/IBM/kui/issues/1456)
- kubectl tables should show official kind in title ([06eec95](https://github.com/IBM/kui/commit/06eec95)), closes [#4127](https://github.com/IBM/kui/issues/4127)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- render kubectl summary tab using forms ([d88436e](https://github.com/IBM/kui/commit/d88436e)), closes [#4014](https://github.com/IBM/kui/issues/4014)
- resize the popup window ([41bf5cf](https://github.com/IBM/kui/commit/41bf5cf)), closes [#4161](https://github.com/IBM/kui/issues/4161)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- use breadcrumbs for TopNavSidecar naming ([5a4611e](https://github.com/IBM/kui/commit/5a4611e)), closes [#4043](https://github.com/IBM/kui/issues/4043) [#3657](https://github.com/IBM/kui/issues/3657) [#4044](https://github.com/IBM/kui/issues/4044)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

# [8.0.0](https://github.com/IBM/kui/compare/v4.5.0...v8.0.0) (2020-03-20)

### Bug Fixes

- **plugins/plugin-sidecar:** when nameHash is displayed, TopNavSidecar doesn't render the dehashed name ([ef887f4](https://github.com/IBM/kui/commit/ef887f4)), closes [#3969](https://github.com/IBM/kui/issues/3969)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- eliminate use of custom <tab> tag ([00e2728](https://github.com/IBM/kui/commit/00e2728)), closes [#3777](https://github.com/IBM/kui/issues/3777)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- Popup client should place InputStripe inside of StatusStripe ([a09138d](https://github.com/IBM/kui/commit/a09138d)), closes [#3949](https://github.com/IBM/kui/issues/3949)
- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- return an NavResponse without links results in blank page ([e684344](https://github.com/IBM/kui/commit/e684344)), closes [#3927](https://github.com/IBM/kui/issues/3927)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/core:** MMR rendering is glitchy ([5ce89aa](https://github.com/IBM/kui/commit/5ce89aa)), closes [#3589](https://github.com/IBM/kui/issues/3589)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- **plugins/plugin-client-common:** keyboard shortcuts for TopTabStripe aren't working ([24d074f](https://github.com/IBM/kui/commit/24d074f)), closes [#3643](https://github.com/IBM/kui/issues/3643)

### Features

- add history to sidecar views ([b1e5543](https://github.com/IBM/kui/commit/b1e5543)), closes [#3960](https://github.com/IBM/kui/issues/3960)
- carbon tables ([237e9a5](https://github.com/IBM/kui/commit/237e9a5)), closes [#3632](https://github.com/IBM/kui/issues/3632)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)
- left-navigation sidecar ([f88329e](https://github.com/IBM/kui/commit/f88329e)), closes [#3635](https://github.com/IBM/kui/issues/3635)
- new client-alternate for bottom-input mode and custom css ([d25f7a0](https://github.com/IBM/kui/commit/d25f7a0)), closes [#3608](https://github.com/IBM/kui/issues/3608)
- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- refine NavResponse and add NavLinks support in LeftNavSidecar ([f1d8d98](https://github.com/IBM/kui/commit/f1d8d98)), closes [#3902](https://github.com/IBM/kui/issues/3902)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- support ReactElement as MultiModalResponse modes ([a20e289](https://github.com/IBM/kui/commit/a20e289)), closes [#3793](https://github.com/IBM/kui/issues/3793)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)

## [6.0.12](https://github.com/IBM/kui/compare/v6.0.11...v6.0.12) (2020-02-03)

**Note:** Version bump only for package @kui-shell/test

## [6.0.11](https://github.com/IBM/kui/compare/v6.0.10...v6.0.11) (2020-02-03)

### Bug Fixes

- **packages/core:** MMR rendering is glitchy ([d314439](https://github.com/IBM/kui/commit/d314439)), closes [#3589](https://github.com/IBM/kui/issues/3589)

## [6.0.10](https://github.com/IBM/kui/compare/v6.0.9...v6.0.10) (2020-02-01)

**Note:** Version bump only for package @kui-shell/test

## [6.0.9](https://github.com/IBM/kui/compare/v6.0.8...v6.0.9) (2020-01-31)

**Note:** Version bump only for package @kui-shell/test

## [6.0.8](https://github.com/IBM/kui/compare/v4.5.0...v6.0.8) (2020-01-30)

### Bug Fixes

- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)

### Features

- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

## [6.0.7](https://github.com/IBM/kui/compare/v4.5.0...v6.0.7) (2020-01-30)

### Bug Fixes

- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)

### Features

- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

## [6.0.6](https://github.com/IBM/kui/compare/v4.5.0...v6.0.6) (2020-01-30)

### Bug Fixes

- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)

### Features

- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

## [6.0.5](https://github.com/IBM/kui/compare/v4.5.0...v6.0.5) (2020-01-29)

### Bug Fixes

- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)

### Features

- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

## [6.0.4](https://github.com/IBM/kui/compare/v6.0.3...v6.0.4) (2020-01-28)

**Note:** Version bump only for package @kui-shell/test

## [6.0.3](https://github.com/IBM/kui/compare/v4.5.0...v6.0.3) (2020-01-28)

### Bug Fixes

- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)

### Features

- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

## [6.0.2](https://github.com/IBM/kui/compare/v4.5.0...v6.0.2) (2020-01-28)

### Bug Fixes

- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)

### Features

- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

## [6.0.1](https://github.com/IBM/kui/compare/v4.5.0...v6.0.1) (2020-01-28)

### Bug Fixes

- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)

### Features

- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

# [6.0.0](https://github.com/IBM/kui/compare/v4.5.0...v6.0.0) (2020-01-27)

### Bug Fixes

- reducing flashing effect for PTY command not found errors ([f160337](https://github.com/IBM/kui/commit/f160337)), closes [#3449](https://github.com/IBM/kui/issues/3449)
- **packages/core:** mmr couldn't show up when the sidecar is minimized ([91cd2cc](https://github.com/IBM/kui/commit/91cd2cc)), closes [#3164](https://github.com/IBM/kui/issues/3164)
- **packages/test:** runMochaLayersv2.sh should export WEBPACK_CLIENT_URL ([14fcdc9](https://github.com/IBM/kui/commit/14fcdc9)), closes [#3407](https://github.com/IBM/kui/issues/3407)
- improve windows build support ([cacd68b](https://github.com/IBM/kui/commit/cacd68b)), closes [#3332](https://github.com/IBM/kui/issues/3332)
- **packages/test:** nameHash waitUntil does not use waitTimeout ([5c996f4](https://github.com/IBM/kui/commit/5c996f4)), closes [#3246](https://github.com/IBM/kui/issues/3246)
- another fix for codecov ([0b10599](https://github.com/IBM/kui/commit/0b10599)), closes [#3217](https://github.com/IBM/kui/issues/3217)
- **packages/core:** sidecar basic function should not require plugins ([07aa3e3](https://github.com/IBM/kui/commit/07aa3e3)), closes [#3172](https://github.com/IBM/kui/issues/3172)
- **packages/test:** runMochaLayers versus external clients ([89578dc](https://github.com/IBM/kui/commit/89578dc)), closes [#3106](https://github.com/IBM/kui/issues/3106)

### Features

- pty should allow for streaming consumption of output ([1886e58](https://github.com/IBM/kui/commit/1886e58)), closes [#3451](https://github.com/IBM/kui/issues/3451)
- support generating es6 modules ([c1ed680](https://github.com/IBM/kui/commit/c1ed680)), closes [#2431](https://github.com/IBM/kui/issues/2431)
- **packages/core:** pass a PreloadRegistrar to plugin preloaders ([54d727a](https://github.com/IBM/kui/commit/54d727a)), closes [#3189](https://github.com/IBM/kui/issues/3189)
- **packages/core:** support updating Table from push notifications ([6bfb255](https://github.com/IBM/kui/commit/6bfb255)), closes [#3295](https://github.com/IBM/kui/issues/3295)
- client test ([4c16985](https://github.com/IBM/kui/commit/4c16985)), closes [#3130](https://github.com/IBM/kui/issues/3130)
- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

# [5.1.0](https://github.com/IBM/kui/compare/v4.5.0...v5.1.0) (2019-10-11)

### Features

- enable plugin-manager for electron clients ([4814cb9](https://github.com/IBM/kui/commit/4814cb9)), closes [#2935](https://github.com/IBM/kui/issues/2935)

# [5.0.0](https://github.com/IBM/kui/compare/v4.5.0...v5.0.0) (2019-10-03)

**Note:** Version bump only for package @kui-shell/test
