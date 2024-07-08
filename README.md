<!-- Additional Badges for consideration -->
<!-- ![npm package minimized gzipped size](https://img.shields.io/bundlejs/size/ag-grid-community?style=for-the-badge)
![Dependents (via libraries.io?style=for-the-badge)](https://img.shields.io/librariesio/dependents/npm/ag-grid-community?style=for-the-badge)
![npms.io](https://img.shields.io/npms-io/maintenance-score/ag-grid-community?style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/ag-grid/ag-grid?style=for-the-badge) -->

<div style="text-align: center;">
    <img src="./github-banner.svg" alt="AG Grid HTML5 Grid trusted by the community, built for enterprise">
    <img src="https://img.shields.io/github/v/release/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Release">
    <img src="https://img.shields.io/npm/dm/ag-grid-community?style=for-the-badge" alt="NPM Downloads">
    <img src="https://img.shields.io/github/stars/ag-grid/ag-grid?style=for-the-badge" alt="GitHub Repo stars">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ag-grid/ag-grid?style=for-the-badge">
    <br><br>
    <p>AG Grid is a <strong>fully-featured</strong> and <strong>highly customizable</strong> JavaScript data grid. It delivers <strong>outstanding performance</strong>, has <strong>no third-party dependencies</strong> and integrates smoothly with <strong>all major JavaScript frameworks</strong>.</p>
</div>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [AG Grid Community vs AG Grid Enterprise](#ag-grid-community-vs-ag-grid-enterprise)
  - [ag-Grid Community ](#ag-grid-community-)
  - [ag-Grid Enterprise ](#ag-grid-enterprise-)
- [Installation](#installation)
- [Usage](#usage)
  - [Add a placeholder to HTML](#add-a-placeholder-to-html)
  - [Import the grid and styles](#import-the-grid-and-styles)
  - [Set configuration](#set-configuration)
  - [Initialise the grid](#initialise-the-grid)
- [Features](#features)
- [Customisations](#customisations)
  - [Custom Components](#custom-components)
  - [Themes](#themes)
  - [Theme Builder](#theme-builder)
- [Community](#community)
  - [Tools \& Extensions](#tools--extensions)
  - [Showcase](#showcase)
- [Support](#support)
  - [Issue Reporting](#issue-reporting)
  - [Asking Questions](#asking-questions)
- [Contributing](#contributing)
- [License](#license)

## AG Grid Community vs AG Grid Enterprise

`ag-grid-community` is the free and open-source version of ag-Grid which comes with all of the core features needed for a data grid. However, for more advanced features and dedicated support, `ag-grid-enterprise` is available under a commercial license.

### ag-Grid Community [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ag-grid-community&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ag-grid-community)

![NPM License](https://img.shields.io/npm/l/ag-grid-community?style=for-the-badge)
![NPM Downloads](https://img.shields.io/npm/dm/ag-grid-community?style=for-the-badge)

-   **Open Source**: Licensed under MIT, making it free to use in both commercial and non-commercial applications.
-   **Core Features**: Includes essential features such as sorting, filtering, pagination, cell editing, and theming.
-   **Community Support**: Access to community support via GitHub Issues and various online forums.

### ag-Grid Enterprise [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ag-grid-enterprise&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ag-grid-community)

![NPM License](https://img.shields.io/npm/l/ag-grid-enterprise?style=for-the-badge)
![NPM Downloads](https://img.shields.io/npm/dm/ag-grid-enterprise?style=for-the-badge)

-   **Commercial License**: Requires a paid license, which includes access to additional features and dedicated support.
-   **Advanced Features**:
    -   **Integrated Charts**: Enhanced data visualization and interaction capabilities.
    -   **Row Grouping and Aggregation**: Group rows and aggregate data dynamically.
    -   **Pivoting**: Advanced pivot table functionalities.
    -   **Integrated Excel Export**: Export data to Excel with extensive customization options.
    -   **Server-Side Row Model**: Efficiently handle large datasets with server-side operations.
    -   **Master/Detail**: Display hierarchical data with master/detail views.
-   **Premium Support**: Get access to dedicated technical support to help you with integration and troubleshooting.

Choosing between `ag-grid-community` and `ag-grid-enterprise` depends on your project's needs and the level of support and advanced features you require. Many users start with the community version and upgrade to the enterprise version as their application grows and demands more sophisticated grid capabilities.

For a detailed comparison, visit the [Pricing](https://ag-grid.com/licence-pricing) page.

## Installation

```sh
$ npm install --save ag-grid-community
```

> AG Grid is also available for [React](https://www.ag-grid.com/react-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github), [Angular](https://www.ag-grid.com/angular-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github) and [Vue](https://www.ag-grid.com/vue-data-grid/getting-started/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github).

## Usage

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

### Set configuration

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

For more information on how to integrate the grid into your project see [Building AG Grid Applications](https://www.ag-grid.com/javascript-data-grid/building/?utm_source=ag-grid-readme&utm_medium=repository&utm_campaign=github).

## Features

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
| Clipboard Operations         |                   | ✔                 |
| Context Menu                 |                   | ✔                 |
| Localisation                 |                   | ✔                 |

For a detailed comparison, visit the [Pricing](https://ag-grid.com/licence-pricing) page.

## Customisations

AG Grid is highly customizable, allowing you to tailor the grid's appearance and functionality to meet your specific requirements. This section covers various customization options, including custom cell renderers, cell editors, and the AG Grid Theme Builder.

### Custom Components

### Themes

### Theme Builder

The AG Grid Theme Builder is a powerful tool that allows you to create custom themes for your ag-Grid instances. You can adjust colors, fonts, borders, and other style properties to match your application's design guidelines.

**Features of the AG Grid Theme Builder:**

-   Interactive Interface: Easily customize the appearance of the grid using a visual interface.
-   Real-Time Preview: See changes in real-time as you adjust theme settings.
-   Export Options: Export your custom theme as CSS or SCSS to integrate seamlessly into your project.

You can access the AG Grid Theme Builder [here](https://www.ag-grid.com/theme-builder/).

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

## Support

AG Grid Enterprise customers have access to dedicated support via ZenDesk, which is monitored by our engineering teams.

### Issue Reporting

If you have found a bug, please report it in this repository's [issues](https://github.com/ag-grid/ag-grid/issues) section. If you're using the Enterprise version, please use the [private ticketing](https://ag-grid.zendesk.com/) system to do that.

### Asking Questions

Look for similar problems on [StackOverflow](https://stackoverflow.com/questions/tagged/ag-grid) using the `ag-grid` tag. If nothing seems related, post a new message there. Please do not use GitHub issues to ask questions.

![Stack Exchange questions](https://img.shields.io/stackexchange/stackoverflow.com/t/ag-grid?style=for-the-badge)

## Contributing

AG Grid is developed by a team of co-located developers in London. If you want to join the team send your application to info@ag-grid.com.

## License

This project is licensed under the MIT license. See the [LICENSE file](./LICENSE.txt) for more info.
