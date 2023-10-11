<template>
    <div>
      <Sidebar /> <!-- Include the Sidebar component -->
      <main>
        <Dashboard /> <!-- Include the Dashboard component -->
        <nuxt /> <!-- This is where your page content will be displayed -->
      </main>
    </div>
  </template>
  
  <script>
  import Sidebar from '@/pages/sidebar.vue'; // Import the Sidebar component
  import Dashboard from '@/pages/dashboard.vue'; // Import the Dashboard component
  
  export default {
    components: {
      Sidebar, // Register the Sidebar component for use in the template
      Dashboard, // Register the Dashboard component for use in the template
    },
  };
  </script>
  
  <style scoped>
  /* Add your layout-specific styles here */
  div {
    display: flex;
    flex-direction: row;
  }
  </style>
  