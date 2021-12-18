<template>
  <v-flex xs12 sm3 md3>
    <div class="caption grey--text">
      {{ $t('torrent.tracker') | titleCase }}
    </div>
    <div class="truncate mr-1">
      {{ torrent.tracker }}
    </div>
  </v-flex>
</template>
<script>
export default {
  name: 'Tracker',
  props: ['torrent']
}
</script>