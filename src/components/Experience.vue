<template>
<div id="two">  <h1 class="heading">My Experience</h1>
 <section class="time-line-box">
            <div class="swiper-container text-center"> 
                <div class="swiper-wrapper">
                    <div class="swiper-slide">
                      <div class="timestamp"><span class="date">01/2013</span></div>
                      <div class="status"><span>Enrolled into high school.</span></div>
                    </div>
                    <div class="swiper-slide">
                      <div class="timestamp"><span class="date">11/2017</span></div>
                      <div class="status"><span>Matriculated + part time catering work.</span></div>
                    </div>
                    <div class="swiper-slide">
                      <div class="timestamp"><span class="date">01/2018</span></div>
                      <div class="status"><span>Become a full time general worker.</span></div>
                    </div>
                    <div class="swiper-slide">
                      <div class="timestamp"><span class="date">12/2019</span></div>
                      <div class="status"><span>Still doing general labour.</span></div>
                    </div>
                    <div class="swiper-slide">
                      <div class="timestamp"><span class="date">06/2020</span></div>
                      <div class="status"><span>Enrolled at CodeSpace.</span></div>
                    </div>
                    <div class="swiper-slide">
                      <div class="timestamp"><span class="date">01/2021</span></div>
                      <div class="status"><span>Uber Eats driver.</span></div>
                    </div>
                    <div class="swiper-slide">
                      <div class="timestamp"><span class="date">04/2021</span></div>
                      <div class="status"><span>Developed microapps for Ayoba.</span></div>
                    </div>
                    <div class="swiper-slide">
                      <div class="timestamp"><span class="date">09/2021</span></div>
                      <div class="status"><span>Enrolled at Life Choices</span></div>
                    </div>
                </div>
                <div class="swiper-pagination"> </div>
            </div>
       </section>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
#two{
  background-color: gray;
  height: 90vh;
}
*{
  color: white;
}
.time-line-box {
  margin-top:100px;
  height: 300px; 
  padding: 100px 0;
  width: 100%;
  background-color: black;
}

.time-line-box .timeline {
  list-style-type: none;
  display: flex;
  padding: 0;
  text-align: center;
}

.time-line-box .timestamp {
  margin: auto;
  margin-bottom: 5px;
  padding: 0px 4px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.time-line-box .status {
  padding: 0px 10px;
  display: flex;
  justify-content: center;
  border-top: 3px solid gray;
  position: relative;
  transition: all 200ms ease-in;
}
.time-line-box .status span {
  padding-top: 8px;
}
.time-line-box .status span:before {
  content: '';
  width: 12px;
  height: 12px;
  background-color: gray;
  border-radius: 12px;
  border: 2px solid red;
  position: absolute;
  left: 50%;
  top: 0%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  transition: all 200ms ease-in;
}

.swiper-container {
  width: 95%; 
  margin: auto;
  overflow-y: auto;
}
.swiper-wrapper{
  display: inline-flex;
  flex-direction: row;
  overflow-y:auto;
  justify-content: center;
}
.swiper-container::-webkit-scrollbar-track{
   background:#a8a8a8b6;
   
}
.swiper-container::-webkit-scrollbar{
  height: 10px;
}
.swiper-container::-webkit-scrollbar-thumb{
   background: #4F4F4F !important;
}
.swiper-slide {
  text-align: center;
  font-size: 12px;
  width: 200px;
  height: 100%;
  position: relative;
}
</style>