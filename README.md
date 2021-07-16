# VTEX inStore QA

This project is to launch the tenant instoreqa using the instore-core gatsby plugins.

## Setup

```bash
yarn
```

PS.: must have npm permission to use private @vtexlab packages

## Run

```bash
yarn start
```

## Build

```bash
yarn build
```

To test build:

```bash
yarn serve
```

## Test

```bash
yarn test
```

## To launch another version

```
Open a PR on this repo (probably updating @vtexlab/gatsby-theme-instore-core version)
```

## Cypress

Declare the environment variables on your terminal:

```bash
export CYPRESS_DEFAULT_LOGIN='VALUE'
export CYPRESS_DEFAULT_PASSWORD='VALUE'
```

And run Cypress locally with:

```bash
yarn cypress:open
```
