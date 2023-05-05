<template>
   <v-container>
      <v-row class="text-center">
         <v-col cols="12">            
            <img
               src="../assets/me.jpg"
               class="my-3"
               contain
               height="200"
               
            />
         </v-col>

         <v-col class="mb-4">
            <h1 class="text-h3 font-weight-bold mb-3y">My Profile</h1>
            <br/><br/>
        
                         
          
           <p style="color: black">Name: Nakamon Katekaew <br/><br/>
           Age: 21<br/><br/>
           Skills: Vue.js, SQL, C# <br/><br/>
           I am currently a student at the Thai-Nichi Internation College<br/><br/>

               
               
            </p>

            
         </v-col>
      </v-row>
   </v-container>
</template>

<script>
export default {
   name: 'HelloWorld',
   data: () => ({
      
   })

}


</script>

<style scoped>
p {
  font-size: 15px;
  font-weight: normal;
  }

</style>
