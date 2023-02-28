<script>
export default {
  data() {
    return { title: "AppFooter" };
  },
};
</script>

<template>
  <div class="footer-container">
    <section>
      <ul>
        <li>DC COMICS</li>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">News</a></li>
        <li>SHOP</li>
        <li><a href="#">Shop DC</a></li>
        <li><a href="#">Shop DC Collectibles</a></li>
      </ul>
      <ul>
        <li>DC</li>
        <li><a href="#">Terms Of Use</a></li>
        <li><a href="#">Privacy policy (New)</a></li>
        <li><a href="#">Ad Choices</a></li>
        <li><a href="#">Advertising</a></li>
        <li><a href="#">Jobs</a></li>
        <li><a href="#">Subscription</a></li>
        <li><a href="#">Talent Workshop</a></li>
        <li><a href="#">CPSC Certificates</a></li>
        <li><a href="#">Ratings</a></li>
        <li><a href="#">Shop Help</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
      <ul>
        <li>SITES</li>
        <li><a href="#">DC</a></li>
        <li><a href="#">MAD Magazine</a></li>
        <li><a href="#">DC Kides</a></li>
        <li><a href="#">DC Universe</a></li>
        <li><a href="#">DC Power Visa</a></li>
      </ul>

      <img src="../assets/img/dc-logo-bg.png" alt="" />
    </section>
    <section>
      <div>
        <button>SIGN UP NOW</button>
      </div>
      <div class="social">
        <span>FOLLOW US</span>
        <img src="../assets/img/footer-facebook.png" alt="" />
        <img src="../assets/img/footer-twitter.png" alt="" />
        <img src="../assets/img/footer-youtube.png" alt="" />
        <img src="../assets/img/footer-pinterest.png" alt="" />
        <img src="../assets/img/footer-periscope.png" alt="" />
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
.footer-container {
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  min-height: 23rem;
  color: white;

  section {
    display: flex;
    margin: 0 auto;
    max-width: 1200px;
    justify-content: space-between;
  }

  ul {
    padding: 20px;
    li {
      padding: 0.25rem;
    }
  }

  .social {
    display: inline-block;
  }
}
</style>
