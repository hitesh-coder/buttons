<template>
  <div class="d-flex flex-row justify-content-start">
    <div class="me-5">
        <div class="h6">&lt;Button disabling /&gt;</div>
        <div class="btn btn-secondary disabled" aria-disabled="true">Disabled</div>
    </div>
    <div>
      <div class="h6">&lt;Button variant="text" disabling /&gt;</div>
      <div class="btn btn-outline-primary disabled" aria-disabled="true">Disabled</div>
    </div>
  </div>
</template>

<script>
export default {
    name: "disabled",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/bootstrap.scss";

.btn-secondary {
    background: $gray-300;
    outline: none;
    border: none;
    color: #3f3f3f;
    border-radius: 6px;
}

.btn-outline-primary{
    border: none;
}
</style>
