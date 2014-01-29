underscore
==========

20 examples of underscore


ONE 

family
[
Object
age: 49
gender: "male"
name: "chuckie"
__proto__: Object
, 
Object
age: 44
gender: "female"
name: "elizabeth"
__proto__: Object
, 
Object
age: 8
gender: "female"
name: "summer"
__proto__: Object
]
_.pluck(family, name)
[undefined, undefined, undefined]
_.pluck(family, 'name')
["chuckie", "elizabeth", "summer"]
_.pluck(family, age)
ReferenceError: age is not defined
_.pluck(family, 'age')
[49, 44, 8]
_.pluck(family, 'gender')
["male", "female", "female"]


TWO

