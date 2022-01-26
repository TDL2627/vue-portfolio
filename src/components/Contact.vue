<template>
<div id="six">
 <h1 class="heading">Contact</h1>
  <div class="container">
        <div class="row">
          <div class="col-lg-6" data-aos="fade-right">
            <!-- the form -->
            <form action="https://formspree.io/f/mleavgwr" method="POST" target="_blank">
              <h4 class="contact-head cnthead">Contact me:</h4>
              <br>
              <div class="col-lg-6" style="display: flex;"> <input name="fname"
                  style="width:100%; margin-left: 2px; margin:20px; border-radius: 20px; border: none; height:40px; padding: 10px; "
                  type="text" placeholder="Name" required> <input name="email"
                  style="width:100%; margin:20px; border-radius: 20px; border: none; height:40px; padding: 10px; "
                  type="email" placeholder="Email" required> </div>

              <div class="col-lg-6 areatxt"> <textarea name="messages" id="areatxt" cols="30" rows="10"
                  placeholder="Type your message" required></textarea> </div>
              <div class="col-lg-6"> <button class="send-but buit" type="submit">Send</button>
                <button  class="reset-but buit" type="reset" value="Reset">Reset</button>
              </div>
            </form>
          </div>
          <div class="col-lg-6" data-aos="fade-left">
            <br>
            <h4 class="cnthead" >Address</h4>
            <br>
            <p class="contact-info1">42 Bongo Cresent</p>
            <p class="contact-info1">Silvertown</p>
            <p class="contact-info1">Athlone</p>
            <p class="contact-info1">Cape Town</p>
            <p class="contact-info1">7764</p>
            <br>
            <p class="contact-info1"><img src="https://img.icons8.com/material-outlined/24/000000/phone.png" /> 066 040
              0809</p>
            <p class="contact-info1"><img
                src="https://img.icons8.com/ios-filled/30/000000/email-open.png" />ashleykannemyer2@gmail.com</p>
            <br>
            
          </div>
         
        </div>

      </div>
</div>
 
</template>

<script>
export default {

}
</script>

<style scoped>
#six{
  background-color: rgb(59, 59, 59);
  height: 100vh;
}
.buit{
  background-color: black;
  color: white;
 border-radius: 25px;
 padding: 10px;
 margin: 10px;
 border: none;
}
.buit:hover{
  background-color: red;
  color: white;
 border-radius: 25px;
}

h1,h4,p{
  color: white;
}
</style>