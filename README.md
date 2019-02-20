# puppeteer-survival https://www.npmjs.com/package/puppeteer

API link on: https://github.com/GoogleChrome/puppeteer#readme

## Execute JavaScript
```
await scope.context.currentPage.evaluate(() => {document.querySelector('a[id="btnSubmit"]').click() })
```