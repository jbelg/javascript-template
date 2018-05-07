# Assignment vs Comparison


This is not only a common mistake, but understanding this is very important ot understanding how variables work.

```js
let a = 4
if (a = 2) {
    console.log(a)
}

if (a == 2) {
    console.log(a)
}


```


[PythonTutor Link](https://goo.gl/oZutMd)

---



## Step 1

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
* __Global Context__
  * _Primitives_  
    a. a: 4


nailed it

---


## Step N

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
+ error

__Actual Happenings:__
* __Global Context__
  * _Primitives_  
    a. a: 2

So wrong.  in this step JS redefined the variable a from 4 to 2.  this happened because js will execute whatever code is in the for statement
in this case, that was "a = 2" which reassigns a to the value 2

---


## Step N

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
* __Global Context__
  * _Primitives_  
    a. a: 2

the console will log "a = 2".

got it

---


## Step N

Be sure to completely fill out your predictions before clicking to the next step in Python tutor.  Committing to your prediction and being forced to see when you're wrong will help you learn faster, and strengthen your ability to read and understand code.

__Predicted Happenings:__
* __Global Context__
  * _Primitives_  
    a. a: 2

i think it will enter the for statement, but not sure why.

got it.  it entered because "==" is a comparison, it checks if the value of a is equal to the value of 2.  it is, so we enter the for


---

then it console logs 2.  done
___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>











