<template>
  <div class="row empty-state">
    <h3 class="title">{{title}}</h3>
    <p class="message">{{message}}</p>
    <slot></slot>
  </div>
</template>
<script>

export default {
  props: {
    title: String,
    message: String,
    buttonText: String,
  },
};
</script>
