# rsschool-cv

# Dmitrii Proskurin

## Junior Frontend Developer

## Contact information:

- Phone: +79045398868
- E-mail: cf.gwod@gmail.com

## About myself

I am studying frontend, I want to become a developer!

## Skills

- HTML5
- CSS3
- JavaScript Basics
- Git, GitHub
- VS Code

## Code example:

    function calculator(string) {

    if (string.includes('+')) {
    let signIndex = string.indexOf('+');

    let result = +string.slice(0, signIndex).trim() + +string.slice(signIndex + 1).trim();

    return(String(result));

} else if (string.includes('-')) {
let signIndex = string.indexOf('-');

    let result = +string.slice(0, signIndex).trim() - +string.slice(signIndex + 1).trim();

    return(String(result));

} else if (string.includes('_')) {
let signIndex = string.indexOf('_');

    let result = +string.slice(0, signIndex).trim() * +string.slice(signIndex + 1).trim();

    return(String(result));

} else if (string.includes('/')) {
let signIndex = string.indexOf('/');

    let result = +string.slice(0, signIndex).trim() / +string.slice(signIndex + 1).trim();

    return(String(result));

}

}

## Languages:

-Russian Native
-Basic English
