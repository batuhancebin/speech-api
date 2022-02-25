<template>
    <p class="note_content">
      {{ noteItem.note }}
    </p>
</template>

<script>
export default {
  props: {
    noteItem: {
      type: Object,
      required: true
    }
  }
};
</script>
