<template>
  <div>
    <span className="user">
      <span className="name">{{ username }}</span>
      <span className="handle">{{ handle }}</span>
    </span>
  </div>
</template>

<script>
export default {
  props: {
    username: {
      type: String,
    },
    handle: {
      type: String,
    },
  },
};
</script>
