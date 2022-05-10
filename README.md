# Messaging App
> A web application that allows users to send direct messages, create/edit channels, and sends SMS notifications. This project utilizes the Stream Chat API for the in-app chat messaging, and the Twilio API to send/receive SMS messages.
> Live demo [_here_](https://garcia116.github.io/messaging-app/). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->

## Technologies Used
- React - version 17.0.2
- Stream Chat - version 5.4.0
- Twilio API
- Heroku


## Features
- Send direct chat messages. All message functionalities such as emojis, file attachments, and gifs available.
- Create/edit channels
- User Dashboard with a search function that allows users to search for certain channels or users.
- Receive SMS message notifications when a user is offline

## Screenshots
#### Sign-up component
<img width="440" alt="chat-1" src="https://user-images.githubusercontent.com/38366630/166405565-e7a039f7-bd89-4091-999f-8c6ca75d3cb7.png">

#### Sign-in component
<img width="440" alt="chat-2" src="https://user-images.githubusercontent.com/38366630/166405582-39136289-38aa-40b1-a316-595ef405dd44.png">

#### Team Channel component
<img width="440" alt="chat-3" src="https://user-images.githubusercontent.com/38366630/166405587-d4093ae3-6e3a-49c6-9547-456b7fdd0456.png">

#### Create a new channel
<img width="440" alt="chat-4" src="https://user-images.githubusercontent.com/38366630/166405590-05ffab16-4cfe-46e8-98f2-c42cda1a6772.png">

#### Edit a channel
<img width="440" alt="chat-5" src="https://user-images.githubusercontent.com/38366630/166405593-13f72f33-d5e7-44de-8408-3d38b8f9392a.png">
<!-- If you have screenshots you'd like to share, include them here. -->


## Setup
Make sure to have React and Heroku installed on your operating system.
Clone this repository. `git clone https://github.com/garcia116/messaging-app.git`
The project dependencies are located under the 'client folder in the 'package.json' file.

First, setup the server folder by creating your own Stream-chat account [_here_](https://getstream.io/chat/) and a Twilio account [_here_](https://www.twilio.com/sms).
After account creations, using your code editor app, go to the project directory and into the 'server' folder, and copy the '.env.sample' file and create a new '.env' file. Inside the '.env', paste your account credentials for the Stream Chat API and the Twilio API.

Create a new Heroku app. `heroku create example`
The server will be running on Heroku. On the project directory shell, run `cd server`. Then add, commit, and push changes to heroku(be sure to be logged in to Heroku `heroku login`).

On the project directory, go to the 'components' folder under the 'client' folder, and open up the 'Auth.jsx' file. Under the 'handleSubmit' function, change the 'URL' key by inputting your own Heroku URL. Now your project should be ready to run.


## Usage
Open up a shell on your project directory, run `cd client` and run `npm start` to start your server.

Navigate to your localhost to view project.


## Room for Improvement

Room for improvement:
- Adding voice channel features

## Acknowledgements
- This project was based on [this tutorial](https://www.youtube.com/watch?v=MJzbJQLGehs&list=PL7jlr9JC8Zqsf3kbq4I3_8L2JcJVbTpkU&index=5).


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->


# Chat Messaging App
### View Project Demo [Here](https://garcia116.github.io/messaging-app/)

