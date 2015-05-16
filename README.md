## Website Performance Optimization portfolio project

This was a project where I took a poor-performing website and optimized it to meet 

### Getting started

####Part 1: Getting the Project to Run Locally

Some useful tips to help you get started:

1. Check out the repository
2. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

3. Open a browser and visit localhost:8080
4. Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ngrok 8080
  ```

5. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)

6. [View online version here](http://brockcooper.github.io/optimization_project/)

####Part 2: Optimizations Made

######Optimizations Made to index.html:
1. Optimized images to actual size needed
2. Reduced image sizes
3. Comibined CSS files to one file
4. Refactored CSS file to call class names instead of using CSS Combinators
4. Moved script and CSS to end of file to load last for faster initial loading times
5. Ensured non-essestial JS was loaded asynchronously
6. Minified CSS and HTML files
