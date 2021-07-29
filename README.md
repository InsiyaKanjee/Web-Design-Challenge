# Web Visualization Dashboard (Latitude)

In this dashboard, individual pages are created for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. There is also a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Design

The consists of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There should is a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A "Comparisons" page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.

The website, at the top of every page, has a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

Finally, the website is deployed to GitHub pages.

There is also a jupyter notebook that converts the cities data from csv to html.

