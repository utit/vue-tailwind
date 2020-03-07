<template>
  <div class="hello">
    <h1 class="mb-3">{{ msg }}</h1>
    <p class="mb-10">
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3 class="mb-3">Installed CLI Plugins</h3>
    <ul class="mb-10 flex justify-center">
      <li class="mr-5"><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li class="mr-5"><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-pwa" target="_blank" rel="noopener">pwa</a></li>
      <li class="mr-5"><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-router" target="_blank" rel="noopener">router</a></li>
      <li class="mr-5"><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-vuex" target="_blank" rel="noopener">vuex</a></li>
      <li class="mr-5"><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
      <li class="mr-5"><a href="https://tailwindcss.com/" target="_blank" rel="noopener">tailwind</a></li>
    </ul>
    <h3 class="mb-3">Essential Links</h3>
    <ul class="flex justify-center">
      <li class="mr-5"><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li class="mr-5"><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li class="mr-5"><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li class="mr-5"><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li class="mr-5"><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
