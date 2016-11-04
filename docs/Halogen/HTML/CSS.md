## Module Halogen.HTML.CSS

This module defines an adapter between the `purescript-halogen` and
`purescript-css` libraries.

#### `style`

``` purescript
style :: forall i. CSS -> Prop i
```

Render a set of rules as an inline style.

For example:

```purescript
HH.div [ CSS.style do color red
                     display block ]
      [ ... ]
```

#### `stylesheet`

``` purescript
stylesheet :: forall p i. CSS -> HTML p i
```

Render a set of rules as a `style` element.


