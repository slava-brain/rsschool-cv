# Viachaslau Liutkevich

## Contacts
   * Location: Grodno, Belarus
   * Phone: +375 (29) 88-55-235
   * E-mail: slava.lyutkevich8308@gmail.com
   * GitHub: [js-react-developer](https://github.com/js-react-developer)
   * Telegram: [Slava Lyutkevich](https://t.me/BrainBelarus)

## About me
I am actively studying HTML, CSS and JavaScript. I easily find common ground in an unfamiliar situation. I am striving to get a position of **Junior JavaScript Developer**.

## Skills
* HTML5, CSS3, SASS, JavaScript, PHP
* React, Redux
* SQL, Node.js
* Wordpress, 1C-Bitrix, Drupal
* Git, Github

## Code Example
**Task description**: Return the number (count) of vowels in the given string. We will consider *a*, *e*, *i*, *o*, *u* as vowels for this Kata (but not y*). The input string will only consist of lower case letters and/or spaces.

**Solution**
```
function getCount(str) {
  var vowelsCount = 0;
  str = str.split(' ').join('');
  for (var i = 0; i < str.length; i++){
    if ('aeiou'.includes(str[i])){
      vowelsCount++;
    }
  }
  return vowelsCount;
}
```