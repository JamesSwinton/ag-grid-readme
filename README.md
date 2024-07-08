<!-- Additional Badges for consideration -->
<!-- ![npm package minimized gzipped size](https://img.shields.io/bundlejs/size/ag-grid-community?style=for-the-badge) -->

<div align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Dark-Theme.svg?raw=true"/>
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Light-Theme.svg?raw=true"/>
      <img width="100%" alt="AG Grid Logo" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-Grid-Logo_Dark-Theme.svg?raw=true"/>
    </picture>
    <div align="center">
        <h4><a href="https://www.ag-grid.com">🌐 Website</a> • <a href="https://www.ag-grid.com/documentation">📖 Documentation</a> • <a href="https://www.ag-grid.com/community">🏘️ Community</a></h4>
    </div>
    <br>
    <img src="https://img.shields.io/github/v/release/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Release">
    <img src="https://img.shields.io/npm/dm/ag-grid-community?style=for-the-badge" alt="NPM Downloads">
    <img src="https://img.shields.io/github/stars/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Repo stars">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ag-grid/ag-grid?style=for-the-badge">
    <br><br>
    <a href="https://sonarcloud.io/dashboard?id=ag-grid-enterprise">
      <img src="https://sonarcloud.io/api/project_badges/measure?project=ag-grid-enterprise&metric=alert_status" alt="Quality Gate Status">
    </a>
    <img src="https://img.shields.io/npms-io/maintenance-score/ag-grid-community" alt="npms.io">
    <img src="https://img.shields.io/github/commit-activity/m/ag-grid/ag-grid" alt="GitHub commit activity">
    <img src="https://img.shields.io/librariesio/dependents/npm/ag-grid-community" alt="Dependents (via libraries.io?style=for-the-badge)">
    <br><br>
    <p>AG Grid is a <strong>fully-featured</strong> and <strong>highly customizable</strong> JavaScript Data Grid. It delivers <strong>outstanding performance</strong>, has <strong>no third-party dependencies</strong> and comes with support for <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-react"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/react.svg?raw=true" height="16" width="16" alt="React Logo"> React</a></strong>, <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-angular"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/angular.svg?raw=true" height="16" width="16" alt="Angular Logo"> Angular</a></strong> and <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-vue"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/vue.svg?raw=true" height="16" width="16" alt="Vue Logo"> Vue</a></strong>.</p>
    <br>
</div>

![Kitchen Sink Demo](./kitchen-sink-demo.png)
<br><br>

## 📖 Overview

<details>
  <summary><strong>Table of Contents</strong></summary>

- [📖 Overview](#-overview)
  - [Features](#features)
  - [Examples](#examples)
- [⚡️ Quick Start](#️-quick-start)
  - [Installation](#installation)
  - [Add a placeholder to HTML](#add-a-placeholder-to-html)
  - [Import the grid and styles](#import-the-grid-and-styles)
  - [Set configuration](#set-configuration)
  - [Initialise the grid](#initialise-the-grid)
  - [Seed Projects](#seed-projects)
- [🛠️ Customisations](#️-customisations)
- [🌍 Community](#-community)
  - [Tools \& Extensions](#tools--extensions)
  - [Showcase](#showcase)
  - [Stargazers](#stargazers)
- [🤝 Support](#-support)
  - [Issue Reporting](#issue-reporting)
  - [Asking Questions](#asking-questions)
  - [Contributing](#contributing)
  - [License](#license)
- [📊 AG Charts](#-ag-charts)
- [📢 Socials](#-socials)
</details>

AG Grid is available in two versions: Community & Enterprise. 

- `ag-grid-community` is free, available under the MIT license, and comes with all of the core features expected from a JavaScript Data Grid, including Sorting, Filtering, Pagination, Editing, Custom Components, Theming and more.
- `ag-grid-enterprise` is available under a commercial license and comes with advanced features, like Integrated Charting, Pivoting, Master/Detail, Infinite Scrolling, and Exporting in addition to dedicated support from our Engineering team.

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
| Integrated Charting          | ❌                | ✅                 |
| Row Grouping and Aggregation | ❌                | ✅                 |
| Pivoting                     | ❌                | ✅                 |
| Range Selection              | ❌                | ✅                 |
| Advanced Filtering           | ❌                | ✅                 |
| Server-Side Row Model        | ❌                | ✅                 |
| Infinite Scrolling           | ❌                | ✅                 |
| Excel Export                 | ❌                | ✅                 |
| Master/Detail                | ❌                | ✅                 |
| Tree Data                    | ❌                | ✅                 |

> [!IMPORTANT]
> Visit the [License](https://www.ag-grid.com/license-pricing/) page for a full comparison.

### Examples

...

## ⚡️ Quick Start

AG Grid is easy to setup - all you need to do is provide your data and define your column structure. Read on for vanilla JavaScript installation instructions, or refer to our framework-specific guides for <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-react"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/react.svg?raw=true" height="16" width="16" alt="React Logo"> React</a></strong>, <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-angular"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/angular.svg?raw=true" height="16" width="16" alt="Angular Logo"> Angular</a></strong> and <strong><a href="https://github.com/ag-grid/ag-grid/tree/latest/packages/ag-grid-vue"><img src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/fw-logos/vue.svg?raw=true" height="16" width="16" alt="Vue Logo"> Vue</a></strong>.

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

### Seed Projects 

We also provide [Seed Projects](https://github.com/ag-grid/ag-grid-seed) to help you get started with common configurations:

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/typescript.svg?raw=true" align="center" width="16" height="16" alt="React Logo">&nbsp;TypeScript</summary>

- [Vite - TypeScript](https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/vite-typescript)
- [Webpack5 - TypeScript](https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/webpack5-typescript)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/javascript.svg?raw=true" align="center" width="16" height="16" alt="React Logo">&nbsp;JavaScript</summary>

- [Webpack5 - JavaScript](https://github.com/ag-grid/ag-grid-seed/tree/main/enterprise/packages/webpack5-javascript)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/react.svg?raw=true" align="center" width="16" height="16" alt="React Logo">&nbsp;React</summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/angular.svg?raw=true" align="center" width="16" height="16" alt="Angular Logo">&nbsp;Angular</summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/vue.svg?raw=true" align="center" width="16" height="16" alt="Vue Logo">&nbsp;Vue</summary>

- [name](link)
</details>

## 🛠️ Customisations

AG Grid is fully customisable, both in terms of appearance and functionality. We have many ways in which the grid can be customised, and a selection of tools to help create those customisations. Expand each section to learn more.

<details>
  <summary>Custom Components</summary>

- [Custom Components](https://www.ag-grid.com/javascript-data-grid/cell-renderer/)
</details>

<details>
  <summary>Themes</summary>

- [Themes](https://www.ag-grid.com/javascript-data-grid/themes/)
</details>

<details>
  <summary>Theme Builder</summary>

- [Theme Builder](https://www.ag-grid.com/theme-builder/)
</details>

<details>
  <summary>Figma Design System</summary>

- [Figma Design System](https://www.figma.com/community/file/1360600846643230092/ag-grid-design-system)
</details>

> [!IMPORTANT]
> For more information on building Data Grids with AG Grid, refer to our [Documentation](https://www.ag-grid.com/javascript-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github).

## 🌍 Community

### Tools & Extensions

AG Grid has a large and active community who have created an ecosystem of 3rd party tools, extensions and utilities to help you build your next project with AG Grid, no matter which language or framework you use. Browse the examples below, or visit our [Community](https://www.ag-grid.com/community/) section to learn more.

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/react.svg?raw=true" align="center" width="16" height="16" alt="React Logo">&nbsp;React</summary>

#### Adaptable
AdapTable for AG Grid is a powerful extension for the market-leading AG Grid Data Grid. AdapTable extends the powerful functionality provided by AG Grid to enable you to build data management applications unparalleled in power and sophistication, with features not previously available.

#### Astro UXDS
Astro UXDS is a collection of guidelines, patterns and components for designing space-based user interface applications which provides a custom `Astro` theme for AG Grid.

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/angular.svg?raw=true" align="center" width="16" height="16" alt="Angular Logo">&nbsp;Angular</summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/typescript.svg?raw=true" align="center" width="16" height="16" alt="TypeScript Logo">&nbsp;TypeScript</summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/python.svg?raw=true" align="center" width="16" height="16" alt="Python Logo">&nbsp;Python</summary>

- [Dash AG Grid](https://www.figma.com/community/file/1360600846643230092/ag-grid-design-system](https://dash.plotly.com/dash-ag-grid)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/svelte.svg?raw=true" align="center" width="16" height="16" alt="Svelte Logo">&nbsp;Svelte</summary>

- [AG Grid Svelte](https://ag-grid-svelte.michael.kim/guide/overview/)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/solidjs.svg?raw=true" align="center" width="16" height="16" alt="SolidJS Logo">&nbsp;SolidJS</summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/vue.svg?raw=true" align="center" width="16" height="16" alt="Vue Logo">&nbsp;Vue</summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/.net.svg?raw=true" align="center" width="16" height="16" alt=".NET Logo">&nbsp;.NET</summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/rust.svg?raw=true" align="center" width="16" height="16" alt="Rust Logo">&nbsp;Rust</summary>

- [name](link)
</details>

<details>
  <summary><img src="https://github.com/ag-grid/ag-grid/blob/a13bc308b641a263e3d531b2ad4ff1f938e7b342/documentation/ag-grid-docs/public/community/frameworks/laravel.svg?raw=true" align="center" width="16" height="16" alt="Laravel Logo">&nbsp;Laravel</summary>

- [name](link)
</details>

[View All](/)

### Showcase

AG Grid is used by 100,000's of developers across the world, from almost every industry. Whilst a lot of these projects are private, we've curated a selection of open-source projects from a variety of industries where household names rely on AG Grid, including [J.P.Morgan](), [MongoDB]() and [Nasa]().

<details>
  <summary>🏦&nbsp;Finance</summary>

- [name](link)
</details>

<details>
  <summary>🤖&nbsp;ML/AI</summary>

- [name](link)
</details>

<details>
  <summary>🫙&nbsp;Database</summary>

- [name](link)
</details>

<details>
  <summary>🚀&nbsp;Aeronautics</summary>

- [name](link)
</details>

[View All](/)

### Stargazers

Founded in 2016, AG Grid has seen a steady-rise in popularity and is now the market leader for Data Grids:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date&theme=dark"/>
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date"/>
  <img width="100%" alt="The AG Grid star history chart" src="https://api.star-history.com/svg?repos=ag-grid/ag-grid&type=Date"/>
</picture>

## 🤝 Support

AG Grid Enterprise customers have access to dedicated support via [ZenDesk](https://ag-grid.zendesk.com/hc/en-us), which is monitored by our engineering teams.

### Issue Reporting

If you have found a bug, please report it in this repository's [issues](https://github.com/ag-grid/ag-grid/issues) section. If you're using the Enterprise version, please use the [private ticketing](https://ag-grid.zendesk.com/) system to do that.

![GitHub Issues or Pull Requests](https://img.shields.io/github/issues-closed/ag-grid/ag-grid?style=for-the-badge&color=%233d8c40)

### Asking Questions

Look for similar problems on [StackOverflow](https://stackoverflow.com/questions/tagged/ag-grid) using the `ag-grid` tag. If nothing seems related, post a new message there. Please do not use GitHub issues to ask questions.

![Stack Exchange questions](https://img.shields.io/stackexchange/stackoverflow.com/t/ag-grid?style=for-the-badge&color=%233d8c40)

### Contributing

AG Grid is developed by a team of co-located developers in London. If you want to join the team send your application to info@ag-grid.com.

### License

This project is licensed under the MIT license. See the [LICENSE file](./LICENSE.txt) for more info.

## 📢 Socials

To keep up to date with all the latest news from AG Grid, follow us on our social platforms:

![Twitter Badge](https://img.shields.io/badge/-X%20(Twitter)-black?style=for-the-badge&logo=x)
![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin)
![YouTube Badge](https://img.shields.io/badge/-YouTube-red?style=for-the-badge&logo=youtube)
![Blog Badge](https://img.shields.io/badge/-Blog-grey?style=for-the-badge&logo=rss)

<h2><img width="24" height="24" src="https://github.com/ag-grid/ag-grid/blob/latest/documentation/ag-grid-docs/public/images/ag-logos/svg-logos/AG-BrandMark_Light-Theme.svg?raw=true" alt="AG ChartsLogo">AG Charts</h2>

If you've made it this far, you may be interested in our latest project: [AG Charts](https://charts.ag-grid.com). The best JavaScript Charting library, in the world.

Initially built to power [Integrated Charts](https://www.ag-grid.com/javascript-data-grid/integrated-charts/) in AG Grid, we open-sourced this project in 2018. Having seen the steady rise in popularity since then, we have decided to invest in AG Charts with a dedicated Enterprise version (`ag-charts-enterprise`) in addition to our continued support of `ag-charts-community`:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ag-grid/ag-charts&type=Date&theme=dark"/>
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ag-grid/ag-charts&type=Date"/>
  <img width="100%" alt="The AG Grid star history chart" src="https://api.star-history.com/svg?repos=ag-grid/ag-charts&type=Date"/>
</picture>

Learn more at [AG-Charts.com](https://charts.ag-grid.com/)
