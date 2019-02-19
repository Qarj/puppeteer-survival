# puppeteer-survival
Puppeteer snippets

## Execute JavaScript
```
await scope.context.currentPage.evaluate(() => {document.querySelector('a[id="btnSubmit"]').click() })
```