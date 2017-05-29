



Take appropriate OTU Table

QC out samples

Split by Time - D3, W3, M3, M6

Filter out singletons etc.

Do Relative Percent


Run Analysis - categorical and continuous Phenos

Results - Tables and Plots (Scatter, Box)





When running ANOVA - should not have data as "NA", 
ANOVA reads it as a category, have it as " "
Month6typefeed has four samples with "NA"
Month6typefeed has one samples with "NA"

On the other hand, box-plot needs "NA" so as not to plot "empty" as another column

Safe to have "empty" cells than labeled as "NA"
So, ANOVA works fine and does not see "NA" label as another category.



The NA of character type is distinct from the string "NA".
Programmers who need to specify an explicit string NA should use NA_character_ rather than "NA", or set elements to NA using is.na<-.
Computations using NA will normally result in NA: a possible exception is where NaN is also involved, in which case either might result.

