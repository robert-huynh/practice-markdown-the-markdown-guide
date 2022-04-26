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

## Heading IDs

- Markdown:

#### My Great Heading {#heading-4}

### Linking to Heading IDs

- Markdown:

[Go to heading 4 section](#heading-4)

## Definition Lists

- Markdown:

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Strikethrough

- Markdown (~~):

The world is ~~flat~~ round

## Task Lists

- Markdown ([x]):

- [x] Write the press release
- [] Update the website
- [] Contact the media

## Automatic URL linking

- Markdown:

http://example.com

### Disable Automatic URL linking

- Markdown:

`http://example.com`


