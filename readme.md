# react-countries-details

A simple react component that provides country details information, including flags, calling codes, postal codes and many more.

## How to use it?

You can use the package in this way:

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
