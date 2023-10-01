<img src=./docs/SussyScriptLogo.png width="500" height="500">

# SussyScript
This is SussyScript. SussyScript is a static and weakly typed coding language inspired by the popular party game Among Us! SussyScript takes influence from the coding conventions of JavaScript and Python, aimed to introduce coding to crewmates (and also beginner coders familiar with Among Us). Being a language targeted at beginners, SussyScript allows users to learn the basic functions of coding, such as looping and expression creation, with terms and keywords that allude to mechanics in Among Us! 

## 🔗 Developers
- [@Mitchell Cootauco](https://github.com/Mcootauc)
- [@Sebastian Cruz](https://github.com/seevass)
- [@Erin Hurlburt](https://github.com/erinhurlburt)
- [@Connor Savage](https://github.com/connorsavage)

## Tech Stack
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
### [Ohm Grammar](https://github.com/Mcootauc/SussyScript/blob/main/src/sussyScript.ohm)

### Imposterous Features:
- Mix of Python & Javascript: No parenthesis in if/while/for statements, but does have brackets
- Among Us-themed language and syntax
- Everything is natively private
- Static and weakly typed
- letus/constus can be used for type inference
- String interpolation
- Suspicious but detailed error messages

## Example Tasks

### Printing

<table>
<tr> <th>JavaScript</th><th>SussyScript</th><tr>
</tr>
<td>

```javascript
console.log(“Hello world!”)
```

</td>

<td>

```
report “Hello world!”
```

</td>
</table>

### Assigning variables

<table>
<tr> <th>JavaScript</th><th>SussyScript</th><tr>
</tr>
<td>

```javascript
let x = 0
const y = 1
```

</td>

<td>

```
letus x = 0
constus x = 0
```

</td>
</table>

### if-statements

<table>
<tr> <th>JavaScript</th><th>SussyScript</th><tr>
</tr>
<td>
    
```javascript
if (x < 10) {
  return 1;
} else if (x < 20) {
  return -1;
} else {
  return 0;
}
```
</td>
<td>
    
```
sus x < 10 {
  vote 1
} mega sus x < 20 {
  vote -1
} mega {
  vote 0
} 
```
</td>
</table>

### Function Declarations

<table>
<tr> <th>JavaScript</th><th>SussyScript</th><tr>
</tr>
<td>
    
```javascript
function evenOrOdd(x){
    return x %  2 ==  0
}
```
</td>
<td>
    
```
task evenOrOdd(x) {
    vote x % 2 == 0
}
```
</td>
</table>

<table>
<tr> <th>JavaScript</th><th>SussyScript</th><tr>
</tr>
<td>
    
```javascript
function add(a, b){
    return a + b;
}
```
</td>
<td>
    
```
task add(a, b) { 
   vote a + b
}
```
</td>
</table>

### Loops

<table>
<tr> <th>JavaScript</th><th>SussyScript</th><tr>
</tr>
<td>
    
```javascript
while(true){
    break
}
```
</td>
<td>
    
```
during crewmate {
    eject
}
```
</td>
</table>

<table>
<tr> <th>JavaScript</th><th>SussyScript</th><tr>
</tr>
<td>
    
```javascript
for (var x = 0; x < 3; x++) {
    break
}
```
</td>
<td>
    
```
scan varus in 0 till 3 {
    eject
}
```
</td>
</table>

### Comments

<table>
<tr> <th>JavaScript</th><th>SussyScript</th><tr>
</tr>
<td> 
    
```javascript
// insert sussy comment
```
</td>
<td>
    
```
cR insert sussy comment
```
</td>
</table>

### Types of Semantic Errors
- Declaring a variable that has already been declared
- Return outside of a function
- Non-boolean value in conditional
- Non-boolean value in while loop
- Incorrect number of function parameters
- Incompaible type comparison
- Repeating and For loop with something other than integer value assigned
- Differen types in ternary conditional return
- "And"/"Or" conditionals not having boolean values
- Break outside of loops
- Calling a function or method that is not initialized
- Use of non-initialized variables

### [Website Link](https://seevass.github.io/)
