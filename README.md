# Belly_Button-Challenge
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Step 1: Plotly
1. Use the D3 library to read in samples.json.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
   - Use sample_values as the values for the bar chart.
   - Use otu_ids as the labels for the bar chart.
   - Use otu_labels as the hovertext for the chart.

### Bar Chart
![newplot (1)](https://user-images.githubusercontent.com/116124181/219553888-e512e582-76c7-4919-96c8-0b933eb512c0.png)



3. Create a bubble chart that displays each sample.
   - Use otu_ids for the x values.
   - Use sample_values for the y values.
   - Use sample_values for the marker size.
   - Use otu_ids for the marker colors.
   - Use otu_labels for the text values.

### Bubble Chart

![newplot (2)](https://user-images.githubusercontent.com/116124181/219553938-f4447a57-ab0d-458b-b059-563037d1eb0d.png)


4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

![dashboard](https://user-images.githubusercontent.com/116124181/219553770-5ecd7c55-266d-4c14-b578-ae6bf9289d50.png)

## Advanced Challenge Assignment (Optional)
The following task is advanced and therefore optional.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

Weekly Washing Frequency Gauge

![newplot](https://user-images.githubusercontent.com/116124181/219553971-6fcc4ef3-c104-48ff-af59-ad97f2215e35.png)

