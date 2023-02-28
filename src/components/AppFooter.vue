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
        <h2>DC COMICS</h2>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">News</a></li>
        <h2>SHOP</h2>
        <li><a href="#">Shop DC</a></li>
        <li><a href="#">Shop DC Collectibles</a></li>
      </ul>
      <ul>
        <h2>DC</h2>
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
        <h2>SITES</h2>
        <li><a href="#">DC</a></li>
        <li><a href="#">MAD Magazine</a></li>
        <li><a href="#">DC Kides</a></li>
        <li><a href="#">DC Universe</a></li>
        <li><a href="#">DC Power Visa</a></li>
      </ul>

      <img class="big-logo" src="../assets/img/dc-logo-bg.png" alt="" />
    </section>

    <div class="bottom-footer">
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

  .bottom-footer {
    padding: 2rem 0;
    background-color: black;
  }

  .big-logo {
    padding: 3rem;
  }

  ul {
    padding: 20px;
    li {
      padding: 0.25rem 0;
    }

    h2 {
      margin: 1rem 0;
    }
    a {
      color: white;
      text-decoration: none;
    }
  }

  .social {
    display: flex;

    // border: 3px dashed blue;

    span {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
      // border: 3px dashed orange;
    }

    img {
      padding: 1rem;
      // border: 3px dashed red;
    }
  }
}
</style>
