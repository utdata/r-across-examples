---
output:
  html_document:
    df_print: paged
knit: (function(inputFile, encoding) { rmarkdown::render(
    inputFile,
    encoding = encoding,
    output_dir = "docs",
    output_file='index.html'
  ) })
---

# Examples using across and if_any

I've struggled trying to use the [`across()`](https://dplyr.tidyverse.org/reference/across.html) functions. I had a specific use case in mind that used `mutate()` across multiple columns for any value from a list.

I figured it out!

## Published notebooks

- [mutate](https://utdata.github.io/r-across-examples/mutate-across.html)
- [filter](https://utdata.github.io/r-across-examples/filter-across.html)
