# Shortest-Path-Finder-PythonProject
Uses the concept of BFS(Breadth First Search) to find out the shortest path between start and end point. 
![demo](https://user-images.githubusercontent.com/53531220/85393786-30054000-b56b-11ea-851e-54fa41684586.PNG)
# About the program
A window is opened in front of the user once this program is runned.
A set of quick instructions is provided at the top of the window.
A grid is present on the window , where the user can put the starting and ending point by choosing the respective key on the keyboard and clicking on any block of the grid. 
User can also place hurdles(obstacles) one by one in the grid, by clicking in the particular position in the grid.
Each press of 'r' in the keyboard places 100 hurdles(obstacles) at random positions in the grid.
After that the user can hit the "spacebar" to see the program finding out the shortest path between start and end point.
Press 'o' to clear the grid.
# About the python modules used
Turtle: To do the overall visualisation of the entire process
Tkinter: To show info if there is not path available between start and end points 
random: to place the obstacles randomly at any point of the grid
numpy: to create 2d arrays to be used as adjancency matrix , also used in making some other necessary arrays. 
