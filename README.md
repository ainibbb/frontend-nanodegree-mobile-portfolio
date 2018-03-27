# Website Optimization Project
###### Udacity Frontend Development Nanodegree

### Project Instrcutions

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path 
and make this page render as quickly as possible by applying the techniques you've picked up in the Critical Rendering Path course.

### How to Use

To run this website, complete the following: 

1. Check out the repository
2. Run the following command in the project folder

  ```bash
  $> cd /path/to/your-project-folder
  $> python3 http.server
  ```

3. Open your favorite web browser and go to the following server: 

  ```
  localhost:8000
  ```

### Optimizations 

- Compressed images for faster loading
- Removed render blocking CSS by adding media queries
- Asychronously loaded JavaScript files
- Removed code causing force synchronous layouts
- Replaced ```.querySelector()``` with ```.getElementById()``` and ```.getElementsByClassNames()```
