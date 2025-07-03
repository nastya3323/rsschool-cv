# Anastasia Dobrynina  

## Contact information
* Phone: +7 (999) 888-66-11
* Email: agent003@mail.ru
* Discord: Anastey_sha (@nastya3323)

## About me
I am passionate about frontend development. Primarily, I am self-taught in technologies related to this field. I am committed to ongoing learning and skill development.

I am eager to create dynamic, responsive, and cross-browser interfaces and applications that will be used by many people. 
My goal is to build solutions that deliver value to both businesses and end-users.

In the future, I see myself as a professional frontend developer who will contribute not only to business and user needs but also mentor aspiring specialists.

## Hard Skills
* HTML
* CSS
* SASS/SCSS
* JavaScript
* React (basic)
* Git and GitHub
* BEM

## Code Example 
**Task**: 
*Given a list of digits, return the smallest number that could be formed from these digits, using the digits only once (ignore duplicates). 
**Only positive integers** in the range of 1 to 9 will be passed to the function.*

**Examples**:
```
[1, 3, 1] ==> 13
[5, 7, 5, 9, 7] ==> 579
[1, 9, 3, 1, 7, 4, 6, 6, 7]  ==> 134679
```
**Solution:**
```
function minValue(values){
  return Number([...new Set(values)].sort((a, b) => a - b).join(""));
}
```