<template>
  <footer>
  <v-footer color="primary lighten-1">
    <v-container>
    <v-row dense class="text-center" >
    <v-col cols="3"></v-col>
      <v-col cols="3" >
        <h5>Community</h5>
        <ul class="footer-list">
          <li><a target="_blank" rel="noopener noreferrer" href="https://www.mediawiki.org">MediaWiki</a></li>
          <li><a target="_blank" rel="noopener noreferrer" href="https://www.wikiba.se">Wikibase</a></li>
          <li><a target="_blank" rel="noopener noreferrer" href="https://www.wikidata.org">Wikidata</a></li>
          <li><a target="_blank" rel="noopener noreferrer" href="https://addshore.com">Addshore</a></li>
        </ul>
      </v-col>
      <v-col cols="3">
        <h5>Organization</h5>
        <ul class="footer-list">
          <li><a target="_blank" rel="noopener noreferrer" href="https://wikiba.se/about-us/">About</a></li>
          <li><a target="_blank" rel="noopener noreferrer" href="https://github.com/wbstack">Github</a></li>
          <li><router-link to="/privacy-policy">Privacy</router-link></li>
          <li><router-link to="/terms-of-use">Terms of Use</router-link></li>
          <li><a target="_blank" rel="noopener noreferrer" href="https://wikiba.se/contact/">Contact</a></li>
        </ul>
      </v-col>
      <v-col cols="3"></v-col>
    </v-row>
    </v-container>
  </v-footer>

  </footer>
</template>

<script>
export default {
  name: 'Foot'
}
</script>

<style scoped>
  ul.footer-list {
    list-style: none;
    padding-left: 0 !important;
  }

  ul.footer-list a,
  .white-footer-links a{
    color: white !important;
  }

</style>
