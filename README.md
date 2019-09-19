Catherine Sherman <br>
Assignment 3 - Persistence: Two-tier Web Application with Flat File Database, Express server, and CSS template
===

Due: September 16th, by 11:59 AM.

## The Ultimate Take-Along To-Do List
https://a3-catsherman.glitch.me/

  The goal of this project was to expand upon my previous to-do list project. To do this, I used express, passport authenticaion, lowdb, and express middleware.
It was challenging to get all of the pieces put togeter, and have the server, database, and client communicate correctly. I chose the passport local stategy for authentication
because, prior to this class, I have very little web development and computer science experience. I chose to use lowdb for the same reason. Putting this project together, although
it built upon last week's work, was a huge challenge. I used two CSS frame works, one from CSS Zen Garden (which Prof. Roberts said was okay), and the light weight awsm.css template
from https://github.com/troxler/awesome-css-frameworks. I chose the CSS Zen Garden one because I really liked how unique it was. I only used it on one page beacuse I knew it wouldn't fit
the to-do list table theme well. I added button styles to the CSS in that page because it previously had none. I chose the awsm.css templete because I liked how straight forward it was (which was 
again a plus with my limited background).

Express Middleware Packages: 
- body-parser: parses the body on the server side
- session:  creates a session Id, cookies can be session specific 
- passport: Used in authentication, and cookies
- helmet: helps with header security
- response time: records the response time for requests 

The account that is already set up is: <br>
    username: cat <br>
    password: cats

Note: I developed this project locally because the database was acting funky with glitch. It seemed to work just fine locally (and I did test it in glich later), but if there are any weird problems please let me know (like modify or delete not registering right away or something).

## Technical Achievements
- **Tech Achievement 1**: I added a separate section for adding accounts/users to the database. It only allows the user to be added if the username is not already in the database.
- **Tech Achievement 2**: I also added extra password security by storing them in salt and hash instead of just plain text.

### Design/Evaluation Achievements
- **Design Achievement 1**: I tried to adapt the CSS Zen Garden template I like to better fit my index page. The original page was much longer.
- **Design Achievement 2**: I used http://mkweb.bcgsc.ca/colorblind/ and https://venngage.com/blog/color-blind-friendly-palette/#5 to learn more about color-blindness. It didn't look like I would need to change my homepage, but I adjusted all of the font, button, and table colors on the userpage template to be color-blind friendly (I used black instead of red-brown).
