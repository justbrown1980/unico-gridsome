<template>
  <div>
    <Header />
      <slot/>
    <Footer />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>

import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Header,
    Footer
  }
}

</script>

<style>
:root {
  --clr-highlight: #eb1c25;
  --clr--highlight-light: #e73a42;
  --clr-dark-bg: rgba(0, 0, 0, 1);
  --clr-light-text: rgba(255, 255, 255, 1);
  --clr-dark-text: rgba(0, 0, 0, 1);
  --font-size--small: 60%;
  --font-size: 100%;
  --ratio: 1.333;
  --p: var(--font-size);
  --h4: calc(var(--font-size)*var(--ratio));
  --h3: calc(var(--h4)*var(--ratio));
  --h2: calc(var(--h3)*var(--ratio));
  --h1: calc(var(--h2)*var(--ratio));
  --media-small: 600px;
  --media-large: 100vw;
  --font-family: "Open Sans", Arial, Helvetica, sans-serif;
}





</style>
