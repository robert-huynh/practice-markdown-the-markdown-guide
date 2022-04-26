# Extended Syntax

## Table

- Markdown (Add 3 or more hyphen): 

| Syntax    | Description |
| ---       | ---         |
| Header    | Title       |
| Paragraph | Text        |

## Alignment

- Markdown:

| Syntax    | Description | Test Text   |
| :---      | :---:       | ---:        |
| Header    | Title       | Here's this |
| Paragraph | Text        | And more    |

## Fenced Code Blocks

- Markdown (use ``` or ~~~):

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Syntax Highlighting

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Footnotes

- Markdown:

Here's a simple footnote, [^1] and here's a longer one. [^bignote]

[^1]: This is the first footnote.
[^bignote]: Here's one with multiple paragraph and code.
  Indent paragraph to include them in the footnote.
  `{ my code }`
  Add as many paragraph as you like.