<template>
    <div class="d-flex flex-row justify-content-space-start">
        <div class="me-5">
            <div class="h6">
                &lt;Button startIcon="local_grocery_store" /&gt;
            </div>
            <div class="btn btn-primary">
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    height="24px"
                    viewBox="0 0 24 24"
                    width="24px"
                    fill="#FFFFFF"
                >
                    <path d="M0 0h24v24H0V0z" fill="none" />
                    <path
                        d="M7 18c-1.1 0-1.99.9-1.99 2S5.9 22 7 22s2-.9 2-2-.9-2-2-2zm10 0c-1.1 0-1.99.9-1.99 2s.89 2 1.99 2 2-.9 2-2-.9-2-2-2zm-1.45-5c.75 0 1.41-.41 1.75-1.03l3.58-6.49c.37-.66-.11-1.48-.87-1.48H5.21l-.94-2H1v2h2l3.6 7.59-1.35 2.44C4.52 15.37 5.48 17 7 17h12v-2H7l1.1-2h7.45zM6.16 6h12.15l-2.76 5H8.53L6.16 6z"
                    />
                </svg>
                Default
            </div>
        </div>
        <div>
            <div class="h6">&lt;Button endIcon="local_grocery_store" /&gt;</div>
            <div class="btn btn-primary">
                Default
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    height="24px"
                    viewBox="0 0 24 24"
                    width="24px"
                    fill="#FFFFFF"
                >
                    <path d="M0 0h24v24H0V0z" fill="none" />
                    <path
                        d="M7 18c-1.1 0-1.99.9-1.99 2S5.9 22 7 22s2-.9 2-2-.9-2-2-2zm10 0c-1.1 0-1.99.9-1.99 2s.89 2 1.99 2 2-.9 2-2-.9-2-2-2zm-1.45-5c.75 0 1.41-.41 1.75-1.03l3.58-6.49c.37-.66-.11-1.48-.87-1.48H5.21l-.94-2H1v2h2l3.6 7.59-1.35 2.44C4.52 15.37 5.48 17 7 17h12v-2H7l1.1-2h7.45zM6.16 6h12.15l-2.76 5H8.53L6.16 6z"
                    />
                </svg>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "grocery",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/bootstrap.scss";
</style>
