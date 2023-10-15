### Hello everyone 👋 im Eugenio Giménez

```javascript
    let techsObj = {
    backEnd: [ "NodeJS", "ExpressJs", "FastAPI", "Django" ],
    frontEnd: [ "HTML&CSS", "ReactJS", "Boostrap" ],
    database: [ "MongoDB", "MySQL" ],
    test: {
        JavaScript: ["Vitest", "Jest"],
        Python: ["Pytest"]
            }
    };

    class WebDeveloper {
      constructor(name, learn, code, techs, joke) {
        this.name = name;
        this.eagerToLearn = learn;
        this.code = code;
        this.technologies = techs;
        this.joke = joke
        }
        
        makeAJoke() {
          console.log(this.joke)
        }
        
        study() {
          this.eagerToLearn === true ? console.log(`Let's code some ${learn}`); : console.log(`Pick any and start train`);
        }
        
    let eugenioGimenez = new WebDeveloper("Eugenio", "testing", ["JavaScript", "Python"], techsObj, "How can you tell that a 
    web developer is working?.. You can hear him Grunting!" )
     
     eugenioGimenez.study()
```

<a href="https://www.linkedin.com/in/eogimenez/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-@eoGimenez-blue?style=flat&logo=linkedin"></a>

<a href="https://portfolio-eogimenez.netlify.app/" target="_blank">⚡ My Portfolio ⚡</a>

<!--
**eoGimenez/eoGimenez** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->
