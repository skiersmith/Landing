<template>
  <div>
    <div class="black-container">

      <div class="github">
        <a href="http://github.com/skiersmith" target="_blank">
          <img class="githubimg skill-image grow" src="../assets/GitHub-Mark.png" alt="github">
        </a>
      </div>
      <div class="spacer3"></div>
      <div class="white-container">
        <div>
          <div class="spacer3"></div>
          <h1>Hunter Smith</h1>
          <h4>Software Engineer</h4>
          <h5>Boise, Id</h5>
          <div class="spacer3"></div>
          <!-- <span class="glyphicon glyphicon-envelope" aria-hidden="true"> skiersmith21@gmail.com</span> -->
        </div>
        <div class="hidden-md-down">
          <img class="img-responsive meImg" src="../assets/IMG_2966-Edit.jpg">
        </div>
      </div>
   
      <div class="spacer2"></div>
      <!-- <div class="spacer2"></div> -->
      <div class="spacer2"></div>


      <!-- <div class="row">
        <div class="col-sm-4 col-sm-offset-2 grow email">
          <span class="glyphicon glyphicon-envelope" aria-hidden="true"> skiersmith21@gmail.com</span>
        </div> -->
        <div class="col-sm-4 col-sm-offset-2 github">
          <!-- <p>Git Hub</p> -->
          <!-- <a href="http://github.com/skiersmith" target="_blank">
            <img class="githubimg skill-image grow" src="https://image.flaticon.com/icons/png/512/25/25231.png" alt="github">
          </a> -->
        </div>
      </div>
      <div class="spacer"></div>
      <h1>Projects</h1>
      <div class="projBody">
        <div class="container">
          <div class="row">
            <a href="https://jht-vue-kanban.herokuapp.com/#/" target="_blank">
              <div class="col-sm-3 col-sm-offset-1  skills grow">
                <img class="projPhoto" src="../assets/photo.png" alt="placeholder">
                <h6 class="proj-title text-center">Kanban Board</h6>
              </div>
            </a>
            <a href="#">
              <div class="col-sm-3 col-sm-offset-1 skills grow">
                <img src="http://placehold.it//150x150" alt="placeholder">
                <h6 class="proj-title text-center">Project Title</h6>
              </div>
            </a>
            <a href="#">
              <div class="col-sm-3 col-sm-offset-1 skills grow">
                <img src="http://placehold.it//150x150" alt="placeholder">
                <h6 class="proj-title text-center">Project Title</h6>
              </div>
            </a>
            <a href="#">
              <div class="col-sm-3 col-sm-offset-1 skills grow">
                <img src="http://placehold.it//150x150" alt="placeholder">
                <h6 class="proj-title text-center">Project Title</h6>
              </div>
            </a>
            <a href="#">
              <div class="col-sm-3 col-sm-offset-1 skills grow">
                <img src="http://placehold.it//150x150" alt="placeholder">
                <h6 class="proj-title text-center">Project Title</h6>
              </div>
            </a>
            <a href="#">
              <div class="col-sm-3 col-sm-offset-1 skills grow">
                <img src="http://placehold.it//150x150" alt="placeholder">
                <h6 class="proj-title text-center">Project Title</h6>
              </div>
            </a>
          </div>
        </div>
      </div>

      <div class="spacer"></div>

      <div class="container box three h-center">
        <div class="row">
          <div class="col-sm-2">
            <img class="grow2 skill-image2" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Vue.js_Logo.svg/1000px-Vue.js_Logo.svg.png"
              alt="">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="https://www.w3.org/html/logo/downloads/HTML5_Logo_512.png" alt="html5 Logo">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="http://w3widgets.com/responsive-slider/img/css3.png" alt="css3 Logo">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="https://seeklogo.com/images/J/javascript-logo-E967E87D74-seeklogo.com.png" alt="js5 Logo">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="https://www.mysql.com/common/logos/logo-mysql-170x115.png" alt="MySql Logo">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="https://camo.githubusercontent.com/0617f4657fef12e8d16db45b8d73def73144b09f/68747470733a2f2f646576656c6f7065722e6665646f726170726f6a6563742e6f72672f7374617469632f6c6f676f2f6373686172702e706e67"
              alt="">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="https://seeklogo.com/images/N/nodejs-logo-FBE122E377-seeklogo.com.png" alt="">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="https://logoepscdnphoto.b-cdn.net/wp-content/uploads/2016/12/bootstrap-logo.png" alt="Adobe PS Logo">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="data:image/jpeg;base64,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"
              alt="Adobe PS Logo">
          </div>
          <div class="col-sm-2">
            <img class="grow skill-image" src="data:image/png;base64,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"
              alt="Adobe PS Logo">
          </div>
        </div>
      </div>

      <div class="spacer"></div>
      <div class="landFoot container">

      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: 'Home',
    data() {
      return {

      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1,
  h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }

  .grow {
    transition: all .2s ease-in-out;
  }

  .grow:hover {
    transform: scale(1.1);
  }

  .grow2 {
    transition: all .2s ease-in-out;
  }

  .grow2:hover {
    transform: scale(1.6);
  }

  .skills {
    height: 20rem;
  }

  .landHead {
    margin: 4rem;
    height: 50vh;
    /* background-color: #9fc7b557; */
    width: 100vw;
  }

  .skill-image {
    height: 100px;
    margin: 1rem;
    transform: scale(0.9)
  }

  .skill-image2 {
    height: 100px;
    margin: 1rem;
    transform: scale(1.4)
  }

  .spacer {
    height: 20rem;
  }

  .spacer3 {
    height: 12rem;
  }

  .spacer2 {
    height: 30rem;
  }

  .projPhoto {
    width: 250px;
  }

  .landFoot {
    height: 20vh;
    background-color: rgba(119, 136, 153, 0.479);
    width: 100vw;

  }

  .projBody {
    /* background-color: rgb(177, 71, 71); */
    width: 100vw;
  }

  /* always present */

  .expand-transition {
    transition: all .3s ease;
    height: 30px;
    padding: 10px;
    background-color: #eee;
    overflow: hidden;
  }

  /* .expand-enter defines the starting state for entering */

  /* .expand-leave defines the ending state for leaving */

  .expand-enter,
  .expand-leave {
    height: 0;
    padding: 0 10px;
    opacity: 0;
  }

  .meImg {
    max-width:100%;
    height:auto;
    /* padding: 3rem; */
  }

  .text-container {
    display: inline;
    /* justify-content: space-around; */
    /* align-content: center; */
    /* background-color: rgba(255, 255, 255, 0.432); */
    position: relative;
    top: 15rem;
    left: 35vw;
    /* width: 100rem; */
    border-radius: 10px;
    

  }

  .black-container {
    /* background-color: black; */
    height: 100vh;
    background-image: url("../assets/rainbow.jpg");

    background-size: 2170px;
    /* justify-content: center; */
  }

  .white-container {
    color: rgb(70, 69, 69);
    width: 30vw;
    font-size:10vw;
    /* height: 15rem; */
   
    background-color: rgb(255, 252, 252);
    /* background-image: url("../assets/Artboard-3.png"); */
    display: flex;
    justify-content: flex-start;
    padding: 1rem;
    /* margin-left: 5px; */
    margin-top: 5px;
    position: sticky;
    top: 10px;
    /* bottom: 5px; */
  }

  .white-container:hover {
    background-color: rgba(255, 255, 255, 0.192);
  }
  .github{
    position: sticky;
    top: 0px;
    float: right;
    /* right: 5px; */
  }
</style>