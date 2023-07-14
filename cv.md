# Kolmak Evgeniy
<img src="https://sun9-58.userapi.com/impf/c636522/v636522762/5eb31/_5fChIJc7sc.jpg?size=2560x1438&quality=96&sign=0c223e3130c33adc00e6d9559297b61f&type=album"  width="600" height="300">

## Contact
Phone: +375(33)305-24-42

Email: zenakolmak669@gmail.com

Address: 73/69, Leninskay Street Chashniki Vitebskay oblast' Belarus

## Objective
1. Web designer
2. Game developer

## Profile
A purposeful, hardworking student who wants to use his skills to grow and progress both as a specialist and as a person.

## Skills
+ English language proficiency level A2 (university courses were completed)
+ There is a basic knowledge of programming languages such as
    * Java
    * C++
    * C#
    * Python

## Code Examples
Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case). The next words should be always capitalized.

```java
class Solution{

static String toCamelCase(String s){

StringBuilder sb = new StringBuilder();

Boolean nextCapital = false;

for (int i=0; i<s.length(); i++) {

    if (Character.isLetter(s.charAt(i))) {

    char tmp = s.charAt(i);

    if (nextCapital) tmp = Character.toUpperCase(tmp);

    sb.append(tmp);

    nextCapital = false;

    } else {
    nextCapital = true;
    }
}

return sb.toString();
}
}
```
## Work experience
rsschool-cv - <https://github.com/EvgeniyKolmak/rsschool-cv/blob/gh-pages/cv.md?plain=1>

## Education
+ __2021 - present__      Software engineer, Faculty of Information Technology and Robotics, 3rd year study, Belarusian National Technical University, Minsk, Belarus

+ __2010 - 2021__         Secondary schooд № 1, Chashniki Belarus