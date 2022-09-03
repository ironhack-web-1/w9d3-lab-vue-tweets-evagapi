<template>
  <div>
    <img :src="imageSrc" className="profile" alt="profile" />
  </div>
</template>

<script>
export default {
  props: {
    imageSrc: {
      type: String,
    },
  },
};
</script>
