[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg)](https://es.wikipedia.org/wiki/C%C3%B3digo_abierto)
![GitHub followers](https://img.shields.io/github/followers/hectrhcc?label=Followers&style=social)
![GitHub stars](https://img.shields.io/github/stars/hectrhcc?label=Stars&style=social)



```js

const frontendDeveloper = {
  name: 'Hector',
  specialty: 'Frontend',
  technologies: ['HTML', 'TailwindCSS', 'Sass', 'JavaScript', 'JQuery', 'React', 'ReactNative', 'Astro', 'Firebase'],
  projects: ['Solware', 'AgricolaDelNorte', 'DocenteMas', 'PortalMascotas', 'LosNueveTalentos'],

  addProject(project) {
    this.projects.push(project);
  },

  introduce() {
    console.log(`Hi, my name is ${this.name}, I'm a developer,
and I'm proficient in the following technologies: ${this.technologies.join(', ')}. 
I've worked on the following projects: ${this.projects.join(', ')}`);
  }
};

frontendDeveloper.addProject('One page');
frontendDeveloper.addProject('Landing page');
frontendDeveloper.addProject('Sitio corporativo');

frontendDeveloper.introduce();


```
