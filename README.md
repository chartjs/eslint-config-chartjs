# eslint-config-chartjs

Chart.js [shareable ESLint config](http://eslint.org/docs/developer-guide/shareable-configs.html).

## Installation

```sh
npm install --save-dev eslint-config-chartjs
```

## Usage

Once the `eslint-config-chartjs` package is installed, you can use it by specifying `chartjs` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```yml
extends: chartjs

rules:
  # Additional, per-project rules...
```
