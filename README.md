# Is It a Movie

Movie adaptations are getting more popular in the 21st century when readers nowadays want a different way to enrich their imagination. "Is It a Movie?" comes into play when readers do not have the time or energy for reading. This application helps readers find out whether a movie adaptation has been created using Google Books APIs and IMDb API. If there is a movie adaptation, this application will retreive rating data from the APIs for comparison. 


## Technologies Used

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [w3schools](https://www.w3schools.com/js/default.asp)
* [IMDb API](https://imdb-api.com)
* [Google Books APIs](https://developers.google.com/books)
* [Tailwindcss](https://tailwindcss.com/)
* [ParsleyJS](https://parsleyjs.org/)
* [Bootstrap](https://getbootstrap.com/)


## Deployed Link

* [Deployed Link to Live Site](https://scottybuoy.github.io/Is-it-a-Movie/)
* [Link to Github](https://github.com/scottybuoy/Is-it-a-Movie.git)


## Getting Started

When "Is It a Movie" runs on a browser, users are invited to enter a book title in a search box. This application utilizes Parsley JS's form validation library to automatically detect users' input.

After the search button is clicked, a simple confirmation page will be displayed for users to confirm whether the search title displayed is what they are looking for. After they confirm the title by clicking on the book title, the book cover will appear as designed, so does the movie poster if the movie is made based on the book. Users are able to see the book rating as well as the movie rating for comparison. 

A local storage feature is also in place so that users can see their search history when using this application.

<br>



## User Stories

As a user, I want to be able to search for a book that turns into a movie.

As a user, I want to be able to search for the information without going into different websites or using multiple applications. 

As a user, I want to compare ratings of the book and movie to know which one is better.  

<br>

### Accessing APIs

We utilized the fetch method to access two api's.

```
fetch(booksRequestUrl)
        .then(function (response) {
            return response.json();
        })
        .then(function (bookData) {
            console.log(bookData);
```

<br>

## Design Layout

![alt text](./assets/images/layout.png)

<br>

## Functionality

This is a demonstration of parsley.js assisting in user input validation.
![A preview of the planner's functionality](https://media.giphy.com/media/166yirPLymxf7j9RPM/giphy.gif)

Here we can see the whole applications functionality
![A preview of the planner's functionality](https://media.giphy.com/media/AVVnl4VYusrsUVsDVY/giphy.gif)

<br>

## CSS Framework Used

*[Tailwindcss](https://tailwindcss.com/docs/installation)


## Authors

* **Scott Everett** 
- [Portfolio](https://scottybuoy.github.io/portfolio-version-1/)
- [Github](https://github.com/scottybuoy)


* **Elliot Park** 
- [Portfolio](https://elliotpark410.github.io/Professional-Portfolio/)
- [Github](https://github.com/elliotpark410)
- [LinkedIn](https://www.linkedin.com/in/elliot-park/)

* **Mandy Tsang** 
- [Portfolio](https://mandytsang007.github.io/HMT-Portfolio/)
- [Github](https://github.com/MANDYTSANG007)
- [LinkedIn](https://www.linkedin.com/in/mandy-tsang-896b2682)

## Learning Objectives
- Upon completion of this application, we acquired the ability to get data from Google Books APIs and IMDb API.
- We sucessfully resolve merge conflicts
- We prepared a professional presentation and repository README.md
- We learned about the workflow of git branching in a collaborative project
- We designed, built, and deplolyed a client-side web application using GitHub Pages
- We practiced Agile software Development


## License

This project is licensed under the MIT License 











Send a message to Elliot Park, Hing Man Tsang






