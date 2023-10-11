<template>
    <div>
      <v-navigation-drawer permanent color="blue" app>
        <v-list-item class="px-2 py-5"></v-list-item>
        <v-list-item-title class="text-capitalize" align="center"></v-list-item-title>
        <v-img src="https://thumbs.dreamstime.com/b/web-page-template-digital-library-banner-electronic-people-characters-vector-illustration-pass-online-courses-read-books-162679711.jpg"></v-img>
        <v-list-item class="px-2 py-5">
          <!-- <v-img :src="require('@/assets/membership.jpeg')"></v-img> -->
        </v-list-item>
  
        <v-list dense>
          <v-list-item
            v-for="item in items"
            :key="item.text"
            @click="navigateTo(item.route)"
            link
          >
            <v-list-item-icon>
              <v-icon>{{ item.icon }}</v-icon>
            </v-list-item-icon>
            <v-list-item-content color="white">
              <v-list-item-title>{{ item.text }}</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
    </div>
   
  </template>
  
  <script>
  // Import Axios if needed
  // import axios from 'axios';
  
  export default {
    data() {
      return {
        selectedItem: 0,
        library_address: "",
        items: [
          { icon: 'fas fa-home', text: 'Dashboard', route: '/dashboard' },
          { icon: 'fa-book', text: 'Bookreq', route: '/bookreq' },
          { icon: 'fa-book', text: 'User', route: '/user' },
          { icon: 'fa-book', text: 'Mobile Management', route: '/mobilemagemnt' },
          // Add more items as needed
        ]
      };
    },
    methods: {
      navigateTo(route) {
        this.$router.push(route);
      }
    }
  };
  </script>

