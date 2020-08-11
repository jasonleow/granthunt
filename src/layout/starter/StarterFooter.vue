<template>
    <footer class="footer has-cards">
        <!--<div class="container container-lg">
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/landing" title="Landing Page">
                            <img v-lazy="'img/theme/landing.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/profile" title="Profile Page">
                            <img v-lazy="'img/theme/profile.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
            </div>
        </div>-->
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <router-link slot="brand" class="navbar-brand mr-lg-5" to="/"><img src="img/brand/blue.png">
                    </router-link>
                    <br/>
                    <br/>
                    <h5 class="text-primary font-weight-light mb-2">Grant Hunt is a chat bot to find grants for charities and non-profits in Singapore.</h5>
                    <br/>
                    <h6 class="mb-0 font-weight-light">Made by <a href="https://twitter.com/jasonleowsg" target="_blank" rel="noopener">@jasonleowsg</a>. 
                    <br/>
                    <br/>
                    This site is made by just one person (me!). <a href="https://www.buymeacoffee.com/jasonleowsg" target="_blank" rel="noopener">Buy me a coffee</a> if the site had been helpful to you.</h6>
                </div>
                <!--<div class="col-lg-6 text-lg-center btn-wrapper">
                    <a target="_blank" href="https://www.facebook.com/gogranthunt/"
                       class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-facebook-square"></i>
                    </a>
                    <a target="_blank" href="https://www.messenger.com/t/gogranthunt"
                       class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Like us">
                        <i class="fa fa-search-plus"></i>
                    </a>
                    <a target="_blank" href="https://dribbble.com/creativetim"
                       class="btn btn-neutral btn-icon-only btn-dribbble btn-lg btn-round" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-dribbble"></i>
                    </a>
                    <a target="_blank" href="https://github.com/creativetimofficial"
                       class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Star on Github">
                        <i class="fa fa-github"></i>
                    </a>
                </div>-->
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        Grant Hunt
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a href="#home" class="nav-link">Home</a>
                        </li>
                        <li class="nav-item">
                            <a href="https://m.me/gogranthunt" class="nav-link" target="_blank">Chat bot</a>
                        </li>
                        <li class="nav-item">
                            <a href="#directory" class="nav-link">Directory</a>
                        </li>
                        <li class="nav-item">
                            <a href="https://goo.gl/forms/IqEc0Mb6XlJp0k933"
                               class="nav-link" target="_blank">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'starter-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
