# Wails Template Quasar (TS)

## About

- This project is a template for [wails](https://wails.io/)
- It utilizes the [quasar](https://quasar.dev/) framework.
- To generate the frontend the following quasar options were used
  - Quasar V2 (Vue 3)
  - Typescript
  - Quasar App CLI with Vite
  - Composition API with <script setup>
  - Sass with SCSS syntax
  - ESLint + Pinia
  - Prettier ESLint preset


## Live Development

To run in live development mode, run `wails dev` in the project directory. In another terminal, go into the `frontend`
directory and run `npm run dev`. The frontend dev server will run on http://localhost:34115. Connect to this in your
browser and connect to your application.

> Note: The quasar dev server is manually configured to run on port :5173
> in order to properly work with wails.
> If this needs to be changed, please adjust the quasar.conf.js and wails.json with the new port

## Building

To build a redistributable, production mode package, use `wails build`.
