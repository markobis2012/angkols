<template>
  <v-container class="fill-height">
    <v-card
      class="mx-auto"
      max-width="400"
      elevation="10"
    >
      <v-img
        class="align-end text-white"
        height="200"
        src="@/images/klogo.png"
        max-height

        style = "background-color: #F53C14;"
      >
        <v-card-title style = "color:white;text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000;">Sales and Inventory System</v-card-title>
      </v-img>
  
      <v-card-subtitle class="pt-4">
        Login
      </v-card-subtitle>
  
      <v-card-text>
        <div><v-text-field label="Username:" variant="underlined"></v-text-field></div>
  
        <div><v-text-field label="Password:" variant="underlined"></v-text-field></div>

        <div><v-checkbox label="Forgot Password?" primary></v-checkbox> </div>
      </v-card-text>
  
      <v-card-actions>
        <v-btn color="orange">
          Log-In
        </v-btn>
  
        <v-btn color="orange">
          Register
        </v-btn>
      </v-card-actions>
    </v-card>
  </v-container>
</template>

<script setup>
  //
</script>
