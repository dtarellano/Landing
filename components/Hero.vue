<template>
  <div class="">
    <div class="container is-fluid">
      <div class="columns">
        <div class="column">
          <div class="card-content">
            <div class="media-content">
              <p class="title is-4">Stop Waisting Food.</p>
            </div>
            <div class="content">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </div>
            <button class="button is-primary">Free Trial</button>
            <button class="button">Learn More</button>
          </div>
        </div>
        <div class="column">
            <div class="card-image">
              <figure class="image">
                <img src="http://via.placeholder.com/350x200" alt="Intro Pic">
              </figure>
            </div>
        </div>
      </div>
    </div>
    <div class="shapes-container">
      <div class="stripe"></div>
    </div>

  </div>
</template>

<script>
export default {};
</script>

<style lang="css" scoped>
  .container {
    position: relative;
  }
  .shapes-container {
    min-height: 80vh;
    background-color: #fff;
    /* margin-top: 192px; */
  }
  .stripe {
    position: relative;
    width: 100%;
  	height: 800px;

    background: #f6fbfd;
  }
  .stripe:after {
    position: absolute;
    width: 100%;
    height: 235px;
  	background: #ecf2f5;
    content: '';
    top: 48px;
    right: 0;
    bottom: 0;
    left: 0;
    transform-origin: top right;
    transform: skewY(-13deg);

  }
</style>
