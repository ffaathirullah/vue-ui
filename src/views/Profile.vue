<template>
  <div class="profile">
  <div class="container">
  <div class="row ">
    <div class="col d-flex justify-content-center">
      <div class="media text-start">
          <img src="./../assets/logo.png" alt="" class="user-pic mr-3">
          <div class="media-body">
              <h5>{{firstName + surName}}</h5>
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. A
          </p>
          </div>
      </div>
    </div>
  </div>
</div>
  </div>
</template>



<script>
import 'bootstrap/dist/css/bootstrap.min.css';
export default {
  name: 'Profile',
  data: function(){
     return {
         firstName: "Fachrul ",
         surName: "Faathirullah" 
         };
  },
}
</script>

<style scoped>
.user-pic {
    height: 120px;
    width: 120px;
    border-radius: 200%;
}
</style>
