<template>
    <div class="dv-menu-container menu-expanded">

        <div class="dv-menu-session-user">
            <Avatar />
            <div class="dv-user-data">
                <h3>Vinicius Malara</h3> 
                <a>Sair</a> 
            </div>
        </div>


        <md-list>
            <md-list-item>
                <md-icon>home</md-icon>
                <span class="md-list-item-text">Início</span>
            </md-list-item>

            <md-list-item>
                <md-icon>person</md-icon>
                <span class="md-list-item-text">Clientes</span>
            </md-list-item>

            <md-list-item>
                <md-icon>directions_car</md-icon>
                <span class="md-list-item-text">Veículos</span>
            </md-list-item>

            <md-list-item>
                <md-icon>navigation</md-icon>
                <span class="md-list-item-text">Triangulação</span>
            </md-list-item>


            <md-list-item>
                <md-icon>account_balance_wallet</md-icon>
                <span class="md-list-item-text">Financeiro</span>
            </md-list-item>

            <md-divider class="md-inset"></md-divider>

        </md-list>

    </div>
</template>

<script>

import Avatar from './subcomponents/Avatar';

export default {
    name: 'SideMenu',
    components: {
        Avatar
    }
}
</script>

<style>
    .dv-menu-container {
        position: fixed;
        top:0;
        left:0;
        height: 100%;
        box-shadow: 1px 0 0 0 #e0e0e0;
        background-color: #ffffff;
        z-index: 999;
    }

    .menu-collapsed {
        width: 80px;
    }

    .menu-expanded {
        width: 240px;
    }

    .dv-menu-session-user {
        display: flex;
        align-items: center;
        width: 100%;
    }
</style>