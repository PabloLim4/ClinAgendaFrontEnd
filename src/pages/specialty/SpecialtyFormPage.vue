<script setup lang="ts">
import { DefaultTemplate } from '@/template'
import { mdiCancel, mdiPlusCircle } from '@mdi/js'

</script>

<template>
  <default-template>
    <template #title>
      <h1>Specilaty Form</h1>
    </template>

    <template #default> Meu formulário de especialidade ficará aqui ;) </template>

    <template #action>
      <v-btn :prepend-icon="mdiCancel" :to="{ name: 'status-list' }"> Cancelar </v-btn>
    
    </template>
  </default-template>
</template>
