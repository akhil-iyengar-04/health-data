# health-data
An analysis of cardiovascular disease using Python data visualization libraries (Pandas, Matplotlib). I've always been interested in the correlation between common health datapoints such as BMI or cholestrol and the prevelance of cardiovascular disease. With a public, crowdsourced dataset (provided on repo), I analyzed this correlation using data visualizations. 

I first calculated BMI for each offered datapoint in an effort to establish correlation between higher BMI and the frequency of cardiovascular disease on a scatterplot. The results were ambigious so I plotted a line of best fit as well. As BMI increased, cholestrol levels increased as well. (Figure 1)

I then wanted to expand my analysis of correlation to cover all datapoints (not just BMI and cardiovascular disease), and thus created a correlation table. The table conveyed high correlation between the two different types of blood pressure, BMI/weight, and other pairs of datapoints (as indicated by light green elements). Interestingly, cardiovascular disease had a semi-high correlation with bmi and blood pressure. (Figure 2)

Finally, I designed a stacked histogram to delve into the relationship between fitness (activity level) and high cholestrol. The results of this visualization were ambigious, likely because activity level reporting is subjective. (Figure 3)
