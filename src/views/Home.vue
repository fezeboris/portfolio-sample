<template>
  <section class="top-section">
    <div class="container-lg py-5">
      <div class="container text-center d-block d-sm-none">
        <img src="../assets/images/p3.png" class="smprofile-img" alt="..." />
      </div>
      <div class="row justify-content-center align-items-center">
        <div class="col-xs-10 col-sm-10 col-md-6 col-lg-7">
          <div class="container my-2">
            <p class="text-xs-center fs-5">Hello, I'm called</p>
            <p class="display-5 text-xs-center fw-bold">BORIS TCHOUANFE</p>
            <div class="wrapper">
              <h5 class="text--static">I AM</h5>
              <h5 class="text--dynamic"></h5>
            </div>
            <!-- <div class="btn-container">
              <button type="button" class="btn cv-btn">download cv</button>

              <button type="button" class="btn btn-outline play-btn">
                play video
              </button>
            </div> -->
          </div>
        </div>
        <div
          class="
            col-xs-10 col-sm-10 col-md-6 col-lg-5
            d-sm-none d-md-block d-none d-sm-block
          "
        >
          <div class="container">
            <img src="../assets/images/profilePi1.png" class="profile-img" alt="..." />
          </div>
        </div>
      </div>
    </div>
  </section>
  
  <section>
    <div class="container-lg my-3">
      <p class="fs-2 text-center fw-bold about pt-4">My Skills</p>
      <div class="row justify-content-center">
        <div class="col-16 col-md-6 col-lg-6">
          <div class="progress my-4">
            <div
              class="progress-bar bg-success"
              role="progressbar"
              style="width: 80%;"
              aria-valuenow="25"
              aria-valuemin="0"
              aria-valuemax="100"
            >
              <span class="fw-bold"
                >HTML &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;80%</span
              >
            </div>
          </div>
          <div class="progress my-4">
            <div
              class="progress-bar bg-warning"
              role="progressbar"
              style="width: 75%"
              aria-valuenow="25"
              aria-valuemin="0"
              aria-valuemax="100"
            >
              <span class="fw-bold"
                >CSS &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;70%</span
              >
            </div>
          </div>
          <div class="progress my-4">
            <div
              class="progress-bar bg-info"
              role="progressbar"
              style="width: 60%"
              aria-valuenow="25"
              aria-valuemin="0"
              aria-valuemax="100"
            >
              <span class="fw-bold"
                >JavaScript&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;65%</span
              >
            </div>
          </div>
        </div>
        <div class="col-16 col-md-6 col-lg-6">
          <div class="progress my-4">
            <div
              class="progress-bar bg-info"
              role="progressbar"
              style="width: 40%"
              aria-valuenow="25"
              aria-valuemin="0"
              aria-valuemax="100"
            >
              <span class="fw-bold"
                >Flutter &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;40%</span
              >
            </div>
          </div>
          <div class="progress my-4">
            <div
              class="progress-bar bg-danger"
              role="progressbar"
              style="width: 50%"
              aria-valuenow="25"
              aria-valuemin="0"
              aria-valuemax="100"
            >
              <span class="fw-bold"
                >WordPress &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;50%</span
              >
            </div>
          </div>
          <div class="progress my-4">
            <div
              class="progress-bar bg-primary"
              role="progressbar"
              style="width: 30%"
              aria-valuenow="25"
              aria-valuemin="0"
              aria-valuemax="100"
            >
              <span class="fw-bold"
                >React js&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;30%</span
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section>
    <div
      id="demo"
      class="carousel slide d-block d-sm-none"
      data-ride="carousel"
    >
      <ul class="carousel-indicators">
        <li data-target="#demo" data-slide-to="0" class="active"></li>
        <li data-target="#demo" data-slide-to="1"></li>
        <li data-target="#demo" data-slide-to="2"></li>
        <li data-target="#demo" data-slide-to="3"></li>
        <li data-target="#demo" data-slide-to="4"></li>
        <li data-target="#demo" data-slide-to="5"></li>
      </ul>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="../assets/images/css3.png"
            alt="slide one"
            width="1100"
            height="500"
          />
          <div class="carousel-caption">CSS 3</div>
        </div>
        <div class="carousel-item">
          <img
            src="../assets/images/vuejs.png"
            alt="slide two"
            width="1100"
            height="500"
          />
          <!-- <div class="carousel-caption">Vue js</div> -->
        </div>
        <div class="carousel-item">
          <img
            src="../assets/images/flutter.jpg"
            alt="slide three"
            width="1100"
            height="500"
          />
          <!-- <div class="carousel-caption">Flutter</div> -->
        </div>
        <div class="carousel-item">
          <img
            src="../assets/images/js3.jpg"
            alt="slide four"
            height="500"
            width="1100"
          />
          <div class="carousel-caption">JavaScript</div>
        </div>
        <div class="carousel-item">
          <img
            src="../assets/images/wp2.jpg"
            alt="slide five"
            width="1100"
            height="500"
          />
          <!-- <div class="carousel-caption">WordPress</div> -->
        </div>
        <div class="carousel-item">
          <img
            src="../assets/images/wdd.jpg"
            alt="slide five"
            width="1100"
            height="500"
          />
          <!-- <div class="carousel-caption">Web design</div> -->
        </div>
      </div>
      <a class="carousel-control-prev" href="#demo" data-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next" href="#demo" data-slide="next">
        <span class="carousel-control-next-icon"></span>
      </a>
    </div>
    <div class="container-lg d-none d-sm-block">
      <div class="row">
        <div class="col-12 col-md-4 col-lg-4 mb-2">
          <img src="../assets/images/css3.png" class="img-fluid" alt="..." />
        </div>
        <div class="col-12 col-md-4 col-lg-4 mb-2">
          <img src="../assets/images/vuejs.png" class="img-fluid" alt="..." />
        </div>
        <div class="col-12 col-md-4 col-lg-4 mb-2">
          <img src="../assets/images/flutter.jpg" class="img-fluid" alt="..." />
        </div>
      </div>
      <div class="row my-3">
        <div class="col-12 col-md-4 col-lg-4 mb-2">
          <img src="../assets/images/js3.jpg" class="img-fluid" alt="..." />
        </div>
        <div class="col-12 col-md-4 col-lg-4 mb-2">
          <img src="../assets/images/wp2.jpg" class="img-fluid" alt="..." />
        </div>
        <div class="col-12 col-md-4 col-lg-4 mb-2">
          <img src="../assets/images/reactjs.jpg" class="img-fluid" alt="..." />
        </div>
      </div>
    </div>
  </section>

 
