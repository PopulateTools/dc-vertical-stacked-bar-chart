<h1 align="center">DC.js Vertical Stacked Bar Chart</h1>

<div align="center">
  DC plugin to render a vertical stacked bar chart.
</div>
<br />

<div align="center">
    <img src="https://img.shields.io/bundlephobia/minzip/dc-vertical-stacked-bar-chart"/>
    <img src="https://img.shields.io/npm/v/dc-vertical-stacked-bar-chart"/>
</div>

## Table of Contents
- [Installation](#Installation)
- [Requirements](#Requirements)
- [How to use](#use)
- [Example](#example)
- [Development](#Development)

## Installation

As a module with NPM or YARN

```bash

# npm 
npm i dc-vertical-stacked-bar-chart --save-dev

# yarn
yarn add dc-vertical-stacked-bar-chart
```

## Requirements

- [DC.JS v4.0.0](https://github.com/dc-js/dc.js/tree/4.2.0)
- [Crossfilter2](https://github.com/crossfilter/crossfilter/tree/1.4.5)


## How to use

```javascript
import stackedVertical from "dc-vertical-stacked-bar-chart";
import crossfilter from "crossfilter2";
import { chartRegistry, renderAll } from "dc";
```

With this plugin, you have to be a little careful. Since it's made for a particular case, we wanted to show only a single vertical bar chart. It works fine with two values. If you add more values, you'll have to calculate the spacing and position of those values. If your datasets contain many values, you will run out of space for the texts and values. You can hide them and let the title show the text and value.


## Example

<h3>Vertical stacked Bar Chart</h3>
<a href="https://n7vx2.csb.app/">
  <img src="https://raw.githubusercontent.com/PopulateTools/dc-vertical-stacked-bar-chart/main/images/dc-vertical-stacked.png"/>
</a>

## Development

- Clone the repo
- Install dependencies
- Start coding! 
- Send a PR

