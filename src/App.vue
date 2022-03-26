<template>
  <LayoutAsideMain>
    <template v-slot:sidebar>
      <nav>
        <ol>
          <li>ABC</li>
          <li>123</li>
          <li>(*&)</li>
        </ol>
      </nav>
    </template>
    <template v-slot:main>
      <h1>Zano</h1>
      <Button />
    </template>
  </LayoutAsideMain>
</template>

<script>
import Button from './Button.vue';
import LayoutAsideMain from './components/LayoutAsideMain.vue';
export default {
  data() {
    return { message: 'Hello Vue!' };
  },
  components: {
    Button,
    LayoutAsideMain,
  },
};
</script>
