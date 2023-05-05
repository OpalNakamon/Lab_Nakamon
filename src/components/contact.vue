<template>
  <div>
    <br /><br />
    <h1 class="text-h3 font-weight-bold mb-3y">My Contact</h1>
    <br /><br />


  <div class="text-box">
  <p >Email: {{ email }}</p>
  </div>
  <div class="text-box">
    <p1>Phone: {{ phone }}</p1>
</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      email: 'Opal.nkm@gmail.com',
      phone: '091-7355905'
    };
  }
};

</script>

<style>
h1 {
  font-size: 24px;
  font-weight: bold;
}

p {
  font-size: 16px;
  margin-bottom: 10px;
  color: black;
  
}

p1 {
  font-size: 16px;
  margin-bottom: 10px;
  color: black;
  
}

.text-box {
  border: 1px solid black; 
  border-radius: 5px; 
  padding: 10px; 
  margin: 10px; 
  background-color: #eee; 
  
}



</style>



