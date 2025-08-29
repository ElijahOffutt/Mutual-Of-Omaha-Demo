<template>
  <v-app>
    <v-navigation-drawer permanent left app absolute>
      <v-list>
        <v-list-item title="Item 1" />
        <v-list-item title="Item 2" />
        <v-list-item title="Item 3" />
        <v-list-item title="Item 4" />
        <v-list-item title="Item 5" />
      </v-list>
    </v-navigation-drawer>
    <v-container>
      <router-view />
    </v-container>
  </v-app>
</template>

<script lang="ts" setup>

interface Link {
  id: string;
  text: string;
  link: string;
}

let links: Link[] = [

]

</script>