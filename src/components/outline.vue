<template>
  <div class="d-flex flex-row justify-content-start">
    <div class="me-5">
      <div class="h6">&lt;Button variant="outline" /&gt;</div>
      <div class="btn btn-outline-primary">Default</div>
    </div>
    <div>
      <div class="h6">&:hover, &:focus</div>
      <div class="btn btn-outline-primary hover">Default</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "outline",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/bootstrap.scss";

.btn-outline-primary {
  color: $blue-500;

  &:hover {
    background: $blue-100;
    color: $blue-500;
  }
}

.hover {
  background: $blue-100;
}
</style>
