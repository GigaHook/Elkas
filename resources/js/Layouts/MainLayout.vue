<template>
  <v-app>

    <v-container style="min-width: 100vw;" class="pa-3">
      <v-app-bar style="height: 42px;" class="">
        <v-row>
          <v-col xl="8" md="9" sm="12" class="py-0">
            <v-btn>Главная</v-btn>
            <v-btn class="nav-item h-100">Дэшборд</v-btn>
            <v-btn class="nav-item">Дэшборд</v-btn>
            
          </v-col>
        </v-row>
      </v-app-bar>
    </v-container>

    <v-container style="min-width: 100vw;">
      <slot/>
    </v-container>

  </v-app>
</template>

<script setup>
import { Link } from '@inertiajs/vue3';





</script>

<style scoped>
.nav-item{
  width:100px;
  height: 42px;
  display: inline-block;
}

</style>