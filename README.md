<h1>SCSS 7-1 Pattern Boilerplate</h1>

<p>Feel free to use this repository to seperate your css into individual folders</p>


<h4>Based on:</h4>

- https://github.com/HugoGiraudel/sass-boilerplate
- https://sass-guidelin.es/#the-7-1-pattern
- https://getbem.com/


Feel free to use your own node package to compile the sass file to css

Or else you could use the script currently in package.json


scss-7-to-1-folder-template/
├── abstracts/
│   ├── _variables.scss
│   └── _mixins.scss
│   ├── _functions.scss
│   └── index.scss
|
├── base/
│   ├── _base.scss
│   ├── _helper.scss
│   ├── _reset.scss
│   ├── _shame.scss
│   └── _typography.scss
|   └── index.scss
|
├── components/
│   ├── _buttons.scss
│   └── _cards.scss
|   └── index.scss
|
├── layout/
│   ├── _header.scss
│   ├── _footer.scss
│   └── _sidebar.scss
|   └── index.scss
|
├── pages/
│   ├── _home.scss
│   └── _about.scss
|   └── index.scss
|
├── themes/
│   ├── _theme.scss
|   └── index.scss
|
├── vendors/
│   ├── _bootstrap.scss
│   └── _jquery-ui.scss
│   └── _vuetify.scss
|   └── index.scss
|
└── main.scss