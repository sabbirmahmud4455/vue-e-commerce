<template>
  <div>
      <nav class="fh5co-nav" role="navigation">
        <div class="container">
          <div class="row">
            <div class="col-md-3 col-xs-2">
              <div id="fh5co-logo">
                <!-- <a href="index.html"></a> -->
                <router-link to="/">Shop.</router-link>
                
                </div>
            </div>
            <div class="col-md-6 col-xs-6 text-center menu-1">
              <ul>
                <li class="has-dropdown">
                  <router-link to="/shop">Shop</router-link>
                  <ul class="dropdown">
                    <li><a href="single.html">Single Shop</a></li>
                  </ul>
                </li>

<!-- <router-link to="/">Home</router-link> |
<router-link to="/about">About</router-link> -->


                <li>
                  <!-- <a href="about.html">About</a> -->
                  <router-link to="/about">About</router-link>
                  </li>
                <li class="has-dropdown">
                  <router-link to="/Services">Services</router-link>
                  <ul class="dropdown">
                    <li><a href="#">Web Design</a></li>
                    <li><a href="#">eCommerce</a></li>
                    <li><a href="#">Branding</a></li>
                    <li><a href="#">API</a></li>
                  </ul>
                </li>
                <li>
                  <router-link to="/Contact">Contact</router-link>
                </li>
              </ul>
            </div>
            <div class="col-md-3 col-xs-4 text-right hidden-xs menu-2">
              <ul>
                <li class="search">
                  <div class="input-group">
                      <input type="text" placeholder="Search..">
                      <span class="input-group-btn">
                        <button class="btn btn-primary" type="button"><i class="icon-search"></i></button>
                      </span>
                    </div>
                </li>
                <li class="shopping-cart"><a href="#" class="cart"><span><small>0</small><i class="icon-shopping-cart"></i></span></a></li>
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

<style>

</style>