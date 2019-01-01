# Attendance-Manager
Basic android app that calculates attendance(uses recycler views, async tasks,SQLite databases, fragments)

Uses most of the basic android concepts within one project.

1.Consists of a bottom navigation view with two menu items,one to store attendance statuses of different subjects and other item a calculator that can be used to insert various values and find corresponding attendance percentages.

2.Uses shared preferences to store the minimum required percentage and to check if the user is a new user(to enable tutorial screen).

3.Uses SQLite database to store the attendance status of various subjects.

4.Uses a RecyclerView to show the attendance status of various subjects.

5.Data to be inserted into each row is retrieved from the database through AsyncTasks to decrease workload on main UI thread.

6.SQLite table is later updated using AsyncTasks each time the app is closed.
