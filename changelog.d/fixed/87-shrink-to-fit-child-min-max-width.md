A float, `inline-block` or flex item with `width: auto` now takes a block-level child's
`min-width`/`max-width` into account when it shrinks to fit its content (#87). The child no
longer sticks out of its parent, and the parent is no longer wider than the child. A percentage
`min-width`/`max-width` on the child is still ignored there, since it has nothing to resolve
against while the parent's width is being found.
