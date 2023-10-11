<!-- bookreq.vue -->


<template>
    <div>
        <div class = "page-background">
      <v-row>
        <v-col cols="6">
          <v-card>
            <v-card-title>Title</v-card-title>
            <v-card-text>Card content goes here.</v-card-text>
            <!-- Use v-card-actions to align buttons to the right -->
            <v-card-actions class="text-right">
              <v-btn>View</v-btn>
              <v-btn>Cancel</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
  
        <v-col cols="6">
          
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
  