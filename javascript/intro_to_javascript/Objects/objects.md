# Object 

```javascript
let programming = {
    languages: ["JavaScript", "Python", "Ruby"],
    isChallenging: true,
    isRewarding: true,
    difficulty: 8,
    jokes: "http://stackoverflow.com/questions/234075/what-is-your-best-programmer-joke"
};


programming.languages.push("Go");

programming.difficulty = 7;

delete programming.jokes;

programming.isFun = true;

for(let i in programming.languages){
let language = programming.languages[i];
 console.log(language)
}

for(let i in programming){
 console.log(i)
}

for(let i in programming){
let language = programming[i];
 console.log(language)
}
```
