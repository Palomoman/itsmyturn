<template>
  <div class="skills-container">
    <div class="skills-articles">
      <h3 style="text-decoration: underline">{{ front }}</h3>
      <div class="card-content">
        <article>{{ front1 }}</article>
        <article>{{ front2 }}</article>
        <article>{{ front3 }}</article>
        <article>{{ front4 }}</article>
        <article>{{ front5 }}</article>
        <article>{{ front6 }}</article>
        <article>{{ front7 }}</article>
        <article>{{ front8 }}</article>
      </div>
    </div>
    <div class="skills-articles">
      <h3 style="text-decoration: underline">{{ back }}</h3>
      <div class="card-content">
        <article>{{ back1 }}</article>
        <article>{{ back2 }}</article>
        <article>{{ back3 }}</article>
        <article>{{ back4 }}</article>
        <article>{{ back5 }}</article>
        <article>{{ back6 }}</article>
      </div>
    </div>
    <div class="skills-articles">
      <h3 style="text-decoration: underline">{{ general }}</h3>
      <div class="card-content">
        <article>{{ general1 }}</article>
        <article>{{ general2 }}</article>
        <article>{{ general3 }}</article>
        <article>{{ general4 }}</article>
        <article>{{ general5 }}</article>
        <article>{{ general6 }}</article>
        <article>{{ general7 }}</article>
        <article>{{ general8 }}</article>
        <article>{{ general9 }}</article>
        <article>{{ general10 }}</article>
        <article>{{ general11 }}</article>
        <article>{{ general12 }}</article>
        <article>{{ general13 }}</article>
        <article>{{ general14 }}</article>
      </div>
    </div>
    <div class="skills-articles">
      <h3 style="text-decoration: underline">{{ design }}</h3>
      <div class="card-content">
        <article>{{ design1 }}</article>
        <article>{{ design2 }}</article>
        <article>{{ design3 }}</article>
        <article>{{ design4 }}</article>
      </div>
    </div>
    <div class="skills-articles">
      <h3 style="text-decoration: underline">{{ idiomas }}</h3>
      <div class="card-content">
        <article>{{ idiomas1 }}</article>
        <article>{{ spanish }}</article>
        <article>{{ idiomas2 }}</article>
        <article>{{ catalan }}</article>
        <article>{{ idiomas3 }}</article>
        <article>{{ english }}</article>
        <article>{{ idiomas4 }}</article>
        <article>{{ japanese }}</article>
      </div>
    </div>
    <div class="skills-articles">
      <h3 style="text-decoration: underline">{{ soft }}</h3>
      <div class="card-content">
        <article>{{ soft1 }}</article>
        <article>{{ soft2 }}</article>
        <article>{{ soft3 }}</article>
        <article>{{ soft4 }}</article>
        <article>{{ soft5 }}</article>
        <article>{{ soft6 }}</article>
        <article>{{ soft7 }}</article>
        <article>{{ soft8 }}</article>
        <article>{{ soft9 }}</article>
        <article>{{ soft10 }}</article>
        <article>{{ soft11 }}</article>
        <article>{{ soft12 }}</article>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TarjetaTextoSkills",
  data() {
    return {
      front: "Frontend Development",
      front1: "Javascript",
      front2: "HTML5",
      front3: "Css3",
      front4: "React",
      front5: "Vue",
      front6: "Sass",
      front7: "Bootstrap",
      front8: "Flexbox",
      back: "Backend Development",
      back1: "Java",
      back2: "Php",
      back3: "NodeJs",
      back4: "Laravel",
      back5: "MySql",
      back6: "MongoDB",
      general: "General Computing",
      general1: "Wordpress",
      general2: "Github",
      general3: "Bitbucket",
      general4: "Linux ubuntu",
      general5: "Apache Servers",
      general6: "Microsoft Office",
      general7: "Unity",
      general8: "Unreal Engine",
      general9: "C Sharp",
      general10: "C++",
      general11: "Visual Studio",
      general12: "Visual Studio Code",
      general13: "Agile Methodologies",
      general14: "Google Suits",
      design: "Graphic Design/Digital Edition",
      design1: "Adobe Photoshop",
      design2: "Adobe Illustrator",
      design3: "Adobe dreamweaber",
      design4: "Figma",
      idiomas: "Languajes",
      idiomas1: "Spanish",
      spanish: "Native",
      idiomas2: "Catalan",
      catalan: "Native",
      idiomas3: "English",
      english: "B2 First",
      idiomas4: "Japanese",
      japanese: "N4 Intermediate",
      soft: "Soft Skills",
      soft1: "Flexible",
      soft2: "Communicative",
      soft3: "Committed",
      soft4: "Avid Learner",
      soft5: "Teamworker",
      soft6: "Adaptable",
      soft7: "Critical",
      soft8: "Resilent",
      soft9: "Creative",
      soft10: "Thoughful",
      soft11: "Neuro-Linguistic Programming Practitioner",
      soft12: "Neuro-Linguistic Programming Master",
    };
  },
};
</script>

<style>
@import "../../assets/css/skillsText.css";
</style>