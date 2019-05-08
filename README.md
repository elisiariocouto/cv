## CV

Used [JSON Resume](https://jsonresume.org) with Elegant theme.

### Instructions

##### Install JSON Resume

`npm install resume-cli`

JSON Resume Themes Server appears to be down, workaround is to install the theme from NPM and move it to the base folder.

`npm install jsonresume-theme-elegant && mv node_modules/jsonresume-theme-elegant .`

##### Test Schema

`resume test`

##### Generate `index.html`

`resume --format html --theme elegant index.html`

Commit and push to `gh-pages` branch to host on GitHub Pages.
