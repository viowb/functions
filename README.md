const Person = require('./classes')

var greet = "Morning"

function add(a,b)
{
    return a+b
}
let sum =add(2,3)
console.log(sum)
//alternatively assign directly as Anonymous function and assign to variables. Minimise the code

let sumOfIntegers = function(c,d)
{
    return c+d
}

let sumOfNumbers= (c,d)=> c+d //fat pipe shorthand operator
//console.log(sumOfNumbers)
console.log(sumOfNumbers(2,3))
console.log(greet)

//for that class you are requiring from another file, you have to create a new object and concactinate the fullname method
let person =new Person("Russ", "Bank")
console.log(person.fullName())
