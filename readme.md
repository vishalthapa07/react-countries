# react-countries

A ReactJS hook to get the country information.

## How to use it?

You can use the project in this way:

### Install

```bash
# with npm
npm install react-countries

# with yarn
yarn add react-countries
```

### Usage

- Import the package in your app:

```js
import { useCountry } from "react-countries";
```

- Get the country information from the hook:

```js
const {loading, error, country} = useCountry('Republic Of India')'
```
