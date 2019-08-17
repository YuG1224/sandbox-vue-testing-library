<template>
  <div>
    <p>Times clicked: {{ count }}</p>
    <button @click="increment">increment</button>
    <button @click="decrement">decrement</button>
  </div>
</template>

<script>
export default {
  name: "Counter",
  data: () => ({
    count: 0
  }),
  methods: {
    increment() {
      this.count++;
    },
    decrement() {
      this.count--;
    }
  }
};
</script>

