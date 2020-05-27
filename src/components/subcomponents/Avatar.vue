<template>
    <div>
        <div class="div-avatar-container">
            <img class="dv-avatar" src="https://steamcdn-a.akamaihd.net/steamcommunity/public/images/avatars/88/88d81cd204c7d8ae016dd8fb844f511190f242d0_full.jpg" />
        </div>
    </div>
</template>

<script>
export default {
    name: "Avatar"
}
</script>

<style>
    .dv-avatar {
        border-radius: 50%;
    }

    .div-avatar-container {
        border: 4px #0065ff solid ;
        width: 70px;
        height: 70px;
        padding: 3px;
        border-radius: 50%;
    }
    

</style>