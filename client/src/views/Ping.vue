<template>
  <div>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'ping',
  data() {
    return {
      msg: 'Hello!',
    };
  },
};
</script>
