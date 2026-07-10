<template>
  <q-page class="flex flex-center">
    <div class="column items-center">
      <div class = "video-background-container">
      <video autoplay muted loop playsinline class ="video-background">
        <source src = "~@/assets/vegeto_Niudacne.mp4" type ="video/mp4">
        Your browser doesn't support video
      </video>
      <div class = "video-overlay-content">
        <img
        alt="Hello Word ALLAH LOVE YOU"
        src="~@/assets/Quasar-logo-vertical.svg"
        style="width: 400px; height: 200px"
        />
      </div>
      </div>

      <q-btn
        class="q-mt-md"
        color="black"
        to="/second"
        label="Go to Second Page"
        no-caps
      />
    </div>
  </q-page>
</template>

<script setup>
//
</script>
