<template>
  <div>
    <v-row>
      <v-col cols="12">
        <v-card>
          <v-card-title>
            <v-icon left color="primary">mdi-hospital-building</v-icon>
            Bienvenido a ClinCorp
          </v-card-title>
          <v-card-text>
            Sistema de gestión clínica corporativa
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>

    <v-row class="mt-4">
      <v-col cols="12" md="4">
        <v-card color="primary" dark>
          <v-card-title>
            <v-icon left>mdi-account-multiple</v-icon>
            Pacientes
          </v-card-title>
          <v-card-text>
            Gestión de información de pacientes
          </v-card-text>
          <v-card-actions>
            <v-btn variant="text">Ver más</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>

      <v-col cols="12" md="4">
        <v-card color="success" dark>
          <v-card-title>
            <v-icon left>mdi-calendar-clock</v-icon>
            Citas
          </v-card-title>
          <v-card-text>
            Programación y seguimiento de citas
          </v-card-text>
          <v-card-actions>
            <v-btn variant="text">Ver más</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>

      <v-col cols="12" md="4">
        <v-card color="info" dark>
          <v-card-title>
            <v-icon left>mdi-chart-line</v-icon>
            Reportes
          </v-card-title>
          <v-card-text>
            Análisis y reportes estadísticos
          </v-card-text>
          <v-card-actions>
            <v-btn variant="text">Ver más</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>

    <v-row class="mt-4">
      <v-col cols="12">
        <v-alert
          type="info"
          variant="tonal"
        >
          <template #prepend>
            <v-icon>mdi-information</v-icon>
          </template>
          Vuetify 3 ha sido implementado correctamente en el proyecto ClinCorp
        </v-alert>
      </v-col>
    </v-row>
  </div>
</template>
