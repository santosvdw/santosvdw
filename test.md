
``` javascript
const name = {
    first_name: Santos,
    age: new Date().getFullYear() - 2007
}

const {first_name, age} = name

function greeting(name,age) {
    console.log(`Hi, I'm ${name} and I'm ${age} years old. It's nice to meet you!`) 
}

greeting(first_name, age)
```
``` console
Hi, I'm Santos and I'm 16 years old. It's nice to meet you!
```
