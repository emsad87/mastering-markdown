# Mastering Markdown h1

```md
# Mastering Markdown h1
```

## Mastering Markdown h2

```md
## Mastering Markdown h2
```

### Mastering Markdown h3

```md
### Mastering Markdown h3
```

#### Mastering Markdown h4

```md
#### Mastering Markdown h4
```

##### Mastering Markdown h5

```md
##### Mastering Markdown h5
```

###### Mastering Markdown h6

```md
###### Mastering Markdown h6
```

---

## Italic

Some _italic_ tekst

```md
Some _italic_ tekst
```

---

## Bold

Some **bold** tekst

```md
Some **bold** tekst
```

---

## Strikethrough

Some ~~Strikethrough~~ tekst

```md
Some ~~Strikethrough~~ tekst
```

---

## Links

[This is a link](https://emsad87.github.io/ "This is a link")

```md
[This is a link](https://emsad87.github.io/ "This is a link")
```

[This is a link separated][1]

```md
[This is a link separated][1]

[1]: https://emsad87.github.io/
```

---

## Images

Image with "alt" and "title"

![Emsad Image](https://emsad87.github.io/img/emsad/emsad3.jpg "Emsad")

```md
![Emsad Image](https://emsad87.github.io/img/emsad/emsad3.jpg "Emsad")
```

Image with separated source link

![Emsad Image][emsad]

```md
![Emsad Image][emsad]

[emsad]: https://emsad87.github.io/img/emsad/emsad3.jpg
```

Image with HTML tags

<img src="https://emsad87.github.io/img/emsad/emsad3.jpg">

```md
<img src="https://emsad87.github.io/img/emsad/emsad3.jpg">
```

Styling Images with css or inline

```html
<style>
  img {
    width: 200px;
  }
</style>

<img width="200px" src="https://emsad87.github.io/img/emsad/emsad3.jpg" />

<img
  style="width: 200px;"
  src="https://emsad87.github.io/img/emsad/emsad3.jpg"
/>
```

---

## Lists

Undordered list

- item1
  - item1
- item2
  - item2
  - item2
- item3

```md
- item1
  - item1
- item2
  - item2
  - item2
- item3
```

Ordered list

1. item1
   1. item1 item1
1. item2
   1. item2 item2
   1. item2 item2
1. item3

```md
1. item1
   1. item1 item1
1. item2
   1. item2 item2
   1. item2 item2
1. item3
```

---

## Linek Breaks

Some tekst<br>
some more tekst on next line

```md
Some tekst<br>
some more tekst on next line
```

## Horizontal lines

Bellow is a horizontal line

---

Above is a horizontal line

```md
Bellow is a horizontal line

---

Above is a horizontal line
```

## Block Quotes

> This is some quote, just about quotes in markdown.
>
> – _Emsad_

```md
> This is some quote, just about quotes in markdown.
>
> – _Emsad_
```

## Code Blocks

Some code example:

```js
var x = 100;
const dog = "Snoop Dogg";
```

````md
    ```js
    var x = 100;
    const dog = "Snoop Dogg";
    ```
````

Some inline `const 2Pac = "4ever"` code.

```md
Some inline `const 2Pac = "4ever"` code.
```

Using diff to show changes like in github

```diff
var x = 100;
- const dog = "Snoop Dogg";
+ const 2Pac = "4ever";
```

````md
    ```diff
    var x = 100;
    - const dog = "Snoop Dogg";
    + const 2Pac = "4ever";
    ```
````

## Table

| Article | Amount |
| :-----: | -----: |
| Banana  |      2 |
|  Grape  |      4 |
|  Apple  |      1 |

```md
| Article | Amount |
| :-----: | -----: |
| Banana  |      2 |
|  Grape  |      4 |
|  Apple  |      1 |
```

## Checkbox

- [ ] Sleep
- [ ] Drink water
- [x] Be positive

<style>
img{
    width: 200px;
}
</style>

[1]: https://emsad87.github.io/
[emsad]: https://emsad87.github.io/img/emsad/emsad3.jpg
