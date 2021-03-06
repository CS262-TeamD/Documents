# The Vision
Our team seeks to create an app to coordinate cleaning assignments and schedules for Calvin Cleaning Crew employees and supervisors. The current system uses paper housekeeping logs and contact lists. These logs waste an estimated 8580 sheets of paper a year. They are also error-prone and innefficient. Our app will remedy this by providing a straightforward interface for instant access to a personalized list of cleaning assignments for employees, a list of cleaning yet to be done, employee information, and time-off requests for supervisors.
# The Details
Upon opening the app, employees can log in and see, in a simple bulleted list, all their cleaning assignments by room numbers, and check them off as they're completed. Employees and supervisors should both be able to leave comments attached to rooms that are visible between other employees and supervisors alike. Employees should be able to easily and straightforwardly request time off to their supervisor.
When a supervisor opens the app, they see a list of rooms that need cleaning, as well as a list of their available employees. From there, they can delegate cleaning assignments to their employees, write and view comments, and check if cleaning has been done. When a time off request is made by an employee, supervisors can either approve, revise, or decline the request.
Eventually, we would like to include the directory of buildings and rooms visibly on a searchable map of campus. Users could also have the ability to leave photos in room comments, and link their schedules to an interactive calendar.
# Non-Functional Requirements
In addition to what the app does, there are also some limitations and requirements regarding <i>how</i> the app operates.
- The app must be built for Android
- The app must run on any smartphone released in the last five years.
- Users should be able to figure out how to use the entire UI in 5 minutes or less.
- Errors should be handled without crashing.
- Several users should be able to use the app at the same time. 
- Communicating with the server shouldn't take more than 5 seconds.

# Where We Ended Up
Our current prototype (at the end of the semester) implements a login screen, which proceeds to the checklist landing page, and the ability to attach comments to rooms. There is a checklist organized by room subheading. The menu on top can navigate to a search tab, allowing the user to search other employees. It also includes an About page with a version of our vision statement and our team members' names. A separate page is loaded if a user logs in with supervisor credentials. This screen allows the users to delegate cleaning tasks to employees and add comments. Our app has also been linked to our database, rather than displaying hard-coded values.
