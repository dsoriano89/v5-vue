<script setup>
import Comp from "@/components/Comp.vue";

const clickHandler = (value) => {
  console.log('clicked!', value);
};

const keyUpHandler = (e) => {
  console.log('text', e.target.value);
};
</script>

<template>
  <main>
    <table border="3px">
      <tr>
        <td><Comp msg="INGATE" @clicou="clickHandler" /></td>
        <td><Comp msg="VUE" /></td>
      </tr>

      <tr>
        <td><Comp msg="CLASS 2" /></td>
        <td><Comp msg="PROPS" /></td>
      </tr>
    </table>
    <button @click="clickHandler">Press the button</button>
    <input type="text" @keyup.enter="keyUpHandler" />
  </main>
</template>
