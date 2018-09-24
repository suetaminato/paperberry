<template>
  <v-layout>
    <v-flex text-xs-center>
      <img src="/v.png" alt="Vuetify.js" class="mb-5">
      <blockquote class="blockquote">
        &#8220;First, solve the problem. Then, write the code.&#8221;
        <footer>
          <small>
            <em class="boom">&mdash;John Johnson</em>
            <ico-heart />
          </small>
        </footer>
      </blockquote>
    </v-flex>
  </v-layout>
</template>

<script>
import IcoHeart from '~/components/Shared/IcoHeart.vue'
export default {
  components: {
    IcoHeart
  }
}
</script>


<style>
</style>