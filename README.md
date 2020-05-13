## React webapp - restful JSON API

A webapp build using react that queries this paginated endpoint and prints out the results as a list

Restful JSON API is provided at http://nyx.vima.ekt.gr:3000


### Test the app
<li>Clone this repository to your local machine</li>
<li>Install dependencies 'npm install'</li>
<li>Start the application 'npm start'</li>

### Overview
<li>Fetch JSON data from http://nyx.vima.ekt.gr:3000/api/books/</li>
<li>Apply custom pagination with page number reflected in the url</li>
<li>Add a search field that upon request populates the `filters` post parameter</li>

### Future Changes
<li>The horizontal scrollbar moves when a user clicks a page number (document.getElementById("book-listing-paginate").scrollLeft += this.state.page;)</li>
<li>Additional filters (filter by year/country)</li>
<li>Add additional scss files/mixins</li>
<li>Lazyload items</li>
<li>Scroll to top function</li>
<li>Deploy app into Github Pages ("deploy": "gh-pages -d build")</li>
