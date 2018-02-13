# css-goodies
Some CSS goodies, stuff that I come by that are worth noting out:


### `> * + *`
That selector allows you to select every adjacent child, in other words any sibling but not the first child.

i.e.
That code would add a top margin for every element in `my-parent-div` except for the first element.
```
.my-parent-div{
  * + * {
    margin-top: 5px;
  }
}
```
