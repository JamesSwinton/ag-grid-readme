<!-- Additional Badges for consideration -->
<!-- ![npm package minimized gzipped size](https://img.shields.io/bundlejs/size/ag-grid-community?style=for-the-badge) -->

<div align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Dark-Theme.svg?raw=true"/>
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Light-Theme.svg?raw=true"/>
      <img width="100%" alt="AG Grid Logo" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Dark-Theme.svg?raw=true"/>
    </picture>
    <div align="center">
        <h4><a href="https://www.ag-grid.com">🌐 Website</a> • <a href="https://www.ag-grid.com/javascript-data-grid/getting-started/">📖 Documentation</a> • <a href="https://www.ag-grid.com/community">🏘️ Community</a></h4>
    </div>
    <br>
    <a href="https://github.com/ag-grid/ag-grid/releases">
        <img src="https://img.shields.io/github/v/release/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Release">
    </a>
    <a href="https://www.npmjs.com/package/ag-grid-community">
        <img src="https://img.shields.io/npm/dm/ag-grid-community?style=for-the-badge" alt="NPM Downloads">
    </a>
    <a href="https://github.com/ag-grid/ag-grid">
        <img src="https://img.shields.io/github/stars/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Repo stars">
    </a>
    <a href="https://github.com/ag-grid/ag-grid">
        <img alt="GitHub forks" src="https://img.shields.io/github/forks/ag-grid/ag-grid?style=for-the-badge">
    </a>
    <br><br>
    <a href="https://sonarcloud.io/dashboard?id=ag-grid-enterprise">
      <img src="https://sonarcloud.io/api/project_badges/measure?project=ag-grid-enterprise&metric=alert_status" alt="Quality Gate Status">
    </a>
    <a href="https://npm.io/package/ag-grid-community">
        <img src="https://img.shields.io/npms-io/maintenance-score/ag-grid-community" alt="npms.io Maintenance Score">
    </a>
    <a href="https://github.com/ag-grid/ag-grid/graphs/commit-activity">
        <img src="https://img.shields.io/github/commit-activity/m/ag-grid/ag-grid" alt="GitHub commit activity">
    </a>
    <a href="https://github.com/ag-grid/ag-grid/network/dependents">
        <img src="https://img.shields.io/librariesio/dependents/npm/ag-grid-community" alt="Dependents (via libraries.io?style=for-the-badge)">
    </a>
    <br><br>
    <p>AG Grid is a <strong>fully-featured</strong> and <strong>highly customizable</strong> JavaScript Data Grid. It delivers <strong>outstanding performance</strong>, has <strong>no third-party dependencies</strong> and comes with support for <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-react"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/react.svg?raw=true" height="16" width="16" alt="React Logo"> React</a></strong>, <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-angular"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/angular.svg?raw=true" height="16" width="16" alt="Angular Logo"> Angular</a></strong> and <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-vue"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/vue.svg?raw=true" height="16" width="16" alt="Vue Logo"> Vue</a></strong>.</p>
    <br>
</div>

![Kitchen Sink Demo](./kitchen-sink-demo.gif)
<div align="right"><span><a href="https://ag-grid.com/example/">Live Demo</a></span></div>

## 📖 Overview

<details>
  <summary><strong>Table of Contents</strong></summary>

- [📖 Overview](#-overview)
  - [Features](#features)
  - [Examples](#examples)
- [⚡️ Quick Start](#️-quick-start)
  - [Installation](#installation)
  - [Setup](#setup)
  - [Seed Projects](#seed-projects)
- [🛠️ Customisations](#️-customisations)
  - [Custom Components](#custom-components)
  - [Themes](#themes)
  - [Custom Themes](#custom-themes)
- [🌍 Community](#-community)
  - [Tools \& Extensions](#tools--extensions)
  - [Showcase](#showcase)
  - [Stargazers](#stargazers)
- [🤝 Support](#-support)
  - [Enterprise Support](#enterprise-support)
  - [Bug Reports](#bug-reports)
  - [Questions](#questions)
  - [Contributing](#contributing)
- [⚠️ License](#️-license)

</details>

AG Grid is available in two versions: Community & Enterprise. 

- `ag-grid-community` is free, available under the MIT license, and comes with all of the core features expected from a JavaScript Data Grid, including Sorting, Filtering, Pagination, Editing, Custom Components, Theming and more.
- `ag-grid-enterprise` is available under a commercial license and comes with advanced features, like Integrated Charting, Row Grouping, Aggregation, Pivoting, Master/Detail, Server-side Row Model, and Exporting in addition to dedicated support from our Engineering team.

### Features

| Feature                      | AG Grid Community | AG Grid Enterprise |
| ---------------------------- | ----------------- | ------------------ |
| Sorting                      | ✅                | ✅                 |
| Filtering                    | ✅                | ✅                 |
| Pagination                   | ✅                | ✅                 |
| Cell Editing                 | ✅                | ✅                 |
| Themes and Styling           | ✅                | ✅                 |
| Selection                    | ✅                | ✅                 |
| Accessibility                | ✅                | ✅                 |
| Custom Components            | ✅                | ✅                 |
| Infinite Scrolling           | ✅                | ✅                 |
| CSV Export                   | ✅                | ✅                 |
| Drag & Drop                  | ✅                | ✅                 |
| Integrated Charting          | ❌                | ✅                 |
| Row Grouping and Aggregation | ❌                | ✅                 |
| Pivoting                     | ❌                | ✅                 |
| Range Selection              | ❌                | ✅                 |
| Advanced Filtering           | ❌                | ✅                 |
| Server-Side Row Model        | ❌                | ✅                 |
| Excel Export                 | ❌                | ✅                 |
| Master/Detail                | ❌                | ✅                 |
| Tree Data                    | ❌                | ✅                 |
| Column menu                  | ❌                | ✅                 |
| Context menu                 | ❌                | ✅                 |
| Clipboard                    | ❌                | ✅                 |
| Support                      | ❌                | ✅                 |
| Perpetual License            | ❌                | ✅                 |

> [!IMPORTANT]
> Visit the [Pricing](https://www.ag-grid.com/license-pricing/) page for a full comparison.

### Examples

We've created several demos to showcase AG Grid's rich feature set across different use cases. See them in action below, or interact with them on our [Demo](https://www.ag-grid.com/example/) page.

<details open>
  <summary>🏦 <b>Financial Demo</b></summary>
  <br>
  <p>Financial data example featuring live updates and sparklines:</p>
  <a href="https://ag-grid.com/example-finance/">
    <img src="./finance-demo.gif" alt="Finance">
  </a>
  <br>
  <div align="right"><span><a href="https://ag-grid.com/example-finance/">Live Demo</a></span>&nbsp;•&nbsp;<span><a href="https://github.com/ag-grid/ag-grid-demos/tree/main/finance">Source Code</a></span></div>
<br>
</details>
<details>
  <summary>📦 <b>Inventory Demo</b></summary>
  <br>
  <p>Inventory data example to view and manage products:</p>
  <a href="https://ag-grid.com/example-inventory/">
    <img src="./inventory-demo.gif" alt="Inventory">
  </a>
  <div align="right"><span><a href="https://ag-grid.com/example-inventory/">Live Demo</a></span>&nbsp;•&nbsp;<span><a href="https://github.com/ag-grid/ag-grid-demos/tree/main/inventory">Source Code</a></span></div>
<br>
</details>
<details>
    
  <summary>🧑‍💼 <b>HR Demo</b></summary>
  <br>
  <p>HR data example showing hierarchical employee data:</p>
  <a href="https://ag-grid.com/example-hr/">
    <img src="./hr-demo.gif" alt="HR">
  </a>
  <div align="right"><span><a href="https://ag-grid.com/example-hr/">Live Demo</a></span>&nbsp;•&nbsp;<span><a href="https://github.com/ag-grid/ag-grid-demos/tree/main/hr">Source Code</a></span></div>
<br>
</details>

## ⚡️ Quick Start

AG Grid is easy to set up - all you need to do is provide your data and define your column structure. Read on for vanilla JavaScript installation instructions, or refer to our framework-specific guides for 
<strong>
    <a href="https://www.ag-grid.com/react-data-grid/getting-started/">
        <img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/react.svg?raw=true" height="16" width="16" alt="React Logo"> React
    </a>
</strong>, 
<strong>
    <a href="https://www.ag-grid.com/angular-data-grid/getting-started/">
        <img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/angular.svg?raw=true" height="16" width="16" alt="Angular Logo"> Angular
    </a>
</strong> and 
<strong>
    <a href="https://www.ag-grid.com/vue-data-grid/getting-started/">
        <img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/vue.svg?raw=true" height="16" width="16" alt="Vue Logo"> Vue.
    </a>
</strong>


### Installation

```sh
$ npm install --save ag-grid-community
```

### Setup

1. Add a placeholder to HTML

```html
<div id="myGrid" style="height: 150px; width: 600px" class="ag-theme-quartz"></div>
```

2. Import the grid and styles

```js
import { createGrid } from 'ag-grid-community';
import 'ag-grid-community/styles/ag-grid.css';
import 'ag-grid-community/styles/ag-theme-quartz.css';
```

3. Set configuration

```js
// Grid Options: Contains all of the Data Grid configurations
const gridOptions = {
    // Row Data: The data to be displayed.
    rowData: [
        { make: 'Tesla', model: 'Model Y', price: 64950, electric: true },
        { make: 'Ford', model: 'F-Series', price: 33850, electric: false },
        { make: 'Toyota', model: 'Corolla', price: 29600, electric: false },
    ],
    // Column Definitions: Defines the columns to be displayed.
    columnDefs: [{ field: 'make' }, { field: 'model' }, { field: 'price' }, { field: 'electric' }],
};
```

4. Initialise the grid

```js
const eGridDiv = document.querySelector('#myGrid');
const api = createGrid(eGridDiv, gridOptions);
```

> [!IMPORTANT]
> For more information on building Data Grids with AG Grid, refer to our [Documentation](https://www.ag-grid.com/javascript-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github).

### Seed Projects 

We also provide [Seed Projects](https://github.com/ag-grid/ag-grid-seed) to help you get started with common configurations:

<table width="100%">
  <thead>
    <tr>
      <th>Environment</th>
      <th>Framework</th>
      <th>Packages</th>
      <th>Modules</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Create React App (CRA)</td>
      <td align="middle"><img width="22" height="22" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/react.svg?raw=true" alt="React Logo"></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/create-react-app">Packages</a></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/modules/create-react-app">Modules</a></td>
    </tr>
    <tr>
      <td>Vite</td>
      <td align="middle"><img width="22" height="22" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/react.svg?raw=true" alt="React Logo"></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/vite-react">Packages</a></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/modules/vite-react">Modules</a></td>
    </tr>
    <tr>
      <td>Vite - TypeScript</td>
      <td align="middle"><img width="22" height="22" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/typescript.svg?raw=true" alt="TypeScript Logo"></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/vite-typescript">Packages</a></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/modules/vite-typescript">Modules</a></td>
    </tr>
    <tr>
      <td>Webpack 5 - TypeScript</td>
      <td align="middle"><img width="22" height="22" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/typescript.svg?raw=true" alt="TypeScript Logo"></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/webpack5-typescript">Packages</a></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/modules/webpack5-typescript">Modules</a></td>
    </tr>
    <tr>
      <td>Webpack 5 - JavaScript</td>
      <td align="middle"><img width="22" height="22" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/javascript.svg?raw=true" alt="JavaScript Logo"></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/webpack5-javascript">Packages</a></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/modules/webpack5-javascript">Modules</a></td>
    </tr>
    <tr>
      <td>Angular CLI</td>
      <td align="middle"><img width="22" height="22" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/angular.svg?raw=true" alt="Angular Logo"></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/angular-cli">Packages</a></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/modules/angular-cli">Modules</a></td>
    </tr>
    <tr>
      <td>Nuxt</td>
      <td align="middle"><img width="22" height="22" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/vue.svg?raw=true" alt="Vue3 Logo"></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/nuxt-vue3">Packages</a></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/modules/nuxt-vue3">Modules</a></td>
    </tr>
    <tr>
      <td>Vite</td>
      <td align="middle"><img width="22" height="22" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/vue.svg?raw=true" alt="Vue3 Logo"></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/vite-vue3">Packages</a></td>
      <td><a href="https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/modules/vite-vue3">Modules</a></td>
    </tr>
  </tbody>
</table>

## 🛠️ Customisations

AG Grid is fully customisable, both in terms of appearance and functionality. There are many ways in which the grid can be customised and a selection of tools to help create those customisations.

### Custom Components

You can create your own Custom Components to customise the behaviour of the grid. For example, you can customise how cells are rendered, how values are edited and also create your own filters.

There are a number of different [Component Types](https://www.ag-grid.com/javascript-data-grid/components/) that you can provide to the grid, including:

* [Cell Component](https://www.ag-grid.com/javascript-data-grid/component-cell-renderer/): To customise the contents of a cell.
* [Header Component](https://www.ag-grid.com/javascript-data-grid/column-headers/): To customise the header of a column and column groups.
* [Edit Component](https://www.ag-grid.com/javascript-data-grid/cell-editors/): To customise the editing of a cell.
* [Filter Component](https://www.ag-grid.com/javascript-data-grid/component-filter/): For custom column filter that appears inside the column menu.
* [Floating Filter](https://www.ag-grid.com/javascript-data-grid/component-floating-filter/): For custom column floating filter that appears inside the column menu.
* [Date Component](https://www.ag-grid.com/javascript-data-grid/filter-date/#custom-selection-component): To customise the date selection component in the date filter.
* [Loading Component](https://www.ag-grid.com/javascript-data-grid/component-loading-cell-renderer/): To customise the loading cell row when using Server Side Row Model.
* [Overlay Component](https://www.ag-grid.com/javascript-data-grid/overlays/): To customise loading and no rows overlay components.
* [Status Bar Component](https://www.ag-grid.com/javascript-data-grid/status-bar/): For custom status bar components.
* [Tool Panel Component](https://www.ag-grid.com/javascript-data-grid/component-tool-panel/): For custom tool panel components.
* [Tooltip Component](https://www.ag-grid.com/javascript-data-grid/tooltips/): For custom cell tooltip components.
* [Menu Item Component](https://www.ag-grid.com/javascript-data-grid/component-menu-item/): To customise the menu items shown in the Column and Context Menus.

To supply a custom cell renderer and filter components to the Grid, create a direct reference to your component within the `gridOptions.columnDefs` property:

```js
gridOptions = {
   columnDefs: [
       {
           field: 'country', // The column to add the component to
           cellRenderer: CountryCellRenderer, // Your custom cell component
           filter: CountryFilter // Your custom filter component
       },
   ],
}
```

### Themes

AG Grid has 4 [themes](https://ag-grid.com/vue-data-grid/global-style/), each available in `light` & `dark` modes. We also supply each theme with an `auto` mode that can toggle the theme based on the users' system preferences:

<table>
    <tr>
        <th>Quartz</th>
        <th>Material</th>
    </tr>
    <tr>
        <td>
            <a href="https://www.ag-grid.com/javascript-data-grid/themes/">
                <picture>
                    <source srcset="./quartz-theme-light.png" media="(prefers-color-scheme: light)">
                    <source srcset="./quartz-theme.png" media="(prefers-color-scheme: dark)">
                    <img src="./quartz-theme.png" alt="Quartz Theme">
                </picture>
            </a>
        </td>
        <td>
            <a href="https://www.ag-grid.com/javascript-data-grid/themes/">
                <picture>
                    <source srcset="./material-theme-light.png" media="(prefers-color-scheme: light)">
                    <source srcset="./material-theme.png" media="(prefers-color-scheme: dark)">
                    <img src="./material-theme.png" alt="Material Theme">
                </picture>
            </a>
        </td>
    </tr>
    <tr>
        <th>Alpine</th>
        <th>Balham</th>
    </tr>
    <tr>
        <td>
            <a href="https://www.ag-grid.com/javascript-data-grid/themes/">
                <picture>
                    <source srcset="./alpine-theme-light.png" media="(prefers-color-scheme: light)">
                    <source srcset="./alpine-theme.png" media="(prefers-color-scheme: dark)">
                    <img src="./alpine-theme.png" alt="Alpine Theme">
                </picture>
            </a>
        </td>
        <td>
            <a href="https://www.ag-grid.com/javascript-data-grid/themes/">
                <picture>
                    <source srcset="./balham-theme-light.png" media="(prefers-color-scheme: light)">
                    <source srcset="./balham-theme.png" media="(prefers-color-scheme: dark)">
                    <img src="./balham-theme.png" alt="Balham Theme">
                </picture>
            </a>
        </td>
    </tr>
</table>

To apply a theme, add the relevant CSS Class to the Data Grid container. For example, to apply the Quartz theme, use the CSS class `ag-theme-quartz`:

```js
<div id="myGrid" style="height: 150px; width: 600px" class="ag-theme-quartz"></div>
```

### Custom Themes

All AG Grid themes can be customised using [CSS variables](https://www.ag-grid.com/javascript-data-grid/global-style-customisation/), or you can create a new theme from scratch with the help of our [Theme Builder](https://www.ag-grid.com/theme-builder/) or [Figma Design System](./figma-design-system).

## 🌍 Community

### Tools & Extensions

AG Grid has a large and active community who have created an [ecosystem of 3rd party tools, extensions and utilities](https://www.ag-grid.com/community/tools-extensions/) to help you build your next project with AG Grid, no matter which language or framework you use:

<div>
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/react.svg?raw=true" align="center" width="16" height="16" alt="React Logo">&nbsp;React</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/angular.svg?raw=true" align="center" width="16" height="16" alt="Angular Logo">&nbsp;Angular</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/typescript.svg?raw=true" align="center" width="16" height="16" alt="TypeScript Logo">&nbsp;TypeScript</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/vue.svg?raw=true" align="center" width="16" height="16" alt="Vue Logo">&nbsp;Vue</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/python.svg?raw=true" align="center" width="16" height="16" alt="Python Logo">&nbsp;Python</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/svelte.svg?raw=true" align="center" width="16" height="16" alt="Svelte Logo">&nbsp;Svelte</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/solidjs.svg?raw=true" align="center" width="16" height="16" alt="SolidJS Logo">&nbsp;SolidJS</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/.net.svg?raw=true" align="center" width="16" height="16" alt=".NET Logo">&nbsp;.NET</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/rust.svg?raw=true" align="center" width="16" height="16" alt="Rust Logo">&nbsp;Rust</span>
    </a> • 
    <a href="https://www.ag-grid.com/community/tools-extensions/">
        <span><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/community/frameworks/laravel.svg?raw=true" align="center" width="16" height="16" alt="Laravel Logo">&nbsp;Laravel</span>
    </a>
</div>

### Showcase

AG Grid is used by 100,000's of developers across the world, from almost every industry. Whilst most of these projects are private, we've curated a selection of open-source projects from different industries where household names rely on AG Grid, including **J.P.Morgan**, **MongoDB** and **NASA**. Visit our [Community Showcase](https://www.ag-grid.com/community/showcase/) page to learn more.

### Stargazers

Founded in 2016, AG Grid has seen a steady rise in popularity and is now the market leader for Data Grids:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date&theme=dark"/>
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date"/>
  <img width="100%" alt="The AG Grid star history chart" src="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date"/>
</picture>

## 🤝 Support

### Enterprise Support

AG Grid Enterprise customers have access to dedicated support via [ZenDesk](https://ag-grid.zendesk.com/hc/en-us), which is monitored by our engineering teams.

### Bug Reports

If you have found a bug, please report it in this repository's [issues](https://github.com/ag-grid/ag-grid/issues) section.

<img src="https://img.shields.io/github/issues-closed/ag-grid/ag-grid?style=for-the-badge&color=%233d8c40" alt="GitHub Issues" height="26">

### Questions

Look for similar problems on [StackOverflow](https://stackoverflow.com/questions/tagged/ag-grid) using the `ag-grid` tag. If nothing seems related, post a new message there. Please do not use GitHub issues to ask questions.

<img src="https://img.shields.io/stackexchange/stackoverflow.com/t/ag-grid?style=for-the-badge&color=%233d8c40" alt="Stack Exchange questions" height="26">

### Contributing

AG Grid is developed by a team of co-located developers in London. If you want to join the team send your application to info@ag-grid.com.

## ⚠️ License

`ag-grid-community` is licensed under the **MIT** license. 

`ag-grid-enterprise` has a **Commercial** license. 

See the [LICENSE file](./LICENSE.txt) for more info.

<div><h2><img vertical-align="middle" width="32" height="32" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-BrandMark_Light-Theme.svg?raw=true" alt="AG ChartsLogo">AG Charts</h2></div>

If you've made it this far, you may be interested in our latest project: [AG Charts](https://charts.ag-grid.com) - The best JavaScript Charting library in the world.

Initially built to power [Integrated Charts](https://www.ag-grid.com/javascript-data-grid/integrated-charts/) in AG Grid, we open-sourced this project in 2018. Having seen the steady rise in popularity since then, we have decided to invest in AG Charts with a dedicated Enterprise version (`ag-charts-enterprise`) in addition to our continued support of `ag-charts-community`.

Learn more at [AG-Charts.com](https://charts.ag-grid.com/)

<div align="center">
    
<hr/>

<strong>Follow us to keep up to date with all the latest news from AG Grid:</strong>

<a href="https://x.com/ag_grid"><img src="https://img.shields.io/badge/-X%20(Twitter)-black?style=for-the-badge&logo=x" alt="Twitter Badge" height="36"></a>
<a href="https://www.linkedin.com/company/ag-grid/"><img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn Badge" height="36"></a>
<a href="https://www.youtube.com/c/ag-grid"><img src="https://img.shields.io/badge/-YouTube-red?style=for-the-badge&logo=youtube" alt="YouTube Badge" height="36"></a>
<a href="https://blog.ag-grid.com"><img src="https://img.shields.io/badge/-Blog-grey?style=for-the-badge&logo=rss" alt="Blog Badge" height="36"></a>

</div>
