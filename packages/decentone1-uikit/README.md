# 🌌 decentone1 UIkit

[![Version](https://img.shields.io/npm/v/@decentone1-libs/uikit)](https://www.npmjs.com/package/@decentone1-libs/uikit) [![Size](https://img.shields.io/bundlephobia/min/@decentone1-libs/uikit)](https://www.npmjs.com/package/@decentone1-libs/uikit)

decentone1 UIkit is a set of React components and hooks used to build pages on decentone1's apps.

## Install

`yarn add @decentone1-libs/uikit`

## Setup

### Theme

Before using decentone1 UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@decentone1-libs/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@decentone1-libs/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://decentone1.github.io/decentone1-uikit/)
