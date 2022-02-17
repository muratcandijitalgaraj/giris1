<template>
  <datepicker class="picker"></datepicker>
</template>

<script>
document.body.innerHTML = document.body.innerHTML.replace(/lol/g, "Seç");

import Datepicker from "vuejs3-datepicker";

export default {
  // ...
  components: {
    Datepicker,
  },
  // ...
};
</script>

<style>
.picker {
  width: 300px;
  height: auto;
}
</style>
