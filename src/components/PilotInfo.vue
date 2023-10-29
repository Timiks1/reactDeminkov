<template>
  <div>
    <h3>{{ pilot.name }}</h3>
    <p>Height: {{ pilot.height }}</p>
    <p>Mass: {{ pilot.mass }}</p>
  </div>
</template>

<script>
export default {
  props: {
    pilot: Object, // Принимаем объект пилота
  },
};
</script>
