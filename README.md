# Plotly-Challenge

![image](https://user-images.githubusercontent.com/71952428/130555431-5e22bc0e-20c9-487f-92b1-33bd21ede804.png)

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Step 1: Plotly


Use the D3 library to read in samples.json.


Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.




Use sample_values as the values for the bar chart.


Use otu_ids as the labels for the bar chart.


Use otu_labels as the hovertext for the chart.

![image](https://user-images.githubusercontent.com/71952428/130555495-5c68fcd2-d84c-4abf-84ea-79231c0d95cf.png)



Create a bubble chart that displays each sample.


![image](https://user-images.githubusercontent.com/71952428/130555552-8708a3c2-be51-4684-a1e3-33810ea09c4a.png)

Use otu_ids for the x values.


Use sample_values for the y values.


Use sample_values for the marker size.


Use otu_ids for the marker colors.


Use otu_labels for the text values.





Display the sample metadata, i.e., an individual's demographic information.


Display each key-value pair from the metadata JSON object somewhere on the page.


![image](https://user-images.githubusercontent.com/71952428/130555581-2f76fee6-7266-4727-a7fa-8547909847a1.png)


Update all of the plots any time that a new sample is selected.

Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:


Advanced Challenge Assignment (Optional)
The following task is advanced and therefore optional.


Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.


You will need to modify the example gauge code to account for values ranging from 0 through 9.


Update the chart whenever a new sample is selected.


