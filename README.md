# Workshop: Bayesian Statistics with JASP 

This repository contains materials for my workshop on Bayesian Statistics with JASP, held at Angelo State University on September 6, 2019

## Materials
- Workshop slides ([pdf](workshop.pdf))
- [JASP software](http://jasp-stats.org)
- Online Bayes factor [calculator](https://tomfaulkenberry.shinyapps.io/anovaBFcalc/) for ANOVA summaries

## Data sets 
Each of the datasets below is formatted in CSV (comma separated value) format, which is the format required for JASP. You will want to download the files somewhere on your computer. Windows users should "right-click" on the CSV link. Mac users should "ctrl+click" on the CSV link. Alternatively, you can download a single ZIP archive of the files [here](https://raw.githubusercontent.com/tomfaulkenberry/bayesAngeloState/master/datasets.zip).

*Note*: all datasets below are from the book *Learning Statistics with JASP* by Navarro, Foxcroft, and Faulkenberry, which is freely downloadable at https://learnstatswithjasp.com.

### Example 1 (independent samples t-test)

Suppose we have 33 students taking Dr Harpo's statistics lectures, and Dr Harpo doesn't grade on a curve. In fact, Dr Harpo's grading is a bit of a mystery, so we don't really know *anything* about what the average grade is for the class as a whole. There are two tutors for the class, Anastasia and Bernadette. There are 15 students in Anastasia's tutorials, and 18 in Bernadette's tutorials. We are interested in whether Anastasia or Bernadette is a better tutor, or if it doesn’t make much of a difference.

- raw data ([csv](https://raw.githubusercontent.com/tomfaulkenberry/bayesAngeloState/master/datasets/ttest1.csv))
- complete JASP file ([jasp](https://raw.githubusercontent.com/tomfaulkenberry/bayesAngeloState/master/datasets/ttest1.jasp))

### Example 2 (paired samples t-test)

Dr. Chico has her students take two major tests -- one early in the semester and one later in the semester. To hear her tell it, she runs a very hard class, one that most students find very challenging. But she argues that by giving hard assessments students are encouraged to work harder. Her theory is that the first test is a bit of a "wake up call" for students. When they realize how hard her class really is, they'll work harder for the second test and get a better mark. Is she right?

- raw data ([csv](https://raw.githubusercontent.com/tomfaulkenberry/bayesAngeloState/master/datasets/ttest2.csv))
- complete JASP file ([jasp](https://raw.githubusercontent.com/tomfaulkenberry/bayesAngeloState/master/datasets/ttest2.jasp))

### Example 3 (correlations)

Is sleep related to grumpiness? More to the point -- is the baby's sleep related to my grumpiness? The data file below contains several variables, including `dan.sleep` (Dani's sleep, measured in hours), `baby.sleep` (the baby's sleep, measured in hours), and `dan.grump` (Dani's grumpiness, measured on a scale of 0 = not at all grumpy to 100 = VERY grumpy). 

- raw data ([csv](https://raw.githubusercontent.com/tomfaulkenberry/bayesAngeloState/master/datasets/correlation.csv))
- complete JASP file ([jasp](https://raw.githubusercontent.com/tomfaulkenberry/bayesAngeloState/master/datasets/correlation.jasp))