</template>

<script>
export default {
  data() {
    return {
      

      name: "",
      email: "",
      subject: "",
      message: "",
    };
  },
  methods: {
   
  },
  mounted() {
    const textElement = document.querySelector(".text--dynamic");
    const wordsArray = [
      "Web developer",
      "Graphic designer",
      "Flutter developer",
      "React developer",
    ];
    let arrayLength = wordsArray.length;

    let currentLetterCount = 0,
      currentWordCount = 0,
      currentText = [],
      currentWord = "",
      currentLetter = "",
      reverse = false;

    function typeWriting() {
      if (currentWordCount <= arrayLength) {
        if (currentWordCount == arrayLength) {
          currentWordCount = 0;
        }

        let letterCount = wordsArray[currentWordCount].length;
        currentWord = wordsArray[currentWordCount];

        if (!reverse && currentLetterCount < letterCount) {
          currentLetter = currentWord[currentLetterCount];
          currentText.push(currentLetter);

          textElement.textContent = currentText.join("");
          currentLetterCount++;
          // console.log(currentText, currentLetterCount, letterCount);
        }

        if (reverse && currentLetterCount <= letterCount) {
          currentText.pop();
          textElement.textContent = currentText.join("");
          currentLetterCount--;
          // console.log(currentText, currentLetterCount);
        }

        if (currentLetterCount == letterCount) {
          reverse = true;
        }

        if (reverse && currentLetterCount == 0) {
          currentText = [];
          currentWordCount++;
          reverse = false;
        }
      }
      setTimeout(typeWriting, 300);
    }

    window.addEventListener("load", typeWriting);

   
  },
};
</script>

<style >
html {
  scroll-behavior: smooth;
}
.top-section {
  /* background: #136fff;
  color: white; */
  min-height: 100%;
  background: linear-gradient(
      0deg,
      rgba(0, 87, 249, 0.142),
      rgba(0, 89, 255, 0.3)
    ),
    url(https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8OXx8ZGV2ZWxvcGVyfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60);
  background-size: cover;
  color: white;
}
.cv-btn {
  background: white;
  border-radius: 20px;
  color: black;
}
.play-btn {
  border-radius: 20px;
  color: white;
  border: 1px solid white;
}
.profile-img {
  width: 400px;
  height: 400px;
}
.smprofile-img {
  width: 150px;
  height: 150px;
}
.btn-container {
  display: flex !important;
  text-align: left;
  margin: 0;
}
.btn-outline {
  margin: 0px 10px;
}
.contact-btn a {
  text-decoration: none;
  color: white;
}
.contact-btn2 a {
  text-decoration: none;
  color: #136fff;
}
.contact-btn2 a:hover {
  text-decoration: none;
  color: #ffff;
}
.about {
  color: #136fff;
}
.body img {
  border-radius: 5px;
}
.footer {
  background: #316ed1;
}
a i {
  color: white !important;
  margin-bottom: 30px;
}
.footer small {
  color: #f0f0f0;
  font-size: 0.7rem;
}

.wrapper {
  height: 50px;
  width: 100%;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-size: 0.8rem;
  line-height: 50px;
  display: flex;
}

.text--static {
  padding-right: 3px;
  text-align: left;
  color: #000;
}

.text--dynamic {
  color: #fff;
  /* background: linear-gradient(
    244deg,
    #daed05 2%,
    #04f6ea 49%,
    #06f616 71%,
    #daed05 100%
  );
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent; */
  border-right: 2px solid;
  height: 50%;
  animation: blink 300ms ease infinite;
}

@keyframes blink {
  0%,
  100% {
    border-right-color: transparent;
  }

  50% {
    border-right-color: limegreen;
  }
}
.carousel-inner img {
  width: 100%;
  height: 100%;
}
.carousel-caption {
  color: #136fff;
  font-weight: bold;
  font-size: 1.5rem;
}
</style>
