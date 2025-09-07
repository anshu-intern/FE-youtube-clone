# YouTube-Clone-Using-the-MERN-Stack
YouTube Clone Using the MERN Stack

Front end for YouTube clone where users can view and interact with videos.
This project is built using MongoDB,Express, React, and Node.js (MERN stack).


Front-End (React)

    1. Home Page:
    ○ Displays a YouTube Header.
    ○ Displays a static sidebar which you can toggle from the top hamburger menu.
    ○ Displays filter buttons at the top.
    ○ Displays a grid of video thumbnails.
    ○ Each video card shows:
        ■ Title
        ■ Thumbnail
        ■ Channel Name
        ■ Views
        ■ Upload date
        
    2. User Authentication:
    ○ Allow users to register and log in with:
        ■ Username
        ■ Email
        ■ Password
    ○ JWT for authentication.
        Before Sign In , header has sign in button.
        When the user clicks on sign in , then it takes to a new URL where user can login and register.
        After signing in , his/her name is be present at the top of the home page in the form of icon.

    3. Search and Filter Functionality:
    ○ Implemented a search bar on the homepage.
        This search bar is present in the header and filters videos based on title.
    ○ Filter buttons are  implemented and filters work based on category.

    4. Video Player Page:
    ○ Displays the selected video with:
        ■ Video player
        ■ Title and description
        ■ Channel name
        ■ Like and dislike buttons
        ■ Comment section (Ignored nested comments for now)

        Users are able to add , edit and delete comments. 
        When a new comment is added , then it is saved in the database along with that video.

    5. Channel Page:
    ○ Options to create a channel only after the user is signed in.
    ○ Displays a list of videos which belong to that particular channel.
    ○ Allows the user to edit or delete their videos.


------------------------------------------------------------------------------------------------------------------------------

🛠️ Technologies Used:

● Frontend:         React, React Router, Axios, Date-fns, Tailwindcss

● Authentication:   JWT (JSON Web Tokens)

● Version Control:  Git and GitHub


--------------------------------------------------------------------------------------------------------------------------------

📦 Installation

1. Clone the repository
    git clone https://github.com/anshu-intern/FE-youtube-clone.git

2. For frontend: 
    a. Navigate into the project directory inside the downloaded folder

    b. Install dependencies
        npm install

    c. Run the development server
        npm run dev

-----------------------------------------------------------------------------------------------------------------------------

Live production deployment (no installation needed):

This project is deployed over the internet using VERCEL.

Access this deployed application on the following link: 

Try it out and do share your valuable feedback!

Thanks!
