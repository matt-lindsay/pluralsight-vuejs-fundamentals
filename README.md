# pluralsight-vuejs-fundamentals
Pluralsight course https://app.pluralsight.com/library/courses/vuejs-fundamentals/table-of-contents

Vue.js App Structure
The Vue instance, usually only one per application.
nvm v8.11.2 for this course.

`$npm run serve` to run the app

Components are Vue instances.

v-bind shortened to :

v-on:click shortened to @click

v-once only evaluates once, when the page is loaded.

v-if is expensive to render as it adds and removes elements from the DOM.

v-show just hides things with a style attribute, which is more efficient.

never use v-if and v-for on the same element.

`<style scoped>` only relates to local styles.

`<style>` refers to global styles. Keep these to a minimum.

Some CSS elements are inherited, be careful of this.

```
<style scoped>
.content >>> .robot-name { // >>> is the deep selector, or /deep/.
  color: red;
  border: 2px solid blue;
}
```
Where a hypen exists in the CSS property (inline styling) encapsulate it in [], otherwise is isn't valid JavaScript.

`<div class="top part" :style="{[background-color]: '3px solid red'}">`

...or you can use camel case...

`<div class="top part" :style="{[backgroundColor]: '3px solid red'}">`

Learn more about life-cycle hooks, to for example fetch data from an API.

Mixins share functionality across componments.