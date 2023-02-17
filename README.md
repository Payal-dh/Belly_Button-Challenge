# Belly_Button-Challenge
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Step 1: Plotly
1. Use the D3 library to read in samples.json.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
   - Use sample_values as the values for the bar chart.
   - Use otu_ids as the labels for the bar chart.
   - Use otu_labels as the hovertext for the chart.

### Bar Chart
![bar](https://user-images.githubusercontent.com/116124181/218005499-abca05be-2653-45e9-a57d-f02261bd3f77.png)


3. Create a bubble chart that displays each sample.
   - Use otu_ids for the x values.
   - Use sample_values for the y values.
   - Use sample_values for the marker size.
   - Use otu_ids for the marker colors.
   - Use otu_labels for the text values.

### Bubble Chart
<img width="1416" alt="bubble_chart" src="https://user-images.githubusercontent.com/116124181/218006099-a6eade79-148f-41fa-8087-fe598366962f.png">


4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

![demographic Info](https://user-images.githubusercontent.com/116124181/218005873-21513ed8-abe5-4035-95c1-c84da30a9a89.png)

![Graphs Image](https://user-images.githubusercontent.com/116124181/218005255-be45b1e6-1d5d-4fc8-ab63-6258856d81fb.png)


## Advanced Challenge Assignment (Optional)
The following task is advanced and therefore optional.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

Weekly Washing Frequency Gauge

<img width="384" alt="gauge" src="https://user-images.githubusercontent.com/116124181/218005316-d1f1017e-8c77-4090-8dfe-e8aa7ce01111.png">

