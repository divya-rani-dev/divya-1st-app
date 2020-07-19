<template>
  <div class="text-center">
    <br>
    <br>
    <v-tooltip right>
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="primary"
          dark
          v-bind="attrs"
          v-on="on"
        >Left</v-btn>
      </template>
      <span>Left tooltip</span>
    </v-tooltip>
  </div>
</template>