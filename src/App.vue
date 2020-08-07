<template>
  <div id="app">
    <Navbar />
    <div class="doctor-profile">
      <DoctorProfileHeader />
    </div>
  </div>
</template>

<script>
import Navbar from "./components/common/navbar.vue";
import DoctorProfileHeader from "./components/DoctorProfile/DoctorProfileHeader.vue";

export default {
  name: "App",
  components: {
    Navbar,
    DoctorProfileHeader,
  },
};
</script>

<style>
body {
  margin: 0;
  direction: rtl;
}
</style>
