<template>
  <div>これはコンポーネントから表示されています。</div>
  <p>{{ message }}</p>
</template>

<script>
export default {
  props: ["message"],
};
</script>
