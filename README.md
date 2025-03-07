[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg)](https://es.wikipedia.org/wiki/C%C3%B3digo_abierto)
![GitHub followers](https://img.shields.io/github/followers/hectrhcc?label=Followers&style=social)
![GitHub stars](https://img.shields.io/github/stars/hectrhcc?label=Stars&style=social)

<a href="https://www.frontendmentor.io/profile/hectrhcc" target="_blank">
  <img  align="left"  width="20px" src="https://simpleicons.vercel.app/frontendmentor/" />
</a>
<a href="https://www.hackerrank.com/profile/hectrhcc" target="_blank">
  <img  align="left"  width="20px" src="https://simpleicons.vercel.app/hackerrank/" />
</a>
<a href="https://www.freecodecamp.org/hectrhcc" target="_blank">
  <img  align="left"  width="20px" src="https://simpleicons.vercel.app/freecodecamp/" />
</a>
<a href="https://codepen.io/hectrhcc/" target="_blank">
  <img  align="left"  width="20px" src="https://simpleicons.vercel.app/codepen/" />
</a>


```js

frontendDeveloper = {
    name: 'Hector',
    specialty: 'Frontend',
    technologies: ['HTML','TailwindCSS','Sass','JavaScript','JQuery', 'React', 'ReactNative', 'Astro', 'Firebase' ],
    projects: [],
    
    addProject(project) {
    this.projects.push(project);
    },
    
    introduce() {
    console.log(`Hi, my name is ${this.name}, I\'m a frontend developer,
    and I\'m proficient in the following technologies: ${this.technologies.join(', ')}. 
    I\'ve worked on the following projects: ${this.projects.map(p => p.name).join(', ')}`);
    }
    };
    
    const blog = {
    name: 'Blog personal'
    };
    
    const landing = {
    name: 'Landing page'
    };
    
    frontendDeveloper.addProject(blog);
    frontendDeveloper.addProject(landing);
    
    frontendDeveloper.introduce();

```
