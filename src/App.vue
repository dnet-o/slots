<template>
  <AppForm>
    <div class="help">
      <p>This is some help text.</p>
    </div>
    <div class="fields">
      <input type="text" placeholder="email">
      <input type="text" placeholder="username">
      <input type="password" placeholder="password">
    </div>
    <div class="buttons">
      <button type="submit">Submit</button>
    </div>
  </AppForm>
  <AppForm />
</template>

<script>
import AppForm from './components/Form.vue'

export default {
  name: 'App',
  components: {
    AppForm,
  }
}
</script>
