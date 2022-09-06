# [rsschool-cv](https://buhlyash.github.io/rsschool-cv/)
# Eduard Kharchevnikov
### Junior Frontend Developer
---
### Contact information:

Phone: 89000218662 <br>
E-mail: harchevnikov2001@mail.ru <br>
Telegram: @Byhlyash <br>
Github: [buhlyash](https://github.com/Buhlyash) <br>

---
### About myself:

Some text about me <br>
Some text about me <br>
Some text about me <br>
Some text about me <br>

---
### Skills and Proficiency
* HTML5, CSS
* JavaScript (Basics)
* Git, GitHub
* VS Code
---
### Code example
**Peak array index KATA from CODEWARS:**  *Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*
```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
---
### Courses
* 123
* 123 
* 123
---
### English
**B1** I studied in the English Club for the several years and passed courses in my university
