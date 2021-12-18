<template>
  <v-flex xs12 sm5 md5>
    <div class="caption grey--text">
      {{ $t('torrent.save_path') | titleCase }}
    </div>
    <div class="truncate mr-4">
      {{ torrent.save_path }}
    </div>
  </v-flex>
</template>
<script>
export default {
  name: 'SavePath',
  props: ['torrent']
}
</script>