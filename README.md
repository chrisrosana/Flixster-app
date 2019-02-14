# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF
`TODO://` Add the URL to your animated app walkthough `gif` in the image tag below, `YOUR_GIF_URL_HERE`. Make sure the gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after after adding gif)

<img src="YOUR_GIF_URL_HERE" width=250><br>

### Notes
Describe any challenges encountered while building the app.
---
Encountered an error called "Thread 1: signal SIGABRT" whenever I tap/clicked the "Superhero" tab on the iPhone. At first I tried to clean and re-build the project but the error still shows up. To resolve the problem, I did some research and based on what I found, my Movie Grid Cell from the Main Storyboard doesn't have an identifier to link with the MovieGridCell.swift.

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthough GIF

<img src="https://raw.githubusercontent.com/chrisrosana/Flixster-app/master/flixApp.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.
---
I was having a problem importing the AlamofireImage. Even though I installed, opened, and added the pod file correctly, I couldn't build the project since it doesn't recognize the AlamofireImage module. But one thing I did do to resolve this problem based on my research is to update the pod on the terminal and clean and build the project folder again.
