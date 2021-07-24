<template>
  <div id="app">
    <v-row>
      <v-col>
        <div class="ad-container">
          <Adsense
            data-ad-client="ca-pub-9315120082985629"
            data-ad-slot="1234567890"
            data-ad-format="auto"
            :data-full-width-responsive="true"
          >
          </Adsense>
        </div>
        
      </v-col>
    </v-row>
    <!-- <v-row>
      <v-col cols="3">
          <div style="height:100vh;background-color:rgb(140 124 124 / 13%)">
            <v-row style="padding-top:17px">
              <v-col cols="5">
                <v-icon>mdi-arrow-left</v-icon>
              </v-col >
              <v-col cols="7">
                <h3 style="color: rgb(169 147 147);">Color</h3>
              </v-col>
            </v-row>

            <v-divider style="margin-top:12px;"></v-divider>

            <v-row style="margin-top: 30px; margin-left: 17px;">
              <v-col cols="12">
                  <label for="">Icon Color:</label><br/>
                  <div class="inputField">
                    <input type="text" class="innerDiv" />
                  </div>
              </v-col>
            </v-row>

             <v-row style="margin-top: 30px; margin-left: 17px;">
              <v-col cols="12">
                  <label for="">Background Color:</label><br/>
                  <div class="inputField">
                    <input type="text" class="innerDiv" id="innerDiv" />
                  </div>
              </v-col>
            </v-row>

            <v-row style="margin-left: 17px;">
              <v-col cols="8">
                <label for="">Enable Gradient:</label><br/>
              </v-col>
              <v-col cols="3" >
                <ToggleButton/>
              </v-col>
            </v-row>

            <v-row>
              <v-col style="font-size: 15px; margin-left: 30px;" cols="10">
                Select two colors and create a gradual color shift between them
              </v-col>
            </v-row>
          </div>
      </v-col>
    </v-row> -->
  </div>
</template>

<script>
// import {ToggleButton} from 'vue-js-toggle-button';
export default ({
  data: () => ({
    isShareOption: false,
    switch1: false
  }),

  components:{
    // ToggleButton
  },

  methods:{
 
  }
})
</script>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');
*{
  color: rgb(169 147 147);
  font-family: 'Roboto', sans-serif;
  font-size: 20px;
}
.inputField{
  border:2px solid gainsboro;
    height: 43px;
    width: 19vw;
    margin-top: 12px;
    display: flex;
    align-items: center;
        border-radius: 5px;
}
.innerDiv{
    border: 1px solid black;
    height: 23px;
    width: 16vw;
    margin-top: 0px;
    margin-left: 22px;
    background-color: red;
}
#innerDiv{
   background-color: cornsilk;
}
</style>