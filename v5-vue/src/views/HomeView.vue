<script setup>
import Comp from "@/components/Comp.vue";
</script>

<template>
  <main>
    <table border="3px">
      <tr>
        <td><Comp msg="INGATE" /></td>
        <td><Comp msg="VUE" /></td>
      </tr>

      <tr>
        <td><Comp msg="CLASS 2" /></td>
        <td><Comp msg="PROPS" /></td>
      </tr>
    </table>
  </main>
</template>
