<template>
<div id="one">
 <h1 class="heading">About me</h1>
    <div class="container" style="text-align: start;">
        <div class="row">
          <div class="col-lg-8">
            <h3> I am  </h3>
            <h3 id="name">Ashley Kannemeyer</h3>
            <h3>Full stack web developer </h3>
            <br>
            <p>I am a smart, hard working person and very eager to learn.I love solving
              problems, I am accustomed to traveling alot and speak multiple languages which allows me to mix and work
              well with others.I am very passionate about everything I do and take pride in what I do.</p>
            <p>I have 2 years of coding experience which I have acquired via self-learning, tertiary
              institutions and multiple work enviroments.I find coding very interesting and beleive it is my super
              power.</p>
            <p >I am well experienced in coding and able to work well with others.</p>
          </div>
          <div class="col-lg-4">
            <h5>Name : Ashley Kannemeyer </h5>
            <hr>
            <h5>Email: ashleykannemeyer2@gmail.com</h5>
           
            <hr>
            <h5>Age : 21</h5>
           
            <hr>
            <h5>From : Cape Town</h5>
          
            <br>
            <br>
            <a id="downloadcv" class="buit"  href="/CV/Ashley's Resume.pdf" download>Download CV</a>
            <br><br>
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
#one{
  background-color: black;
  height: 90vh;
}
h1,h3,p,h5{
  color: white;
}
#name{
  color: red;
  text-decoration: underline white;
}
.buit{
  background-color: red;
  border-radius: 25px;
  color:white;
  text-decoration: none;
  padding: 10px;
}

</style>