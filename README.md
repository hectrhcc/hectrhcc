```js

const frontendDeveloper = {
  name: 'Hector',
  specialty: 'Frontend',
  technologies: ['HTML5', 'CSS3', 'JavaScript', 'JQuery', 'Bootstrap', 'Saas','React'],
  projects: [],

  addProject(project) {
    this.projects.push(project);
  },

  introduce() {
    console.log(`Hi, my name is ${this.name} and I'm a frontend developer.`); 
  }
}

// Creamos proyectos
const blog = {
  name: 'Blog personal'
};

const landing = {
  name: 'Landing page'  
};

// Agregamos proyectos
frontendDeveloper.addProject(blog);
frontendDeveloper.addProject(landing);

// Presentación
frontendDeveloper.introduce();
```
