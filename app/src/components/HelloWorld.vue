<template>
  <div class="hello">
    <h1>{{ msg }}</h1>


    <button v-on:click="showAlertPopup('Oath of Gippocrat')">Show alert popup!</button>
    <p>
      For more info on how Buddy can help you launch killer apps, {{test}}<br>
      check out the
      <a href="http://buddy.works" target="_blank" rel="noopener">Buddy homepage</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://buddy.works/pricing" target="_blank" rel="noopener">Pricing</a></li>
      <li><a href="https://buddy.works/knowledge" target="_blank" rel="noopener">Docs</a></li>
      <li><a href="https://buddy.works/help" target="_blank" rel="noopener">Support</a></li>
      <li><a href="https://app.buddy.works/sign-up" target="_blank" rel="noopener">Free Trial</a></li>
      <li><a href="https://buddy.works/blog" target="_blank" rel="noopener">Blog</a></li>
    </ul>
    <h3>Social Media</h3>
    <ul>
      <li><a href="https://www.facebook.com/gitbuddy" target="_blank" rel="noopener">Facebook</a></li>
      <li><a href="https://twitter.com/buddygit" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://www.linkedin.com/company/10293199" target="_blank" rel="noopener">LinkedIn</a></li>
      <li><a href="#" target="_blank" rel="noopener">Email</a></li>
      <li><a href="https://github.com/buddy-works" target="_blank" rel="noopener">GitHub</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      test: 'TEST_DATA'
    }
  },

  methods: {
    showAlertPopup(str) {
      alert(str);
    },
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: #42b983;
}
</style>