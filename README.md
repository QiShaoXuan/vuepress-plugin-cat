# vuepress-plugin-cat

## How to use

1. install `npm i vuepress-plugin-cat -S`

2. import in .vue file

```html
<template>
  <div class="home">
    <cat/>
  </div>
</template>

<script>
import Cat from "vuepress-plugin-cat/cat"
export default {
  name: "home",
  components: {
    Cat
  }
};
</script>
```

## Tip

- This plugin supports `vuepress 1.x`
- This plugin will randomly change the white cat or black cat when router path change.

## Demo

- https://qishaoxuan.github.io/css_tricks/
