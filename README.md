Bible verses storage for Bible Tab extension

*If you are not a developer, I encourage you to use this Google Form http://bit.ly/2DhznDb to add verses.*

# How to contribute

### 1 Clone this project.

```
git clone https://github.com/tatthien/bible-tab-verses.git
```

### 2 Add your verse follow this syntax.

```js
{
    "content": {
      "vi": "Vietnamese content",
      "en": "English content"
    },
    "code": "Book code",
    "chapter": "chapter number",
    "verse": "verse number"
}
```

Notes:

- `content`: Use VB1925 for Vietnamese and NIV for English. All versions can be found at [bible.com/bible](bible.com/bible).
- `code`: Please use the code standard [here](https://github.com/tatthien/bible-tab/blob/master/src/map.js).

Example:

```js
{
    "content": {
      "vi": "Ban đầu Đức Chúa Trời dựng nên trời đất.",
      "en": "In the beginning God created the heavens and the earth. "
    },
    "code": "gen",
    "chapter": "1",
    "verse": "1"
}
```

### 3 Create a PR.

PR title convention: `[WIP] book-name.chapter.verse`

Example: `[WIP] Genesis.1.1`

### 4 Your PR will be reviewed and merged.
