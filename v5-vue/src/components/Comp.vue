<script setup>
const props = defineProps({
  msg: String,
})

const emits = defineEmits (['clicou'])

const clickHandler = () => {
  emits('clicou', props.msg);
};

</script>

<template>
  <div>
    {{ props.msg }}

    <button @click="clickHandler">Press the button</button>
  </div>
</template>
