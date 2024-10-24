<template>
  <div class="title">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <img class="profile__image" alt="Vue logo"
      src="https://scontent.fcpe1-1.fna.fbcdn.net/v/t1.6435-9/56407400_2109815529132049_4219529197627899904_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=1d70fc&_nc_ohc=oyaLWTrjCloQ7kNvgGb8Jo1&_nc_ht=scontent.fcpe1-1.fna&_nc_gid=AkVJbyme9Rr7fn4fHPEYrjF&oh=00_AYA4xZnl23-tsTm52mQX8MRNL6Zc_QmTzc8U8OhAJtwcnw&oe=6740E961">
    <div style="margin-left: 10px; align-content: center;">
      <h1 style="text-align: left;">GUSTAVO OLAF FELIX CHAN</h1>
      <h2 style="text-align: left;">ING. EN SISTEMAS COMPUTACIONALES</h2>
    </div>
  </div>
  <ProfessionalProfile />
  <Contact />
  <Skills />
  <Education />
  <AboutMe />
  <WorkExperience />
  <Certifications />
  <Courses />
  <Languages />
  <AditionalInformation />
  <References />

  Ejemplos:<br>
  <a
    href="https://marketplace.canva.com/EAFbvOwKdrw/1/0/1236w/canva-curr%C3%ADculum-vitae-cv-de-administraci%C3%B3n-simple-beige-EVejeuHz-Tc.jpg">Ejemplo
    1</a><br>
  <a
    href="https://marketplace.canva.com/EAFnMaExwbk/1/0/1236w/canva-curr%C3%ADculum-vitae-cv-de-administraci%C3%B3n-simple-azul--EeZkEFjcoc.jpg">Ejemplo
    2</a><br>
  <a
    href="https://marketplace.canva.com/EAFYID1Rg2Y/1/0/1131w/canva-curriculum-cv-resume-academico-minimalista-profesional-simple-blanco-kZdYE9UEmec.jpg">Ejemplo
    3</a><br>
  <a
    href="https://www.modelos-de-curriculum.com/wp-content/uploads/2022/10/formato-curriculum-vitae-rellenar-editar.jpg">Ejemplo
    4</a><br>
  <a href="https://cdn-images.zety.es/pages/blog_curriculum_programador_plantilla_cascade.png">Ejemplo 5</a><br>
  <a href="https://d1xn1bcogdo8ve.cloudfront.net/2519/image.png">Ejemplo 6</a>
</template>

<script>
import ProfessionalProfile from './components/Sections/ProfessionalProfile/index.vue';
import Contact from './components/Sections/Contact/index.vue';
import Skills from './components/Sections/Skills/index.vue';
import Education from './components/Sections/Education/index.vue';
import AboutMe from './components/Sections/AboutMe/index.vue';
import WorkExperience from './components/Sections/WorkExperience/index.vue';
import Certifications from './components/Sections/Certifications/index.vue';
import Courses from './components/Sections/Courses/index.vue';
import Languages from './components/Sections/Languages/index.vue';
import AditionalInformation from './components/Sections/AditionalInformation/index.vue';
import References from './components/Sections/References/index.vue';
export default {
  name: 'App',
  components: {
    ProfessionalProfile,
    Contact,
    Skills,
    Education,
    AboutMe,
    WorkExperience,
    Certifications,
    Courses,
    Languages,
    AditionalInformation,
    References
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.title {
  display: flex;
  text-align: center;

}

.profile__image {
  border-radius: 50%;
  width: 200px;
  height: 200px;
  object-fit: cover;
}
</style>
