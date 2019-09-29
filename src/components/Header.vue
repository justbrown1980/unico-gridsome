<template>
    <header role="banner" class="triangle__border--bottom">

        <div class="header__container">

            <a href="index.html" class="logo">
                <picture>
                    <img src="unico-red-logo.png" alt="Logo" width="300" height="76">
                </picture>
            </a>

            <nav id="menu" role="navigation">
                <label for="tm" id="toggle-menu">Navigation <span class="drop-icon">▾</span></label>
                <input type="checkbox" id="tm">
                <ul class="main-menu clearfix">
                  <li><a href="index.html">Home</a></li>
                  <li><a href="#">Menu 
                      <span class="drop-icon">▾</span>
                      <label title="Toggle Drop-down" class="drop-icon" for="sm1">▾</label>
                    </a>
                    <input type="checkbox" id="sm1">
                    <ul class="sub-menu">
                      <li><a href="#">Pizza
                          <span class="drop-icon">▾</span>
                          <label title="Toggle Drop-down" class="drop-icon" for="sm2">▾</label>
                        </a>
                        <input type="checkbox" id="sm2">
                        <ul class="sub-menu">
                          <li><a href="traditional.html">Traditional</a></li>
                          <li><a href="gourmet-meat.html">Gourmet Meat</a></li>
                          <li><a href="gourmet-seafood.html">Gourmet Seafood</a></li>
                          <li><a href="gourmet-veggie.html">Gourmet Veggie</a></li>
                          <li><a href="desserts.html">Dessert</a></li>
                        </ul>
                      </li>
                      <li><a href="pides.html">Turkish Pides</a></li>
                      <li><a href="gozleme.html">Gozleme</a></li>
                      <li><a href="kebabs.html">Kebabs</a></li>
                      <li><a href="hsp.html">HSP</a></li>
                      <li><a href="mains.html">Mains</a></li>

                       
                    </ul>
                  </li>
                  <li><a href="#footer-tabs">Location and Hours</a></li>
                </ul>
              </nav>  <!-- end navigation -->
              
            <aside>
                <a href="https://www.facebook.com/unicopizzakebab"><img src="social-facebook.svg" width="60" height="60"></a>
                <a href="tel:94321911" class="btn btn__outline">order now: 9432 1911</a>
            </aside>

            
        </div><!-- / wrapper -->

    </header>



</template>

<script>
export default {

}
</script>

<style>

</style>