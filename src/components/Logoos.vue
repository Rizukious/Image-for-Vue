<template>
    <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logo</h2>
        <div class="item-logos">
            <img class="logo" alt="Favicon logo" src="../assets/favicon.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/logo.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Mozila logo" src="../assets/Mozilla_Firefox.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Favicon logo" src="../assets/favicon.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Vue logo" src="../assets/logo.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Mozila logo" src="../assets/Mozilla_Firefox.png">
        </div>
    </div>
</template>

<script>
export default {
    // Mengexport file Logoos.vue ke App.vue
    name : 'Logoos'
}
</script>

<style scoped>
/* Memberi Style pada Logoos.vue */
.title-header {
    margin-bottom: 80px;
    text-align: left;
}
.logos-wrapper {
    width: 62%;
    overflow: hidden;
    margin: auto;
}
.item-logos {
    float: left;
    margin-right: 70px;
    margin-bottom: 70px;
    width: 150px;
    height: 150px;
}
.item-logos .logo {
    width: 150px;
    height: 150px;
}
</style>