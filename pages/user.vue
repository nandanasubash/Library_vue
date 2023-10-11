<!-- user.vue -->

<!-- 
<template>
   <div>
      <v-snackbar
      v-model="snackAlert">
      Order placed sucessfullly
      <template>
         <v-btn color="green"
         v-bind="attrs"
         @click="snackAlert=false"
         >
         Close
            
         </v-btn>
      </template>

      </v-snackbar>
   </div>
   
  </template>
  <script>
  export default{
   data:()=> {
      return{
         snackAlert:false,
      }
   }
  }
</script>
  
   -->
   <!-- <template>
      <v-card>
         <v-card-title>
            <span class="text-h5">Member</span>
         </v-card-title>
         <v-card-text>
            <v-row>
               <v-col
               cols="12"
               sm="6"
               md="4"
               >
            <v-text-field
            label="first name"
            v-model="firstname">

            </v-text-field>
            </v-col>
            </v-row>
         </v-card-text>
      </v-card>


      <div>
    <v-btn @click="handleButtonClick">Click me</v-btn>
  </div>



   </template>
  <script>







  
export default {
  data() {
    return {
      firstname: "",
    };
  },
  methods: {
    handleButtonClick() {
      // Handle the button click event here
      // You can add your custom logic or perform an action
      alert('Button clicked!');
    },
  },
};

</script> -->
<!-- <template>
   <div>
     <v-card>
       <v-card-title>
         <span class="text-h5" style="color: red;">Member</span>
         
       </v-card-title>
      </v-card>
      <v-divider></v-divider>
       <v-card>
       <v-row>
        
           
           <v-col cols="12" sm="6" md="4">
             <v-text-field label="First Name" v-model="firstname"></v-text-field></v-col>
       </v-row>
       <v-row>
             <v-col cols="12" sm="6" md="4">
             <v-text-field label="card number" v-model="cardnumber"></v-text-field>
           
           </v-col>
         </v-row>
        
       
     </v-card>
 
     <div>
       <v-btn @click="handleButtonClick">Click me</v-btn>
     </div>
   </div>
 </template>
 
 <script>
 export default {
   data() {
     return {
       firstname: "",
     };
   },
   methods: {
     handleButtonClick() {
       // Handle the button click event here
       // You can add your custom logic or perform an action
       alert('Button clicked!');
       this.fetchDataFromApi();
    },
    fetchDataFromApi() {
      // Replace 'your_api_endpoint' with your actual API endpoint
      axios.get('your_api_endpoint')
        .then((response) => {
          // Handle the API response data
          this.responseData = response.data;
        })
        .catch((error) => {
          console.error('Error fetching data from the API:', error);
        });
    },
  },
     }
   
 
 </script>
  -->
  <template>
   <div>
     <v-card>
       <v-card-title>
         <span class="text-h5" style="color: red;">Member</span>
       </v-card-title>
     </v-card>
     <v-divider></v-divider> <!-- Horizontal underline here -->
     <v-card>
       <v-row>
         <v-col cols="12" md="6">
           <v-text-field label="First Name" v-model="firstname"></v-text-field>
         </v-col>
         <v-col cols="12" md="6">
           <!-- First button -->
           <v-btn @click="handleButtonClick">Click me</v-btn>
         </v-col>
       </v-row>
       
       <v-row>
         <v-col cols="12" md="6">
           <v-text-field label="Card Number" v-model="cardnumber"></v-text-field>
         </v-col>
         <v-col cols="12" md="6">
           <!-- Second button -->
           <v-btn @click="handleSecondButtonClick">Second Button</v-btn>
         </v-col>
       </v-row>
       <v-divider></v-divider> <!-- Horizontal underline here -->
     </v-card>
   </div>
 </template>
 
 <script>
 export default {
   data() {
     return {
       firstname: "",
       cardnumber: "",
     };
   },
   methods: {
     handleButtonClick() {
       // Handle the first button click event here
       // You can add your custom logic or perform an action
       alert('First Button clicked!');
       // Add any other logic you need here
     },
     handleSecondButtonClick() {
       // Handle the second button click event here
       // You can add your custom logic or perform an action
       alert('Second Button clicked!');
       // Add any other logic you need here
     },
   },
 };
 </script>
 