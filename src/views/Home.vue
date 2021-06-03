<template>
  <div id="home">
    <!-- <v-container>
      <h1>home</h1>
      <p class="purple lighten-4 white--text text--darken-10">
        fid trainning home page
      </p>
      <p class="text-uppercase">Codemobiles 1234</p>
      <p class="display-4">Codemobiles 1234</p>
      <p class="title font-weight-thin">fidtest</p>

      <v-btn medium depressed class="primary yellow--text mr-5">RUN</v-btn>
      <v-btn medium depressed class="primary yellow--text mr-5">RUN</v-btn>
      <v-btn fab depressed class="primary yellow--text mr-5">RUN</v-btn>
      <v-btn outlined color="pink" class="mr-5">RUN</v-btn>
      <v-btn outlined color="pink" class="mr-5"
        >EMAIL <v-icon>email</v-icon>
      </v-btn>
      <v-btn outlined color="pink" class="mr-5"
        ><span>EMAIL</span> <v-icon> mdi-arrow-left</v-icon>
      </v-btn>
      <v-btn medium class="primary">
        <v-icon left>favorite</v-icon>
        <span>Love you</span>
      </v-btn>

      <v-container>
        <v-btn class="hidden-md-and-down" color="success"
          >only show when sm</v-btn
        >
      </v-container>
    </v-container> -->

    <!-- Grid System -->
    <v-container fluid>
      <v-row no-gutters>
        <v-col cols="6" md="4">
          <v-btn outlined block color="success" @click="alert('Block1')"
            >Block 1</v-btn
          >
        </v-col>
        <v-col cols="6" md="4">
          <v-btn outlined block color="success">Block 2</v-btn>
        </v-col>
        <v-col cols="12" sm="12" md="4">
          <v-btn outlined block color="success">Block 3</v-btn>
        </v-col>
      </v-row>

      <!-- flex demo -->
      <v-row no-gutters class="justify-center align-content-center" style="height:200px;background-color:green;">
        <v-col cols="2">
          <v-btn block outlined color="success">Text</v-btn>
        </v-col>
        <v-col cols="2">
          <v-btn block outlined color="success">Text</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
  methods: {
    alert(msg) {
      alert(msg);
    },
  },
};
</script>
