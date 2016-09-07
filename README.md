# MarkDown Basics
---------------

### HEADERS, PARAGRAPHS, BLOCKQUOTES

Markdown offers two styles of `headers`: *`Setext`* and *`atx`*.

`Setext-style` headers for `<h1>` and `<h2>` are created by "underlining" with equal signs (`=`) and hyphens (`-`), respectively.

    A First Level Header
    ====================

    A Second Level Header
    ---------------------

To create an `atx-style` header, you put 1-6 hash marks (`#`) at the beginning of the line -- the number of hashes equals the resulting HTML header level.

    ### Third header
    ...
    ###### Sixth header

`<p></p>` A `paragraph` is simply one or more consecutive lines of text, separated by one or more blank lines. (A blank line is any line that looks like a blank line — a line containing nothing but spaces or tabs is considered blank.) Normal paragraphs should not be indented with spaces or tabs.

    The quick brown fox jumped over the lazy dog's back.

`Blockquotes` are indicated using email-style '`>`' angle brackets.

    > This is a blockquote.
    >
    > This is the second paragraph in the blockquote.
    >
    > ## This is an H2 in a blockquote

### PHRASE EMPHASIS

Markdown uses `asterisks (*)` and `underscores (_)` to indicate spans of emphasis.

`italic`

    Some of these words *are emphasized*.
    Some of these words _are emphasized also_.

`bold`

    Use two asterisks for **strong emphasis**.
    Or, if you prefer, __use two underscores instead__.

### LISTS

`Unordered (bulleted)` lists use asterisks, pluses, and hyphens (`*`, `+`, and `-`) as list markers. These three markers are interchangable; this:

    *   Candy.
    *   Gum.

this:

    +   Candy.
    +   Gum.

and this:

    -   Candy.
    -   Gum.

`Ordered (numbered)` lists use regular numbers, followed by periods, as list markers:

    1.  Red
    2.  Green
    3.  Blue

If you put `blank lines between items`, you'll get `<p>` tags for the
list item text. You can create `multi-paragraph list items` by indenting
the paragraphs by 4 spaces or 1 tab:

    *   A list item.

        With multiple paragraphs.

    *   Another item in the list.



http://daringfireball.net/projects/markdown/
