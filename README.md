# MarkDown Basics
<!-- --------------- -->

## Headers, Paragraphs, Blockquotes
----------------------------------

Markdown offers two styles of __`headers`__: *`Setext`* and *`atx`*.

`Setext-style` headers for `<h1>` and `<h2>` are created by "underlining" with equal signs (`=`) and hyphens (`-`), respectively.

    A First Level Header
    ====================

    A Second Level Header
    ---------------------

To create an `atx-style` header, you put 1-6 hash marks (`#`) at the beginning of the line -- the number of hashes equals the resulting HTML header level.

    ### Third header
    ...
    ###### Sixth header

`<p></p>` A __`paragraph`__ is simply one or more consecutive lines of text, separated by one or more blank lines. (A blank line is any line that looks like a blank line — a line containing nothing but spaces or tabs is considered blank.) Normal paragraphs should not be indented with spaces or tabs.

    The quick brown fox jumped over the lazy dog's back.

__`Blockquotes`__ are indicated using email-style '`>`' angle brackets.

    > This is a blockquote.
    >
    > This is the second paragraph in the blockquote.
    >
    > ## This is an H2 in a blockquote


## Phrase Emphasis
----------------------------------


Markdown uses `asterisks (*)` and `underscores (_)` to indicate spans of emphasis.

__`italic`__

    Some of these words *are emphasized*.
    Some of these words _are emphasized also_.

__`bold`__

    Use two asterisks for **strong emphasis**.
    Or, if you prefer, __use two underscores instead__.

## Lists
----------------------------------


__`Unordered`__ (bulleted) lists use asterisks, pluses, and hyphens (`*`, `+`, and `-`) as list markers. These three markers are interchangable; this:

    *   Candy.
    *   Gum.

this:

    +   Candy.
    +   Gum.

and this:

    -   Candy.
    -   Gum.

__`Ordered`__ (numbered) lists use regular numbers, followed by periods, as list markers:

    1.  Red
    2.  Green
    3.  Blue

If you put _blank lines between items_, you'll get `<p>` tags for the list item text. You can create __multi-paragraph list items__ by indenting the paragraphs by 4 spaces or 1 tab:

    *   A list item.

        With multiple paragraphs.

    *   Another item in the list.

## Links
----------------------------------

Markdown supports two styles for creating links: *inline* and *reference*. With both styles, you use square brackets to delimit the text you want to turn into a link.

__Inline-style links__ use parentheses immediately after the link text.
For example:

    This is an [example link](http://example.com/).

Optionally, you may include a _**title**_ attribute in the parentheses:

    This is an [example link](http://example.com/ "With a Title").

__Reference-style links__ allow you to refer to your links by names, which you define elsewhere in your document:

    I get 10 times more traffic from [Google][1] than from
    [Yahoo][2] or [MSN][3].

    [1]: http://google.com/        "Google"
    [2]: http://search.yahoo.com/  "Yahoo Search"
    [3]: http://search.msn.com/    "MSN Search"

The _title_ attribute is optional. Link names may contain letters, numbers and spaces, but are *not* case sensitive:

    I start my morning with a cup of coffee and
    [The New York Times][NY Times].

    [ny times]: http://www.nytimes.com/








Source from [here](http://daringfireball.net/projects/markdown/).
