
1. no need input in webpack.config.js
Webpack expects the entry point to be ./src/index.js (auto)

The bundle will be placed into

./dist/main.js

2. no need include script bunlde in html
With webpack there’s no need to include your Javascript inside the HTML file: the bundle will be automatically injected into the page.