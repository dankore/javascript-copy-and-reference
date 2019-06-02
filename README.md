# javascript-copy-and-reference
### How to reference in JavaScript
```
person = {
  name: "Adamu",
  age: 20
  }
  
  const newPerson = person; 
  
  The above returns: 
  person = {
  name: "Adamu",
  age: 20
  }
```

### How to make a copy in JavaScript

```
  Copy an object:
  
  person = {
  name: "Adamu",
  age: 20
  }
  
  //Make a copy
  const copyOfPersonObject = Object.assign({}, person);  
  ```
  There are other ways to copy an object. [3 Ways to clone objects in Javascript by Farzad YZ.](https://medium.com/@Farzad_YZ/3-ways-to-clone-objects-in-javascript-f752d148054d)
  
  
  ```
  Copy an array:
  
  players = ["Adamu", "Talatu", "Amina", "Usman"];
  
  //Make a copy
  newArray = [...players].
  ```
  There are other ways to copy an array. [Ways to clone an array by Samantha Ming.](https://www.samanthaming.com/tidbits/35-es6-way-to-clone-an-array)
