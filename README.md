
# <h1> Lead Liaison Task </h1>

> By: **Ahmed Zakaria**

### About


### Technologies
-React JS
-Ecma
-Scss
-Github

### Library
google-maps-react

### Handel carousel in 3 screens
I collect all numbers that control in the carousel in state of array and setState in every screen
 Markup : * pc screen :  setScreenLmts([2, 6, 2, 3, 0])
          * tab screen : setScreenLmts([1, 4, 1, 2, 0])
          * phone screen :  setScreenLmts([0, 2, 0, 1, 0])
          
screenLmts       | Explanation
-------------    | -------------
screenLmts[0,2]  | number of items in one slide - 1
screenLmts[1]    | number of items in one slide * 2
screenLmts[3]    | number of items in one slide 
screenLmts[4]    | index of 1st item in list as all

### To start project on web server 
npm start

