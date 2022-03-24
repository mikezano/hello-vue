<template>
  <div>
    {{ message }}
  </div>
  <Button />
</template>

<script>
import Button from './Button.vue'
export default {
  data() {
    return { message: "Hello Vue!" };
  },
  components:{
    Button
  }
};
</script>