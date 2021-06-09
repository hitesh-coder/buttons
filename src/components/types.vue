<template>
  <div class="d-flex flex-row justify-content-space-start">
    <div class="me-5">
      <div class="h6">&lt;Button color="default" /&gt;</div>
      <button type="button" class="btn default">Default</button>
    </div>
    <div class="me-5">
      <div class="h6">&lt;Button color="primary" /&gt;</div>
      <div type="button" class="btn btn-primary">Default</div>
    </div>
    <div class="me-5">
      <div class="h6">&lt;Button color="secondary" /&gt;</div>
      <div type="button" class="btn btn-secondary">Secondary</div>
    </div>
    <div>
      <div class="h6">&lt;Button color="danger" /&gt;</div>
      <div type="button" class="btn btn-danger">Danger</div>
    </div>
  </div>
</template>

<script>
export default {
    components: { },
  name: "types",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/bootstrap.scss";

*{
    white-space: nowrap;
}

.default{
    background: $gray-400;

    &:hover{
        background: $gray-600;
    }
}
</style>
