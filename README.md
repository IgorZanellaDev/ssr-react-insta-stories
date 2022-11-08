<h1 style="margin: 0" align="center">📸 ssr-react-insta-stories</h1>
<p style="margin: 0" align="center">Fork of <a href="https://github.com/mohitk05/react-insta-stories">react-insta-stories</a></p>
<p align="center">A React component for Instagram like stories</p>

<div align="center"><a href="https://www.npmjs.com/package/react-insta-stories"><img alt="NPM" src="https://img.shields.io/npm/v/react-insta-stories.svg"></a>&nbsp;<a href="https://standardjs.com"><img alt="JavaScript Style Guide" src="https://img.shields.io/badge/code_style-standard-brightgreen.svg"></a>&nbsp;<a href="#backers"><img alt="Backers on Open Collective" src="https://opencollective.com/react-insta-stories/backers/badge.svg"></a>&nbsp;<a href="#sponsors"><img alt="Sponsors on Open Collective" src="https://opencollective.com/react-insta-stories/sponsors/badge.svg"></a></div>

## 🤷 Why
Why did I make this fork? When you go for SSR-only on Gatsby, Next, etc. you can't use packages with `window` or `document` from JavaScript.

## ❌ No keyboardNavigation
To make it work on SSR I removed `document` and `window` references, so I removed `keyboardNavigation` prop which used JavaScript `document` for event listeners on keyboard. 

## 🌍 Different WebPack style-loader
To make it work on SSR I change WebPack `style-loader` with `isomorphic-style-loader`, which is the style-loader to use if you use a component for SSR.

## ⚙️ Install

```bash
npm install --save ssr-react-insta-stories
```

## 📄 Docs

Official docs on official repository: https://github.com/mohitk05/react-insta-stories

## 🪳 Bugs

Report bugs and issues on official repository: https://github.com/mohitk05/react-insta-stories
