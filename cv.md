## Full name
Melukh Daria Pavlovna

## Contact information
- **Phone:** +375 (44) 475-68-99
- **Email:** 823meli@gmail.com
- **GitHub:** [Kalanho](https://github.com/Kalanho)

## About me
I am a fourth-year student at the Belarusian State Academy of Telecommunications (BSAT). I strive to develop my programming skills and acquire the necessary knowledge for successful employment in an IT company and further professional growth. I am responsible and goal-oriented, and enjoy solving technical problems and working in a team.

## Skills
- **Programming languages:** JavaScript, Java (basic knowledge), C# (basic knowledge), C++ (basic knowledge)
- **Basic knowledge:** OOP, data structures, algorithms
- **Tools and version control systems:** Git
- **Web technologies:** SQL, HTML, CSS basics

## Code example
function createPhoneNumber(numbers) {
  if (
    numbers.length !== 10 ||
    !numbers.every(num => Number.isInteger(num) && num >= 0 && num <= 9)
  ) {
    throw new Error("Массив должен содержать 10 чисел от 0 до 9");
  }

  const areaCode = numbers.slice(0, 3).join('');
  const firstPart = numbers.slice(3, 6).join('');
  const secondPart = numbers.slice(6, 10).join('');

  return `(${areaCode}) ${firstPart}-${secondPart}`;
}
## Work experience 
**I am currently undergoing training and am ready for an internship to gain practical experience**

## Education
**Belarusian State Academy of Telecommunications (BSAT)**
-Fourth-year student
-Major: Applied Informatics

## English
**Level**: B1 (Intermediate)