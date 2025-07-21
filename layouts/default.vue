<template>
  <v-app>
    <v-app-bar
      color="primary"
      dark
      app
    >
      <v-app-bar-title>ClinCorp</v-app-bar-title>
      
      <v-spacer />
      
      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <v-container fluid>
        <slot />
      </v-container>
    </v-main>

    <v-footer
      color="primary"
      dark
      app
    >
      <span>&copy; {{ new Date().getFullYear() }} ClinCorp - Sistema Clínico Corporativo</span>
    </v-footer>
  </v-app>
</template>
