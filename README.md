# Weather-Analysis-Web-Page
 
       
       
       The Web Design Challenge makes use of data and charts generated in the Python API WeatherPy
       Challenge in order to create a responsive website using HTML and CSS.  Website can be viewed at:
       http://kmspitzer.github.io/Weather-Analysis-Web-Page/
       
       Data:
       -----
       The cities.csv file created as output of the WeatherPy functionality is read in to a Pandas
       dataframe, the index is converted to a regular column, the columns are rearranged for display
       on our website, and the file is written to Resources/cities.html to facilitate use in our
       weather_data.html page.
       
       
       Navigation Bar:
       ---------------
       Each page of the website has the same navigation bar, using the Bootstrap navbar class.
       The brand button will always take the user back to the landing page.  To the right,
       there is a dropdown menu leading to our visualization pages, one for each of our 4 main
       plots, a link to a comparisons page, a link to a data page, and a link to a Bootstrap
       Carousel page containing Northern and Southern Hemisphere comparisons (Bonus functionality).
       The navigation bar is responsive, and changes the right-side links to a dropdown menu icon
       (hamburger) on smaller pages to preserve all navigation bar functionality.
       
       Landing Page:
       -------------
       The landing page consists of a summary of the WeatherPy project, and a sidebar with photo
       links to our visualization pages.
       
       Visualization Pages:
       --------------------
       Each visualization page displays the appropriate plot in the main page area, followed by
       a short description of the plot.  To the right is the sidebar with photo links to all of
       the visualization pages.
       
       Comparison Page:
       ----------------
       The comparison page displays all 4 main plots so that the user can compare them to one
       another. Each plot links to the corresponding visualization page.
       
       Data Page:
       ----------
       The data page displays a table of the city data used in the creation of the plots.  The
       table scrolls vertically and horizontally, when the screen is narrow and scrolling is
       needed to see all columns.
       
       BONUS: Hemispheres Carousel
       ---------------------------
       I added additional functionality which lands on a descriptive page introducing the
       comparisons between Northern and Southern Hemisphere data which we generated in
       the WeatherPy project.  The carousel proceeds to the next or previous slide upon
       user click on the outer carousel arrows.  The carousel will not change slides without
       user action.
       
       Each subsequent slide on the carousel contains Northern and Southern Hemisphere plots
       of a weather phenomemon, and each image has an associated descriptive paragraph.  On
       hover, the image will zoom in for closer user inspection.
       

