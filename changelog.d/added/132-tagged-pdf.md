`--tagged` (`tagged: true` in the Ruby gem, `?tagged` on the server) writes a tagged PDF
(#132). It adds a structure tree for screen readers and other assistive technology:
headings (`H1` to `H6`), paragraphs, lists (`L`, `LI`, `Lbl`, `LBody`), tables (`Table`,
`THead`/`TBody`/`TFoot`, `TR`, `TH` with `Scope`, `TD`, spans, `Caption`), links (each with its
annotation) and images with an `alt` as `Figure`s carrying it. Backgrounds, borders, headers,
footers, a `<thead>` repeated on a later page and an `<img>` without `alt` are marked as
artifacts, and the `lang` of `<html>` becomes the document `/Lang`. `--streaming` does not
support it.
