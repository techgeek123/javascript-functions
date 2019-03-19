# Releases


## Release0:

1. What is the output?
```js
(function () {
    var test = 5;

    if (false) {
        test = 7;
    } else {
        console.log(test + 2);
    }
}());
```
2. What is the output? Is `test` global?
```
(function () {
    test = 5;

    if (false) {
        var test;
    } else {
        console.log(test + 2);
    }
}());
```
3. What is the output? Will it error and break? Is `test` defined?
```js
(function () {
    if (false) {
        var test = 3;
    } else {
        console.log(test + 2);
    }
}());
```
4. What is the output? Is `one` defined? Will it error? Or is it one of these digits: 3, 4, 5, or 6?

```js
(function () {
    test = 5;

    if (false) {
        var test = 3;
    } else {
        console.log(one(test));
    }

    function one(value) {
        return value + 1;
    }
}());
```