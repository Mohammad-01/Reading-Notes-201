![fig1](https://i.ytimg.com/vi/k8yJCeuP6I8/maxresdefault.jpg)

## What is localStorage in JavaScript?
* localStorage is a feature that allows JavaScript sites and apps to save key-value pairs in a web browser without having to worry about them expiring. This means that the data stored in the browser will survive the closing of the browser window.

## How to save localStorage?
* After the browser has been restarted, any content/data stored to the localStorage object will be available (closed and opened again). SetItem() is a method that can be used to save an item to localStorage. A key and a value must be passed to this method.

## Is it possible to hack local storage?
* If an attacker is able to run JavaScript on your website, they will be able to access all of the data you've saved in local storage and send it to their own domain. This means that everything sensitive you have in local storage (such as a user's session data) is vulnerable.

## localStorage methods: 

To use localStorage in your web applications, there are five    methods to choose from:

1- setItem(): Add key and value to localStorage

2- getItem(): This is how you get items from localStorage

3- removeItem(): Remove an item by key from localStorage

4- clear(): Clear all localStorage

5- key(): Passed a number to retrieve the key of a localStorage

## Is localStorage (API)?
* The Web Storage API adds two new properties to the Window object: Window. sessionStorage and Window. localStorage, which provide you access to the current domain's session and local Storage objects, respectively, as well as a Window. localStorage property.