<template>
  <v-layout align-center justify-center fill-height>
    <v-flex xs12>
      <v-layout row wrap>
        <v-flex xs12 mb-5>
          <h1
            class="text-xs-center text-uppercase font-weight-black"
            :class="[
              { 'display-2': $vuetify.breakpoint.mdAndUp },
              { 'display-1': $vuetify.breakpoint.smOnly }
            ]"
          >
            <span style="color: #d21414">
              <i class="fas fa-circle logo"></i>
              Access denied
            </span>
            
          </h1>
           </v-layout>
    </v-flex>
  </v-layout>
</template>



<style scoped>
.v-messages {
  color: #eee !important;
}

.logo {
  animation: fade-in-out 2s ease-in-out infinite;
}

@keyframes fade-in-out {
  0% {
    opacity: 1;
  }
  10% {
    opacity: 1;
  }

  50% {
    opacity: 0;
  }

  90% {
    opacity: 1;
  }
}
</style>
