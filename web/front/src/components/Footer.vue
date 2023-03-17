<template>
  <v-footer padless color="indigo darken-2">
    <v-row justify="center" no-gutters>
      <v-col class="py-4 text-center white--text" cols="12">{{ new Date().getFullYear() }} - Cornfield</v-col>

    </v-row>
  </v-footer>
</template>

<script>
export default {
  data() {
    return {
      icp_record: ''
    }
  },
  mounted() {
    this.$root.$on('msg', (msg) => {
      this.icp_record = msg
    })
  }
}
</script>

<style>
</style>