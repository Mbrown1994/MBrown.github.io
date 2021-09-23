Programming Background
================
Mary Brown
9/14/2021

## Response to prompt one

So far, R is the only programming experience that I’ve had. I’ve messed
around a little with the basics of SAS but didn’t learn about it in
great detail. From what I did learn, I can say that I enjoy R more -
especially the more that I use it. Before this class, I was not familiar
with R markdown but I really enjoy using it. I like how code chunks work
with regular text and the knit function is also very helpful. I would
consider R difficult to learn but I think that’s because I had not been
exposed to programming previously. This class has been very helpful,
though!

## Example R Markdown output
```{r, include=TRUE}
plot(iris)
```

![](/Users/marybrown/Desktop/R%20Programming/git-project/MBrown1994.github.io/_posts/2021-9-14-Second-Blog-Post_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

``` r
library(rmarkdown)
rmarkdown::render("~/Desktop/R Programming/RProject/_Rmd/2021-9-14-Second-Blog-Post.Rmd",
                  output_format = "github_document",
                  output_dir = "../_posts/",
                  output_options = list(html_preview=FALSE, keep_html=FALSE)
                  )  
```
