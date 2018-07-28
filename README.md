#Repro

## Quick Start

1. Clone the repository with `git@github.com:joshuaalpuerto/rbp-repro-error-swallowed.git`
2. `yarn`
3. `yarn start`

I added an error under `app/containers/HomePage/actions.js`
```js
/*
 * Home Actions
 * ...
 */

shouldThrowError // <---line 20
```

This should throw an error on `console.log` but it doesn't.
