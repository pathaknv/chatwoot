<template>
  <span class="message-text__wrap">
    <span v-html="message" class="message-text"></span>
    <span class="time">{{readableTime}}</span>
  </span>
</template>

<script>
export default {
  props: [
    'message',
    'readableTime',
  ],
};
</script>
