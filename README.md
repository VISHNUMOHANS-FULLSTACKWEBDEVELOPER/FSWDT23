# FSWDT23
DAY23
Js day2 Array and objecs,non primitive datatypes
console.log("hello wrold");
VM131:1 hello wrold
undefined
age=21
21
console.log(age);
VM210:1 21
undefined
var name="vishnu";
undefined
console.log(name);
VM387:1 vishnu
undefined
var isyoung=true;
undefined
console.log(isyoung);
VM530:1 true
undefined
console.log("isyoung");
VM552:1 isyoung
undefined
console.log("is young",isyoung);
VM614:1 is young true
undefined
var stud=["abc", "vbn","klo"];
undefined
console.log(stud);
VM760:1 (3) ['abc', 'vbn', 'klo']
undefined
console.log(stud[0]);
VM857:1 abc
undefined
var objName={
    age=12,
VM918:2 Uncaught SyntaxError: Invalid shorthand property initializerUnderstand this error
var objName={
    age=12,name="abc",schoolcompleted="true"}
VM993:2 Uncaught SyntaxError: Invalid shorthand property initializerUnderstand this error
console.log(objName);
VM1074:1 Uncaught ReferenceError: objName is not defined
    at <anonymous>:1:13
(anonymous) @ VM1074:1Understand this error
var objName={
    age=12,name="abc",schoolcompleted="true"};
VM1080:2 Uncaught SyntaxError: Invalid shorthand property initializerUnderstand this error
var objName={
    age:12,name:"abc",schoolcompleted:true};
undefined
console.log(objNmae);
VM1177:1 Uncaught ReferenceError: objNmae is not defined
    at <anonymous>:1:13
(anonymous) @ VM1177:1Understand this error
console.log(objName);
VM1270:1 {age: 12, name: 'abc', schoolcompleted: true}
undefined
console.log(objNmae.age);
VM1300:1 Uncaught ReferenceError: objNmae is not defined
    at <anonymous>:1:13
(anonymous) @ VM1300:1Understand this error
console.log(objNmae.name);



VM1330:1 Uncaught ReferenceError: objNmae is not defined
    at <anonymous>:1:13
(anonymous) @ VM1330:1Understand this error
var objName={
    age:12,name:"abc",schoolcompleted:true};
undefined
console.log(objNmae.name);
VM1358:1 Uncaught ReferenceError: objNmae is not defined
    at <anonymous>:1:13
(anonymous) @ VM1358:1Understand this error
console.log(objName.name);
VM1368:1 abc
