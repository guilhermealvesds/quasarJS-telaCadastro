<template>
  <div class="window-height window-width row justify-center items-center">
    <q-card
      class="my-card text-white"
      style="
        background: radial-gradient(circle, #5fc77b 0%, #2a702b 100%);
        height: 100vh;
        width: 100vw;
      "
    >
      <q-card-section>
        <q-input
          standout="bg-teal text-white"
          v-model="text"
          label="Nome"
        />
        <q-input
          standout="bg-teal text-white"
          v-model="text"
          label="Sobrenome"
        />
        <q-input
          standout="bg-teal text-white"
          v-model="text"
          label="Endereço"
        />
        <q-input
          standout="bg-teal text-white"
          v-model="text"
          label="Cidade"
        />
        <q-input
          standout="bg-teal text-white"
          v-model="text"
          label="Telefone"
        />
        <q-input
          standout="bg-teal text-white"
          v-model="text"
          label="Email"
        />
      </q-card-section>

      <q-card-section class="window-width row justify-center items-center">
          <q-btn outline style="color: #0e2b16; margin-left: 2px" label="Enviar" />
          <q-btn outline style="color: #0e2b16; margin-left: 3px" label="Cancelar" />
      </q-card-section>
    </q-card>
  </div>
</template>
