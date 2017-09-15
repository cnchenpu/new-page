# Markdown syntax

This is an H1
=============

This is an H2
-------------

# This is an H1
## This is an H2
###### This is an H6

# This is an H1 #
## This is an H2 ##
### This is an H3 ###

> This is the first level of quoting.
>> This is nested blockquote.
> Back to the first level.

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");

# list
* Red
* Green
* Blue

+ Red
+ Green
+ Blue

- Red
- Green
- Blue

1. First
2. Second
3. Third

***

# hyperlink

[Google] [1] [Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

[Google] [1] [Yahoo] [2] or [MSN] [3].
  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"

---

# empphasize

*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~middle line~~

---

# insert picture

![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")

![Alt text][id]
[id]: url/to/image  "Optional title attribute"


