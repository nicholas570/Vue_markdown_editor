<template>
  <div>{{ test }}</div>
</template>

<script>
export default {
  name: "Editor",
  props: {
    test: {
      type: String,
      required: true
    }
  }
};
</script>

<style></style>
