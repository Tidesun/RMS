# RMS
## generate fake data
Based on mean value of abundance for OTU(each kind of taxonomy) in each district, I generate random data by Guassian(in group variance set to 1 since we do not have that data)
## result
Generated data for sure has same mean value as real data.
I do the Kruskal Wallis test on the generated data. It shows great difference between real statistic and fake one. Maybe in group variance is set wrongly. But we do not have that data. It is what I can do for now based on the data I have.
Generated random data is in output.xlsx
column is OTU.
row is each sample.
data is raw abundance.
