<template>
  <div class="dashboard">
    
    <h1 class="subheading grey--text">Dashboard</h1>
          <v-container class="my-5">
            
            <v-card flat class="pa-3">
                <v-layout row wrap>
                  <v-flex xs12 md6>
                    <div class="caption grey--text">Project Title</div>                    
                    <div>Create New Website</div>
                  </v-flex>
                  <v-flex xs6 sm4 md2>
                    <div class="caption grey--text">Person</div>
                    <dir> The Net Ninja</dir>
                  </v-flex>
                   <v-flex xs2 sm4 md2>
                    <div class="caption grey--text">Due By</div>
                    <dir>1st Jan 2019</dir>
                  </v-flex>
                   <v-flex xs2 sm4 md2>
                    <div class="caption grey--text">Status</div>
                    <dir>Ongoing</dir>
                  </v-flex>
                </v-layout>
            </v-card>
            

          </v-container>
  </div>
</template>

<script>
  
  export default {
        data:function(){
            return{
              projects:[
                
              ]
            }
        }
  }
</script>
