## This is Code Snippets of Magic Box for VS Code.

### Install

#### Manual Install

Go to the [git](https://github.com/TJS-95/Magic-Box-Snippets-VSCode) and download the snippets folder, then copy the files in the folder to the path directly:

+ **Mac**: /Users/*< your-user-name >*/Library/Application Support/Code/User/snippets/
+ **Windows**: *< your-installed-driver >* :\Users\ *< your-user-name >* \AppData\Roaming\Code\User\snippets\

#### Through VS Code Extensions

+ From website: Go to Visual Studio Code [Marketplace](https://marketplace.visualstudio.com/vscode), and search 'Magic Box Snippets', then click the install button.
+ From VS Code: click extensions sidebar, and search 'Magic Box Snippets', then click the install button.

### Special Instruction

1. For the components like `bk-table` which need children components to be its content, use `v-for` to loop to generate the children components.

### Snippets List

1. All the Magic Box tags below, ignore the closure and more detailed information. Such as `bkr` to `<bk-radio>`, actually that represents `<bk-radio v-model="${1}" label="${2}">$3</bk-radio>`
2. The sinppets' order follows the order of the components of Guide on Magic Box official website basically. <!--Supply extra General and Options parts.-->
3. Totally 101 snippets. Will add more if necessary.
4. **Only work in .vue file for now.**

#### Basic Part

|No.|Trigger&nbsp;Key|Element Tag|
|:------:|:--------------:|:--------|
|1. | `bk-row` | `<bk-row>` |
|2. | `bk-col` | `<bk-col>` |
|3. | `bkcpr` | `#1272FF` |
|4. | `bkcd` | `#FF9214` |
|5. | `bkcs` | `#27C274` |
|6. | `bkcw` | `#FFC01F` |
|7. | `bkcgery` | `#B2BDCC` |
|8. | `bk-button` | `<bk-button>` |
|9. | `bk-button-group` | `<bk-button-group>` |
|10. | `bk-link` | `<bk-link>` |
|11. | `bk-icon` | `<bk-icon>` |

#### Form Part

|No. |  Trigger&nbsp;Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `bk-radio` | `<bk-radio>` |
|2. | `bk-radio-group` | `<bk-radio-group>` |
|3. | `bk-radio-group-button` | `<bk-radio-group> with <bk-radio-button>` |
|4. | `bk-radio-button` | `<bk-radio-button>` |
|5. | `bk-checkbox` | `<bk-checkbox>` |
|6. | `bk-checkbox-group` | `<bk-checkbox-group>` |
|9. | `bk-input` | `<bk-input>` |
|10. | `bk-input:type` | `<bk-input type="textarea">` |
|11. | `bk-tag-input` | `<bk-tag-input>` |
|12. | `bk-input>slot` | `<template slot='prepend|append'>` |
|13. | `bk-input-number` | `<bk-input type="number">` |
|14. | `bk-select` | `<bk-select>` |
|15. | `bk-select:remote` | `<bk-select :remote-method="">` |
|16. | `bk-option` | `<bk-option>` |
|17. | `<bk-option-group>` | `<bk-option-group>` |
|18. | `bk-search-select` | `<bk-search-select>` |
|19. | `bk-search-select:remote` | `<bk-search-select :remote-method="">` |
|20. | `bk-cascade` | `<bk-cascade>`|
|21. | `bk-switcher` | `<bk-switcher>` |
|22. | `bk-color-picker` | `<bk-color-picker>` |
|23. | `bk-slider` | `<bk-slider>` |
|24. | `bk-date-picker` | `<bk-date-picker>` |
|25. | `bk-date-picker:range` | `<bk-date-picker type="datetimerange">` |
|26. | `bk-date-picker:up` | `<bk-date-picker up-to-now>` |
|27. | `bk-time-picker` | `<bk-time-picker type="time">` |
|28. | `bk-time-picker:timerange` | `<bk-time-picker type="timerange">` |
|29. | `bk-calendar` | `<bk-calendar>` |
|30. | `bk-almanac` | `<bk-almanac>` |
|31. | `bk-upload` | `<bk-upload>` |
|32. | `bk-rate` | `<bk-rate>` |
|33. | `bk-transfer` | `<bk-transfer>` |
|34. | `bk-form` | `<bk-form>` |
|35. | `bk-form-item` | `<bk-form-item>` |
|36. | `bk-form-item>input` | `<bk-form-item> <bk-input /> </bk-form-item>` |

#### Data Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `bk-table` | `<bk-table>` |
|2. | `bk-table-column` | `<bk-table-column>` |
|3. | `bk-table:pagination` | `<bk-table :pagination="">` |
|3. | `bk-tag` | `<bk-tag>` |
|4. | `bk-progress` | `<bk-progress>` |
|5. | `bk-round-progress` | `<bk-round-progress>` |
|6. | `bk-tree` | `<bk-tree>` |
|7. | `bk-big-tree` | `<bk-big-tree>` |
|8. | `bk-timeline` | `<bk-timeline>` |
|9. | `bk-collapse` | `<bk-collapse>` |
|10. | `bk-collapse-item` | `<bk-collapse-item>` |
|11. | `bk-diff` | `<bk-diff>` |
|12. | `bk-dropdown` | `<bk-dropdown>` |
|13. | `bk-description` | `<bk-description>` |
|14. | `bk-description-item` | `<bk-description-item>` |
|15. | `bk-swiper` | `<bk-swiper>` |
|16. | `bk-pagination` | `<bk-pagination>` |
|17. | `bk-badge` | `<bk-badge>` |
|18. | `bk-animate-number` | `<bk-animate-number>` |
|19. | `bk-image` | `<bk-image>` |
|20. | `bk-image:preview` | `<bk-image :preview-src-list="">` |
|21. | `bk-zoom-image` | `<bk-zoom-image>` |
|22. | `bk-virtual-scroll` | `<bk-virtual-scroll>` |

#### Notice Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `bk-alert` | `<bk-alert>` |
|2. | `bk-exception` | `<bk-exception>` |
|3. | `bk-popover` | `<bk-popover>` |
|4. | `bk-sideslider` | `<bk-sideslider>` |
|5. | `bk-popconfirm` | `<bk-popconfirm>` |
|6. | `bk-dialog` | `<bk-dialog>` |
|7. | `bk-tooltip` | `<bk-tooltip>` |
|8. | `bk-card` | `<bk-card>` |
|9. | `bk-spin` | `<bk-spin>` |
|  |  | Attribute |
|10. | `v-bkloading` | `v-bkloading` |
|11. | `v-bk-tooltips` | `v-bk-tooltips` |
|12. | `v-bk-tooltips.theme` | `v-bk-tooltips="{ theme: ''}"` |
|  |  | Method |
|13. | `bkInfo` | `this.$bkInfo({})` |
|14. | `bkLoading` | `this.$bkLoading({})` |
|15. | `bkMessage` | `this.$bkMessage({})` |
|16. | `bkMessage.theme` | `this.$bkMessage({ theme: '' })` |
|17. | `bkNotify` | `this.$bkNotify({})` |
|18. | `bkNotify.theme` | `this.$bkNotify({ theme: '' })` |


#### Navigation Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `bk-simple-nav` | `<bk-simple-nav>` |
|2. | `bk-resize-layout` | `<bk-resize-layout>` |
|3. | `bk-tab` | `<bk-tab>` |
|4. | `bk-tab-panel` | `<bk-tab-panel>` |
|5. | `bk-breadcrumb` | `<bk-breadcrumb>` |
|6. | `bk-breadcrumb-item` | `<bk-breadcrumb-item>` |
|7. | `bk-dropdown` | `<bk-dropdown>` |
|8. | `bk-steps` | `<bk-steps>` |
|9. | `bk-process` | `<bk-process>` |
|10. | `bk-divider` | `<bk-divider>` |
|11. | `bk-fixed-navbar` | `<bk-fixed-navbar>` |
|12. | `bk-back-top` | `<bk-back-top>` |
|13. | `bk-affix` | `<bk-affix>` |

####  Directive Part

|No. |  Trigger Key | Directive |
|:------:|:--------------:|:--------|
|1. | `v-bk-clickoutside` | `v-bk-clickoutside>` |
|2. | `v-bk-overflow-tip` | `v-bk-overflow-tips` |
|3. | `v-bk-copy` | `v-bk-copy` |

