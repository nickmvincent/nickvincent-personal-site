<template>
  <div class="hello">
    <h2>{{ msg }}</h2>
    <h2>Essential Links</h2>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Current Work</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">CV (document)</a></li>
      <li><a href="https://gitter.im/vuejs/vue" target="_blank" rel="noopener">Project Portfolio</a></li>
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank" rel="noopener">Docs for This Template</a></li>
    </ul>
    <h2>External</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank" rel="noopener">LinkedIn</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank" rel="noopener">Github</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: "Hello! I'm Nick, but my offical paperwork calls me Nicholas. This site contains my work, contact information, and more.",
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495E;
}
</style>
