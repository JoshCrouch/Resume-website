<script setup>
import Navbar from "./components/Navbar.vue"
import Contact from "./components/Content/Contact.vue"
import Cover_Letter from "./components/Content/Cover Letter.vue"
import Education from "./components/Content/Education.vue"
import Relevant_Skills from "./components/Content/Relevant Skills.vue"
import Projects from "./components/Content/Projects.vue"
import Interests_and_Qualities from "./components/Content/Interests and Qualities.vue"
import Experience from "./components/Content/Experience.vue"
import References from "./components/Content/References.vue"
import Thanks from "./components/Content/Thanks.vue"
</script>

<template>
  <div>
    <Navbar class="h-full w-1/6 bg-white fixed Navbar"/>
    <div class="text-white p-10 Content">
      <Contact id="Contact" />
      <Cover_Letter id="Cover_Letter" />
      <Education id="Education" />
      <Relevant_Skills id="Relevant_Skills" />
      <Projects id="Projects" />
      <Experience id="Experience" />
      <Interests_and_Qualities id="Interest_and_Qualities" />
      <References id="References" />
      <Thanks id="Thanks" />
    </div>
  </div>
</template>

<style>
html {
  scroll-behavior: smooth;
}

h1 {
  font-size: 1.5rem/* 24px */;
  line-height: 2rem/* 32px */;
}
body {
  font-size: 1.25rem/* 20px */;
  line-height: 1.75rem/* 28px */;
}
a:hover {
  color: rgb(34 211 238);
}

a {
  transition: 100ms all ease-in-out;
  color: rgb(165 243 252);
}

.Navbar, .Headshot {
  visibility: hidden;
}

@media screen and (min-width: 1100px) {
  .Navbar, .Headshot {
    visibility: visible;
  }
  .Content {
    margin-left: 16.66%;
  }
}

</style>
