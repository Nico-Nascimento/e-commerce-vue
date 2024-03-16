<template>
    <v-app-bar height="80" flat>
        <v-app-bar-title>
            <h4>
                <strong class="color">E-</strong>COMMERCE
                <a href="https://vuetifyjs.com/en/" target="_blank"><img src="../../assets/logo.png" alt="logo vue" height="16" width="16"></a>
            </h4>
        </v-app-bar-title>
        <v-spacer></v-spacer>
        <v-btn>Opiniões sobre o site</v-btn>
        <v-btn prepend-icon="mdi mdi-email">
            <template v-slot:prepend>
                <v-icon color=""></v-icon>
            </template>
            nico.nascimento@gmail.com
        </v-btn>
        <v-btn prepend-icon="mdi mdi-cart">
            <template v-slot:prepend>
                <v-icon></v-icon>
            </template>
            Carrinho
        </v-btn>
    </v-app-bar>
    <v-app-bar height="80" flat color="white">
        <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
            <template v-slot:append>
                <v-icon></v-icon>
            </template>
            Todas as categorias
        </v-btn>
    </v-app-bar>
</template>

<script setup>

</script>

<style scoped>
.color {
    color: #1867C0;
}

</style>
