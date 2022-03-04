# Solutions for "Who likes it?"

> Kata Link: [Who likes it?](https://www.codewars.com/kata/5266876b8f4bf2da9b000362)

<details open>
<summary>JavaScript</summary>
<p>

```js
function likes(names) {
    const result = {
        0: ['no one likes this'],
        1: [`${names[0]} likes this`],
        2: [`${names[0]} and ${names[1]} like this`],
        3: [`${names[0]}, ${names[1]} and ${names[2]} like this`],
        4: [`${names[0]}, ${names[1]} and ${(names.length - 2)} others like this`]
    };

    return result[Math.min(names.length, 4)].join('');
}
```

</p>
</details>
