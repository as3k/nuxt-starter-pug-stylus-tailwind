<template lang="pug">
  .container
    div
      Logo
      h1.title(class="text-6xl font-bold py-16") Pug + Stylus + Tailwind

      .links
        a(href="https://nuxtjs.org"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        ) Documentation

        a(href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        ) Github


</template>

<script>
export default {}
</script>

<style lang="stylus">
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container
  margin 0 auto
  min-height 100vh
  display flex
  justify-content center
  align-items center
  text-align center


.title
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif
  display block
  color #35495e
  letter-spacing 1px


.subtitle
  font-weight 300
  font-size 42px
  color #526488
  word-spacing 5px
  padding-bottom 15px


.links
  padding-top 15px

</style>
