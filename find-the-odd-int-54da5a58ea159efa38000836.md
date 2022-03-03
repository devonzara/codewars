# Solutions to "Find the odd int"

> Kata Link: [Find the odd int](https://www.codewars.com/kata/54da5a58ea159efa38000836)

<details open>
<summary>JavaScript</summary>
<p>

```js
function findOdd(array) {
    const map = {};
    array.forEach(i => map[i] ? delete map[i] : map[i] = 1);
    return parseInt(Object.keys(map)[0]);
}
```

</p>
</details>
