<template>
  <div>
<Navbar/>

  <router-view/>
  <Footer/>
  </div>
</template>

<script>
import Navbar from './components/Navbar';
import Footer from './components/Footer';
export default {
  components: {
    Navbar,
    Footer
  }
}
</script>

<style >
::-webkit-scrollbar {
  width: 6px;
  border-radius: 2px;
}
::-webkit-scrollbar-thumb {
  border-radius: 2px;
  background-color: black;
  border-radius: 10px;
  border: solid #6d6d6d 10px;
}
::-webkit-scrollbar-track {
  /* margin-top: 45px; */
  background-color: #ebebeb;
  border-radius: 10px;
  width: 6px;
}
nav .navbar-nav a.router-link-exact-active {
  color: #2c3e50;
  /* text-decoration: underline; */
  border-bottom: 3px solid #2c3e50;
}
</style>
