# Web Visualization Dashboard

### Create a dashboard showing off the analysis using HTML and CSS

#### https://poonam-ux.github.io/Web-Visualization-Dashboard/ 

In this activity, I created a visualization dashboard website by plotting weather data.
Individual pages for each plot and a means by which we can navigate between them were created. These pages contain the visualizations and their corresponding explanations. The website also contains a Landing page where we can see a comparison of all of the plots, and a Data page where we can view the data used to build these pages.

The website consists of 7 pages, including:

* A landing page containing:
    * An explanation of the project.
    * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking on them takes the user to that visualization.

![](https://github.com/poonam-ux/Web-Visualization-Dashboard/blob/main/Visualizations/landing_page_large_screen_sm.png)

![](https://github.com/poonam-ux/Web-Visualization-Dashboard/blob/main/Visualizations/landing_page_small_screen_sm.png)

* Four visualization pages, each with:
    * A descriptive title and heading tag.
    * The plot/visualization itself for the selected comparison.
    * A paragraph describing the plot and its significance.

![](https://github.com/poonam-ux/Web-Visualization-Dashboard/blob/main/Visualizations/visualization_page_large_screen_sm.png)

* A “Comparisons” page that:
    * Contains all of the visualizations on the same page so we can easily visually compare them.
    * Uses a Bootstrap grid for the visualizations.
    * The grid consists of two visualizations across on medium and larger screens, and 1 across on extra-small and small screens.

![](https://github.com/poonam-ux/Web-Visualization-Dashboard/blob/main/Visualizations/comparisons_page_large_screen_sm.png)

* A “Data” page that:
    * Displays a responsive table containing the data used in the visualizations.
    * The table is created with the bootstrap table component.
    * The data comes from converting csv file to HTML by usings pandas’ method called to_html that allows you to generate a HTML table from a pandas dataframe.

![](https://github.com/poonam-ux/Web-Visualization-Dashboard/blob/main/Visualizations/data_page_large_screen_sm.png)

![](https://github.com/poonam-ux/Web-Visualization-Dashboard/blob/main/Resources/csv_to_html.png)
    
* The website has a navigation menu, at the top of every page, that:
    * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
    * Contains a dropdown menu on the right of the navbar named “Plots” that provides a link to each individual visualization page.
    * Provides two more text links on the right: “Comparisons,” which links to the comparisons page, and “Data,” which links to the data page.
    * Is responsive (using media queries).

![](https://github.com/poonam-ux/Web-Visualization-Dashboard/blob/main/Visualizations/navigation_menu_large_screen_sm.png)
