## Return Negative

function makeNegative(num) {
if (Math.sign(num)=== 1){
num = num \*= -1
}else{
''
}
return num
// Code?
}

## Sum of Positive

function positiveSum(arr) {
let sum = 0
arr.forEach(r=>{
if(Math.sign(r) === 1){
sum += r
}else{
''
}
})
return sum
}

## Function 2

function square (){

let num = arguments[0]
let ans = num \* num
return ans
}

## Sum Arrays

function sum (numbers) {
"use strict";
let sum = 0
if (numbers.length > 0){
numbers.forEach(n =>{
sum += n
})
}
return sum
};

## Reversed Strings

function solution(str){
let newStr = ''
for(let i = str.length-1; i > -1; i--){
newStr += str[i]
}
return newStr
}
