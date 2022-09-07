# Khudych Anastasiia

## Contacts:

- Discord: Anastassia(0629)
- email: anastasiiakhudych@gmail.com
- Telegram: @Anastasiia_Khudych

## About myself:

I am 22 years old. I want to have a good job with the opportunities to grow, develop myself, and learn something new and valuable. I am that type of person who
studies continuously, I am seeking new knowledge. Once have tried programming at the university while I was doing my diploma I understood that I wanted to learn
more about this. So now I am developing my skills to be a Front-end developer.

## Skills:

- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code

## Code example:

_deepCount function returns the number of ALL elements within an array, including any within inner-level arrays_

```
function deepCount(arr) {
    let result = 0;

    for (let i = 0; i < arr.length; i++) {
        if (Array.isArray(arr[i])) {
            result += 1;
            result = result + deepCount(arr[i]);
        } else {
            result += 1;
        }
    }

    return result;
}
```

## Education:

- V. N. Karazin Kharkiv National University (faculty of biology)
- freeCodeCamp - Responsive Web Design
- JS/FE PRE-SCHOOL 2022Q2 (JAVASCRIPT)

## Languages:

- Russian, Ukrainian - Native
- English - B1+

## Projects:

- [Momentum app] (https://rolling-scopes-school.github.io/anastasiia-khudych-JSFEPRESCHOOL2022Q2/momentum/)
- [Travel website] (https://rolling-scopes-school.github.io/anastasiia-khudych-JSFEPRESCHOOL2022Q2/travel/)
- [Eldritch Horror] (https://rolling-scopes-school.github.io/anastasiia-khudych-JSFEPRESCHOOL2022Q2/codejam/)
