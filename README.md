<div align="center">
    <img src="https://github.com/frappe/design/blob/master/logos/data-table-logo.svg" height="128">
    <h2>Frappe DataTable</h2>
    <p align="center">
    <p>
    A modern datatable library for the web
    </p>

[![travis build](https://api.travis-ci.com/frappe/datatable.svg?branch=master)](https://travis-ci.org/frappe/datatable)
[![npm version](https://badge.fury.io/js/frappe-datatable.svg)](https://badge.fury.io/js/frappe-datatable)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)

</div>

## Introduction

Frappe DataTable is a simple, modern and interactive datatable library for displaying tabular data. Originally built for [ERPNext](https://github.com/frappe/erpnext), it can be used to render large amount of rows without sacrificing performance and has the basic data grid features like inline editing and keyboard navigation. It does not require jQuery, like most data grids out there.

## Demo

![datatable-demo-2](https://user-images.githubusercontent.com/9355208/40740030-5412aa40-6465-11e8-8542-b0247ab1daac.gif)

## Features

### Cell Features

* Custom Formatters
* Inline Editing
* Mouse Selection
* Copy Cells
* Keyboard Navigation
* Custom Cell Editor

### Column Features

* Reorder Columns
* Sort by Column
* Remove / Hide Column
* Custom Actions
* Resize Column
* Flexible Layout

### Row Features

* Row Selection
* Tree Structured Rows
* Inline Filters
* Large Number of Rows
* Dynamic Row Height

## Install

```bash
yarn add frappe-datatable
# or
npm install frappe-datatable
```

> Note: [`sortablejs`](https://github.com/RubaXa/Sortable) and [`clusterize.js`](https://github.com/NeXTs/Clusterize.js) are required to be installed as well.

## Usage

```js
const datatable = new DataTable('#datatable', {
  columns: [ 'First Name', 'Last Name', 'Position' ],
  data: [
    [ 'Don', 'Joe', 'Designer' ],
    [ 'Mary', 'Jane', 'Software Developer' ]
  ]
});
```

## Contribution

* `yarn start` - Start dev server

Now you can open the `index.html` located in the root folder, and start development. Make sure to fix all eslint errors before making a Pull Request.


## License

[MIT](http://opensource.org/licenses/MIT)
