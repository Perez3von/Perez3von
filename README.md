### Hello, Person viewing my profile! š

```
_______________________________________________________________________________________
const softwareEngineer = new SoftwareEngineer({
  name:'Evon Perez', 
  age:29, 
  some_hobbies:['drone photography', 'gaming'],
  some_interests: ['AI', 'Old rock music', 'Math'],
  some_skills: ['problem solving', 'creative']
});

softwareEngineer.helloMessage(); // expect 'Hello, My name is Evon Perez and I'm 29 years old.'
console.log(softwareEngineer.hobbies); //expect ['drone photography', 'gaming']
softwareEngineer.writeCode('some super cool backend project');
softwareEngineer.sleep();
_______________________________________________________________________________________
class SoftwareEngineer {

  constructor(info){

    this.name = info.name;
    this.age = info.age;
    this.hobbies = info.some_hobbies;
    this.interests = info.some_interests;
    this.skills = info.some_skills;

  }

  writeCode(task){ 

  let code = '';
  let working = true;
  console.log("I'm coding...");
  
    while(working){
    
      console.log('Still coding...');
      drinkRedbull();
      code = code + code(task);
      working = status(task, code);

    }

  console.log("I'm done coding...");
  return code;

  }

  sleep(){ 
  
  setTimeout(() => {console.log("Well rested")}, 2.88 * 10000)  //hopefully 8hrs
 
  }

  helloMessage(){

  console.log(`Hello, My name is ${this.name} and I'm ${this.age} years old.`);

  }

}
_______________________________________________________________________________________
```




<!--
**Perez3von/Perez3von** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
