<template>

    <div class="dv-topbar-container">
        <div class="dv-logo-container">
            <h1>Dryve</h1>
        </div>
        <div>
            <input placeholder="Pesquisar" />
        </div>
    </div>

</template>

<script>
export default {
    name: "TopBar"
}
</script>

<style>
    .dv-topbar-container {
        height: 70px;
        box-shadow: 0 1px 0 0 #e0e0e0;
        background-color: #ffffff;
        position:fixed;
        width: 100%;
    }

    .dv-logo-container{
        margin-left: 90px;
    }
</style>