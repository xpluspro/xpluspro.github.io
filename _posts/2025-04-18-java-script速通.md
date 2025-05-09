---
layout: post
title: 
date: 2025-04-18 09:02
category: 
author: 
tags: []
summary: 
---
## 事例
```js
>> console.log('hello world');
>> hello world
>> 2+2
>> 4
>> alert('hello world');
>> 弹窗“hello world”
```

## 变量和常量
```var const let```
- ```var``` 变量（可以在函数和外侧重复命名，此时两者不同）
- ```const``` 常量
- ```let``` 变量（在一个程序中只能有一个）

## 原生数据类型
- ```String```
- ```Number```
- ```null```
- ```boolean```
- ```undefined```

```js
const username="John";
const age=30;
const rate=4.5;
const isCool=true;
const x=null;
const y=undefined;
let z;(undefined)
```

可以认为每个变量有一个变量类型和一个变量内容

## 模板字符串
```js
const username = "John";
const age = 30;

// 连接
console.log("My name is " + username + " and I am age");
const hello = `My name is ${username} and I am ${age}`;
console.log(hello);
```

## 字符串的函数
```js
const s="hello world";
s.length
s.toUpperCase
s.toLowerCase
s.substring(0,4) "hell"  (参考py)
s.split("") 返回一数组，目前是一个字符一切
s.split(",")
```

## 数组
Array和Object都是引用类型，当用const声明数组和对象时，const生命的常量保存的仅仅是指针，这就意味着只要保证数组和对象的指针不发生改变，修改其中的值是允许的。
```js
const numbers = new Array(1,2,3,4,5);
const fruits = ["apples","oranges","pears",10,true];
fruits[5]="grape";
print(fruits)
>> ["apples","oranges","pears",10,true,"grape"]
fruit.push("222");
fruit.unshift("111");
fruit.pop();
```