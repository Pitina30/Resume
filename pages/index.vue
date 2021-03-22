<template>
  <div>
    <div class="bgggg d-flex justify-center align-center">
      <!-- <img src="@/assets/pompom.jpg" class="bgggg" /> -->
      <div>
        <v-avatar class="ava" size="220">
          <img src="@/assets/hamm.jpg" />
        </v-avatar>
      </div>
    </div>
    <div class="align-center text-center">
      <p class="text-h4">Profile</p>
      <p>
        Name:
        <a href="//www.facebook.com/hamham3199" target="_blank">
          Pitina Prangsombat
        </a>
      </p>
      <p>Birthdate: 30 Oct 1999</p>
      <p>Tel. 061-2705113</p>
      <p>Email: pitina.prangs@gmail.com</p>
    </div>

    <div class="align-center text-center">
      <p class="text-h4">Education</p>
      <p>Bachelor of Science in Computer Science.</p>
      <p>Minor Subject is Division of Korean,Faculty of Humanities.</p>
      <p>Chiang Mai University, Chiang Mai</p>
    </div>

    <div class="align-center text-center">
      <p class="text-h4">Skill</p>
      <p>
        Python <br />
        C,C++ <br />
        Java
      </p>
    </div>

    <div class="align-center text-center">
      <p class="text-h4">Interests</p>
      <p>Web Developer</p>
      <p>Fronted Developer</p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.bgggg {
  background-color: #dfc2a7;
  height: 300px;
}

a:link {
  color: black;
  text-decoration: none;
}

a:visited {
  color: black;
}

a:hover {
  color: #5e35b1;
}

a:active {
  color: deeppink;
}
</style>
