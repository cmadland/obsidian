---
DOI: 
Date: 2018
Rating: 0/5
Title: "Handbook of Educational Measurement and Psychometrics Using R"
ShortSummary: ""
annotation-target: desjardinsHandbookEducationalMeasurement2018.pdf
tags: 
---


#### [Handbook of Educational Measurement and Psychometrics Using R](desjardinsHandbookEducationalMeasurement2018.pdf)




> [!tldr] Summary
> A short summary - or an abstract in 3 sentences, relating to YOU. What did YOU find interesting about this paper. 

> [!cite] Bibliography
>Desjardins, C. D., & Bulut, O. (2018). _Handbook of Educational Measurement and Psychometrics Using R_ (1st ed.). Chapman and Hall/CRC. [https://doi.org/10.1201/b20498](https://doi.org/10.1201/b20498)

> [!quote] Quotable
> Imagine you would quote this paper in your publication. How would you do it? It is probably just one sentence followed by the reference. It is the most intense condensation of the information in this paper and forces you to be on point. 
> 
> You can have multiple alternatives. 


#### Aim of Paper


#### Key insights 




#### Annotations


Classical Test Theory 

 

2.2 What Is Measurement? 

 

Generally speaking, measurement is the quantification of a construct by assigning numerical values or qualitative labels based on a set of rules, principles, or operations. 

 

A construct, trait, or domain is a theoretical entity or concept, such as reading ability, intelligence, or executive functioning. In education and psychology, we usually cannot measure constructs directly because they are latent (unobserved), and thus we must make inferences about them from their manifestations. To measure a latent construct, we develop and use items (or tasks) in measurement instruments. These items are typically referred to as “manifest variables” that provide an operational definition of the latent construct being measured. 

 

2.3 Issues in Measurement 

 

Validity refers to the degree to which we are measuring what we have intended to measure. Validity aims to investigate whether the manifest variables are the true manifestations of the target construct or something else. 

 

All validity evidence essentially falls under the umbrella of construct validity.1 Chapter 4 covers factor analysis, which is often considered a method for assessing construct validity. 

 

Although it has always been considered a stand-alone concept, reliability is, in fact, a form of validity evidence. Reliability refers to the consistency of the results from a measurement instrument. 

 

For example, if we administered an instrument repeatedly, would the results be the same, similar, or would they vary significantly? If the scores vary significantly, then they will have low reliability and contain a high amount of measurement error. To make valid inferences based on the results from a measurement instrument, the reliability of the results is essential. 

 

Generally speaking, we want the results or scores from an instrument to reflect what we intend to measure. If the results are independent of examinee characteristics (e.g., gender, ethnicity, and cultural background) and test administrations (e.g., the administration of a test in 2016 and 2017), then we can say that the instrument is invariant. 

 

Finally, a score scale underlying a measurement instrument has important properties. A scale typically consists of a set of values or labels that are used to categorize or quantify what is being measured. 

 

2.3.1 Type of Scales 

 

Measurement scales are typically classified as nominal, ordinal, interval, and ratio. 

 

A nominal scale consists of qualitative and unordered categories. For example, a scale that assigns numbers to someone’s favorite color is inherently unordered, and by extension qualitative, because we cannot rank color.2 

 

Unlike nominal scales, ordinal scales are inherently ordered. An ordinal scale can be either quantitative (e.g., first, second, and third positions in a race) or qualitative (e.g., excellent, proficient, developing, and beginning in a scoring rubric). However, with ordinal scales, we do not know the distance between adjacent categories and there is no reason to assume that the distance between adjacent categories is equivalent. 

 

If we have an ordered scale with equal intervals, then our scale is said to be at least an interval scale. If the scale has an absolute zero, then our scale would be a ratio scale, otherwise it is an interval scale. 

 

n addition, ratio scales have a real zero point, indicating the absence of the construct being measured. Unlike the ordinal and interval scales, ratio scales allow interpreting the proportions of the values on the scale (e.g., 10 inches are twice as long as 5 inches). 

 

Data from nominal and ordinal scales are often referred to as categorical or discrete data, while data from interval and ratio scales are referred to as continuous data. 

 

With interval and ratio scales, we can calculate descriptive statistics (e.g., mean and standard deviation); however, such statistics are inappropriate with nominal and ordinal scales. We may examine scatter plots, histograms, or stem and leaf plots with interval and ratio scales. With nominal or ordinal scales, we may construct contingency tables to show the number or proportion of respondents endorsing a certain response, and create bar charts, dot plots, or mosaic plots. 

 

Another extremely powerful plot is a type of plot known as a trellis or facet plot. A trellis plot can show the relationship between two variables conditional on a third (as we briefly mentioned in Chapter 1). For example, if we want to see how the age distribution for the examinees differed by gender, we would do the following: age_gender_table <- table(gender_nominal, age_ordinal) age_gender_df <- data.frame(age_gender_table) dotplot(age_ordinal ~ Freq | gender_nominal, age_gender_df, xlab = "Frequency", ylab = "Age") The above code first creates a two-way table (age_gender_table) and then converts it into a data frame (age_gender_df). This is a necessary, intermediate step for plotting with the dotplot function. As a reminder the “|” sign can be interpreted as “conditional on” and not as a boolean “or.” In the example above, the dotplot function plots the frequency distribution of the age variable conditional on the gender variable. 

 

2.4 The Classical Test Theory Framework 

 

Classical test theory (CTT), also called true score theory, is a measurement framework that allows us to understand, manipulate, and interpret measured outcomes. The premise of CTT is that every measurement contains error and that any, and all, observations are imperfect. 

 

Mathematically, CTT is expressed as: X = T + E. 

 

In the CTT model, X is the observable measurement/test score; T is the true (latent) measurement/total test score; and E is the random error. 

 

To use 

 

the CTT model, there are four additional assumptions beyond the general form presented in Equation 2.1: 1. E(X) = T , the expected value of the observed score is the true score, 2. Cov(T, E) = 0, the true score and error are independent, 3. Cov(E1, E2) = 0, the errors across test forms are independent, and 4. Cov(E1, T2) = 0, the error on one form is independent of the true score on another form. Because of these assumptions, the CTT model can be re-expressed as the simple sum of orthogonal (i.e., uncorrelated) variance components as shown below: σ2 X = σ2 T + σ2 E. 

 

Equation 2.2 states that observed score variance is the sum of true score and error variances. Within this model, true score variance is assumed to be constant (e.g., it will never change regardless of the form of the instrument, the date of the assessment, etc.), while error variance fluctuates (e.g., some forms may contain more error than others). The measurement error can be divided into random (unpredictable and inconsistent) and systematic (constant and predictable) error. 

 




#### Related