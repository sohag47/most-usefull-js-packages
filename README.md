# Most Useful JavaScript Packages for React

A curated list of the most useful JavaScript packages for React development, organized by category.

## Table of Contents
- [UI Component Libraries](#ui-component-libraries)
- [State Management](#state-management)
- [Routing](#routing)
- [Forms](#forms)
- [Data Fetching](#data-fetching)
- [Animation](#animation)
- [Styling](#styling)
- [Testing](#testing)
- [Development Tools](#development-tools)
- [Utilities](#utilities)
- [Charts & Visualization](#charts--visualization)
- [Icons](#icons)
- [Date & Time](#date--time)
- [Drag & Drop](#drag--drop)
- [Table & Grid](#table--grid)

## UI Component Libraries

### Material-UI (MUI)
```bash
npm install @mui/material @emotion/react @emotion/styled
```
A comprehensive React component library that implements Google's Material Design.

### Ant Design
```bash
npm install antd
```
Enterprise-class UI design language and React UI library with a set of high-quality components.

### Chakra UI
```bash
npm install @chakra-ui/react @emotion/react @emotion/styled framer-motion
```
A simple, modular and accessible component library that provides building blocks for React applications.

### React Bootstrap
```bash
npm install react-bootstrap bootstrap
```
Bootstrap components built with React, replacing Bootstrap's JavaScript with React components.

### Mantine
```bash
npm install @mantine/core @mantine/hooks
```
A fully featured React components library with 100+ customizable components.

## State Management

### Redux Toolkit
```bash
npm install @reduxjs/toolkit react-redux
```
The official, opinionated, batteries-included toolset for efficient Redux development.

### Zustand
```bash
npm install zustand
```
A small, fast and scalable bearbones state-management solution using simplified flux principles.

### Jotai
```bash
npm install jotai
```
Primitive and flexible state management for React based on atomic state.

### Recoil
```bash
npm install recoil
```
A state management library for React that provides several capabilities for managing global state.

### MobX
```bash
npm install mobx mobx-react-lite
```
Simple, scalable state management through transparent functional reactive programming.

## Routing

### React Router
```bash
npm install react-router-dom
```
The standard routing library for React applications.

### TanStack Router
```bash
npm install @tanstack/react-router
```
A fully type-safe React router with built-in data fetching and state management.

## Forms

### React Hook Form
```bash
npm install react-hook-form
```
Performant, flexible and extensible forms with easy-to-use validation.

### Formik
```bash
npm install formik
```
Build forms in React without the tears, handling form state, validation, and submission.

### React Final Form
```bash
npm install react-final-form final-form
```
High performance subscription-based form state management for React.

### Yup
```bash
npm install yup
```
JavaScript schema builder for value parsing and validation (works great with form libraries).

### Zod
```bash
npm install zod
```
TypeScript-first schema validation with static type inference.

## Data Fetching

### TanStack Query (React Query)
```bash
npm install @tanstack/react-query
```
Powerful asynchronous state management for TS/JS, REST, and GraphQL.

### SWR
```bash
npm install swr
```
React Hooks for data fetching by Vercel, with built-in cache and revalidation.

### Axios
```bash
npm install axios
```
Promise-based HTTP client for the browser and Node.js.

### Apollo Client
```bash
npm install @apollo/client graphql
```
A comprehensive state management library for JavaScript that enables you to manage both local and remote data with GraphQL.

## Animation

### Framer Motion
```bash
npm install framer-motion
```
A production-ready motion library for React with declarative animations.

### React Spring
```bash
npm install @react-spring/web
```
Spring-physics based animation library that covers most UI related animation needs.

### GSAP (GreenSock)
```bash
npm install gsap
```
Professional-grade JavaScript animation for the modern web.

### React Transition Group
```bash
npm install react-transition-group
```
An easy way to perform animations when a React component enters or leaves the DOM.

## Styling

### Styled Components
```bash
npm install styled-components
```
Visual primitives for the component age using tagged template literals.

### Emotion
```bash
npm install @emotion/react @emotion/styled
```
A library designed for writing CSS styles with JavaScript.

### Tailwind CSS
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```
A utility-first CSS framework for rapidly building custom designs.

### CSS Modules
Built into Create React App and Next.js - scoped CSS for components.

## Testing

### Jest
```bash
npm install --save-dev jest
```
Delightful JavaScript testing framework with a focus on simplicity.

### React Testing Library
```bash
npm install --save-dev @testing-library/react @testing-library/jest-dom
```
Simple and complete testing utilities that encourage good testing practices.

### Vitest
```bash
npm install --save-dev vitest
```
A blazing fast unit test framework powered by Vite.

### Cypress
```bash
npm install --save-dev cypress
```
Fast, easy and reliable testing for anything that runs in a browser.

### Playwright
```bash
npm install --save-dev @playwright/test
```
Reliable end-to-end testing for modern web apps.

## Development Tools

### ESLint
```bash
npm install --save-dev eslint
```
Find and fix problems in your JavaScript code.

### Prettier
```bash
npm install --save-dev prettier
```
An opinionated code formatter that supports many languages.

### Storybook
```bash
npx storybook@latest init
```
Build UI components and pages in isolation for development, testing, and documentation.

### React DevTools
Browser extension for debugging React applications.

## Utilities

### Lodash
```bash
npm install lodash
```
A modern JavaScript utility library delivering modularity, performance & extras.

### Date-fns
```bash
npm install date-fns
```
Modern JavaScript date utility library - modular and lightweight.

### Ramda
```bash
npm install ramda
```
A practical functional library for JavaScript programmers.

### Classnames
```bash
npm install classnames
```
A simple JavaScript utility for conditionally joining classNames together.

### UUID
```bash
npm install uuid
```
Generate RFC-compliant UUIDs in JavaScript.

### Immer
```bash
npm install immer
```
Create the next immutable state by mutating the current one.

## Charts & Visualization

### Recharts
```bash
npm install recharts
```
A composable charting library built on React components.

### Chart.js with React-Chartjs-2
```bash
npm install chart.js react-chartjs-2
```
Simple yet flexible JavaScript charting for React.

### Victory
```bash
npm install victory
```
A collection of composable React components for building interactive data visualizations.

### D3.js
```bash
npm install d3
```
JavaScript library for manipulating documents based on data.

### Nivo
```bash
npm install @nivo/core @nivo/bar @nivo/line
```
Provides a rich set of data visualization components built on top of D3.

## Icons

### React Icons
```bash
npm install react-icons
```
Include popular icons in your React projects easily with react-icons.

### Font Awesome
```bash
npm install @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/react-fontawesome
```
The iconic font and CSS toolkit.

### Lucide React
```bash
npm install lucide-react
```
Beautiful & consistent icon toolkit made by the community.

### Heroicons
```bash
npm install @heroicons/react
```
Beautiful hand-crafted SVG icons by the makers of Tailwind CSS.

## Date & Time

### Moment.js (Legacy)
```bash
npm install moment
```
Parse, validate, manipulate, and display dates and times in JavaScript.
Note: Consider using date-fns or Day.js for new projects.

### Day.js
```bash
npm install dayjs
```
Fast 2kB alternative to Moment.js with the same modern API.

### React Datepicker
```bash
npm install react-datepicker
```
A simple and reusable datepicker component for React.

### React Day Picker
```bash
npm install react-day-picker date-fns
```
Lightweight date picker component for React.

## Drag & Drop

### React DnD
```bash
npm install react-dnd react-dnd-html5-backend
```
A set of React utilities to help you build complex drag and drop interfaces.

### dnd-kit
```bash
npm install @dnd-kit/core @dnd-kit/sortable
```
A modern, lightweight, performant drag & drop toolkit for React.

### React Beautiful DnD
```bash
npm install react-beautiful-dnd
```
Beautiful and accessible drag and drop for lists with React.

## Table & Grid

### TanStack Table (React Table)
```bash
npm install @tanstack/react-table
```
Headless UI for building powerful tables & datagrids.

### AG Grid
```bash
npm install ag-grid-react ag-grid-community
```
The best JavaScript data table for building enterprise applications.

### React Data Grid
```bash
npm install react-data-grid
```
Excel-like grid component built with React.

## Additional Recommendations

### Next.js
```bash
npx create-next-app@latest
```
The React Framework for production with server-side rendering and static site generation.

### Vite
```bash
npm create vite@latest
```
Next generation frontend tooling - incredibly fast build tool.

### TypeScript
```bash
npm install --save-dev typescript @types/react @types/react-dom
```
Typed superset of JavaScript that compiles to plain JavaScript.

## Contributing

Feel free to submit pull requests to add more useful packages or update existing ones.

## License

MIT