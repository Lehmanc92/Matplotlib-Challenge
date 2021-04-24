# Matplotlib-Challenge

In this project, pharmaceutical data was imported from a csv and passed into a data frame.  The pharmaceutical data contained the observed tumor volumes of mice treated with one of eight diffrent pharmaceuticals.  Mice are equally distributed by sex, and numerous timepoints are taken for each mouse, typically over a timespan of 40 days.

A more in depth look examined the Capomulin, Ramicane, Infubinol, and Ceftamin drug groups, and their respective observed tumor volumes.  These were visualized via a box-and-whisker plot; after calculating each drug group's quartiles, interquartile ranges, and upper and lower bounds, the one outlier from the Infubinol group was identified.

A focused observation of a single Capomulin-treated mouse through a line plot was used to examine how the drug affected tumor volume.

Finally, average tumor volumes vs average weights were visualized in a scatter plot.  Linear regression was used to determine relationships between the two variables, and it was found that the two variables have a strong positive correlation.  As mouse size increases, the tumor volume proportionally increases with its larger host.
