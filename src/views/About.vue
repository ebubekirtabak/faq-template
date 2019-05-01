<template>
  <div class="about">
    <h1>This is an about page</h1>
    <QuestionEditorComponent />
  </div>
</template>

<script>
import QuestionEditorComponent from '@/components/admin/QuestionEditorComponent.vue';

export default {
  name: 'About',
  components: {
    QuestionEditorComponent
  },
}
</script>