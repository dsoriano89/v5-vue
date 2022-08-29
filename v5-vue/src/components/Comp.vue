<script setup>
const text = "V5-Vue";
const props = defineProps({
  msg: String,
});
</script>

<template>
  <div>
    {{ text }}
    <br />
    {{ props.msg }}
  </div>
</template>
