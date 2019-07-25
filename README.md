# Learn wix-code

#### Description

This is a guide for a beginner to learn wix code. This article will focus more on the javascript side than wix. this article is targeted for intermediate wix user with no or less programming knowledge who are interested to learn wix code.

Section is split into :

### 1. Javascript

> - part 1 : Understanding Syntax
> - on this part you will need to focus more on the memory than logic
> - you will need memorize syntax, basic rule and code execution in theory

> - part 2 : ES6 way
> - on this part you will be learning modern(short) way of writing code
> - Do not skip this part without learning "Promise"
> - Spend as much as you can on "Promise"

> - part 3 : Technique and Debugging
> - on this part you will be learning to use chrome developer tools
> - Debouncer and Throttling
> - Leverage of external API

### 2. Wix code

> - Part 1: Wix code using setting
> - Learn to connect with dataset setting there is so much you can just by selecting the options
> - Connect Form, Database, Index page, Dynamic page without using code

> - Part 2 : Wix code using javascript
> - Connect Form, Database, Index page, Dynamic page using code
> - Create filter, calculator application

###

---

## Javascript

## _Part 1 : Syntax and theory_

This is the very basic feature, you need to be strong at this before you start part 2

### 1. Variable

- `var, let and const` when and how to use

- Mutation, Hoisting, Scope
- https://dev.to/sarah-chima/var-let-and-const--whats-the-difference-69e

### 2. Function types

- `declaration, anonymous, arrow and expression function`

- learn more about here : https://dmitripavlutin.com/6-ways-to-declare-javascript-functions/

- lear use case of different type function

### 3. Datatype 1

- `sting, number, boolean, date, undefined, null, Object, Array and Date`

- learn `typeof` keyword during this session
- Learn syntax of object and array

### 4. Condition 1

- if/else, switch statement

### 5. Loop 1

- `for` -loop, `while` loop

### 6. Scope, event loop, synchronous and asynchronous

- This is a theory part, learn more about the execution of the code , it will help in writing a optimized code
- Best way to learn is to watch this video, they will show graphical representation of event loop
- What the heck is the event loop anyway? | Philip Roberts | JSConf EU
  https://www.youtube.com/watch?v=8aGhZQkoFbQ
- Jake Archibald: In The Loop - JSConf.Asia 2018
  https://www.youtube.com/watch?v=cCOL7MC4Pl0

## _Part 2 : ES6 way_

part 2 will cover ES6 way of writing JS like forEach, reduce and also this will introduce to Object and array

### 1. Datatype 2

- (Date)
- Know about the DATE UTC and local time zone
- Learn how to set/get date and time
- Learn to remove timezone and add a different time zone

### 2. Loop 2 High-Order function

- (forEach, filter, map, reduce, sort, every) for Array
- (keys, hasPrototype) for Object

### 3. Condition 2

- ternary operator, spread operator, increment ++, ||, &&
- links : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions-and-Operators

```
let name = undefined || "Salman";
console.log(name); // Salman
```

### 4. Promise

- resolve and reject
- Async and await to resolve promise
- try and catch syntax
- Promise.All

## _Part 3: Debugging and technique_

- Working of deboucer and throttling expained
- Break points, Call stack and event loop using http://latentflip.com/loupe/
- wix code on the live site, how to debug the live site

---

## Wix Code

## _Part 1: Wix code using setting_

### 1. Where to write code

- Different place to write the code : Page, Site, Backend, Public
- Import/export code from different region
- learn in detail for Page and Site

### 2. Database Manipulation

- Article link: https://www.wix.com/corvid/reference/wix-data.html
- WixData insert, update, delete, Options
- Hidden columns \_id, \_owner, \_createdDate, \_updatedDate
- Datatype for string, number, gallery, image and video

### 3. Play with wix elements

- Article link : https://www.wix.com/corvid/reference/$w.html
- how to use user element and event trigger
- Connect the wix element with the dataset element and submit a form
- Dataset filter and sort

### 4. Repeater and Pagination

- Article Repeater: https://www.wix.com/corvid/reference/$w.Repeater.html
- Article Pagination: https://www.wix.com/corvid/reference/$w.Pagination.html
- Connect the repeater to the dataset and dynamic page

## _Part 2 : Wix code using javascript_

### 1. Where to write code 2

- Different place to write the code : Page, Site, Backend, Public
- Import/export code from different region

### 2. Database Manipulation 2

- WixData hook
- Dataset how to use .onBeforeSave, .onAfterSave, .setFieldValue
- Filter the dataset element

### 3. Play with wix elements 2

- debouncer on key press, dropdown change
- Create a simple Multiplication Calculator
- Use code to manipulate the elements

### 4. Repeater and Pagination 2

- Connect the repeater using code .data
- Connect the pagination using code
- use .onItemReady(), .forItems(), .forEachItem()



