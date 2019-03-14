## CV

Used [JSON Resume](https://jsonresume.org) with Elegant theme.

---

### Instructions

###### Install JSON Resume

`npm install resume-cli`

JSON Resume Themes Server appears to be down, workaround is to install the theme from NPM.

`npm install jsonresume-theme-elegant`

###### Test Schema

`resume test`

###### Start HTTP server to preview

`resume serve`

###### Generate `index.html`

`resume --format html --theme elegant`

Commit and push to `gh-pages` branch to host on GitHub Pages.

###### Generate PDF

`resume --format pdf --theme elegant`
