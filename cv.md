# **MARGARITA DOVGIALLO**

## __Contacts__
- __Location:__ Saint Petersburg, Russia
- __Phone:__ +7&#8209;(953)&#8209;367&#8209;53&#8209;83
- __Email:__ margaridiv@mail.ru
- __GitHub:__ [https://github.com/Reria](https://github.com/Reria)

## __About me__
I am a lawyer by education. For several years I worked as a legal adviser at a large system-forming industrial enterprise in St. Petersburg.  
I am currently studying to become a frontend developer, because I want to do creative tasks more.  
The experience of law has strengthened my communication skills, teamwork skills, taught me to understand the specifics of the activities and document flow of companies,  
as well as to approach the details carefully.

## __Skills__
- HTML
- CSS
- JavaScript (basic)
- Git
- Figma (start)

## __Code example__
Task: "The main idea is to count all the occurring characters in a string.  
If you have a string like aba, then the result should be {'a': 2, 'b': 1}. What if the string is empty?  
Then the result should be empty object literal, {}."
```javascript
function count(string) {
  let obj = {};
  let a = string.split('');
  a.forEach(function(item, index, array) {
    if (item in obj) {
      obj[item] += 1;
    } else {
      obj[item] = 1;
    }
  });
  return obj;
}