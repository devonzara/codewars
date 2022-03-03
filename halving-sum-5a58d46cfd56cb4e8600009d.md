# Solutions for "Halving Sum"

> Kata Link: [Halving Sum](https://www.codewars.com/kata/5a58d46cfd56cb4e8600009d)

<details open>
<summary>JavaScript</summary>
<p>

```js
function halvingSum(integer) {
    if (integer === 1) return 1;
    return integer + halvingSum(parseInt(integer / 2));
}
```

</p>
</details>
