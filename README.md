# pluralsight-vuejs-fundamentals
Pluralsight course https://app.pluralsight.com/library/courses/vuejs-fundamentals/table-of-contents

Vue.js App Structure
The Vue instance, usually only one per application.
nvm v8.11.2 for this course.

Components are Vue instances.

v-bind shortened to :
v-on:click shortened to @click
v-once only evaluates once, when the page is loaded.
v-if is expensive to render as it adds and removes elements from the DOM.
v-show just hides things with a style attribute, which is more efficient.
never use v-if and v-for on the same element.