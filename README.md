## Índice

- [Índice](#índice)

### Tables
|     | Command          | Action                                        |
| :-- | :--------------- | :-------------------------------------------- |
| ⚙️  | `dev` or `start` | Starts local dev server at `localhost:3000`.  |
| ⚙️  | `build`          | Build your production site to `./dist/`.      |
| ⚙️  | `preview`        | Preview your build locally, before deploying. |


### 🤝 Contributing
<a href="https://github.com/midudev/esland-web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=midudev/esland-web" />
</a>


## Math expression
$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$


## Syntaxis
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Syntaxis Oculta
<details>
<summary>Recursive quicksort implemented in Raku.</summary>

```raku
multi quicksort([]) { () }
multi quicksort([$pivot, *@rest]) {
    my $before := @rest.grep(* before $pivot);
    my $after  := @rest.grep(* !before $pivot);
    flat quicksort($before), $pivot, quicksort($after)
}
```
</details>

## Horizontal Lines (3 ways)
---
***
___

## Basics
**This is bold text** <br>
_This text is italicized_ <br>
~~This was mistaken text~~ <br>
**This text is _extremely_ important** <br>
***All this text is important*** <br>
This is a <sub>subscript</sub> text <br>
This is a <sup>superscript</sup> text <br>
<kbd>cmd + shift + p</kbd>
<kbd> <br> cmd + shift + p <br> </kbd>
<kbd>[Link with blue](https://google.es)</kbd>
[<kbd>Link without blue</kbd>](https://google.es)

> Text that is a quote
```
php artisan serve
```
The background color is `#ffffff`

This site was built using [GitHub Pages](https://pages.github.com/)


## Lists 1
- George Washington
* John Adams
+ Thomas Jefferson

## Lists 2
1. James Madison
1. James Monroe
1. John Quincy Adams

## Lists 3
1. First list item
   - First nested list item
     - Second nested list item

## Task Lists
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue

## Notas de pie
Here is a simple footnote[^1].
A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

## Mensaje oculto en el Readme
<!-- This content will not appear in the rendered Markdown -->

## Details code (md)

````md
<details>
<summary>title of the content (*not* support **markdown** syntax ~~hmm~~)</summary>

content body (support **markdown** syntax ~~hmm~~)

</details>
````

## Details code 2 (md)
````md
```
{
  support: "codeblock to"
}
````

## Details code 3 (md + json)
````md
```json
{
  support: "codeblock to"
}
````

## Info icon
ℹ️

## Volver a un link personalizado
**[⬆ Volver a índice](#índice)**


## Box 0
<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>

## Box 1
| :exclamation:  You have to read about this   |
|----------------------------------------------|

## Box 2
| :warning: WARNING           |
|:----------------------------|
| Another way to warn you     |

## Box 3
| :memo:        | This is something that is good to note       |
|---------------|:---------------------------------------------|

## Box 4

> Buenas <br>
> Use `git status` to list all new or modified files that haven't yet been committed.

> Buenas <br>
>> Use `git status` to list all new or modified files that haven't yet been committed.

> [!WARNING]
> Alerta Warning

> [!NOTE]
> Alerta Note

> [!TIP]
> Alerta Tip

> [!IMPORTANT]
> Alerta Warning

> [!CAUTION]
> Alerta Caution
