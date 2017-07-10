# \<list-item\>

ES6 Polymer 2 list item with a skeleton loader

- See the API docs for styling

## Usage
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-loader.js"></script>
    <link rel="import" href="list-item.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<list-item
  headline="<list-item>"
  text="ES6 Polymer 2 list item with a skeleton loader">
</list-item>

<style>
  list-item.dark{
    background: #303030;
    --text-color: #ffffff;
    --secondary-text-color: #bcbcbc;
    --loader-background: #111;
    --loader-color: #7CB342;
    color: var(--text-color);
  }
</style>

<list-item class="dark" loading>
  Slotted Content also works...
  Remove the loading attribute to reveal this text
</list-item>
```

## Install
```
bower i ryanburns23/list-item --S
```
