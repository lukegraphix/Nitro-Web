<template>
  <ds-card :header="$t('settings.languages.name')">
    <hc-empty
      icon="tasks"
      message="Comming Soon…"
    />
  </ds-card>
</template>

<script>
import HcEmpty from '~/components/Empty.vue'

export default {
  components: {
    HcEmpty
  }
}
</script>
