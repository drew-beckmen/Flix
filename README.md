# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="http://g.recordit.co/2wmYeODarP.gif" width=250><br>

### Notes

The major concepts covered this week include:
* Navigation with push navigation and tab bar navigation
* Collection Views (sibling to table view)
* Passing data from one view to another (utilizing the `prepare` method and the `sender` parameter)
* Creating a detail view for a specific movie

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthrough GIF

![demo](flixster.gif)

### Notes
For a while, I worked to resolve the issue of the table view's scrolling bar not hugging the right side of the screen. I did not solve the issue, but I hope to continue troubleshooting when we work on part 2 next week. I am excited to learn about Auto Layout to create apps that are responsive on all different screen sizes!
