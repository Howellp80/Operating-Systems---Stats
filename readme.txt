This is a bash shell script to calculate mean averages and medians of numbers that can be input
to this script from either a file or via stdin. The script should be able to calculate the mean and
median across the rows or down the columns.

Uasge is:
stats {-rows|-cols} [input_file]

| = or. Choose rows or colums
[] = optional input file

e.g.:
$ stats -rows test_file
Average Median
1 1
474 5
13 7
11 8
3 4
693 6
