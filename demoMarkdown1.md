## Markdown Alerts
---

> [!NOTE]
> Useful information that users should know, even when skimming content.
> Testing this feature out.

__Warning__
__Note__


## HEX and RGB Color Palette
---

#### HEX Color Palette

Change the color to red `#FF0000`
<font color="#FF0000">Color</font>
<font color="#800080">Color</font>

#### RGB Color Palette

- type: markdown
    content: >
      <h1><font color="rgb(128, 0, 128)">This text should be purple</font></h1>


## Blockquotes
---

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

## Fenced Code Blocks
---

```
`#FF0000` Error: there was a problem with the editor.
```

```
``rgb(R,G,B)` Error: there was a problem with the editor.
```

```
``rgb(9, 105, 218)`` Error: there was a problem with the editor.
```

## Syntax Highlighting in your fenced code block
---

```javascript
let fruits = ['Apple, 'Banana', 'Mango', 'Orange', 'Pineapple'];
let citrus = fruits.slcie(2,4);

console.log(citrus); // ['Mongo', 'Orange']
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```diff
- fatal: []: FAILED! => {
-   "msg": "template error while templating string: unexpected char \"'\" at 41. String: {{ mongodb_packages.mongodb_app_installer'] }}"
- }
```

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

## Emoji
---

That is so funny! :joy:
(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

Ship my package 🚄 🦐

## Conventional Commits
---

(See also [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/))

Types other than fix: and feat: are allowed, for example @commitlint/config-conventional (based on the Angular convention) recommends build:, chore:, ci:, docs:, style:, refactor:, perf:, test:, and others.

### Highlight
---

I need to highlight these ==very important words==.

### Subscript
---

H~2~O

### Superscript
---

X^2^

## Other code
---

$\color{red}{\textsf{lorem ipsum}}$

$\color{red}{\textsf{fatal: []: FAILED! => {
    "msg": "template error while templating string: unexpected char \"'\" at 41. String: {{ mongodb_packages.mongodb_app_installer'] }}"
}}}$

- `docs/`
    > A placeholder directory for your project documentation and a [docs readme template]() to help you get started.

```markdown
- fatal: []: FAILED! => {
-   "msg": "template error while templating string: unexpected char \"'\" at 41. String: {{ mongodb_packages.mongodb_app_installer'] }}"
- }
```

<font color="red">
 fatal: []: FAILED! => {
   "msg": "template error while templating string: unexpected char \"'\" at 41. String: {{ mongodb_packages.mongodb_app_installer'] }}"
 }</font>


<font color="red">This is some text!</font>


<code style="color : name_color">text</code>
<code style="color : blue">text</code>

