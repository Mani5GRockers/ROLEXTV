<template color="#445064">
  <v-container fluid class="text-xs-center">
    <v-layout justify-center :align-center="$vuetify.breakpoint.mdAndUp" fill-height>
      <v-flex xs12 md10>
        <h1 class="title my-5">About RX100</h1>

        <p>RX100 created by Mani5GRockers</p>
		 <p>explore & share and play media of files online</p>
        <p>
          RX100 Torrent open sources
        </p>
		<p>
         Visit the github repository from
         github
        </p>
        
        <p>Telegram user: @Mani5GRockers</p>
        <p>
          Backend is based on
          webtorrent project
        </p>
        <p>
          Video Player is based on
          Plyr.js
        </p>
        <p>
          RX100 Torrent is a
          vue.js project
        </p>
        <p>
          Movies from
         yts
        </p>
        <p>
          Subtitles from
        opensubtitles.org
        </p>
 <h2 class="title my-5">$$$ Thanks For Visiting $$$</h2>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: "about",
  created() {
    document.title = "RX100 - About";
  }
};
</script>
