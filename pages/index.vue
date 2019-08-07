<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        Jenkins PoC
      </h1>
      <h2 class="subtitle">
        I am a vue + nuxt demo site built from CI. Version 1.0.1
      </h2>
      <div class="links">
        <a
          href="https://oopsidontgoanywhere.com"
          target="_blank"
          class="button--green"
        >
          Click me
        </a>
        <a
          href="https://gotyouagain.com"
          target="_blank"
          class="button--grey"
        >
          Or me
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
