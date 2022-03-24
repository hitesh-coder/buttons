<template>
  <div class="d-flex flex-row justify-content-start">
    <div class="me-5">
      <div class="h6">&lt;Button variant="text" /&gt;</div>
      <div class="btn btn-outline-primary">Default</div>
    </div>
    <div>
      <div class="h6">&:hover, &:focus</div>
      <div class="btn btn-outline-primary hover">Defaults</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "text",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/bootstrap.scss";

.btn-outline-primary {
  color: $blue-500;
  border: none;

  &:hover {
    background: $blue-100;
    color: $blue-500;
  }
}

.hover {
  background: $blue-100;
}
</style>
