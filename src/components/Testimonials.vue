<template>
<div id="five">
 <h1 class="heading">Testimonials</h1>  
  <div class="container">
        <div class="row">
          <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="accordion-item testi" data-aos="fade-left">
              <img class="people-pic" src="../assets/people/Godwin.jpeg" alt="godwin">
              <h2 class="accordion-header" id="headingOne">

                <button class="accordion-button collapsed buit" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
             <h5>Godwin</h5>
                </button>
              </h2>
              <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <h3 class="testi-title">Head of Curriculum and Learning</h3> "Based on the time that I have known Ashley, he will measure
                  up to high organisational expectations."
                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="accordion-item testi" data-aos="fade-right">
              <img class="people-pic" style="background-color:white;" src="../assets/people/jason-wandrag-nobg-2.png" alt="jason">
              <h2 class="accordion-header" id="heading3">

                <button class="accordion-button collapsed buit" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapse3" aria-expanded="false" aria-controls="collapse3">
                  <h5>Jason</h5>
                </button>
              </h2>
              <div id="collapse3" class="accordion-collapse collapse" aria-labelledby="heading3"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <h3 class="testi-title">Lecturer</h3> "Ashley brings a unique energy to my class. He enjoys participating in class
                  activities. It's always great to see him well-behaved in my class. I am excited about Ashley's
                  potential and I can't wait to see how he will grow in the future."
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="accordion-item testi" data-aos="fade-left">
              <img class="people-pic" src="../assets/people/Bulela1.jpg" alt="bulela">
              <h2 class="accordion-header" id="heading4">

                <button class="accordion-button collapsed buit" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapse4" aria-expanded="false" aria-controls="collapse4">
                  <h5>Bulela</h5>
                </button>
              </h2>
              <div id="collapse4" class="accordion-collapse collapse" aria-labelledby="heading4"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <h3 class="testi-title">Peer</h3> "He can work well with others."
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="accordion-item testi" data-aos="fade-right">
              <img class="people-pic" src="../assets/people/Jude3.jpg" alt="jude">
              <h2 class="accordion-header" id="heading5">

                <button class="accordion-button collapsed buit" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapse5" aria-expanded="false" aria-controls="collapse5">
                  <h5>Jude</h5>
                </button>
              </h2>
              <div id="collapse5" class="accordion-collapse collapse" aria-labelledby="heading5"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <h3 class="testi-title">Peer</h3> "He knows what he is doing."
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="accordion-item testi" data-aos="fade-left">
              <img class="people-pic" src="../assets/people/Kischa4.jpg" alt="Kischa">
              <h2 class="accordion-header" id="heading6">

                <button class="accordion-button collapsed buit" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapse6" aria-expanded="false" aria-controls="collapse6">
                  <h5>Kischa</h5>
                </button>
              </h2>
              <div id="collapse6" class="accordion-collapse collapse" aria-labelledby="heading6"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <h3 class="testi-title">Peer</h3> "He is very creative."
                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="accordion-item testi" data-aos="fade-right">
              <img class="people-pic" src="../assets/people/Seth3.jpg" alt="seth">
              <h2 class="accordion-header" id="heading8">


                <button class="accordion-button collapsed buit" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapse8" aria-expanded="false" aria-controls="collapse8">
                  <h5>Seth</h5>
                </button>
              </h2>
              <div id="collapse8" class="accordion-collapse collapse" aria-labelledby="heading8"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <h3 class="testi-title">Peer</h3> "He is always willing to help."
                </div>
              </div>
            </div>
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
#five{
  background-color: gray;
  height: max-content;
  text-align: center;
}
*{
  color: white;
  text-align: center !important;
}
.accordion-item{
  width: 300px;
  margin:20px;
  margin-right: 50px;
  border-radius: 25px !important;
  background: rgb(59, 59, 59) ;
  

backdrop-filter: blur( 4px )!important;
-webkit-backdrop-filter: blur( 4px )!important;

  
}
.accordion-button:not(.collapsed)::after {
   background-image: url("https://img.icons8.com/material-outlined/24/000000/down--v1.png") !important;
  transform: rotate(
-180deg);
}
.accordion-button::after {
  background-image: url("https://img.icons8.com/material-outlined/24/000000/down--v1.png") !important;
}

.accordion-button{
  color:black !important;
  box-shadow: none !important;
  background-color: red  !important;
}
.accordion-button:focus{
  color:black !important;
  box-shadow: none !important;
  background-color: red !important;
}
.accordion-button:active{
  color:black !important;
  box-shadow: none !important;
  background-color: red !important;
}
.accordion-button::after{
  color: black !important;
}
.accordion-button::before{
  border: 2px solid gray !important;
}

.accordion-body{
  color: white;
  font-family: sans-serif;
  height: 150px;
  overflow-y: scroll;
}

.people-pic{
  border-radius: 25px;
  height: 150px;
  width: 200px;
  border: 2px solid black;
  margin-top: 50px;
 
}
.testi{
  margin-left: 50px;
}
.testi-title{
  color: white !important;
  text-decoration: red underline;
}
h5{
  margin-left: 40%;
}
</style>