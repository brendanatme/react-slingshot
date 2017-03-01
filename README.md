<p>Based off the very magical [React SlingShot](https://github.com/coryhouse/react-slingshot) but with some customizations:

1. Removed Sass support
1. Added PostCSS support
1. Added CSS Modules support
1. more boilerplate files kept after removing demo

Current steps to get up and running:

1. download
1. run `npm run setup`
1. run `npm run remove-demo`
1. run `npm run start`
1. now the dev env will break. You'll need to edit some files:
1. add a working `/routes.js` file (that returns a <Route /> component)
1. edit `/index.js` to use a `styles.css` instead of `styles.scss`
1. Das it dawg
