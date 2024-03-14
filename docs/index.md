# Mkdocs-website

For full documentation visit [mkdocs.org](https://www.mkdocs.org/)

List

* [Blog](https://jaspervincent.github.io)
* [jekyll-website](https://jaspervincent.github.io/jekyll-website)
* [hugo-website](https://jaspervincent.github.io/hugo-website)
* [Mkdocs-website](https://jaspervincent.github.io/mkdocs-website)

* [jekyll-归档](https://jaspervincent.github.io/jekyll-website/archive.html)
* [hugo-归档](https://jaspervincent.github.io/hugo-website/tags/)

## Code Annotation Examples

### Codeblocks 代码块

Some `Code` goes here.

### Plain codeblock 普通代码块

```
Some code here
def myfunction()
// some comment
```

#### Code for a specific language 特定语言的代码

Some more code with the `py` at the start:

```py
import tensorflow as tf
def whatever()
```
#### With a title 带标题

```py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### With line numbers 有行号

```py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### Highlighting lines 突出显示行

```py hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
## Icons and Emojs

:smile: 

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }