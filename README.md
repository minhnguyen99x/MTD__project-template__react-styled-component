# React + TypeScript frontend template

A starter for React apps in TypeScript, with UI, state, forms and translations already wired together.

## What is included

- **UI:** MUI components rendered through styled-components (`@mui/styled-engine-sc`), global styles and a shared theme
- **State:** Redux Toolkit with redux-saga middleware for side effects
- **Translations:** react-intl with English and Vietnamese messages and a language switcher in the header
- **Routing:** react-router with a shared layout (header, search, footer)
- **Path aliases:** configured through CRACO

## Structure

```
src/
  components/  layout, header (search, language select), footer, product card
  pages/       Home, Register (form placeholder)
  store/       Redux store and models
  services/    API calls
  locale/      en, vi
  constants/   routes, theme, locales
  mock/        sample product data
```

## Run

```bash
npm install
npm start
```
