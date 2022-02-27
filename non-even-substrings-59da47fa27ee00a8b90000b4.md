# Solutions to "Non-even substrings"

> Kata Link: [Non-even substrings](https://www.codewars.com/kata/59da47fa27ee00a8b90000b4)

<details open>
<summary>JavaScript</summary>
<p>

```js
function solve(string) {
    return [...string].reduce((count, number, index) => {
        return count + number % 2 * ++index;
    }, 0);
}
```

</p>
</details>
