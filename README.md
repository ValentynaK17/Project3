# Book Review Insights
In this project, we are analyzing and visualizing Authors' success based on Book Ratings. This will help business with planning of customer engagement strategies and promotional activities. <br>
Within the dashboard we focused on two main metrics, that we think are the indicators of the author's success: 
 - popularity, represented by how many reviews their books get,
 - quality of engagement, reflected in average ratings score.

That’s why the top part of the dashboard shows a bar chart, which lists the top 10 authors by the total number of reviews. 
This view allows us to quickly identify which authors are most talked about. <br>
Additionally, the criteria can be adjusted to discover the top 10 authors based on the average rating score across all their rated books.<br>
For a more detailed analysis, the lower section of the dashboard, which uses the so-called quadrant approach, plots the average rating score against the reviews count, with the size of the bubbles representing the recency of the release (with bigger markers we have more recent publication year). This provides us an insight into the current author’s standing.<br>
Here we have four areas:
 - *Green*: Big winners with highly popular books that also receive great reviews.
 - *Red*: These books haven't made much of a splash, with fewer reviews and lower ratings.
 - *Orange*: these are Contradictory books with many reviews indicating high sales, but still for some reason receive not really great ratings
 - *Yellow*: where the majority of books fall for most of the authors. These are well-rated books that haven't been noticed by as many people yet.

<p align="center">
<img src="https://github.com/ValentynaK17/Project3/blob/main/Visuals/DefaultView.png" width=“275">
</p>
Switching to the High-Level Distribution, represents the distribution by quadrants to provide a 'bird’s eye view' of the author's overall reader engagement and insights per publcation year. <br><br>

<p align="center">
<img src="https://github.com/ValentynaK17/Project3/blob/main/Visuals/HighLevelDistributions.png" width=“275">
</p>

### Installation
The project can be run using following steps:
1. Database Setup - Run Jupyter Notebook DB_setup.ipynb to get the merged data
2. Running the Flask Application - Run the app.py file to get the jsonified data
3. Interactive Visualizations - The html page will by default display a Dashboard with
    - Bar Chart: Top 10 Authors based on Average Rating Score. There is ability to switch to Top 10 by Reviews Count, using respective dropdown
    - Quadrant Analysis: Author with a book, which has the highest reviews count in our database is selected by default. There are options to change the level of detalization using Radio Buttons and change the Author using provided dropdown.


### References
 - [Flask and mongodb](https://www.digitalocean.com/community/tutorials/how-to-use-mongodb-in-a-flask-application)
 - [Installation of charts js](https://www.chartjs.org/docs/latest/getting-started/installation.html)
 - [chartsjs intro](https://www.chartjs.org/docs/latest/getting-started/usage.html)
 - [Redraw chart in charts js](https://stackoverflow.com/questions/40056555/destroy-chart-js-bar-graph-to-redraw-other-graph-in-same-canvas)
 - [Merge of collections](https://www.mongodb.com/developer/languages/python/python-quickstart-aggregation/)
 - [Filter an array of objects](https://builtin.com/software-engineering-perspectives/javascript-filter)
 - [Merge data in mongodb](https://jira.mongodb.org/browse/SERVER-30812)
 - [Remove fields after merge of data in mongodb](https://www.mongodb.com/docs/manual/reference/operator/aggregation/unset/)
 - [ForEach](https://www.w3schools.com/jsref/jsref_foreach.asp)
 - [How to find keys of a dictionary in js](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)
 - [Lines on bubble chart](https://stackoverflow.com/questions/42423167/custom-vertical-line-using-plotly-js)
 - [pie-donut](https://codepen.io/Shokeen/pen/gxwKKO)
 - [text inside donut](https://stackoverflow.com/questions/28097184/adding-text-to-the-center-of-a-d3-donut-graph)
 - [General info in layout parameters](https://plotly.com/javascript/reference/layout/xaxis/)
 - [Remove duplicates](https://www.geeksforgeeks.org/how-to-remove-duplicate-elements-from-javascript-array/)
 - [Extract a substring](https://www.w3schools.com/jsref/jsref_substring.asp)
 - [Sort array of objects](https://www.javascripttutorial.net/array/javascript-sort-an-array-of-objects/)


### Acknowledgements
Shout out to the contributors to this project:
1. Daria Z.
2. Neha S.
3. Seeke O.D
4. Valentyna K.

 
