# NES2303_common_tests

## Other statistical tests
Covers other statistical tests within an lm / glm framework, and gives examples of use with 'traditional' R commands and in lm / glm approach. Tests covered include:
* t-distribution vs normal distribution
* parametric vs non-parametric
* One-sample t-test and Wilcoxon tests
* Paired t-test and Wilcoxon matched-pairs test
* Student's independent t-test
* Correlation and rank correlation
* One-way ANOVA, Two-way ANOVA, ANCOVA (already done, but just for completeness)
* Chi-squared test using `chisq.test` and `glm`. Latter is easier for `ggplot2` visualisation as long data format needed

## Changes, things to add
* Check shiny website: seems slow to load and some quizzes missing
* Add Mann-Whitney U test for non-parametric equivalent of Student's independent t-test
* Update the original _Common statistical tests are linear models_ <https://lindeloev.github.io/tests-as-linear/linear_tests_cheat_sheet.pdf> so that the tests and graphics match what is taught on NES2303. Currently it is too complex.
* Update the 2-page BIO2020 "cheat-sheet" (which uses RStudio cheat-sheet formatting) to remove `bio2020` package, simplify, clarify etc.

## Mixed-effects models with `nlme`
Students on the Animal Behaviour module are asked to do a repeated-measures ANOVA; they are given instructions in Minitab (mixture of agric and zoology students). I have provided instructions in the past for our zoology students to do this, using `nlme`. Should this be added as a separate(?) shiny app?
