<template>
  <h3>模版语法</h3>
  <p>{{ msg }}</p>
  <p>{{ hello }}</p>
  <p>{{ number + 1 }}</p>
</template>
<script>
export default {
  data() {
    return {
      msg: "神奇的魔法",
      hello: "hello world",
      number: 10,
    };
  },
};
</script>