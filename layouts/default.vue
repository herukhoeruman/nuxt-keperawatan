<template>
  <div id="root" class="root mn--max hd--expanded">
    <section id="content" class="content">
      <nuxt />
      <AppFooter />
    </section>

    <AppSidebar />
    <AppHeader />
  </div>
</template>

<script>
import AppHeader from '~/components/layouts/AppHeader.vue'
import AppSidebar from '~/components/layouts/AppSidebar.vue'
import AppFooter from '~/components/layouts/AppFooter.vue'

export default {
  name: 'default',
  components: {
    AppHeader: AppHeader,
    AppSidebar: AppSidebar,
    AppFooter: AppFooter,
  },
}
</script>
