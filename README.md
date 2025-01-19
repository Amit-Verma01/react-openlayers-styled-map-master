# react-openlayers-styled-map

> Openlayers map component wrapped in react component with style and global hooks

[![NPM](https://img.shields.io/npm/v/react-openlayers-styled-map.svg)](https://www.npmjs.com/package/react-openlayers-styled-map) [![TypeScript Style Guide](https://img.shields.io/badge/code_style-typecript-brightgreen.svg)](https://www.typescriptlang.org/)
![NPM](https://img.shields.io/npm/l/react-openlayers-styled-map)


This (react-openlayers-styled-map) is a React.JS component made in Typescript.
It acts as a wrapper around [OpenLayers](https://openlayers.org/) map object and tries to supress the complexity of a starting map project.

Currently, the lib has a simple global state hook that provides access from any part of a react project to the OL map object and some extra key functions.

Also, some usefull styled and ready-to-use map controls, some of them directly translated from OL Docs.

- Measure Polygon area
- Measure Distance
- Export map as image (uses [html2canvas](https://www.npmjs.com/package/html2canvas))
- Export map as PDF (uses [jsPDF](https://www.npmjs.com/package/jspdf))
- Draw Circle Radius
- Pin Coordinates
- Redirect to Google Street View from point

## Install

```bash
npm install --save react-openlayers-styled-map
//or
yarn add react-openlayers-styled-map

//ATTENTION
//react-openlayers-styled-map uses Openlayers (ol) package as peer dependency
npm install ol
yarn add ol
```

