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
    <img alt="Static Badge" src="https://img.shields.io/badge/-X%20(Twitter)-black?style=for-the-badge&logo=x">
    <img alt="Static Badge" src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin">
    <img alt="Static Badge" src="https://img.shields.io/badge/-youtube-red?style=for-the-badge&logo=youtube">
    <img alt="Static Badge" src="https://img.shields.io/badge/-blog-grey?style=for-the-badge&logo=rss">
    <br><br>
    <img src="https://img.shields.io/github/v/release/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Release">
    <img src="https://img.shields.io/npm/dm/ag-grid-community?style=for-the-badge" alt="NPM Downloads">
    <img src="https://img.shields.io/github/stars/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Repo stars">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ag-grid/ag-grid?style=for-the-badge">
    <br><br>
    <p>AG Grid is a <strong>fully-featured</strong> and <strong>highly customizable</strong> JavaScript data grid. It delivers <strong>outstanding performance</strong>, has <strong>no third-party dependencies</strong> and integrates smoothly with <strong>all major JavaScript frameworks</strong>.</p>
    <br>
    <p><a href="./#overview">Overview</a> • <a href="./#features">Features</a> • <a href="./#get-started">Get Started</a> • <a href="./#community">Community</a> • <a href="./#support">Support</a></p>
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

## 🎯 Features

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

## ⚡️ Quick Start

AG Grid is easy to get started with all you need to do is provide your data and define your column structure. We also provide seed repositories to help you get started with common configurations:

- [Vite - TypeScript](https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/vite-typescript)
- [Webpack5 - JavaScript](https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/webpack5-javascript)
- [Webpack5 - TypeScript](https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/webpack5-typescript)

### Installation

```sh
$ npm install --save ag-grid-community
```

> [!NOTE]
> AG Grid is also available for [React](https://www.ag-grid.com/react-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github), [Angular](https://www.ag-grid.com/angular-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github) and [Vue](https://www.ag-grid.com/vue-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github).

### Add a placeholder to HTML

```html
<div id="myGrid" style="height: 150px; width: 600px" class="ag-theme-quartz"></div>
```

### Import the grid and styles

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

### Initialise the grid

```js
const eGridDiv = document.querySelector('#myGrid');
const api = createGrid(eGridDiv, gridOptions);
```

### Customisations

AG Grid is fully customisable, both in terms of appearance and functionality. We have many ways in which the grid can be customised and a selection of tools to help create those customisations. Expand each section to learn more.

<details>
  <summary><b>Custom Components</b></summary>

- [Custom Components](https://www.ag-grid.com/javascript-data-grid/cell-renderer/)
</details>

<details>
  <summary><b>Themes</b></summary>

- [Themes](https://www.ag-grid.com/javascript-data-grid/themes/)
</details>

<details>
  <summary><b>Theme Builder</b></summary>

- [Theme Builder](https://www.ag-grid.com/theme-builder/)
</details>

<details>
  <summary><b>Figma Design System</b></summary>

- [Figma Design System](https://www.figma.com/community/file/1360600846643230092/ag-grid-design-system)
</details>

> [!Note]
> For more information on how to integrate the grid into your project see [Building AG Grid Applications](https://www.ag-grid.com/javascript-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github).

## Community

AG Grid has a large community who have developed an entire ecosystem of community-built tools, extensions and utilities to help you create your next project, no matter which language or framework you use. Browse some examples below, or visit our [Community](https://www.ag-grid.com/community/) section to learn more.

### Tools & Extensions

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/python.svg?raw=true" align="center" width="16" height="16" alt="Python Logo">&nbsp;<b>Python</b></summary>

- [Dash AG Grid](https://www.figma.com/community/file/1360600846643230092/ag-grid-design-system](https://dash.plotly.com/dash-ag-grid)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/svelte.svg?raw=true" align="center" width="16" height="16" alt="Svelte Logo">&nbsp;<b>Svelte</b></summary>

- [AG Grid Svelte](https://ag-grid-svelte.michael.kim/guide/overview/)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/solidjs.svg?raw=true" align="center" width="16" height="16" alt="SolidJS Logo">&nbsp;<b>SolidJS</b></summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/.net.svg?raw=true" align="center" width="16" height="16" alt=".NET Logo">&nbsp;<b>.NET</b></summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/rust.svg?raw=true" align="center" width="16" height="16" alt="Rust Logo">&nbsp;<b>Rust</b></summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/laravel.svg?raw=true" align="center" width="16" height="16" alt="Laravel Logo">&nbsp;<b>Laravel</b></summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/react.svg?raw=true" align="center" width="16" height="16" alt="React Logo">&nbsp;<b>React</b></summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/angular.svg?raw=true" align="center" width="16" height="16" alt="Angular Logo">&nbsp;<b>Angular</b></summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/vue.svg?raw=true" align="center" width="16" height="16" alt="Vue Logo">&nbsp;<b>Vue</b></summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/typescript.svg?raw=true" align="center" width="16" height="16" alt="TypeScript Logo">&nbsp;<b>TypeScript</b></summary>

- [name](link)
</details>

[View All](/)

### Showcase

<details>
  <summary>🏦&nbsp;<b>Finance</b></summary>

- [name](link)
</details>

<details>
  <summary>🤖&nbsp;<b>ML/AI</b></summary>

- [name](link)
</details>

<details>
  <summary>🫙&nbsp;<b>Database</b></summary>

- [name](link)
</details>

<details>
  <summary>🚀&nbsp;<b>Aeronautics</b></summary>

- [name](link)
</details>

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
