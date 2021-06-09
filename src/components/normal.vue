<template>
    <div class="template">
        <div class="d-flex flex-row justify-content-start">
            <div class="me-5">
                <div class="h6">&lt;Button /&gt;</div>
                <div class="btn btn-secondary shadow-sm">Default</div>
            </div>
            <div>
                <div class="h6">&:hover, &:focus</div>
                <div class="btn btn-secondary hover shadow-sm">Default</div>
            </div>
        </div>
        <br /><br />
        <outline />

        <br /><br />
        <Text />

        <br /><br />
        <disabledShadow />

        <br /><br />
        <disabled />

        <br /><br />
        <grocery />

        <br /><br />
        <sizes />

        <br /><br />
        <types />
    </div>
</template>

<script>
import outline from "./outline.vue";
import Text from "./text.vue";
import disabledShadow from "./disabledShadow.vue";
import Disabled from './disabled.vue';
import Grocery from './grocery.vue';
import Sizes from './sizes.vue';
import Types from './types.vue';

export default {
    name: "normal",
    components: { outline, Text, disabledShadow, Disabled, Grocery, Sizes, Types },
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

.hover {
    color: white;
    background: $gray-600;
}
</style>
