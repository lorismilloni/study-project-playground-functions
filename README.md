# study-project-playground-functions
Made in **17/11/2021**.

## In this assignment from Trybe we've tested our JavaScript skills.
#### Writing code using variables and primitive types, dinamic types, logical opertators, arithmetic operators and assingment operators. We also used loop and iterator, if/else, for/in, objects and functions. We learned how to organize our code, to break our problems in little baby steps, and to use programming logic to solve our problems.
<img src='https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg' width='40'/>

#### Here is a code snippet:

 ```javascript
function fizzBuzz(numeros) {
  let retorno = [];
  for (let index = 0; index < numeros.length; index += 1) {
    if (numeros[index] % 3 === 0) {
      if (numeros[index] % 5 === 0) {
        retorno.push('fizzBuzz');
      } else {
        retorno.push('fizz');
      }
    } else if (numeros[index] % 5 === 0) {
      retorno.push('buzz');
    } else {
      retorno.push('bug!');
    }
  }
  return retorno;
}
```
#### Trybe has a private repository with files that can't be shared. So here is my commit history print:
<img src="images-readme/commit-history.png">

#### Here is the Trybe Evaluator
<img src="images-readme/evaluator.png">
