# Function.prototype.call

This is an important concept for functional programming and for reusing functions in different use cases.  
"Call" is a tricky method, but once I get it I'll really get execution contexts.  Very important.

```js
function contexting() {
  console.log(this)
  console.log(this.name) 
}

let marta_context = {
  name: "marta"
}

let jake_context = {
  name: "jake"
}

contexting()
contexting.call(marta_context)
contexting.call(jake_context)

```


[PythonTutor Link](https://goo.gl/DEh5xt)

---


## Step 1

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
* __Global Context__
  * _Objects_  
    a. contexting: Function
    b. marta_context: Object


I was right.

---


## Step 2


__Predicted Happenings:__
* __Global Context__
  * _Objects_  
    a. contexting: Function
    b. marta_context: Object
    c. jake_context: Object


we were right

---


## Step 3

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
* __Global Context__
  * _Objects_  
    a. contexting: Function
    b. marta_context: Object
    c. jake_context: Object
* __contexting context:__
  * no variables

i  was right

---

## Step 4

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
+ ERROR: "this" has not been declared

__Actual Happenings:__
* __Global Context__
  * _Objects_  
    a. contexting: Function
    b. marta_context: Object
    c. jake_context: Object
* __contexting context:__
  * no variables

I was partly right.  "this"is undefined, but it didn't give an error.  It just console logged undefined.

---

## Step 5

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
+ ERROR: cannot find name of undefined

__Actual Happenings:__
+ TypeError: Cannot read property 'name' of undefined 

I got it right. not the right wording, but close enough.  
next time i see this error i will know the problem is with the variable on the left, not on the right

---

edited code to comment out the "contexting()" line so i can go past the error

---

## New step 4

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
* __Global Context__
  * _Objects_  
    a. contexting: Function
    b. marta_context: Object
    c. jake_context: Object
* __contexting context:__
  * empty


__Actual Happenings:__
* __Global Context__
  * _Objects_  
    a. contexting: Function
    b. marta_context: Object
    c. jake_context: Object
* __contexting context:__
  * this: Object with "marta" name

...

---


## Step N

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
* __Global Context__
  * _Primitives_  
    a. 
  * _Objects_  
    a.
* __Other Contexts__
  * _Primitives_  
    a. 
  * _Objects_  
    a.

__Actual Happenings:__
* __Global Context__
  * _Primitives_  
    a. 
  * _Objects_  
    a.
* __Other Contexts__
  * _Primitives_  
    a.   
  * _Objects_  
    a.

Description of what happened in this step, and how well you predicted it.  This is your space to describe anything that happened but doesn't fall into the bulleted categories.







___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>











