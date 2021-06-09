<template>
  <div class="d-flex flex-row justify-content-space-start">
    <div class="me-5">
      <div class="h6">&lt;Button size="sm" /&gt;</div>
      <div class="btn btn-primary btn-sm">Default</div>
    </div>
    <div class="me-5">
      <div class="h6">&lt;Button size="md" /&gt;</div>
      <div class="btn btn-primary btn-md">Default</div>
    </div>
    <div>
      <div class="h6">&lt;Button size="lg" /&gt;</div>
      <div class="btn btn-primary btn-lg">Default</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "sizes",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/bootstrap.scss";
</style>
