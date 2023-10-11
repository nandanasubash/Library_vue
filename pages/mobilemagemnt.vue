<template>
    <div>
      
       <div class = "page-background">
      
      
        <v-row class="px-8 pt-8">
          <v-col lg="3" cols="4">
            <v-card class="mx-auto" max-width="400">
                <v-card-text >
                    <v-img :src="require('@/assets/lib.jpeg')"></v-img>
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
                            <div>
                               <v-btn color="primary">
                                <v-icon left>mdi-pencil</v-icon>
                                    View
                                </v-btn>
                             </div>


                          <!-- </router-link> -->
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
                    <v-img :src="require('@/assets/lib.jpeg')"></v-img>
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
                          <div>
                               <v-btn color="primary">
                                <v-icon left>mdi-pencil</v-icon>
                                    View
                                </v-btn>
                             </div>
                          <!-- </router-link> -->
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