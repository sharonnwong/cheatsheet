# javascript

In javascript, variables don't have to be 'typed'
But they still have a type

- Boolean: true/false
- String: 'hello'
- Integer/Float: 10/10.1
- Array: []
- Object: {}
- Function


### function

function adder(a, b){
    return a+b
}

adder(2,3) // return 5

// This is the exact same thing
var adder = (a,b) => a+b
var adder = (a,b) => (a+b)

// asynchronous functions
async function(){
    // use 'await' in here
}


### arrays

var a = [1,2,3]
a[0] // 1

// loop
a.map((item,index)) =>{
    console.log(item,index)
}

// return a new array that is filtered by the condition
a.filter((item,index)) => {
    return item>1
}

// sort (return a number)
a.sort((item1,item2) => item1-item2)

### object

var obj = {
    hi: 'hello',
    num: 7,
    child:{
        name: 'Evna',
        age: 31,
        sayHi:function(){
            console.log('hi')
        }
    }
}

obj.child.sayHi()
obj['child']['sayHi']()


### if statement
if (2>1){
    console.log("yes! math is real")
}