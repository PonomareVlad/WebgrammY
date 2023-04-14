# WebgrammY

> Override [grammY](https://grammy.dev) for web-only export.

This package re-exports the default `grammy` export from the `grammy/web` path.

This will help you use plugins in a web environment that mostly use the default `grammy` export.

#### How to configure package.json:

```json
{
  "dependencies": {
    "grammy": "npm:webgrammy@latest"
  },
  "overrides": {
    "grammy": {
      ".": "npm:webgrammy@latest",
      "grammy": "^1.15.3"
    }
  }
}
```

###### You can replace `^1.15.3` by any version of [grammY](https://npmjs.com/package/grammy?activeTab=versions) package.

Made with 💜 by [Vladislav Ponomarev](https://GitHub.com/PonomareVlad)
