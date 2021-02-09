# _Pig Latin_

#### _A simple web application to translate to Pig Latin_

#### By _**HR Williams**_

## Technologies Used

* _HTML_
* _CSS_
* _JavaScript_
* _jQuery_

## Description

_This is an assignment for Epicodus to practice new skills in TDD and JavaScript Looping. It is a simple program where a user can enter words and they will be translated in to Pig Latin_

## Setup/Installation Requirements

* _clone this repository to your desktop_
* _navigate to the top level of the directory_
* _open index.html in web browser_

## Tests

**Describe: `pigLatin()`** <br>
Test: "It will add 'way' to the end of words that begin with a vowel"
Expect(pigLatin("a")).toEqual("away");

Test: "For words beginning with a consenant it will move consenant + add ay to the end" <br>
Expect(pigLatin(be)).toEqual("ebay);

Test: "For words beginning with 2 or more consenants it will move consenants + ay to the end" <br>
Expect(pigLatin(chad)).toEqual("adchay");

Test: "For words with first consonants including 'qu' it will move consenants and u + ay to the end" <br>
Expect(pigLatin(quilt)).toEqual("iltquay");

Test: "For words with first consonants including other consenants + 'qu' it will move consenants and u + ay to the end" <br>
Expect(pigLatin(squab)).toEqual("absquay");

## Known Bugs

* _{Example: I would like to add more styling}_

## License

_[MIT](https://choosealicense.com/licenses/mit/)_

Copyright (c) 2021 HR Williams

## Contact Information

HR Williams <williams.hr@gmail.com>