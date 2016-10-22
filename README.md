## Website Performance Optimization portfolio project

### Getting started

Some useful tips to help you get started:

1. Check out the repository vinayeh10.github.io
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights!

OR

2. Host your files on Github with username.gitub.io as repository name and use  the username.github.io URL to analyze the page in pagespeed Insights

####Part 1: Optimize PageSpeed Insights score for index.html

Visit https://vinayeh10.github.io to view live site.

Optimizations include:
- CSS and JavaScript minified
- Async JavaScript tagged
- Media specifc CSS tagged
- Inline CSS
- Anyalytics script move below the fold
- Images optimized



####Part 2: Optimize Frames per Second in pizza.html

Clone or download this repository and view pizza.html to see the site.

Optimizations include:
- document.getElementById() and document.getElementsByClassName() Web API calls used for speed
- DOM calls moved outside of for loops and saved to local variable
- Saved array lengths in local variable
- Declare variables outside of loops
- window.screen.height and window.screen.width used to calculate number of pizzas needed to fill browser window  

### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
