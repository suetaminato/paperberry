<template>
  <div class="text-xs-center">
    <v-menu
      bottom
      origin="center center"
      transition="scale-transition"
    >
        <v-btn
          :key="i"
          v-for="(page, i) in pages"
          slot="activator"
          color="primary"
          dark
        >
          {{ page.title }}
        </v-btn>


    </v-menu>
  </div>
</template>

<script>
  export default {
    data(){
      return{
        pages: [
          { title: 'HOME', to: '/' },
          { title: 'ONDE ENCONTRAR', to: '/' },
          { title: 'FREE!', to: '/' },
          { title: 'SOBRE NÓS', to: '/' },
          { title: 'CONTATO', to: '/' }
        ],
        items: [
        { icon: 'apps', title: 'Welcome', to: '/' },
        { icon: 'bubble_chart', title: 'Inspire', to: '/inspire' }
      ],
      }
    }
  }
</script>


<style>
</style>
