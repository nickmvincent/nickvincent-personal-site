<template>
  <div id="app">
    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style lang='sass'>
@import "node_modules/bulma/sass/utilities/initial-variables"

$family-serif: "Merriweather", "Georgia", serif

$primary: $blue
// Use the existing orange as the danger color
$danger: $orange
$family-primary: $family-serif
@import "node_modules/bulma/bulma"

</style>
