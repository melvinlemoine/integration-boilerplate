# Integration boiler plate

Repository created for students who want to set up simple integration projects quickly.

➡ In this repository, all is ready, just `$ npm install` to install packages & watch SASS with `$ npm run watch`.

# Commands

_Before use the commands, don't forget to install the dependencies with `$ npm install`._

- `$ npm run watch` : compile the SASS on save.
- `$ npm run deploy` : compile the SASS to CSS properly _(more about this below)_.

# CSS render

To compile the SASS to CSS properly _(the `$ npm run watch` command only compile but do not autoprefix and clean)_, execute `$ npm run deploy`.
This will compile the SASS with :

- Autoprefixer : add automaticly prefixs to maximize compatibility with all browsers
- Clean CSS : Removed comments and minify the stylesheet

# Contribute

Just make pull request to improve this repository 😏
