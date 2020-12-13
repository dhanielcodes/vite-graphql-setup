## Description

This repository contains a basic setup for [Tailwind](https://tailwindcss.com/), [Vue 3](https://v3.vuejs.org/) using [Vite](https://github.com/vitejs/vite) for bundling and also a basic structure for GraphQL support using [Vue Apollo](https://v4.apollo.vuejs.org/)

## Technologies

* [Tailwind](https://tailwindcss.com/)
* [Vue 3](https://v3.vuejs.org/)
* [Vite](https://github.com/vitejs/vite)
* [Vue Router](https://next.router.vuejs.org/)
* [Typescript](https://www.typescriptlang.org/)
* [Vue Apollo](https://v4.apollo.vuejs.org/)
* [Apollo](https://www.apollographql.com/docs/)
* [GraphQL Codegen](https://graphql-code-generator.com/)

## Quality Controls

* [Prettier](https://prettier.io/)
* [Commitlint](http://commitlint.js.org/)
* [Husky](https://typicode.github.io/husky) & [Lintstaged](https://github.com/okonet/lint-staged) (to help keep the quality workflow seamless)

## Folder Structure

### src/css

Applications stylesheets should be placed here.

### src/components

Reusable components used throughout the application should be situated here.

### src/hooks

You should place your application hooks in this folder with the advent of [Composition API](https://v3.vuejs.org/api/composition-api.html#composition-api) in Vue 3.

### src/pages

This folder contains your application pages.

### src/graphql

This folder contains everything regarding the graphql setup, queries, mutations and also files generated by [GraphQL Codegen](https://graphql-code-generator.com/) when you run `yarn codegen`

**src/graphql/queries**

Queries for each GraphQL types should be placed in here. Example, your GraphQL API has a **User** type and you need to write queries for that type, you should create a corresponding file **user.ts** and write your queries in the file/module.

**src/graphql/mutations**

The same convention that exists for GraphQL queries should be used for mutations also.

| :info: **/public/,/src/assets**     |
|:------------------------------------|
| You should read up on [Vite](https://github.com/vitejs/vite) to give you an overview of how this folders are used. |