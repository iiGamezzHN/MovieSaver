# MovieSaver app

## Goals

This app aims to help you remember all the films that you don't want to forget.

## Problem

> Write a statement about the problem that your finished project will solve. 
	The problem1 has to be clearly described and very specific. In total, keep the problem statement to four or five lines of text.
	
When you've seen a lot of movies it becomes problemetic to remember all the good ones. It's inefficiënt to just note down the
names of the movies you like, because that doesn't give you a lot of information. It's also inefficiënt to save webpages of the
movies with information. So what you need is a way to save your favourite movies, with pictures, cast, synopsis and posibly
even your own rating

## Solution

### Description and visualization

Describe your solution in full detail.

- Summarize your idea in a single sentence, connecting it to the “gap” that you describe.

In this app you can save all your favourite movies complete with picture, cast, synopsis (and your personal rating)

- Include a visual sketch of what the final product will look like for the user; 
if you envision the application to have multiple screens, sketch these all out separately. 
Clearly specify the possible user interactions, and include concrete examples of data. 
Your sketches do not have to be professional-looking, but they have to be complete and neat!


### Features

> Include a list of main features that will be available to users. All features should also be visible in the sketch. 
Keep it brief.

Main features:
- Search for movies
- Search for future movies
- Save movies

> Split the features into 1) the minimum viable product (MVP) and 2) parts that are optional to implement.

> A minimum viable product is the product with as least features as possible, which still helps solve the problem for your 
  target audience. We think it’s important to clearly define this, because it defines the minimum amount of work that you 
  will have to put into the project.

Minimum viable product:
- Search for movies
- Search for future movies
- Save movies
- Save series (if available)
- Remove movies from saved list

Optional part:
- Rate saved movies
- Sort saved movies
- Save favourite actors
- Set alarm for release of future movie
- Include a trailer

## Prerequisites
### Data Source

The data of the movies is acquired through the Rotten Tomatoes API. Information can be found at the 
[Any API](https://any-api.com/rottentomatoes_com/rottentomatoes_com/docs/Search/MoviesSearchSearch/) website. The data for
the future movies can also be found on the 
[Any API](https://any-api.com/rottentomatoes_com/rottentomatoes_com/docs/Movie_Lists/UpcomingMoviesMovieLists/) website.

> List the data sources that you will use and whether you will need to transform the data before it is usable for 
your application. The list should include links to where the data sources can be downloaded or accessed.

### External components

> List the external components (libraries like d3-tip or SQLite) that you need to implement certain features. 
Include the names, and if the component is not standard, include a link to its website.

I might have to use SQLite or something like that, since SharedPreferences might not be enough to save all the data.

### Review of similar apps/vizualizations

Rotten Tomatoes (website): The website of RT is the origin of the API that I will use. You can search for movies, series, 
top movie, lists and actors. All items can be rated by both critics and normal people, so it gives you an overview of how the
critis rate is versus how the average person rates it. You are able to add things to your "To Watch" list or your "Not 
Interested" list. You can't log in on the website on your phone though, so the lists are unusable, and they don't have an app.

Filmy (app): This app let's you search for movies and series and gives you information on them. They also show popular and 
upcoming films. Unfortunately you get an ad each time you click something, whidh is really annoying and is something why I would
never use it.

> Include a review of similar mobile apps or related visualizations, in terms of features and technical aspects: 
what do they do? how have they implemented it? can you do it in the same way?

### Hardest parts

I think the hardest part is going to be to get the API to work properly. And also to only get the information that I want to
save and pass it through.

> Identify the hardest parts of implementing your application: think of technical problems or limitations that could 
arise during development and what possibilities you have to overcome these.

