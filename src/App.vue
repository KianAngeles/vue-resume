<template>
  <article class="paper" role="document">
    <MyProfile />

    <section class="section two-col">
      <MyEducation />
      <MySkills />
    </section>

    <footer class="section">
      <h2>Contact Information</h2>
      <p class="meta">
        Address: Mansfield Residences, Angeles City, Philippines •
        Email: angeleskiancharles@gmail.com •
        Phone: +63 929 641 8227
      </p>
    </footer>
  </article>
</template>

<script>
import MyProfile from "./components/MyProfile.vue";
import MyEducation from "./components/MyEducation.vue";
import MySkills from "./components/MySkills.vue";

export default {
  name: "App",
  components: {
    MyProfile,
    MyEducation,
    MySkills
  }
};
</script>
