### Hello, person viewing my profile! 👋

```

class Human {

  constructor(info){

    this.name = info.name;
    this.age = info.age;
    this.hobbies = info.someHobbies;
    this.interests = info.someInterests;
    this.skills = info.someSkills;

  }

  writeCode(task){ 

  let code = '';
  let working = true;
  console.log('I'm coding...');
  
    while(working){
    
      console.log('Still coding...');
      drinkRedbull();
      code = code + code(task);
      working = status(code);

    }

  console.log('I'm done coding...');
  return code;

  }

  sleep(){ 

  setTimeout(console.log('Well rested'), 2.88 * 10000); //hopefully 8hrs

  }

  helloMessage(){

  console.log(`Hello, My name is ${this.name} and I'm ${this.age} years old.`);

  }

}


const person = new Human({
  name:'Evon Perez', 
  age:29, 
  someHobbies:['drone photography', 'gaming'].
  someInterests: ['AI', 'IoT', 'Math'],
  someSkills: ['problem solving', 'future thinking']
});

person.helloMessage(); // expect 'Hello, My name is Evon Perez and I'm 29 years old.'
person.hobbies; //expect ['drone photography', 'gaming']
person.writeCode('some super cool AI project');
person.sleep();


```




<!--
**Perez3von/Perez3von** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
