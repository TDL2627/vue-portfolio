<template>
<div id="pcnav">

  <ul class="nav justify-content-center" >
  <li class="nav-item">
    <a class="nav-link active" aria-current="page" href="#">Active</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Link</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Link</a>
  </li>
  <li class="nav-item">
    <a class="nav-link disabled">Disabled</a>
  </li>
</ul>
</div>


<div id="mobnav">
<nav class="navbar navbar-light bg-dark fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" style="color:white;" href="#">Portfolio</a>
    <button style="background-color:white;" class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Offcanvas</h5>
        <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#one">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#two">Experience</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#three">Skills</a>
          </li>
           <li class="nav-item">
            <a class="nav-link" href="#four">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#five">Testimonials</a>
          </li>
           <li class="nav-item">
            <a class="nav-link" href="#six">Contact</a>
          </li>
        </ul>
       
      </div>
    </div>
  </div>
</nav>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
h1{
    color: aqua;
}
#mobnav{
  display: none;
}
#pcnav{
 position: fixed;
 width: 100%;
 z-index: 999;
 background-color: black;
}

@media screen and (max-width: 600px) {
  #mobnav {
    display: initial;
  }
  #pcnav{
    display: none;
  }
}
</style>