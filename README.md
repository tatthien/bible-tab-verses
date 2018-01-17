Bible verses storage for Bible Tab extension

# How to contribute

1. Clone this project.

```
git clone https://github.com/tatthien/bible-tab-verses.git
```

2. Add your verse follow this syntax

```js
{
    "content": {
      "vi": "Vietnamese content",
      "en": "English content"
    },
    "book": {
      "vi": "Vietnamese book name",
      "en": "English book name"
    },
    "code": "Book code",
    "chapter": "chapter number",
    "verse": "verse number"
}
```

Notes:

- `content`: Use VB1925 for Vietnamese and NIV for English. All versions can be found at [bible.com/bible](bible.com/bible).
- `code`: Please use the code standard of [bible.com/bible](bible.com/bible).

Example:

```js
{
    "content": {
      "vi": "Ban đầu Đức Chúa Trời dựng nên trời đất.",
      "en": "In the beginning God created the heavens and the earth. "
    },
    "book": {
      "vi": "Sáng-thế Ký",
      "en": "Genesis"
    },
    "code": "GEN",
    "chapter": "1",
    "verse": "1"
}
```

3. Create a PR.

PR title convention.

`[WIP] book-name.chapter.verse`

Example: `[WIP] Genesis.1.1`

4. Your PR will be reviewed and merged.
