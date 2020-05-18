# Jekyll & Tailwind CSS Boilerplate

A bare bones [Jekyll](https://jekyllrb.com/) site which comes preconfigured to use [Tailwind CSS](https://tailwindcss.com/) for styling.

## Features

- 🤍 Ships free of styling or theming. [Add a theme](https://jekyllrb.com/resources/) or [get started with Tailwind CSS](https://tailwindcss.com/docs/utility-first/).
- 📈 Ships Google Analytics and SEO ready
- 🍕 Dev mode: your Jekyll site is refreshed on file changes and all Tailwind CSS classes are available for use.
- 💻 Release mode: CSS is optimised by striping out unused classes and minifying the file.

---

## Install

- [Download Ruby](https://www.ruby-lang.org/en/downloads/)
- [Download NPM](https://www.npmjs.com/get-npm)
- Run `$ npm run setup` to setup the project.

---

## How to Use

### 🍕 Development

```$ npm run dev```

- Generates _all_ Tailwind CSS classes so you can develop without regenerating them.
- Runs the Jekyll watcher which regenerates the site when files are modified.
- [More detail here](/readme-css.md).

#### Dev Tools
- Consider using the VSCode extension [Tailwind CSS intelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) (Extension ID `bradlc.vscode-tailwindcss`).
- Consider installing [live-server](https://www.npmjs.com/package/live-server) to refresh the browser on file changes. Watch the `_site/` folder as follows: `$ live-server _site/`.

### 💻 Release

```$ npm run rel```

- Generates the minimum Tailwind CSS necessary to display your site in order to keep the file size tiny.
- Minifies the CSS to reduce the file size even more.
- Builds the jekyll site to the `_site` folder.
- [More detail here](/readme-css.md).

To deploy on [Netlify](https://www.netlify.com/) for example, use the following build settings:
- Build command: `npm run rel`
- Publish Directory: `_site`

---

Having trouble? Check out the [troubleshoot guide](readme-css.md#troubleshoot) or post an issue.