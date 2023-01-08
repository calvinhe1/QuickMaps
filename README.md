# QuickMaps

QuickMaps is mapping software that provides detailed information about geographical regions worldwide, largely inspired by Google Maps. This project was written using C++, and utilizes the OpenStreetMap API for its data source, and EZGL and GTK graphics libraries for the user interface.

NOTE: This project is written for the school course ECE297, so the source code will not be made public.

# Main Features

* QuickMaps provides visualization of all geographic features (roads, buildings, points of interest, subway stations, bus routes, street names, etc.)
* User-interactive controls
    * The keyboard or the built-in buttons can allow the user to move around the map and zoom in/out to view the map more clearly
* Searching path feature
    * Provide two intersections, and the shortest path will be generated between the two points
    * The path is visualized in the UI and the directions to go from point A to point B are shown in the sidebar
    * The Djikstra’s pathfinding algorithm was implemented to help find the shortest path
* Find feature
    * By providing an intersection, street, or point of interest (e.g. restaurants, schools), the application will find and zoom into the location
    
    
# Demos

## Overall view of QuickMaps
![OverallView](https://user-images.githubusercontent.com/66074281/211181053-964665eb-0071-4d5c-ba98-64ad6731f72a.gif)

## Searching path with mouse
![SearchMouse](https://user-images.githubusercontent.com/66074281/211181129-28238123-aa62-468f-a572-1d0012c31be6.gif)

## Searching path with buttons and keyboard
![SearchKeyboard](https://user-images.githubusercontent.com/66074281/211181345-3bd4ee84-d57d-4a6f-ad9e-c4f4e3c140ab.gif)

## Finding an intersection
![FindIntersection](https://user-images.githubusercontent.com/66074281/211181332-8aab42b5-042d-4fdf-a2ff-c5dd41b387fa.gif)

## Finding a street
![FindStreet](https://user-images.githubusercontent.com/66074281/211181341-dd8fb8ff-3b5d-4b22-95e4-975464552c0a.gif)

## Finding a Point of Interest
![FindPOI](https://user-images.githubusercontent.com/66074281/211181330-f7b487b9-8341-4e8d-8522-68c8e8ea763a.gif)

