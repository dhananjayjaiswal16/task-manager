<template>
  <button class="btn">{{ btnText }}</button>
</template>

<script>
export default {
  name: "Button",
  props: {
    btnText: String,
    btnColor: String,
  },
};
</script>