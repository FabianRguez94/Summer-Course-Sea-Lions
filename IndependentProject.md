Monitoring touristic boats in La Lobera Island using satellite images
================
(Rodriguez-Gonzalez, 2019)
2019-05-31

## Summary

## Question(s)

  - Question 1: There is a ilegal Sea lions whatching during closure
    season?
  - Question 2: How many boats there are in the area?

## Introduction

Sea lions colony in La Lobera has a very important role because they are
bioindicators of ecosystem health being one of the top predators. During
recent years, ecotourism and the observation of sea lions in the area
has increased.

In 2015 a closure was established corresponding to the breeding season
during Jun 1 to Aug 31. However, the area does not have good vigilancy.
for which it is necessary to monitor the area

The use of satellite images gives us a great advantage to be able to
count and even measure the boats.That is why in this work is intended to
monitor the population with this news technologies.

## Methods

Touristic boats counts were made in “La Lobera” La Paz, B.C.S., Mexico
(Figure 1) during the closure season (jun 1 - Aug 31) in 2017-2018,
using Planet.

![Figure 1. Study area](l.png)

Measurements of the boats were made in Google Earth Pro, and the counts
![Figure 2. Measuring boats](t.png)

To add images from your local files that are stored in the same
directory (folder) as your Rproject, replace the web address above with
the fliename of your image.

## Results

![optional caption text](r.png) Summarize the current status of the
project - i.e., how far you got in your data collection, what’s left to
do, any patterns you’ve noticed so far. etc.

Once you’ve collected your data, this is where you’ll do your R plotting
and analyses.

You can embed plots in this section, for example (replace this with your
own when you’re ready to make plots):

![](IndependentProject_files/figure-gfm/pressure%20plot-1.png)<!-- -->

(Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot, but this can be
changed if, for example, you want to share both your code and your plots
with collaborators in early stages of a manuscript.)

You would also do your analyses in this section, and you can choose
whether or not your code and analytical results show up in the output
(knitted) document, for example (replace this with your own when you’re
ready to do analyses):

``` r
model <- lm(pressure~temperature, data = pressure)
summary(model)
```

    ## 
    ## Call:
    ## lm(formula = pressure ~ temperature, data = pressure)
    ## 
    ## Residuals:
    ##     Min      1Q  Median      3Q     Max 
    ## -158.08 -117.06  -32.84   72.30  409.43 
    ## 
    ## Coefficients:
    ##              Estimate Std. Error t value Pr(>|t|)    
    ## (Intercept) -147.8989    66.5529  -2.222 0.040124 *  
    ## temperature    1.5124     0.3158   4.788 0.000171 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## Residual standard error: 150.8 on 17 degrees of freedom
    ## Multiple R-squared:  0.5742, Adjusted R-squared:  0.5492 
    ## F-statistic: 22.93 on 1 and 17 DF,  p-value: 0.000171

## Discussion

insert here a few sentences about anything you’ve learned so far - e.g.,
any unexpected patterns, any challenges you’ve had, next steps, etc.

## References

You won’t likely need this section at this stage, but when you’re
writing a paper, can insert references into RMardown docs - see
<https://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html>.
