``` javascript
const me = {
    first_name: "Santos",
    age: new Date().getFullYear() - 2007,
    "education": ["Informatica (BSc)", "University of Amsterdam"]
}

const {first_name, age, education} = me

function greeting(name, age, education) {
    console.log(`Hi, I'm ${name} and I'm ${age} years old. Currently I'm studying ${education[0]} at the ${education[1]}. It's nice to meet you!`) 
}

greeting(first_name, age, education)

////

let myStack = ['javascript', 'php', 'laravel', 'html', 'scss', 'css'];

console.log(`This is my stack: ${myStack}`);

```
``` console
Hi, I'm Santos and I'm 17 years old. Currently I'm studying Informatica (BSc) at the University of Amsterdam. It's nice to meet you!
This is my stack: javascript, php, laravel, html, scss, css
```


<!--
### Wat heb ik de afgelopen week gedaan?
<!-a-START_SECTION:waka-a->

```text
JavaScript   2 hrs 12 mins   ██████████████████▓░░░░░░   74.43 %
Markdown     18 mins         ██▓░░░░░░░░░░░░░░░░░░░░░░   10.65 %
CSS          11 mins         █▓░░░░░░░░░░░░░░░░░░░░░░░   06.66 %
Text         4 mins          ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.36 %
JSON         3 mins          ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.09 %
HTML         2 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.55 %
```

<!-a-END_SECTION:waka-a-> 
-->


<!--<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=santosvdw&show_icons=true&locale=en" alt="santosvdw" /></p>-->
