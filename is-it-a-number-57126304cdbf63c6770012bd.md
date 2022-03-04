# Solutions for "Is it a number?"

> Kata Link: [Is it a number?](https://www.codewars.com/kata/57126304cdbf63c6770012bd)

<details open>
<summary>JavaScript</summary>
<p>

Readable Solution:
```js
function isDigit(string) {
    if (string.trim('') === '') return false;
    return string == Number(string);
}
```

Short Solution:
```js
const isDigit = s => !!s.trim`` && s == +s;
```

</p>
</details>
