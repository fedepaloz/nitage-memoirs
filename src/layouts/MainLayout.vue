<template>
  <q-layout>
    <q-page-container
      class="full-width row justify-center items-center content-start"
    >
      <div class="col-6">
        <h1>how do you feel today</h1>
        <q-select v-model="model" :options="options" label="Standard" />
      </div>
    </q-page-container>
  </q-layout>
</template>
