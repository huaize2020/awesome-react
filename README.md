[English](./README-en.md) | 简体中文

> 正在持续建设中...

## 目录

- [目录](#目录)
- [UI框架](#ui框架)
- [UI组件](#ui组件)
  - [按钮](#按钮)
  - [图标](#图标)
  - [布局](#布局)
    - [flexbox实现](#flexbox实现)
  - [提示工具](#提示工具)
  - [导航菜单](#导航菜单)
  - [粘性吸顶](#粘性吸顶)
  - [标签页](#标签页)
  - [拖放](#拖放)
  - [可编辑数据网格/电子表格](#可编辑数据网格电子表格)
  - [表格](#表格)
  - [查看/预览器](#查看预览器)
  - [表单组件](#表单组件)
    - [日期和时间选择器](#日期和时间选择器)
    - [状态切换按钮](#状态切换按钮)
    - [表情符号选择器](#表情符号选择器)
    - [富文本编辑器](#富文本编辑器)
    - [代码编辑器](#代码编辑器)
    - [Markdown编辑器](#markdown编辑器)
    - [图片编辑](#图片编辑)
- [UI动画](#ui动画)
  - [视觉差](#视觉差)
- [开发工具](#开发工具)
  - [测试相关](#测试相关)

## UI框架

- [ant-design](https://github.com/ant-design/ant-design) - 一套企业级 UI 设计语言和 React 组件库。 ![](https://img.shields.io/github/stars/ant-design/ant-design.svg?style=social&label=Star)
- [material-ui](https://github.com/mui-org/material-ui) - 一套React 组件，以实现更快、更轻松的 Web 开发。 ![](https://img.shields.io/github/stars/mui-org/material-ui.svg?style=social&label=Star)
- [chakra-ui](https://github.com/chakra-ui/chakra-ui) - 用于 React 应用程序的简单、模块化和可访问性的 UI 组件。 ![](https://img.shields.io/github/stars/chakra-ui/chakra-ui.svg?style=social&label=Star)
- [react-bootstrap](https://github.com/react-bootstrap/react-bootstrap) - 使用 React 构建的 Bootstrap 组件。 ![](https://img.shields.io/github/stars/react-bootstrap/react-bootstrap.svg?style=social&label=Star)
- [blueprint](https://github.com/palantir/blueprint) - 用于 Web 的基于 React 的 UI 工具包。 ![](https://img.shields.io/github/stars/palantir/blueprint.svg?style=social&label=Star)
- [semantic-ui-react](https://github.com/Semantic-Org/Semantic-UI-React) - Semantic 官方提供的 React 封装。 ![](https://img.shields.io/github/stars/Semantic-Org/Semantic-UI-React.svg?style=social&label=Star)
- [office-ui-fabric-react](https://github.com/OfficeDev/office-ui-fabric-react) - 用于构建Microsoft Web体验的React组件。 ![](https://img.shields.io/github/stars/OfficeDev/office-ui-fabric-react.svg?style=social&label=Star)
- [Fluent UI](https://github.com/microsoft/fluentui) - 一套用于构建 Microsoft Web 体验的 React 组件。 ![](https://img.shields.io/github/stars/microsoft/fluentui.svg?style=social&label=Star)
- [evergreen](https://github.com/segmentio/evergreen) - Segment使用的UI框架。 ![](https://img.shields.io/github/stars/segmentio/evergreen.svg?style=social&label=Star)
- [reactstrap](https://github.com/reactstrap/reactstrap) - 简单的 React Bootstrap 4 组件。 ![](https://img.shields.io/github/stars/reactstrap/reactstrap.svg?style=social&label=Star)
- [rebass](https://github.com/rebassjs/rebass) - 使用 styled-system 构建的原始React UI 组件。 ![](https://img.shields.io/github/stars/rebassjs/rebass.svg?style=social&label=Star)
- [grommet](https://github.com/grommet/grommet) - 基于React的整洁框架，提供可访问性、模块化、响应性和主题。 ![](https://img.shields.io/github/stars/grommet/grommet.svg?style=social&label=Star)
- [baseweb](https://github.com/uber/baseweb) - Base 是一个由现代的、响应式的、有生命力的组件组成的设计系统。 Base Web 是 Base 的 React 实现。 ![](https://img.shields.io/github/stars/uber/baseweb.svg?style=social&label=Star)
- [rsuite](https://github.com/rsuite/rsuite) - 一套 React 组件。 ![](https://img.shields.io/github/stars/rsuite/rsuite.svg?style=social&label=Star)
- [react-spectrum](https://github.com/adobe/react-spectrum) - Adobe 的库和工具集合，可帮助您构建适应性强、可访问且强大的用户体验。 ![](https://img.shields.io/github/stars/adobe/react-spectrum.svg?style=social&label=Star)
- [reakit](https://github.com/reakit/reakit) - 可访问、可组合和可定制的React组件。 ![](https://img.shields.io/github/stars/reakit/reakit.svg?style=social&label=Star)
- [carbon](https://github.com/carbon-design-system/carbon) - IBM构建的设计系统。 ![](https://img.shields.io/github/stars/carbon-design-system/carbon.svg?style=social&label=Star)
- [searchkit](https://github.com/searchkit/searchkit) - React UI组件/小部件。使用`Elasticsearch`构建出色搜索体验的最简单方法。 ![](https://img.shields.io/github/stars/searchkit/searchkit.svg?style=social&label=Star)
- [gestalt](https://github.com/pinterest/gestalt) - 一组支持 Pinterest设计语言的组件。 ![](https://img.shields.io/github/stars/pinterest/gestalt.svg?style=social&label=Star)
- [eui](https://github.com/elastic/eui) - 弹性式UI框架。 ![](https://img.shields.io/github/stars/elastic/eui.svg?style=social&label=Star)
- [ring-ui](https://github.com/JetBrains/ring-ui) - JetBrains的 Web UI组件库。 ![](https://img.shields.io/github/stars/JetBrains/ring-ui.svg?style=social&label=Star)
- [zeit-ui-react](https://github.com/zeit-ui/react) - 现代简约的 React UI库。 ![](https://img.shields.io/github/stars/zeit-ui/react.svg?style=social&label=Star)
- [primereact](https://github.com/primefaces/primereact) - 一个完整的 React UI 框架，包含 50 多个具有material、bootstrap和自定义主题的组件。 ![](https://img.shields.io/github/stars/primefaces/primereact.svg?style=social&label=Star)
- [mantine](https://github.com/mantinedev/mantine) -具有原生深色主题支持的 React 组件和Hooks库专注于可用性、可访问性和开发人员体验。 ![](https://img.shields.io/github/stars/mantinedev/mantine.svg?style=social&label=Star)
- [ChatUI](https://github.com/alibaba/ChatUI) - 服务于对话领域的设计和开发体系。 ![](https://img.shields.io/github/stars/alibaba/ChatUI.svg?style=social&label=Star)
- [orbit-components](https://github.com/kiwicom/orbit-components) - 用于构建面向旅行的项目的组件。 ![](https://img.shields.io/github/stars/kiwicom/orbit-components.svg?style=social&label=Star)
- [react-bulma-components](https://github.com/couds/react-bulma-components) - Bulma 的React组件。 ![](https://img.shields.io/github/stars/couds/react-bulma-components.svg?style=social&label=Star)
- [bumbag-ui](https://github.com/bumbag/bumbag-ui) - 使用 Bumbag 构建具备可访问性且主题化的 React 应用程序。 ![](https://img.shields.io/github/stars/bumbag/bumbag-ui.svg?style=social&label=Star)
- [shineout](https://github.com/sheinsight/shineout) - 中文友好的组件集：表单元素、导航、表格、树、树选择下拉等。 ![](https://img.shields.io/github/stars/sheinsight/shineout.svg?style=social&label=Star)
- [pivotal-ui-react](https://github.com/pivotal-cf/pivotal-ui) - 基于自定义版本的Bootstrap库的React组件。 ![](https://img.shields.io/github/stars/pivotal-cf/pivotal-ui.svg?style=social&label=Star)
- [react-foundation](https://github.com/nordsoftware/react-foundation) - 作为React组件的基础。 ![](https://img.shields.io/github/stars/nordsoftware/react-foundation.svg?style=social&label=Star)
- [react-bulma](https://github.com/kulakowka/react-bulma) - 基于 Flexbox 的现代 CSS 框架的 React.js 组件。 ![](https://img.shields.io/github/stars/kulakowka/react-bulma.svg?style=social&label=Star)
- [trunx](https://github.com/fibo/trunx) - 使用 TypeScript 实现，基于Bulma 的React 组件。 ![](https://img.shields.io/github/stars/fibo/trunx.svg?style=social&label=Star)
- [cdbreact](https://github.com/Devwares-Team/cdbreact) - 优雅的UI Kit库和可重用组件，用于构建移动优先、响应式网站和Web应用程序。 ![](https://img.shields.io/github/stars/Devwares-Team/cdbreact.svg?style=social&label=Star)

## UI组件
### 按钮

- [react-awesome-button](https://github.com/rcaferati/react-awesome-button) - 带有加载进度和社交分享操作的 3D 动画 60fps 按钮。 ![](https://img.shields.io/github/stars/rcaferati/react-awesome-button.svg?style=social&label=Star)
- [reactive-button](https://github.com/arifszn/reactive-button) - 一个漂亮的带有进度指示器的动画按钮组件。 ![](https://img.shields.io/github/stars/arifszn/reactive-button.svg?style=social&label=Star)

### 图标

- [react-icons](https://github.com/gorangajic/react-icons) - 使用ES6导入React SVG流行图标库。![](https://img.shields.io/github/stars/gorangajic/react-icons.svg?style=social&label=Star)
- [react-fontawesome](https://github.com/danawoodman/react-fontawesome) - Font Awesome组件。 ![](https://img.shields.io/github/stars/danawoodman/react-fontawesome.svg?style=social&label=Star)
- [iconify-react](https://github.com/iconify/iconify-react) - 来自50多个图标集的超过4万个图标，包括所有流行的图标和表情符号集。 ![](https://img.shields.io/github/stars/iconify/iconify-react.svg?style=social&label=Star)
- [react-open-doodles](https://github.com/lunahq/react-open-doodles) - 由`opendoodles`提供的一组免费粗略插图。 ![](https://img.shields.io/github/stars/lunahq/react-open-doodles.svg?style=social&label=Star)

### 布局

- [react-grid-layout](https://github.com/STRML/react-grid-layout) - 网格布局系统，可以实现响应式的网格布局，并且支持分割点（breakpoints）的设置，灵活运用可以方便的实现拖拽式组件。 ![](https://img.shields.io/github/stars/STRML/react-grid-layout.svg?style=social&label=Star)
- [golden-layout](https://github.com/deepstreamIO/golden-layout) - 一款强大的响应式多窗口分割管理器。 ![](https://img.shields.io/github/stars/deepstreamIO/golden-layout.svg?style=social&label=Star)
- [autoresponsive-react](https://github.com/xudafeng/autoresponsive-react) - 自动响应式网格布局库。 ![](https://img.shields.io/github/stars/xudafeng/autoresponsive-react.svg?style=social&label=Star)
- [react-masonry-component](https://github.com/eiriklv/react-masonry-component) - 基于@desandro's Masonry的封装。 ![](https://img.shields.io/github/stars/eiriklv/react-masonry-component.svg?style=social&label=Star)
- [react-stonecutter](https://github.com/dantrain/react-stonecutter) - 动画网格布局组件。 ![](https://img.shields.io/github/stars/dantrain/react-stonecutter.svg?style=social&label=Star)
- [react-spaces](https://github.com/aeagle/react-spaces) - 使您可以将页面或容器划分为可嵌套的锚定，可滚动和可调整大小的空间。 ![](https://img.shields.io/github/stars/aeagle/react-spaces.svg?style=social&label=Star)
- [muuri-react](https://github.com/Paol-imi/muuri-react) - 响应式、可排序、可筛选和可拖动的网格布局。 ![](https://img.shields.io/github/stars/Paol-imi/muuri-react.svg?style=social&label=Star)
- [m-react-splitters](https://github.com/martinnov92/React-Splitters) - 拆分器组件，用 TypeScript 编写。 ![](https://img.shields.io/github/stars/martinnov92/React-Splitters.svg?style=social&label=Star)

#### flexbox实现

- [hedron](https://github.com/JSBros/hedron) - 一个简洁的flexbox网格系统，由样式组件提供支持。 ![](https://img.shields.io/github/stars/JSBros/hedron.svg?style=social&label=Star)
- [react-reflex](https://github.com/leefsmp/Re-Flex) - 用于高级React Web应用程序的Flex布局容器组件。 ![](https://img.shields.io/github/stars/leefsmp/Re-Flex.svg?style=social&label=Star)
- [flexbox-react](https://github.com/nachoaIvarez/flexbox-react) - 无偏见、符合标准的 flexbox 组件. ![](https://img.shields.io/github/stars/nachoaIvarez/flexbox-react.svg?style=social&label=Star)
- [react-flexbox](https://github.com/tcoopman/react-flexbox) - React flexbox思想。 ![](https://img.shields.io/github/stars/tcoopman/react-flexbox.svg?style=social&label=Star)

### 提示工具

- [react-tooltip](https://github.com/wwayne/react-tooltip) - React提示工具组件。 ![](https://img.shields.io/github/stars/wwayne/react-tooltip.svg?style=social&label=Star)
- [react-popper](https://github.com/popperjs/react-popper) - 🍿⚛官方 React 库，使用定位库 Popper。 ![](https://img.shields.io/github/stars/popperjs/react-popper.svg?style=social&label=Star)

### 导航菜单

- [react-burger-menu](https://github.com/negomi/react-burger-menu) - 带有特效和样式的侧边栏菜单。 ![](https://img.shields.io/github/stars/negomi/react-burger-menu.svg?style=social&label=Star)
- [hamburger-react](https://github.com/luukdv/hamburger-react) - React 的动画汉堡菜单图标。 ![](https://img.shields.io/github/stars/luukdv/hamburger-react.svg?style=social&label=Star)
- [react-planet](https://github.com/innFactory/react-planet) - 创建看起来像行星的圆形菜单。 ![](https://img.shields.io/github/stars/innFactory/react-planet.svg?style=social&label=Star)
- [react-offcanvas](https://github.com/vutran/react-offcanvas) - 侧边栏菜单。 ![](https://img.shields.io/github/stars/vutran/react-offcanvas.svg?style=social&label=Star)

### 粘性吸顶

- [react-sticky](https://github.com/captivationsoftware/react-sticky) - &lt;Sticky /&gt;组件。 ![](https://img.shields.io/github/stars/captivationsoftware/react-sticky.svg?style=social&label=Star)
- [react-headroom](https://github.com/KyleAMathews/react-headroom) - 隐藏头部，直到你需要它。 ![](https://img.shields.io/github/stars/KyleAMathews/react-headroom.svg?style=social&label=Star)
- [react-stickynode](https://github.com/yahoo/react-stickynode) - 一个高性能和全面的React吸顶。 ![](https://img.shields.io/github/stars/yahoo/react-stickynode.svg?style=social&label=Star)

### 标签页

- [react-tabs](https://github.com/reactjs/react-tabs) - 选项卡切换组件。 ![](https://img.shields.io/github/stars/reactjs/react-tabs.svg?style=social&label=Star)
- [react-tabtab](https://github.com/ctxhou/react-tabtab) - 选项卡切换组件。 ![](https://img.shields.io/github/stars/ctxhou/react-tabtab.svg?style=social&label=Star)

### 拖放

- [react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd) - 漂亮且易于使用的 React 列表拖拽。 ![](https://img.shields.io/github/stars/atlassian/react-beautiful-dnd.svg?style=social&label=Star)
- [react-dnd](https://github.com/gaearon/react-dnd) - 拖拽库 ![](https://img.shields.io/github/stars/gaearon/react-dnd.svg?style=social&label=Star)
- [react-dropzone](https://github.com/okonet/react-dropzone) - 简单 HTML5 拖放区。 ![](https://img.shields.io/github/stars/okonet/react-dropzone.svg?style=social&label=Star)
- [react-draggable](https://github.com/mzabriskie/react-draggable) - React可拖动组件。 ![](https://img.shields.io/github/stars/mzabriskie/react-draggable.svg?style=social&label=Star)
- [react-movable](https://github.com/tajo/react-movable) - 可访问且简约（<4kB gzipped）库，用于在列表和表格中进行垂直拖放。 ![](https://img.shields.io/github/stars/tajo/react-movable.svg?style=social&label=Star)
- [react-dragula](https://github.com/bevacqua/react-dragula) - 拖放如此简单，让人心痛。 ![](https://img.shields.io/github/stars/bevacqua/react-dragula.svg?style=social&label=Star)
- [react-sortable-pane](https://github.com/bokuweb/react-sortable-pane) - 可排序和可调整大小的窗格组件。 ![](https://img.shields.io/github/stars/bokuweb/react-sortable-pane.svg?style=social&label=Star)

### 可编辑数据网格/电子表格

- [ag-grid](https://github.com/ceolter/ag-grid) - 高级数据网格/数据表，支持原生JavaScript/React/AngularJS/Web Components. ![](https://img.shields.io/github/stars/ceolter/ag-grid.svg?style=social&label=Star)
- [react-data-grid](https://github.com/adazzle/react-data-grid) - 类似Excel的数据网格。 ![](https://img.shields.io/github/stars/adazzle/react-data-grid.svg?style=social&label=Star)
- [revo-grid](https://github.com/revolist/revogrid) - 适用于React/AngularJS/Vue/Web组件的强大数据网格，具有高级定制功能。 ![](https://img.shields.io/github/stars/revolist/revogrid.svg?style=social&label=Star)
- [ReactGrid](https://github.com/silevis/reactgrid) - 向您的应用程序添加类似电子表格的行为。 ![](https://img.shields.io/github/stars/silevis/reactgrid.svg?style=social&label=Star)
- [gigatables-react](https://github.com/GigaTables/reactables) - 排序、分页/无限滚动、全局/列搜索、AJAX CRUD等。 ![](https://img.shields.io/github/stars/GigaTables/reactables.svg?style=social&label=Star)

### 表格

- [react-table](https://github.com/tannerlinsley/react-table) - 用于构建快速且可扩展的表和数据网格的Hooks。 ![](https://img.shields.io/github/stars/tannerlinsley/react-table.svg?style=social&label=Star)
- [material-table](https://github.com/mbrn/material-table) - 基于Material UI，添加：分组、树数据、可扩展行、导出、内联编辑。 ![](https://img.shields.io/github/stars/mbrn/material-table.svg?style=social&label=Star)
- [mui-datatables](https://github.com/gregnb/mui-datatables) - 基于Material UI。添加：搜索、样式设置、过滤、调整大小/隐藏列、导出、打印、选择/扩展行。 ![](https://img.shields.io/github/stars/gregnb/mui-datatables.svg?style=social&label=Star)
- [@devexpress/dx-react-grid](https://github.com/DevExpress/devextreme-reactive) -  用于Bootstrap和Material Design的基于插件的高性能数据网格。![](https://img.shields.io/github/stars/DevExpress/devextreme-reactive.svg?style=social&label=Star)
- [react-data-table](https://github.com/jbetancur/react-data-table-component) - 可访问、响应式、主题化、声明式可配置表，具有排序、可选行、可扩展行、分页。 ![](https://img.shields.io/github/stars/jbetancur/react-data-table-component.svg?style=social&label=Star)
- [rsuite-table](https://github.com/rsuite/rsuite-table) - 支持虚拟化的表组件。 ![](https://img.shields.io/github/stars/rsuite/rsuite-table.svg?style=social&label=Star)
- [ka-table](https://github.com/komarovalexander/ka-table) - 可定制的表格组件，具有排序、过滤、分组、虚拟化、编辑等功能。 ![](https://img.shields.io/github/stars/komarovalexander/ka-table.svg?style=social&label=Star)
- [sematable](https://github.com/sematext/sematable) - 基于redux/react的客户端排序、分页和文本过滤器。 ![](https://img.shields.io/github/stars/sematext/sematable.svg?style=social&label=Star)
- [@progress/kendo-react-grid](https://github.com/telerik/kendo-react) - 强大的数据网格组件，具有 100 多种即用型功能，如分页、排序、导出到Excel等。 ![](https://img.shields.io/github/stars/telerik/kendo-react.svg?style=social&label=Star)

### 查看/预览器

- [react-markdown](https://github.com/rexxars/react-markdown) - 一个渲染Markdown的React组件。 ![](https://img.shields.io/github/stars/rexxars/react-markdown.svg?style=social&label=Star)
- [react-pdf](https://github.com/wojtekmaj/react-pdf) - 实现在React应用中PDF在线预览。 ![](https://img.shields.io/github/stars/wojtekmaj/react-pdf.svg?style=social&label=Star)
- [react-json-tree](https://github.com/alexkuz/react-json-tree) - JSON预览组件，从redux-devtools提取出。![](https://img.shields.io/github/stars/alexkuz/react-json-tree.svg?style=social&label=Star)
- [react-pdf-viewer](https://github.com/phuoc-ng/react-pdf-viewer) - 一个预览PDF文档的React组件。![](https://img.shields.io/github/stars/phuoc-ng/react-pdf-viewer.svg?style=social&label=Star)

### 表单组件

#### 日期和时间选择器

- [react-datepicker](https://github.com/Hacker0x01/react-datepicker) - 一个简单且可重用的 React 日期选择器组件。 ![](https://img.shields.io/github/stars/Hacker0x01/react-datepicker.svg?style=social&label=Star)
- [react-big-calendar](https://github.com/intljusticemission/react-big-calendar) - Gcal/outlook类似的日历组件。 ![](https://img.shields.io/github/stars/intljusticemission/react-big-calendar.svg?style=social&label=Star)
- [react-day-picker](https://github.com/gpbl/react-day-picker) - React 的灵活日期选择器。![](https://img.shields.io/github/stars/gpbl/react-day-picker.svg?style=social&label=Star)
- [react-calendar](https://github.com/wojtekmaj/react-calendar) - React 应用程序的终极日历。 ![](https://img.shields.io/github/stars/wojtekmaj/react-calendar.svg?style=social&label=Star)
- [react-date-range](https://github.com/Adphorus/react-date-range) - 用于选择日期和日期范围的React组件。 ![](https://img.shields.io/github/stars/Adphorus/react-date-range.svg?style=social&label=Star)
- [react-datetime](https://github.com/YouCanBookMe/react-datetime) - 轻量级但完整的日期时间选择器React组件。 ![](https://img.shields.io/github/stars/YouCanBookMe/react-datetime.svg?style=social&label=Star)
- [devextreme-reactive](https://github.com/DevExpress/devextreme-reactive) - 基于插件，用于Material Design的高性能调度程序/日历。 ![](https://img.shields.io/github/stars/DevExpress/devextreme-reactive.svg?style=social&label=Star)
- [react-nice-dates](https://github.com/hernansartorio/react-nice-dates) - 响应式、对移动端Touch友好和模块化的日期选择器库。 ![](https://img.shields.io/github/stars/hernansartorio/react-nice-dates.svg?style=social&label=Star)
- [react-flatpickr](https://github.com/coderhaoxin/react-flatpickr) - React 的 Flatpickr。 ![](https://img.shields.io/github/stars/coderhaoxin/react-flatpickr.svg?style=social&label=Star)
- [react-date-picker](https://github.com/wojtekmaj/react-date-picker) - 日期选择器。 ![](https://img.shields.io/github/stars/wojtekmaj/react-date-picker.svg?style=social&label=Star)
- [react-yearly-calendar](https://github.com/BelkaLab/react-yearly-calendar) - 年历组件。 ![](https://img.shields.io/github/stars/BelkaLab/react-yearly-calendar.svg?style=social&label=Star)
- [react-datepicker2](https://github.com/mberneti/react-datepicker2) - 一个简单且可重用的日期选择器组件（支持波斯 jalali 日历）。 ![](https://img.shields.io/github/stars/mberneti/react-datepicker2.svg?style=social&label=Star)
- [date-range-picker](https://github.com/almogtavor/date-range-picker) - 支持日期、范围和范围选择的日历组件。 ![](https://img.shields.io/github/stars/almogtavor/date-range-picker.svg?style=social&label=Star)
- [react-simple-timefield](https://github.com/antonfisher/react-simple-timefield) - 简单的时间输入。 ![](https://img.shields.io/github/stars/antonfisher/react-simple-timefield.svg?style=social&label=Star)
- [react-timezone-select](https://github.com/ndom91/react-timezone-select) - D动态、简洁的时区选择，基于`react-select`。 ![](https://img.shields.io/github/stars/ndom91/react-timezone-select.svg?style=social&label=Star)

#### 状态切换按钮

- [react-toggle](https://github.com/instructure-react/react-toggle) - 一个优雅的、可访问的 React切换组件。 还有一个美化的复选框。 ![](https://img.shields.io/github/stars/instructure-react/react-toggle.svg?style=social&label=Star)
- [react-ios-switch](https://github.com/clari/react-ios-switch) - React切换组件。 ![](https://img.shields.io/github/stars/clari/react-ios-switch.svg?style=social&label=Star)

#### 表情符号选择器

- [interweave-emoji-picker](https://github.com/milesj/interweave/tree/master/packages/emoji-picker) - 由`Interweave`和`Emojibase`提供支持的基于 React的表情符号选择器。 ![](https://img.shields.io/github/stars/milesj/interweave.svg?style=social&label=Star)

#### 富文本编辑器

- [slate](https://github.com/ianstormtaylor/slate) - 一个完全可定制的框架，用于在浏览器中构建富文本编辑器。 ![](https://img.shields.io/github/stars/ianstormtaylor/slate.svg?style=social&label=Star)
- [draft-js](https://github.com/facebook/draft-js) - Draft.js是一个 JavaScript富文本编辑器框架，为React构建并由不可变模型支持。 ![](https://img.shields.io/github/stars/facebook/draft-js.svg?style=social&label=Star)
- [react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) - 基于[DraftJS](https://draftjs.org/)封装的可见即可得的编辑器。 ![](https://img.shields.io/github/stars/jpuri/react-draft-wysiwyg.svg?style=social&label=Star)
- [react-quill](https://github.com/zenoamaro/react-quill) - 基于Quill封装。 ![](https://img.shields.io/github/stars/zenoamaro/react-quill.svg?style=social&label=Star)
- [alloyeditor](https://github.com/liferay/alloy-editor) - 基于CKEditor完全重写的UI可见即可得的编辑器 ![](https://img.shields.io/github/stars/liferay/alloy-editor.svg?style=social&label=Star)
- [remirror](https://github.com/remirror/remirror) - 用于React的`ProseMirror` 工具包。 ![](https://img.shields.io/github/stars/remirror/remirror.svg?style=social&label=Star)
- [react-contenteditable](https://github.com/lovasoa/react-contenteditable) - 基于div可编辑内容的React组件。 ![](https://img.shields.io/github/stars/lovasoa/react-contenteditable.svg?style=social&label=Star)
- [megadraft](https://github.com/globocom/megadraft) - 建立在Draft.js之上的富文本编辑器。 ![](https://img.shields.io/github/stars/globocom/megadraft.svg?style=social&label=Star)
- [edtr-io](https://github.com/edtr-io/edtr-io) - 带有插件的可见即可得内嵌 Web 编辑器。 ![](https://img.shields.io/github/stars/edtr-io/edtr-io.svg?style=social&label=Star)
- [react-medium-editor](https://github.com/wangzuo/react-medium-editor) - medium编辑器封装。 ![](https://img.shields.io/github/stars/wangzuo/react-medium-editor.svg?style=social&label=Star)
- [ckeditor5-react](https://github.com/ckeditor/ckeditor5-react) - 基于CKEditor 5官方富文本编辑器封装。 ![](https://img.shields.io/github/stars/ckeditor/ckeditor5-react.svg?style=social&label=Star)
- [smartblock](https://github.com/appleple/smartblock) - 基于ProseMirror的可见即可得的编辑器。 ![](https://img.shields.io/github/stars/appleple/smartblock.svg?style=social&label=Star)
- [react-trumbowyg](https://github.com/RD17/react-trumbowyg) - 基于[Trumbowyg](https://alex-d.github.io/Trumbowyg/)的封装。 ![](https://img.shields.io/github/stars/RD17/react-trumbowyg.svg?style=social&label=Star)
- [ckeditor4-react](https://github.com/ckeditor/ckeditor4-react) - 基于CKEditor 4 rich文本编辑器封装。 ![](https://img.shields.io/github/stars/ckeditor/ckeditor4-react.svg?style=social&label=Star)
- [react-editor](https://github.com/fritx/react-editor) - 可以插入图片和HTML的简单富文本编辑器。 ![](https://img.shields.io/github/stars/fritx/react-editor.svg?style=social&label=Star)

#### 代码编辑器

- [react-ace](https://github.com/securingsincity/react-ace) - 基于Ace (Advanced Code Editor)封装。 ![](https://img.shields.io/github/stars/securingsincity/react-ace.svg?style=social&label=Star)
- [react-codemirror](https://github.com/uiwjs/react-codemirror) - 基于CodeMirror封装的React组件。 ![](https://img.shields.io/github/stars/uiwjs/react-codemirror.svg?style=social&label=Star)
- [react-monacoeditor](https://github.com/jaywcjlove/react-monacoeditor) - 基于Monaco Editor封装的React组件。 ![](https://img.shields.io/github/stars/jaywcjlove/react-monacoeditor.svg?style=social&label=Star)

#### Markdown编辑器

- [react-md-editor](https://github.com/uiwjs/react-md-editor) - 可预览的简单Markdown编辑器，使用React.js和TypeScript实现。 ![](https://img.shields.io/github/stars/uiwjs/react-md-editor.svg?style=social&label=Star)
- [react-simplemde-editor](https://github.com/RIP21/react-simplemde-editor) - 基于[EasyMDE (the most fresh SimpleMDE fork)](https://github.com/Ionaru/easy-markdown-editor)封装的React组件. ![](https://img.shields.io/github/stars/RIP21/react-simplemde-editor.svg?style=social&label=Star)
- [react-md-editor](https://github.com/JedWatson/react-md-editor) - Markdown编辑器。 ![](https://img.shields.io/github/stars/JedWatson/react-md-editor.svg?style=social&label=Star)
- [react-markdown-editor](https://github.com/jrm2k6/react-markdown-editor) - 使用React/Reflux简单markdown编辑器。 ![](https://img.shields.io/github/stars/jrm2k6/react-markdown-editor.svg?style=social&label=Star)

#### 图片编辑

- [react-image-crop](https://github.com/DominicTobias/react-image-crop) - 响应式图像裁剪工具。 ![](https://img.shields.io/github/stars/DominicTobias/react-image-crop.svg?style=social&label=Star)
- [react-avatar-editor](https://github.com/mosch/react-avatar-editor) - 类似Facebook的头像/个人资料图片组件。 ![](https://img.shields.io/github/stars/mosch/react-avatar-editor.svg?style=social&label=Star)
- [react-easy-crop](https://github.com/ricardo-ch/react-easy-crop) - 通过简单的交互来裁剪/旋转图像/视频的组件。移动端触摸友好。 ![](https://img.shields.io/github/stars/ricardo-ch/react-easy-crop.svg?style=social&label=Star)
- [react-image-cropper](https://github.com/jerryshew/react-image-cropper) - 图像裁剪。 ![](https://img.shields.io/github/stars/jerryshew/react-image-cropper.svg?style=social&label=Star)
- [react-avatar-generator](https://github.com/JosephSmith127/react-avatar-generator) - 为用户头像生成有趣的万花筒。 ![](https://img.shields.io/github/stars/JosephSmith127/react-avatar-generator.svg?style=social&label=Star)

## UI动画

- [react-spring](https://github.com/react-spring/react-spring) - 基于弹簧物理的动画库。 ![](https://img.shields.io/github/stars/react-spring/react-spring.svg?style=social&label=Star)
- [react-motion](https://github.com/chenglou/react-motion) - 一个解决您的动画问题的弹簧。 ![](https://img.shields.io/github/stars/chenglou/react-motion.svg?style=social&label=Star)
- [framer-motion](https://github.com/framer/motion) - 动画和手势库。 ![](https://img.shields.io/github/stars/framer/motion.svg?style=social&label=Star)
- [react-flip-move](https://github.com/joshwcomeau/react-flip-move) - 使用FLIP技术在DOM更改的时候（例如列表重新排序）轻松实现动画。Effortless animation between DOM changes (eg. list reordering) using the FLIP technique. ![](https://img.shields.io/github/stars/joshwcomeau/react-flip-move.svg?style=social&label=Star)
- [velocity-react](https://github.com/twitter-fabric/velocity-react) - 基于Velocity.js的封装。 ![](https://img.shields.io/github/stars/twitter-fabric/velocity-react.svg?style=social&label=Star)
- [react-animations](https://github.com/FormidableLabs/react-animations) - 内联样式库的动画集合，React-animations实现了animate.css中的所有动画。 ![](https://img.shields.io/github/stars/FormidableLabs/react-animations.svg?style=social&label=Star)
- [react-router-transition](https://github.com/maisano/react-router-transition) - 为react-router构建的变换库，基于react-motion。 ![](https://img.shields.io/github/stars/maisano/react-router-transition.svg?style=social&label=Star)
- [react-tsparticles](https://github.com/matteobruni/tsparticles/blob/master/components/react/README.md) - 轻量级组件，可轻松创建交互式粒子动画。 ![](https://img.shields.io/github/stars/matteobruni/tsparticles.svg?style=social&label=Star)
- [react-reveal](https://github.com/rnosov/react-reveal) - 轻松地添加滚动动画到您的React应用程序 ![](https://img.shields.io/github/stars/rnosov/react-reveal.svg?style=social&label=Star)
- [react-anime](https://github.com/stelatech/react-anime) - 一个超级简单的动画库。 ![](https://img.shields.io/github/stars/stelatech/react-anime.svg?style=social&label=Star)
- [react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) - 使用React和GSAP的全部功能。 ![](https://img.shields.io/github/stars/azazdeaz/react-gsap-enhancer.svg?style=social&label=Star)
- [data-driven-motion](https://github.com/tkh44/data-driven-motion) - 轻松为您的数据制作动画。 ![](https://img.shields.io/github/stars/tkh44/data-driven-motion.svg?style=social&label=Star)
- [gooey-react](https://github.com/luukdv/gooey-react) - React的粘性效果，用于形状斑点/元球。 ![](https://img.shields.io/github/stars/luukdv/gooey-react.svg?style=social&label=Star)
- [react-particles-bg](https://github.com/lindelof/particles-bg) - 粒子背景。 ![](https://img.shields.io/github/stars/lindelof/particles-bg.svg?style=social&label=Star)
- [react-mt-svg-lines](https://github.com/moarwick/react-mt-svg-lines) - SVG线条描边动画封装。 ![](https://img.shields.io/github/stars/moarwick/react-mt-svg-lines.svg?style=social&label=Star)
- [react-spark-scroll](https://github.com/gilbox/react-spark-scroll) - 用于React的基于滚动的动作和动画。 ![](https://img.shields.io/github/stars/gilbox/react-spark-scroll.svg?style=social&label=Star)
- [react-track](https://github.com/gilbox/react-track) - 跟踪DOM元素的位置，创建很酷的动画。 ![](https://img.shields.io/github/stars/gilbox/react-track.svg?style=social&label=Star)
- [tween-one](https://github.com/react-component/tween-one) - 让一个React元素动画。 ![](https://img.shields.io/github/stars/react-component/tween-one.svg?style=social&label=Star)
- [react-web-animation](https://github.com/bringking/react-web-animation) - 用于Web动画API的React组件. ![](https://img.shields.io/github/stars/bringking/react-web-animation.svg?style=social&label=Star)
- [react-transitive-number](https://github.com/Lapple/react-transitive-number) - 将过渡效果应用于数字字符串，就像旧的 Groupon 计时器。 ![](https://img.shields.io/github/stars/Lapple/react-transitive-number.svg?style=social&label=Star)
- [react-tweenful](https://github.com/teodosii/react-tweenful) - 动画引擎，可让您对DOM节点、挂载、卸载、子元素更改/转换进行动画处理。 ![](https://img.shields.io/github/stars/teodosii/react-tweenful.svg?style=social&label=Star)
- [auto-size-transition](https://github.com/DualWield/auto-size-transition) - 尺寸大小可以随着内容变化而动态变化。 ![](https://img.shields.io/github/stars/DualWield/auto-size-transition.svg?style=social&label=Star)

### 视觉差

- [react-parallax](https://github.com/rrutsche/react-parallax) - 视觉差效果。 ![](https://img.shields.io/github/stars/rrutsche/react-parallax.svg?style=social&label=Star)
- [react-parallax-tilt](https://github.com/mkosir/react-parallax-tilt) - 轻松在组件上应用视差倾斜悬停效果。Easily apply parallax tilt hover effect on components. ![](https://img.shields.io/github/stars/mkosir/react-parallax-tilt.svg?style=social&label=Star)
- [react-parallax-component](https://github.com/keske/react-parallax-component) - 在组件上添加滚动视差效果的最简单方法。 ![](https://img.shields.io/github/stars/keske/react-parallax-component.svg?style=social&label=Star)

## 开发工具

### 测试相关

- [jest](https://github.com/facebook/jest) - 愉悦的JavaScript测试。 ![](https://img.shields.io/github/stars/facebook/jest.svg?style=social&label=Star)
- [enzyme](https://github.com/airbnb/enzyme) - 用于React的测试工具。 ![](https://img.shields.io/github/stars/airbnb/enzyme.svg?style=social&label=Star)
- [react-testing-library](https://github.com/testing-library/react-testing-library) - 🐐 简单而完整的React DOM测试实用程序，鼓励良好的测试实践。 ![](https://img.shields.io/github/stars/testing-library/react-testing-library.svg?style=social&label=Star)
- [chai-enzyme](https://github.com/producthunt/chai-enzyme) - 配合enzyme使用的Chai.js断言库和便利函数 ![](https://img.shields.io/github/stars/producthunt/chai-enzyme.svg?style=social&label=Star)
- [ui-harness](https://github.com/philcockfield/ui-harness) - 在React中创建、隔离和测试模块化UI组件。 ![](https://img.shields.io/github/stars/philcockfield/ui-harness.svg?style=social&label=Star)
- [react-unit](https://github.com/pzavolinsky/react-unit) - 轻量级单元测试库。 ![](https://img.shields.io/github/stars/pzavolinsky/react-unit.svg?style=social&label=Star)
- [unexpected-react](https://github.com/bruderstein/unexpected-react) - unexpected插件，用于测试完整React虚拟DOM以及浅层渲染器。![](https://img.shields.io/github/stars/bruderstein/unexpected-react.svg?style=social&label=Star)
- [redux-test-recorder](https://github.com/conorhastings/redux-test-recorder) - 一个redux中间件，通过ui交互自动生成reducers的测试。 ![](https://img.shields.io/github/stars/tcoopman/react-flexbox.svg?style=social&label=Star)
- [rut](https://github.com/milesj/rut) - 使用`react-test-renderer`使React测试变得容易。支持DOM和自定义渲染器。![](https://img.shields.io/github/stars/milesj/rut.svg?style=social&label=Star)
