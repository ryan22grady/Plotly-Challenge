# Plotly-Challengee - Belly Button Biodiversity
  In this assignment, I built an interactive dashboard to explore the Belly Button Biodiversity in my Github Pages, which catalogs the microbes that colonize human navels.
  Results, are given by Subject ID and the dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
  
### Step 1: Plotly
1. Use the D3 library to read in samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

- Use sample_values as the values for the bar chart.

- Use otu_ids as the labels for the bar chart.

- Use otu_labels as the hovertext for the chart.

3. Create a bubble chart that displays each sample.
Use otu_ids for the x values.

- Use sample_values for the y values.

- Use sample_values for the marker size.

- Use otu_ids for the marker colors.

- Use otu_labels for the text values.

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

6. Update all of the plots any time that a new sample is selected.

### Step 2: Advanced Challenge Assignment (Optional)

The following task was advanced and therefore...SO MUCH FUN!

- I adapted the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

- Then, I modified the example gauge code to account for values ranging from 0 through 9.

- Update the chart whenever a new sample is selected.

### Deployment 
- Deploy my app to a free static page hosting service, GitHub Pages.

#### Tools and Sources
- Plot.ly

- Javascript

- HTML

- D3.js

- JSON

- GitHub and GitHub Pages

- console.log

- Refered to the Plotly.js documentation when building my plots.

- Also refered to other key sources such as A customizable D3 gauge

- Plotly Custom Data

- Plotly Bar chart

- Plotly Real time chart

