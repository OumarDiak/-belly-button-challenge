# -belly-button-challenge

This challenge, I learned how to creat a dashboard that displays data from a bellybutton biodiversity dataset. The primary functions are buildMetadata() and buildCharts(), which dynamically generate the metadata panel and the charts (bubble chart and bar chart) based on the selected sample ID. The metadata function fetches data using D3.js from a JSON file and filters it based on the sample ID. It then displays the relevant information on the web page by clearing any previous content and appending new tags for each key-value pair of the selected sample’s metadata. Similarly, the buildCharts() function processes the sample data to extract the necessary values for constructing both a bubble chart and a bar chart using Plotly.js. The bubble chart displays the bacteria cultures per sample, while the bar chart shows the top 10 bacteria cultures found.

The init() function is called when the page loads. It fetches the sample names from the dataset and populates the dropdown menu, allowing users to select different sample IDs. Upon selecting a sample, the optionChanged() function is triggered, which updates both the metadata panel and the charts with the new sample data. The entire dashboard is rendered and updated dynamically as users interact with the dropdown, creating an interactive visualization experience that is powered by D3.js and Plotly.js for data manipulation and chart rendering.

I work on this project with the assistance of the class cohort YARA EL-EMAM! She assisted me a lot in this project as I was having hard time working on it by myself. 









