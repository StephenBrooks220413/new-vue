<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <br /> <br />
    <div class="container">
      <div class="intro-img">
        <img src="../assets/desktop.png"
          alt="intro" 
          width="300"
          height="250"
        /> <br />
        <p class="lead-text text-center">
          I use Vue.js for it's light weight, flexibility, easy
          integrations with axios, and requires less files to 
          run versus React or Angular. Making it the stack of 
          choice for me most of the time. Other popular or 
          preferred ways of building code is asp.Net Core.
        </p>
        <br/><br/><br/>
        <div class="row">
        <h2 class="text-center">Responsive Images</h2>
          <div class="col-md-4">
            <h3>Front End</h3>
            <br/>
            <img src="../assets/sass.png"
              alt="intro" 
              class="w-100 hover-shadow"
            />
          </div>
          <div class="col-md-4">
            <h3>layouts</h3>
            <br/>
            <img src="../assets/layout.png"
              alt="intro" 
              class="w-100 hover-shadow"
            />
          </div>
          <div class="col-md-4">
            <h3>back End</h3>
            <br/>
            <img src="../assets/backend.png"
              alt="intro" 
              class="w-75 hover-shadow"
            />
          </div>
        </div>
      </div>
    </div>
    <br /><br /><br />
    <div class="jumbotron text-center">
      <h1 class="display-4">Recent Projects</h1>
      <br />
    </div>
    <div id="carouselExampleCaptions" class="carousel slide" data-mdb-ride="carousel">
      <ol class="carousel-indicators">
        <li
          data-mdb-target="#carouselExampleCaptions"
          data-mdb-slide-to="0"
          class="active"
        ></li>
        <li data-mdb-target="#carouselExampleCaptions" data-mdb-slide-to="1"></li>
        <li data-mdb-target="#carouselExampleCaptions" data-mdb-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="https://mdbootstrap.com/img/new/slides/041.jpg"
            class="d-block w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h2>TouchedByMe</h2>
            <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img
            src="https://mdbootstrap.com/img/new/slides/042.jpg"
            class="d-block w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Second slide label</h5>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img
            src="https://mdbootstrap.com/img/new/slides/043.jpg"
            class="d-block w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Third slide label</h5>
            <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleCaptions"
        role="button"
        data-mdb-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleCaptions"
        role="button"
        data-mdb-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </a>
    </div>
    <br/><br/>
    <div class="lightbox container">
      <div class="row">
        <div class="col-lg-6">
          <ul class="rating" data-mdb-toggle="rating" data-mdb-readonly="true" data-mdb-value="3">
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
          </ul>
          <h4>Restuarant App</h4>
          <img
            src="https://mdbootstrap.com/img/Photos/Thumbnails/Slides/1.jpg"
            data-mdb-img="https://mdbootstrap.com/img/Photos/Slides/1.jpg"
            alt="Lightbox image 1"
            class="w-100 mb-2 mb-md-4"
          />
          <ul class="rating" data-mdb-toggle="rating" data-mdb-readonly="true" data-mdb-value="3">
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
          </ul>
          <h4>Food App</h4>
          <img
            src="https://mdbootstrap.com/img/Photos/Thumbnails/Square/1.jpg"
            data-mdb-img="https://mdbootstrap.com/img/Photos/Square/1.jpg"
            alt="Lightbox image 2"
            class="w-100"
          />
        </div>
        <div class="col-lg-6">
          <ul class="rating" data-mdb-toggle="rating" data-mdb-readonly="true" data-mdb-value="3">
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
            <li>
              <i class="far fa-star fa-sm text-primary"></i>
            </li>
          </ul>
          <h4>Beverage App</h4>
          <img
            src="https://mdbootstrap.com/img/Photos/Thumbnails/Vertical/1.jpg"
            data-mdb-img="https://mdbootstrap.com/img/Photos/Vertical/1.jpg"
            alt="Lightbox image 3"
            class="w-100"
          />
        </div>
      </div>
    </div>
  </div>
  <br/><br/>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String
  }
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.intro-img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
h3 {
  margin: 40px 0 0;
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
.lead-text {
  font-size: 20px;
  margin-top:60px;
}
</style>
