<script setup>

</script>
<template>
    <div class="header">
        <div class="wrap">
            <div class="logo">
                <img src="../../public/logo.jpg" alt="logo">
            </div>
            <div class="text">
                <p>Jerry's Blog</p>
            </div>
        </div>
    </div>
</template>
<style scoped lang="scss">
.header {
    display: flex;
    width: 100%;
    justify-content: center;
    height: 100px;
    border-style: dashed;
}

.wrap {
    display: flex;
    align-items: center;
    width: 1200px;
}

.logo {
    img {
        width: 50px;
        height: 50px;
        margin-right: 100px;
    }
}

.text {
    font-size: large;
    font-weight: 500;
}
</style>
