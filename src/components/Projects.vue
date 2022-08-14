<template>
    <section>
    <div class="container">
      <div class="row g-2">
        
        <div class="col-10 col-md-4">
          <div class="p-3">
            <div class="card" style="width: 20rem">
                <img src="../assets/images/kwik.png" alt="" class="projectImg">
              <div class="card-body">
                <h5 class="card-title fw-bold text-center">
                    Kwikklik  Mobile first web app
                  
                </h5>
                <p class="card-text">
                    Fighting the Wicked Problem of SGBV
                </p>
                <p class="card-text text-center">
                   Almost completed(maintainance)
                </p>
                <a
                  target="blank"
                  href="https://vast-cove-60888.herokuapp.com/"
                  class="btn btn-md btn-primary visitBtn"
                  >visit</a
                >
              </div>
            </div>
          </div>
        </div>
        <div class="col-10 col-md-4">
          <div class="p-3">
            <div class="card" style="width: 20rem">
                <img src="../assets/images/boris.png" alt="" class="projectImg">

              <div class="card-body">
                <h5 class="card-title fw-bold text-center">
                  My personal portfolio
                </h5>
                <p class="card-text">
                 
                </p>
                <p class="text-center">Maintainance</p>
                <a
                target="blank"
                  href="https://tchouanfeboris.herokuapp.com/"
                  class="btn btn-md btn-primary visitBtn"
                  >visit</a
                >
              </div>
            </div>
          </div>
        </div>
        
       
        <div class="col-10 col-md-4">
          <div class="p-3">
            <div class="card" style="width: 20rem">
             
              <div class="card-body">
                <img src="../assets/images/aloyem.png" alt="" class="projectImg">
                <h5 class="card-title fw-bold text-center">
                  portfolio
                </h5>
                <p class=" text-center">
                    Prof.Dr. Djuidje Kenmoe Aloyem
                </p>
                <p class="text-center">maintaining</p>
                <br />
                <a
                  target="blank"
                  href="https://www.researchgate.net/publication/278665399_Smart_dampers_control_in_a_Remoissenet-Peyrard_substrate_potential"
                  class="btn btn-md btn-primary visitBtn"
                  >visit</a
                >
              </div>
            </div>
          </div>
        </div>
         <div class="col-10 col-md-4">
          <div class="p-3">
            <div class="card" style="width: 20rem">
             
              <div class="card-body">
                <img src="../assets/images/influz.png" alt="" class=" projectImg">
                <h5 class="card-title fw-bold text-center">
                  Infuzz.ai
                </h5>
                <p class="card-text">
                 Integrate AI into
                 your Apps
                 Seamlessly
                </p>
                <p class="text-center">Ongoing</p>
                <br />
                <a
                  target="blank"
                  href="https://www.researchgate.net/publication/278665399_Smart_dampers_control_in_a_Remoissenet-Peyrard_substrate_potential"
                  class="btn btn-md btn-primary visitBtn"
                  >visit</a
                >
              </div>
            </div>
          </div>
        </div>
        <div class="col-10 col-md-4">
          <div class="p-3">
            <div class="card" style="width: 20rem">
             
              <div class="card-body">
                <img src="../assets/images/dev.jpg" alt="" class="projectImg">
                <h5 class="card-title fw-bold text-center">
                  DevEvolution
                </h5>
                <p class=" text-center">
                    
                </p>
                <p class="text-center">Starting</p>
                <br />
                <a
                  target="blank"
                  href="#"
                  class="btn btn-md btn-primary visitBtn"
                  >visit</a
                >
              </div>
            </div>
          </div>
        </div>
        
      </div>
    </div>
  </section>
        
        

</template>

<script>
    export default {
        
    }
</script>

<style  scoped>
section {
  padding-top: 2rem;
  min-height: 100vh;
  background: url(../assets/images/moleculeBg.jpg);
  background-size: cover;
  color: black;
}
.card {
  margin: 0 auto;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}
.card-body img{
    width:100%;
}
.card:hover {
  transition: 1s ease-in-out;
  transform: translateY(-20px);
  box-shadow: rgba(50, 50, 93, 0.25) 0px 30px 60px -12px,
    rgba(0, 0, 0, 0.3) 0px 18px 36px -18px;
}
.card img {
  height: 16rem;
}
.card-text {
  text-align: justify !important;
}
.visitBtn{
    width: 150px;
    margin: 0px auto;
    display: block;
}
/* .projectImg{
    height: 250px !important;
   
} */

</style>