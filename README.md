# frontmatter-markdown-loader-vue-sample

- Sample Vue app to use [frontmatter-markdown-loader](https://github.com/hmsk/frontmatter-markdown-loader)

## Project setup

<npm-or-yarn>If works as a Vue component, this line should disappear. Try in your local!</npm-or-yarn>

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

## Here's code snipet which should not be compiled as Vue's template

Reported in [Issue #4](https://github.com/hmsk/frontmatter-markdown-loader/issues/4)

```html
<html lang="{{ app()->getLocale() }}">
  <body>
    {{ something }}
  </body>
</html>
```

In [Issue #6](https://github.com/hmsk/frontmatter-markdown-loader/issues/6), reported `inline code` is not working correctly.

## Asset transformation

![This image should be rendered on Vue](./src/assets/logo.png)
