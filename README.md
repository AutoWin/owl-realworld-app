# ![RealWorld Example App](logo.png)

[![Deploy on Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Coding-Dodo/owl-realworld-app)

> ### OWL (Odoo Web Library) codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld) spec and API.

### [Demo](https://owl-realworld.netlify.app)&nbsp;&nbsp;&nbsp;&nbsp;[RealWorld](https://github.com/gothinkster/realworld)

This codebase was created to demonstrate a fully fledged fullstack application built with OWL (Odoo Web Library) including CRUD operations, authentication, routing, pagination, and more.

We've gone to great lengths to adhere to the OWL (Odoo Web Library) community styleguides & best practices.

For more information on how to this works with other frontends/backends, head over to the [RealWorld](https://github.com/gothinkster/realworld) repo.

# How it works

Making use of:

- Basic Components composition
- OWL Store to get user state, authentication actions, getters, synchronisation with LocalStorage
- Using Axios for API Calls
- Routing
  - Dynamic routing with parameters
  - Routing guards for authenticated routes
- `willStart`, `willUpdateProps` examples
- events triggerring from child Components and custom event catching in Parent
- hooks `onWillStart`, `onWillUpdateProps` for dynamic component loading data at render.
- custom hooks to share logic with examples of:
  - `useEnv` to access router
  - `useGetters` to access store actions
  - `useComponent` to trigger event
- creating a custom `useApi` hook to demonstrate mixin/composition

# Getting started

Install dependencies:

```bash
npm install
```

Dev with livereload:

```bash
npm run dev
```

Production build

```bash
npm run build
```

Run tests

```bash
npm run test
```
