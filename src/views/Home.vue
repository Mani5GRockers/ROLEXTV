<template>
  <v-layout align-center justify-center fill-height>
   <span style="color: #d21414">
              <i class="fas fa-circle logo"></i>
              Access denied
            </span>
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
