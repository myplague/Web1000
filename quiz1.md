#Quiz 1

1. An angular directive is:
  1. The same thing as a Controller
  2. A way to define a custom element or attribute.
  3. A way to use ng-app
  4. A way for angular to communicate with a specific API

A way to define a custom element or attribute.


2. Write the JavaScript code necessary to create a controller named "PageController" which prints the string "hello world" as soon as the page loads and the controller runs.

app.controller("PageController", ['$scope', function($scope){
  console.log('hello wordl');
  }])



3. Given the following angular module declaration:

  ```JavaScript
  var app = angular.module("CookiesApp", ['ngRoute', 'ngAnimate']);
  ```
  How do you bind this angular module to a particular portion of your html page (for instance the body tag)?

 <body ng-app='CookiesApp'>


4. Run Euclid’s GCD algorithm for the following pairs of numbers. Show work.
  1.	10, 99
      99 10
      89 10......
      9  10
      10 9
      10 - 9 1

  2.	12, 128

      128 12
      116 12
      104 12
       92 12
       80 12
       68-12
       56-12
       44-12
       32-12
       20-12
       8-12
       12-8 4




  3.	65536, 1024
       64

  4.	24, 40
      8


  5.	58, 57
1

  6.	32, 48
      16


  7.	44, 121
      121 44
      77 44
      33 44
      44 33
      11



5.	Given two temperatures, return true if one is less than 0 and the other is greater than 100.
  a.	icyHot(120, -1) → true
  b.	icyHot(-1, 120) → true
  c.	icyHot(2, 120) → false


  function icyHot(t1,t2){
    if (t1 < 0 && t2 > 100 || t2 < 0  && t1 > 100){
      return true
    }
    else return false
  }

6.	Given 2 ints, a and b, return true if one if them is 10 or if their sum is 10.
  a.	makes10(9, 10) → true
  b.	makes10(9, 9) → false
  c.	makes10(1, 9) → true

function makes10(a,b){
  if (a = 10 && b = 10 || (a + b)==10 ){
    return true
  }
  else return false
}




7.	Given a string, take the first 2 chars and return the string with the 2 chars added at both the front and back, so "kitten" yields"kikittenki". If the string length is less than 2, use whatever chars are there.
  a.	front22("kitten") → "kikittenki"
  b.	front22("Ha") → "HaHaHa"
  c.	front22("abc") → "ababcab"


function front22(str){
  if (str.length < 2){
    return str.substring(0,2)+str+str.substring(0,2)
  } else
  return str+str+str

}






8. Solve https://codility.com/programmers/lessons/3-time_complexity/frog_jmp/
  Submit the screenshot of your solution after being put through the codility grader.

9. Solve https://codility.com/programmers/lessons/3-time_complexity/tape_equilibrium/
  Submit a screenshot of your solution after being put through the codility grader.
