# html5-simple-date-input-polyfill
Just include this simple script and IE (>=10) and Firefox will support `<input type="date">` without any dependencies, not even jQuery! 🎉

Support dynamically created inputs, so can be used in single page applications.

Support Angular 2+ (and possibly other libraries) bindings.

# Usage

#### webpack

In package.json, under dependencies, add
`"html5-simple-date-input-polyfill": "bdavis252/html5-simple-date-input-polyfill#1.2"`
(github claims semver syntax works here but I haven't tried it)

then run npm i.

Afterwards, add this to your styles.css
`@import '../node_modules/html5-simple-date-input-polyfill/html5-simple-date-input-polyfill.css';`
(there is an scss version too, see below)

And in polyfills.ts add this.
`import 'html5-simple-date-input-polyfill';`

#### Browser

`<link rel="stylesheet" href="html5-simple-date-input-polyfill.css" />`

`<script src="html5-simple-date-input-polyfill.min.js"></script>`

#### SCSS (optional)
`@import "../node_modules/html5-simple-date-input-polyfill/html5-simple-date-input-polyfill.scss";`
