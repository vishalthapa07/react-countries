# react-countries-details

A simple react component that provides country information, including flags, calling codes, and postal codes. It makes adding international features to your app quick and easy.

## How to use it?

You can use the project in this way:

### Install

```bash
# with npm
npm install react-countries-details

# with yarn
yarn add react-countries-details
```

### Usage

- Import the package in your app:

```js
import { useCountry } from "react-countries-details";
```

- Get the country information from the hook:

```js
const {loading, error, country} = useCountry('Republic Of India')'
```

### Author

- [Mr. Thapa, Vishal](https://vishalthapa.netlify.app/)
