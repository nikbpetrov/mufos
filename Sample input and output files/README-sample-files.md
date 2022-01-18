The "Input files" folder contains 12 files each with different possible data input formats. There are 5 core formats:
+ raw data, in which each variable is a separate column and each row is a new value for the variable (i.e. the typical rectangular dataset);
+ correlation table data, in which one column contains one variable's name, a second column contains the other variable's name and third and fourth columns which contain the correlation coefficients and associated p values, respectively. Each row represents an additional correlational test between variables;
+ independent t-test statistics, in which there is one column for each dependent variable name, six columns that contain information about the mean, standard deviation and sample size for each group (3 statistics by 2 groups) and an optional column whether equality of variance is assumed (if this column is missing, equality of variance is assumed). Each row represents a new group comparison;
+ SPSS table, which is an excel (.xlsx) file, produced by exporting a specific table from the SPSS Output window (for step-by-step instructions on how to export an SPSS table, see [the MUFOS Help Guide and Documentation](../master/MUFOS%20Help%20Guide%20and%20Documentation_1.0.docx))
+ p values table, which must contain a column of p values, with other optional columns

For each of the 12 input files, there are corresponding output files in both Microsoft Word and Microsoft Excel. The output files in Excel and Word contain the same information but are styled differently. The Excel files are contained in the "Ouput files - Excel" folder, and the Word files - the "Output files - Word" folder.

Throughout all files, there is simulated dummy data, in which the naming convention is "var" (short for variable) followed by a unique number.
