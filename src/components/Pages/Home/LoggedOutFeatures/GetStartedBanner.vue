<template>
  <div>
    <v-row>
      <v-col cols="12" md="6">
        <v-row>
          <h1 class="header-main">Welcome to schmickikibase.cloud</h1>
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>

<script>

export default {
  name: 'GetStartedBanner',
  components: {},
  data () {
    return {

    }
  }
}
</script>

<style scoped>
  h1.header-main{
    font-size: 64px;
    font-weight: 400;
    line-height: 72px;
  }

  h2.header-main{
    font-size: 32px;
    font-weight: 300;
    line-height: 72px;
  }

  h2.header-secondary{
    font-size: 20px;
    font-weight: 300;
    line-height: 35px;
  }
</style>
