<template>
  <div class="note-container">
    <div class="note-editor">
      <NoteSelector />
      <p class="note-editor-info">Timestamp here...</p>
      <textarea class="note-editor-input">
	          First note...
	          Note text here...
	        </textarea
      >
    </div>
  </div>
</template>

<script>
import NoteSelector from "./NoteSelector.vue";
export default {
  components: {
    NoteSelector,
  },
};
</script>
