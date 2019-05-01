<template>
  <CKEditorComponent />
</template>

<script>
import CKEditorComponent from '@/components/admin/CKEditorComponent.vue';
export default {
  name: 'QuestionEditorComponent',
  components: {
    CKEditorComponent
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
