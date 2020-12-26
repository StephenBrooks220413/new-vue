<template>
  <div class="about">
    <h1>About Us</h1>
    <br /><br /><br />
    <div class="row">
      <div class="col-3">
        <!-- Tab navs -->
        <div
          class="nav flex-column nav-tabs"
          id="v-tabs-tab"
          role="tablist"
          aria-orientation="vertical"
        >
          <a
            class="nav-link active"
            id="v-tabs-home-tab"
            data-mdb-toggle="tab"
            href="#v-tabs-home"
            role="tab"
            aria-controls="v-tabs-home"
            aria-selected="true"
            >Home</a
          >
          <a
            class="nav-link"
            id="v-tabs-profile-tab"
            data-mdb-toggle="tab"
            href="#v-tabs-profile"
            role="tab"
            aria-controls="v-tabs-profile"
            aria-selected="false"
            >Profile</a
          >
          <a
            class="nav-link"
            id="v-tabs-messages-tab"
            data-mdb-toggle="tab"
            href="#v-tabs-messages"
            role="tab"
            aria-controls="v-tabs-messages"
            aria-selected="false"
            >Messages</a
          >
        </div>
        <!-- Tab navs -->
      </div>
      <br /><br /><br />
      <div class="jumbotron text-center">
        <img
          src="https://mdbootstrap.com/img/new/standard/city/042.jpg"
          class="img-fluid shadow-2-strong"
          alt="profile"
        />
      </div>
      <div class="text col-9">
        <!-- Tab content -->
        <div class="tab-content" id="v-tabs-tabContent">
          <div
            class="tab-pane fade show active text-center container"
            id="v-tabs-home"
            role="tabpanel"
            aria-labelledby="v-tabs-home-tab"
          >
            
            Integer quis auctor elit sed vulputate mi sit. Orci dapibus ultrices in iaculis nunc sed augue. Vitae justo eget magna fermentum iaculis. Tortor aliquam nulla facilisi cras fermentum odio eu feugiat. Tellus mauris a diam maecenas sed enim. Cras ornare arcu dui vivamus arcu felis bibendum ut. Aliquam ultrices sagittis orci a. Enim sed faucibus turpis in eu mi bibendum. Elementum facilisis leo vel fringilla est ullamcorper. Nisi porta lorem mollis aliquam. Tincidunt nunc pulvinar sapien et ligula. Nisi quis eleifend quam adipiscing vitae proin sagittis. Arcu risus quis varius quam quisque id diam. Habitant morbi tristique senectus et netus et. Nec feugiat nisl pretium fusce id. Risus nullam eget felis eget nunc lobortis mattis aliquam. Massa sed elementum tempus egestas sed sed risus pretium.
          </div>
          <div
            class="tab-pane fade"
            id="v-tabs-profile"
            role="tabpanel"
            aria-labelledby="v-tabs-profile-tab container"
          >
            Est ante in nibh mauris cursus mattis molestie a iaculis. Praesent tristique magna sit amet. Posuere lorem ipsum dolor sit amet consectetur adipiscing elit duis. Nisl suscipit adipiscing bibendum est ultricies. Eget dolor morbi non arcu risus quis varius quam. Convallis posuere morbi leo urna molestie. Aliquam id diam maecenas ultricies mi eget mauris pharetra. Consectetur purus ut faucibus pulvinar elementum integer enim neque. Tempor orci dapibus ultrices in. Lobortis feugiat vivamus at augue. Scelerisque mauris pellentesque pulvinar pellentesque habitant. Lacus viverra vitae congue eu consequat ac. Et ligula ullamcorper malesuada proin libero nunc. Pellentesque pulvinar pellentesque habitant morbi tristique senectus et netus et. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Pretium fusce id velit ut tortor pretium viverra suspendisse. Leo vel fringilla est ullamcorper eget nulla.
          </div>
          <div
            class="tab-pane fade"
            id="v-tabs-messages"
            role="tabpanel"
            aria-labelledby="v-tabs-messages-tab container"
          >
            Tellus elementum sagittis vitae et leo duis. Potenti nullam ac tortor vitae purus faucibus ornare suspendisse sed. Turpis egestas sed tempus urna et pharetra pharetra. Porttitor leo a diam sollicitudin tempor id eu. Diam volutpat commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Nunc sed velit dignissim sodales ut eu sem integer vitae. Tempus imperdiet nulla malesuada pellentesque elit eget gravida cum sociis. Elit pellentesque habitant morbi tristique senectus. Velit egestas dui id ornare arcu odio. Pretium viverra suspendisse potenti nullam. Neque vitae tempus quam pellentesque. Metus vulputate eu scelerisque felis imperdiet proin fermentum leo. Enim facilisis gravida neque convallis a cras. Non curabitur gravida arcu ac tortor. Sed turpis tincidunt id aliquet. Commodo ullamcorper a lacus vestibulum sed arcu. Congue nisi vitae suscipit tellus. Mauris commodo quis imperdiet massa tincidunt. Egestas diam in arcu cursus euismod quis viverra nibh.
          </div>
        </div>
        <!-- Tab content -->
      </div>
    </div>
    <br /><br />
    <hr />
    <br/>
    <h1 class="display-4">Featured Section</h1>
    <div class="container">
      <div class="row">
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Special title treatment</h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Special title treatment</h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Special title treatment</h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      </div>
    </div>
    <br/>
    <hr />
    <div class="calendar" id="calendar-2" data-mdb-monday-first="true"></div>
  </div>
</template>

<script>
</script>

<style scoped>
.about {
  margin-top: 70px;
}
.jumbotron {
  width: 350px!important;
  height: 300px!important;
  margin-left: 15%;
  margin-right: auto;
}
.col-sm-4 {
  margin-top: 5px;
  margin-bottom: 5px;
}
  .text {
    width:90%;
    padding-left: 20%;
  }
.card-body {
  background: url(https://images.unsplash.com/photo-1501630834273-4b5604d2ee31?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80) no-repeat center center fixed!important; 
  -webkit-background-size: cover!important;
  -moz-background-size: cover!important;
  -o-background-size: cover!important;
  background-size: cover!important;
  width: auto;
}
</style>