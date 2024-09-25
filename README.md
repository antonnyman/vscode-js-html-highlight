<div align="center">
  <img src="img/512x512@2x.png" alt="worktop" width="230" />
</div>

# VSCode syntax highlighting for HTML JS/TS string template literals

This plugin allows for syntax highlighting when working with HTML in string template literals. Useful if you're working in a simple Node/Bun/Deno project and just want to inline some HTML.

```ts
// Similar syntax to Apollo GraphQL higlighting in VSCode

let htmlString := /* html */ `<!DOCTYPE html><head><title>Hello World!</title></head><body></body></html>`
```

**Note!** This plugin will _just_ highlight. It doesn't support formatting, LSP etc.

[Add extension to VSCode](https://marketplace.visualstudio.com/items?itemName=antonnyman.js-html-highlight)

Working with SQL in raw string literals using Go? Check out my other plugin (that this one is based on): [SQL Syntax Highlighter for Go](https://github.com/antonnyman/vscode-go-sql-highlight)
