# HelloWorld
A project to practise using git.
A simple Hello World example was placed.
这是一个普通段落：

    这是一个代码区块。
* * *

***

*****

- - -

---------------------------------------
This is an H1
=============

This is an H2
-------------
# 这是 H1

## 这是 H2

###### 这是 H6
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.


> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
  consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
  Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
  Suspendisse id sem consectetuer libero luctus adipiscing.

嵌套
> This is the first level of quoting.
>
>> This is nested blockquote.
>
> Back to the first level.

*   Red
*   Green
*   Blue


+   Red
+   Green
+   Blue


-   Red
-   Green
-   Blue


1.  Bird
2.  McHale
3.  Parish


*   A list item with a blockquote:
    > This is a blockquote
    > inside a list item.

行内式链接
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

参考式
This is [an example][id] reference-style link.

[id]: http://www.baidu.com/  "Optional Title Here"

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [Google]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

Use the `printf()` function.

``There is a literal backtick () here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

Please don't use any `<blink>` tags.

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.

![Alt text](C:\Users\kotar\Pictures\Camera Roll\20160906_174837_722.jpg)

![Alt text](http://www.mtr.bj.cn/images/x_yqlj_banner.png)

![Alt text][imgid]

[imgid]: C:\Users\kotar\Pictures\CameraRoll\ChMkJ1auyiSIdnO2AB7ek9x9APQAAH8rAGxbCMAHt6r886.jpg "Optional title attribute"

~~Mistaken text.~~

```
x = 0
x = 2 + 2
what is x
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

`:`在最左边表示左对齐，`:`在最右边表示右对齐，左右两边都有`:`表示居中。
