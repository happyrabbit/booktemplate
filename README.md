# Book Template

It is a simple bookdown template 

- change the following links in `_output.yml`:

```r
      before: |
        <li><a href="http://linhui.org">Hui's Homepage</a></li>
      after: |
        <li><a href="https://github.com/rstudio/bookdown" target="blank">Published with bookdown</a></li>
    edit:
      link: https://github.com/happyrabbit/booktemplate/master/%s
```

- change the `output_dir`: `/Users/Documents/GitHub/booktemplate`

```r
book_filename: "booktemplate"
chapter_name: "Chapter "
output_dir: "/Users/Documents/GitHub/booktemplate"
always_allow_html: yes
```

- Run this code in R Console: `bookdown::render_book("index.Rmd", "bookdown::gitbook")`
