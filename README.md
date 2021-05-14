# 🥞 Durian Exhange UIkit

Durian Exchange UI kit is a set of React components and hooks used to build pages on Durian Exchange's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @durianexchange/uikit`

## Setup

### Theme

Before using Durian Exchange UI kit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@durianexchange/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@durianexchange/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.