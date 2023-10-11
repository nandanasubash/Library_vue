<!-- dashboard.vue -->

<template>
    <div>
      
       <div class = "page-background">
      
      
        <v-row class="px-8 pt-8">
          <v-col lg="3" cols="4">
            <v-card class="mx-auto" max-width="400">
                <v-card-text >
                    <v-img :src="require('@/assets/membership.jpeg')"></v-img>
            </v-card-text>
             
              <v-card-text>
                <v-card color="lime-darken-3">
                  <v-list-item three-line>
                    <v-list-item-content>
                    
                        <v-col cols="3">
                          <!-- <router-link to="/user" style="text-decoration:none"> -->
                          <v-btn fab color="lime-darken-3" elevation="0">
                            <!-- <v-icon color="white">fas fa-hand-holding fa-flip-vertical</v-icon> -->
                            <v-icon color="white">fa-user-plus</v-icon>
                          </v-btn>
                          <!-- </router-link> -->
                        </v-col>
                        <v-col>
                      <v-list-item-title class="headline ml-1 mt-3 white--text">
                        Membership
                      </v-list-item-title>
                     </v-col>
                    
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-card-text>
            </v-card>
          </v-col>
          
         
   
          <v-col lg="3" cols="4">
            <v-card class="mx-auto" max-width="400">
                <v-card-text >
                    <v-img :src="require('@/assets/green.jpeg')"></v-img>
            </v-card-text>
             
              <v-card-text>
                <v-card color="lime-darken-3">
                  <v-list-item three-line>
                    <v-list-item-content>
                     
                        <v-col cols="3">
                          <!-- <router-link to="/user" style="text-decoration:none"> -->
                          <v-btn fab color="lime-darken-3" elevation="0">
                            <!-- <v-icon color="white">fas fa-hand-holding fa-flip-vertical</v-icon> -->
                            <v-icon color="white">fa-user-plus</v-icon>
                          </v-btn>
                          <!-- </router-link> -->
                        </v-col>
                        <v-col>
                      <v-list-item-title class="headline ml-1 mt-3 white--text">
                        BOOK REQUEST
                      </v-list-item-title>
                     </v-col>
                     
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-card-text>
            </v-card>
          </v-col>
          
          
          <v-col lg="3" cols="4">
            <v-card class="mx-auto" max-width="400">
                <v-card-text >
                    <v-img :src="require('@/assets/violet.jpg')"></v-img>
            </v-card-text>
             
              <v-card-text>
                <v-card color="lime-darken-3">
                  <v-list-item three-line>
                    <v-list-item-content>
                    
                        <v-col cols="3">
                          <!-- <router-link to="/user" style="text-decoration:none"> -->
                          <v-btn fab color="lime-darken-3" elevation="0">
                            <!-- <v-icon color="white">fas fa-hand-holding fa-flip-vertical</v-icon> -->
                            <v-icon color="white">fa-user-plus</v-icon>
                          </v-btn>
                          <!-- </router-link> -->
                        </v-col>
                        <v-col>
                      <v-list-item-title class="headline ml-1 mt-3 white--text">
                        Book Return
                      </v-list-item-title>
                     </v-col>
                    
                    </v-list-item-content>
                  </v-list-item>
                </v-card>
              </v-card-text>
            </v-card>
          </v-col>
          
          
        </v-row>
     
      
    </div>
    </div>
    
 


  </template>
  <style>
  .page-background{
    background-image:url('assets\color.jpeg');
    background-size: cover;
    background-position: center;
  }
</style>
  