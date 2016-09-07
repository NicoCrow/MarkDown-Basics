# MarkDown Basics #
<!-- --------------- -->

*  [Headers, Paragraphs, Blockquotes](#headers-paragraphs-blockquotes)
*  [Phrase Emphasis](#phrase-emphasis)
*  [Lists](#lists)
*  [Links](#links)
*  [Images](#images)
*  [Code](#code)

## Headers, Paragraphs, Blockquotes ##
<!-- ---------------------------------- -->

Markdown offers two styles of __headers__: *`Setext`* and *`atx`*.

`Setext-style` headers for `<h1>` and `<h2>` are created by "underlining" with equal signs (`=`) and hyphens (`-`), respectively.

    A First Level Header
    ====================

    A Second Level Header
    ---------------------

To create an `atx-style` header, you put 1-6 hash marks (`#`) at the beginning of the line -- the number of hashes equals the resulting HTML header level.

    ### Third header ###
    ...
    ###### Sixth header ######

`<p></p>` A __paragraph__ is simply one or more consecutive lines of text, separated by one or more blank lines. (A blank line is any line that looks like a blank line — a line containing nothing but spaces or tabs is considered blank.) Normal paragraphs should not be indented with spaces or tabs.

    The quick brown fox jumped over the lazy dog's back.

__Blockquotes__ are indicated using email-style '`>`' angle brackets.

    > This is a blockquote.
    >
    > This is the second paragraph in the blockquote.
    >
    > ## This is an H2 in a blockquote


## Phrase Emphasis ##
<!-- ---------------------------------- -->


Markdown uses `asterisks (*)` and `underscores (_)` to indicate spans of emphasis.

__italic__

    Some of these words *are emphasized*.
    Some of these words _are emphasized also_.

__bold__

    Use two asterisks for **strong emphasis**.
    Or, if you prefer, __use two underscores instead__.

## Lists ##
<!-- ---------------------------------- -->


__Unordered__ (bulleted) lists use asterisks, pluses, and hyphens (`*`, `+`, and `-`) as list markers. These three markers are interchangable; this:

    *   Candy.
    *   Gum.

this:

    +   Candy.
    +   Gum.

and this:

    -   Candy.
    -   Gum.

__Ordered__ (numbered) lists use regular numbers, followed by periods, as list markers:

    1.  Red
    2.  Green
    3.  Blue

If you put _blank lines between items_, you'll get `<p>` tags for the list item text. You can create __multi-paragraph list items__ by indenting the paragraphs by 4 spaces or 1 tab:

    *   A list item.

        With multiple paragraphs.

    *   Another item in the list.

## Links ##
<!-- ---------------------------------- -->

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

## Images ##
<!-- ---------------------------------- -->

Image syntax is very much like link syntax.

Inline (titles are optional):

    ![alt text](/path/to/img.jpg "Title")

Reference-style:

    ![alt text][id]

    [id]: /path/to/img.jpg "Title"

## Code ##
<!-- ---------------------------------- -->


In a regular paragraph, you can create code span by wrapping text in backtick quotes. Any ampersands (`&`) and angle brackets (`<` or `>`) will automatically be translated into HTML entities. This makes it easy to use Markdown to write about HTML example code:

    I strongly recommend against using any `<blink>` tags.

    I wish SmartyPants used named entities like `&mdash;`
    instead of decimal-encoded entites like `&#8212;`.

To specify an entire block of pre-formatted code, indent every line of the block by 4 spaces or 1 tab. Just like with code spans, `&`, `<`, and `>` characters will be escaped automatically.


    If you want your page to validate under XHTML 1.0 Strict,
    you've got to put paragraph tags in your blockquotes:

        <blockquote>
            <p>For example.</p>
        </blockquote>


Source: [daringfireball.net](http://daringfireball.net/projects/markdown/).
