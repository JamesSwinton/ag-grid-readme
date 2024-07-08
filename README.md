<!-- Additional Badges for consideration -->
<!-- ![npm package minimized gzipped size](https://img.shields.io/bundlejs/size/ag-grid-community?style=for-the-badge)
![Dependents (via libraries.io?style=for-the-badge)](https://img.shields.io/librariesio/dependents/npm/ag-grid-community?style=for-the-badge)
![npms.io](https://img.shields.io/npms-io/maintenance-score/ag-grid-community?style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/ag-grid/ag-grid?style=for-the-badge) -->

<div align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Dark-Theme.svg?raw=true"/>
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Light-Theme.svg?raw=true"/>
      <img width="100%" alt="AG Grid Logo" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Dark-Theme.svg?raw=true"/>
    </picture>
    <br><br>
    <img src="https://img.shields.io/github/v/release/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Release">
    <img src="https://img.shields.io/npm/dm/ag-grid-community?style=for-the-badge" alt="NPM Downloads">
    <img src="https://img.shields.io/github/stars/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Repo stars">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ag-grid/ag-grid?style=for-the-badge">
    <br><br>
    <p>AG Grid is a <strong>fully-featured</strong> and <strong>highly customizable</strong> JavaScript data grid. It delivers <strong>outstanding performance</strong>, has <strong>no third-party dependencies</strong> and integrates smoothly with <strong>all major JavaScript frameworks</strong>.</p>
    <br>
    <p><a href="./#overview">Overview</a> • <a href="./#get-started">Get Started</a> • <a href="./#community">Community</a> • <a href="./#support">Support</a></p>
</div>


<div align="center">
    <br>
    <a href="https://github.com/ag-grid/ag-grid-react"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/react.svg?raw=true" height="32" width="32" alt="React Logo"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://github.com/ag-grid/ag-grid-angular"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/angular.svg?raw=true" height="32" width="32" alt="Angular Logo"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://github.com/ag-grid/ag-grid-vue"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/vue.svg?raw=true" height="32" width="32" alt="Vue Logo"><a/>
</div>

## Overview

AG Grid is available in two versions: Community & Enterprise. 

- `ag-grid-community` is free, available under the MIT license, and comes with all of the core features expected from a Data Grid, including Sorting, Filtering, Pagination, Editing, Custom Components, Theming and more.
- `ag-grid-enterprise` is available under a commercial license and comes with advanced features, like Integrated Charting, Pivoting, Master/Detail, Infinite Scrolling, and Exporting in addition to dedicated support from our Engineering team.

### Features

| Feature                      | AG Grid Community | AG Grid Enterprise |
| ---------------------------- | ----------------- | ------------------ |
| Sorting                      | ✔                | ✔                 |
| Filtering                    | ✔                | ✔                 |
| Pagination                   | ✔                | ✔                 |
| Cell Editing                 | ✔                | ✔                 |
| Themes and Styling           | ✔                | ✔                 |
| Selection                    | ✔                | ✔                 |
| Accessibility                | ✔                | ✔                 |
| Custom Components            | ✔                | ✔                 |
| Integrated Charting          |                   | ✔                 |
| Row Grouping and Aggregation |                   | ✔                 |
| Pivoting                     |                   | ✔                 |
| Range Selection              |                   | ✔                 |
| Advanced Filtering           |                   | ✔                 |
| Server-Side Row Model        |                   | ✔                 |
| Infinite Scrolling           |                   | ✔                 |
| Excel Export                 |                   | ✔                 |
| Master/Detail                |                   | ✔                 |
| Tree Data                    |                   | ✔                 |

Visit the [Pricing](https://ag-grid.com/licence-pricing) page for a full comparison.

## Get Started

### Installation

```sh
$ npm install --save ag-grid-community
```

> AG Grid is also available for [React](https://www.ag-grid.com/react-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github), [Angular](https://www.ag-grid.com/angular-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github) and [Vue](https://www.ag-grid.com/vue-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github).

### Quick Start

#### Add a placeholder to HTML

```html
<div id="myGrid" style="height: 150px; width: 600px" class="ag-theme-quartz"></div>
```

#### Import the grid and styles

```js
import { createGrid } from 'ag-grid-community';
import 'ag-grid-community/styles/ag-grid.css';
import 'ag-grid-community/styles/ag-theme-quartz.css';
```

#### Set configuration

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

#### Initialise the grid

```js
const eGridDiv = document.querySelector('#myGrid');
const api = createGrid(eGridDiv, gridOptions);
```

For more information on how to integrate the grid into your project see [Building AG Grid Applications](https://www.ag-grid.com/javascript-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github).

### Customisations

AG Grid is fully customisable, both in terms of appearance and functionality. To alter the look & feel of the data grid, choose from and customise one of our 5 themes, or create your own entirely with our Theme Builder. 

#### Custom Components

AG Grid allows you to add your components within cells, so you can customise the functionality in any way you like.

#### Themes & Styles

AG Grid comes with 5 themes which can be customised by overridding CSS variables. You can also create your own themes entirely using our new Theme Builder - a drag-and-drop interface for prototyping and designing new AG Grid themes:

- [Themes](https://www.ag-grid.com/javascript-data-grid/themes/)
- [Theme Builder](https://www.ag-grid.com/theme-builder/)
- [Figma Design System](https://www.figma.com/community/file/1360600846643230092/ag-grid-design-system)

## Community

AG Grid has a community of...

### Tools & Extensions

-   Python
-   Svelte
-   SolidJS
-   .NET
-   Rust
-   No-code/Low-code

[View All](/)

### Showcase

-   Finance
-   ML/AI
-   Databases
-   Aeronautics

[View All](/)

### Stargazers

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date&theme=dark"/>
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date"/>
  <img width="100%" alt="The AG Grid star history chart" src="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date"/>
</picture>

## Support

AG Grid Enterprise customers have access to dedicated support via ZenDesk, which is monitored by our engineering teams.

### Issue Reporting

If you have found a bug, please report it in this repository's [issues](https://github.com/ag-grid/ag-grid/issues) section. If you're using the Enterprise version, please use the [private ticketing](https://ag-grid.zendesk.com/) system to do that.

### Asking Questions

Look for similar problems on [StackOverflow](https://stackoverflow.com/questions/tagged/ag-grid) using the `ag-grid` tag. If nothing seems related, post a new message there. Please do not use GitHub issues to ask questions.

![Stack Exchange questions](https://img.shields.io/stackexchange/stackoverflow.com/t/ag-grid?style=for-the-badge)

### Contributing

AG Grid is developed by a team of co-located developers in London. If you want to join the team send your application to info@ag-grid.com.

### License

This project is licensed under the MIT license. See the [LICENSE file](./LICENSE.txt) for more info.
