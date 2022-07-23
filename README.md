# dusk-flex-theme-template

[Getting started](#getting-started) |
[New code submission](#new-code-submission) |
[License](#license)

## Getting started

Dusk Flex represents a HTML-first, Bootstrap 5 and jQuery/JavaScript-only-as-needed approach to theme development. It's Shopify's first source available theme with performance, flexibility, and [Online Store 2.0 features](https://www.shopify.com/partners/blog/shopify-online-store) built-in and acts as a reference for building Shopify themes.

- **Download Or Pull the code before start project**
- **Please use the hypen and prefix (WS--) for class name. EX: ws--heading-h1**
- **Please use the flickity for carousel or slider [Flickity](https://flickity.metafizzy.co/#getting-started)**
- **Please make sure every section is responsive**
- **Finaly, before push the code, please create an new branch with task name. EX: limon-task-1**

Say you're building a new theme off Dusk Flex template but you still want to be able to pull in the latest changes, you can add a remote `upstream` pointing to this Dusk Flex repository.

1. Navigate to your local theme folder.
2. Verify the list of remotes and validate that you have both an `origin` and `upstream`:

```sh
git remote -v
```

3. If you don't see an `upstream`, you can add one that points to Shopify's Dusk Flex repository:

```sh
git remote add upstream https://github.com/Limonrana/dusk-flex-theme-template.git
```

4. Pull in the latest Dawn changes into your repository:

```sh
git fetch upstream
git pull upstream main
```

## New code submission

Ensure that push the new code create an new branch with your task name. EX: limon-task-1

## License

Copyright (c) 2022-present Web Soft King LTD.
