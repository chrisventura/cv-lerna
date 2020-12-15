# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

### [5.1.1](https://github.com/chrisventura/cv-lerna/compare/@cv/test-package@5.1.0...@cv/test-package@5.1.1) (2020-12-03)


### Bug Fixes

* small fix is small ([9871ea2](https://github.com/chrisventura/cv-lerna/commit/9871ea263405830fe6d2621c688fda80aabe8737))



## [5.1.0](https://github.com/chrisventura/cv-lerna/compare/@cv/test-package@5.0.0...@cv/test-package@5.1.0) (2020-12-03)


### Features

* changes in two packages ([#4](https://github.com/chrisventura/cv-lerna/issues/4)) ([16ed7e5](https://github.com/chrisventura/cv-lerna/commit/16ed7e560b87a278d424ec5ec41cb44af5a83a0e))




## [5.0.0](https://github.com/chrisventura/cv-lerna/compare/@cv/test-package@4.0.0...@cv/test-package@5.0.0) (2020-12-03)


### ⚠ BREAKING CHANGES

* secret breaking

### Bug Fixes

* secret breaking ([014634a](https://github.com/chrisventura/cv-lerna/commit/014634a507434924b255aaf49c0ecb276b8f430f))



## [4.0.0](https://github.com/chrisventura/cv-lerna/compare/@cv/test-package@3.0.0...@cv/test-package@4.0.0) (2020-12-03)


### ⚠ BREAKING CHANGES

* this is a big one bro.

### Features

* another big change ([717ed17](https://github.com/chrisventura/cv-lerna/commit/717ed17e751ff14625a495612ab7d06dbe505ebe))



# [3.0.0](https://github.com/chrisventura/cv-lerna/compare/@cv/test-package@2.0.3...@cv/test-package@3.0.0) (2020-12-03)


### Features

* big ol changes ([a48efc2](https://github.com/chrisventura/cv-lerna/commit/a48efc2e9e8992e2f1cc64f05b9b3b4076852f0e))


### BREAKING CHANGES

* this is a big ol breaking change





## [2.0.3](https://github.com/chrisventura/cv-lerna/compare/@cv/test-package@2.0.2...@cv/test-package@2.0.3) (2020-12-03)


### Bug Fixes

* minor fix ([ef15664](https://github.com/chrisventura/cv-lerna/commit/ef15664b95e56b14dfad2c8049b23d0fcc19a567))





## [2.0.2](https://github.com/chrisventura/cv-lerna/compare/@cv/test-package@2.0.1...@cv/test-package@2.0.2) (2020-12-03)

**Note:** Version bump only for package @cv/test-package






## [6.0.0] - 11/23/2020

### Changed

- **Breaking Change:** `Card` fits to width of parent

### Fixed

- Link button wraps by default

## [5.0.0] - 11/06/2020

### Changed

- **Breaking Change:** Removed margin from `Empty` and `Tag`

### Added

- Updated the modal wrapper to pass through the confirm modal functions
- Styled the confirm modals

### Fixed

- Remove hover and pressed states on disabled tabs
- Text color for links in Alerts

## [4.8.0] - 10/23/2020

### Changed

- Revert Button wrapper
- Style `text` button as a white link

## [4.7.1] - 10/22/2020

### Fixed

- Wrap Button to allow proper ghost link styling
- Remove hover underline on link buttons

## [4.7.0] - 10/19/2020

### Added

- Styling for solid state radio buttons
- Modal Wrapper: Make modal's default behaviour to have maskClosable={false}

## [4.6.8] - 10/15/2020

### Fixed

- Apply proper class to properly style danger buttons

## [4.6.7] - 9/28/2020

### Updated

- Bump ANTD dependency

## [4.6.6] - 9/24/2020

### Fixed

- Link hover color
- Tabs hover color

## [4.6.5] - 9/18/2020

### Fixed

- Link button states now aligned with the design guidelines

## [4.6.4] - 9/17/2020

### Fixed

- Input with icon padding from 8px to 12px
- Background color and padding for inputs with error help text

## [4.6.3] - 9/16/2020

### Fixed

- Inputs heights

## [4.6.2] - 09/11/2020

### Update

- Bump for the style tokens color fix

## [4.6.1] - 09/01/2020

### Fixed

- Remove custom error message from the result component

## [4.6.0] - 09/01/2020

### Changed

- Typography marks changed to green-light

## [4.5.1] - 08/20/2020

### Fixed

- Fixed issue with Result Component (not accepting icon = null)
- Fixed missing default images from AntD

### Updates

- Default messages from Result Component to remove Hub Reference (more generic)

## [4.5.0] - 08/20/2020

### Added

- Adding accessibility output from tokens

## [4.4.0] - 08/20/2020

### Added

- styling white link btn

## [4.3.0] - 08/19/2020

### Updated

- Card padding for cards on mobile

## [4.2.2] - 08/18/2020

### Fixed

- Default spin icon

## [4.2.1] - 08/17/2020

### Updated

- Default spin icon

### Fixed

- Alignment for select content

## [4.2.0] - 07/29/2020

### Updated

- Input style when inside of a table

### Added

- `TableHelper` containing the `EditableRow` and `EditableCell` to help on the creation of editable tables.

## [4.1.0] - 07/14/2020

### Updated

- Default icon for the Empty Component
- Antd dependency to 4.4.2

## [4.0.5] - 06/24/2020

### Fixed

- AntD for select with tags

## [4.0.4] - 06/23/2020

### Fixed

- Exports of `antd/lib` and `antd/es` under `@iqmetrix/antd`

## [4.0.3] - 06/16/2020

### Fixed

- Exports for the result component shouldn't have mention to `IQ`
- Removed `I` from `Result` component interfaces
- Right export for icons: `@iqmetrix/antd/icons`

## [4.0.2] - 06/11/2020

### Fixed

- PageHeader Style

## [4.0.1] - 06/10/2020

### Fixed

- PageHeader Style

## [4.0.0] - 06/09/2020

### Changed

- AntD is not a peer dependency anymore (now it is wrapped)
- Organized Less styles (created \_there.less, dark.less and moved variables out of index.less)
- Jumped versions 2 and 3 to follow the `major` version of antd

### Updated

- Using antd 4;

### Added

- Wrapper for `Result` component
- Wrapper for `Alert` component
- Wrapper for `AntD` component
- Wrapper for `AntD/Icons` component
- `Center` component (from storybook)

### Fixed

- Menu styling
- Alert component typing
- Result component props
- Tests for Result component

## [1.25.0] - 06/04/2020

### Updated

- Packages/Dependencies updated. Running `npx npm-check-updates --semverLevel major -u && npx lerna publish`

## [1.24.0] - 06/06/2020

### Changed

- Styling for extra elements on card

## [1.23.0] - 05/07/2020

### Added

- -webkit-text-fill-color to disabled inputs for the color to work in safari

## [1.22.0] - 04/24/2020

### Changed

- Styling for radio wrapper line height to use style token spacingBaseXlarge

## [1.21.0] - 04/9/2020

### Added

- Styling for buttons when inside modal and using href through okButtonProps

## [1.20.0] - 03/24/2020

### Added

- Input animation in the loading spinner so it doesn't show up until 1 second later

## [1.19.0] - 03/16/2020

### Changed

- Datepicker styling

## [1.18.0] - 03/10/2020

### Changed

- Page header styles to fit when used inside of page-layout component

## [1.17.0] - 03/10/2020

### Added

- Skeleton custom styling

## [1.16.0] - 02/14/2020

### Changed

- Input stories styling (frontend-packages#792)
- Updates peerDepencies formart and change updates the package dependencies

### Added

- Created a helper folder to add utilities to use with AntD css
- Added AntD Badges helper

## [1.15.0] - 02/10/2020

### Changed

- Background-color for input when there is an error

## [1.14.0] - 02/03/2020

### Changed

- Card padding for Media-Queries-Xsmall

## [1.13.0] - 01/27/2020

### Fixed

- Removed link button shadow where it shouldn't be

## [1.12.4] - 01/22/2020

### Fixed

- Padding for range Datepicker was affected by other styling

### Fixed

- Solves issue #265 where a long file name is truncated when it should not be.

## [1.12.3] - 01/13/2020

### Fixed

- Padding for ant-dropdown-menu-item-divider to be initial, otherwise the line appears way too thick.

## [1.12.2] - 01/10/2020

### Fixed

- Fixed list styling that was affecting pagination component styling, when it shouldn't

## [1.12.1] - 12/19/2019

### Fixed

- Fix upload component styling to cut filename when it is too big

## [1.12.0] - 11/06/2019

### Fixed

- Fix upload component bug (icon aligment and add 20px padding) #228

### Changed

- Divided remain styles from index.less into different files
- Changed color and padding for select component

### Added

- Global style for UL and OL lists

## [1.11.0] - 11/06/2019

### Changed

- Tweaked dropdown item height for Select component

## [1.10.0] - 11/05/2019

### Changed

- Update antd dependency to 3.25.0

## [1.10.0] - 11/05/2019

- Changed padding for dropdown-items

## [1.9.0] - 11/05/2019

### Changed

- Style Description component #187
- Update the `@box-shadow-base` - AB#166304

## [1.8.0] - 10/29/2019

### Changed

- Style InputNumber padding, height, and width
- Tweaking left and right input paddings when there are icons to 32px
- Update input styling #220

## [1.7.0] - 10/17/2019

### Added

- New error variable, AB#159963
- Fixing icon position for alerts, AB#163883

## [1.6.1] - 10/11/2019

### Fixed

- update the `@list-item-padding` padding - AB#165595

## [1.6.0] - 09/06/2019

### Changed

- Use spacing style-tokens instead of hardcoded values

## [1.5.0] - 09/05/2019

### Changed

- Updated styles for antd/result, related #193 #190 #189

## [1.4.0] - 09/04/2019

### Added

- New antd variables up to antd@3.23.1, AB#159810

### Changed

- Reference style-tokens for base padding values, AB#159812

## [1.3.0] - 08/20/2019

### Changed

- PageHeader padding values, closes #178

## [1.2.0] - 08/13/2019

### Changed

- Hide empty state on loading tables
- Move card padding, closes #169
- Center table pagination, closes #166
- Style modal acording to #172
- Use blue-light for processing color

## [1.1.0] - 07/31/2019

### Changed

- Tweak PageHeader styling to use new classes and set line-height

## [1.0.0] - 07/26/2019

### Added

- Add bottom border to PageHeader

### Changed

- Use input heights from style-tokens

## [1.0.0-beta.7] - 07/23/2019

### Changed

- Convert base line-height from px to unitless
- publish dist files only
- Fixed issue #151, card title font weight

## [1.0.0-beta.6] - 07/15/2019

### Changed

- Update `antd` to 3.20.3

### Tests

- Removed storybook

## [1.0.0-beta.5] - 07/10/2019

### Added

- Form layout styles

## [1.0.0-beta.4] - 07/08/2019

### Changed

- Update styles

  - Checkbox
  - Radio
  - Card
  - PageHeader
  - Modals
  - Switch

## [1.0.0-beta.3] - 06/28/2019

### Changed

- Tweak style values

## [1.0.0-beta.2] - 06/20/2019

### Changed

- Styling AntD variables

### Tests

- Stories for all visual componentsjk

## [1.0.0-beta.1] - 05/30/2019

### Tests

- Add Storybook

### Changed

- Antd base typography to use style-token typography values

## [1.0.0-beta.0] - 05/30/2019

### Added

- Initial implemenation
- Output empty JS module
- Output CSS file
