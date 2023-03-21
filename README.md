
# Reddit Favourites App

The React Reddit Favourites App allows a user to keep a list of their favourite Reddit posts. The app uses the Reddit API to fetch the top 10 posts from a subreddit sorted by "hot", allows the user to select their favourite posts, and stores the IDs of those posts in the user's browser using the Web Storage API.

##  Disclaimer
The project available in this repository is an academic project and is not intended to be publicly available since it is related to academic coursework, and there is a potential for academic misconduct if it is used improperly. Therefore, only a video recording of the project is available for viewing.

If you would like to request access to code base and additional materials related to this project, please contact me directly and make your request. Please note that access to any additional materials will be granted solely at my discretion and only for legitimate educational or research purposes.

By accessing the video recording of this project, you acknowledge and agree that you will not use it for any unauthorized or unethical purposes, and that any misuse of the project may result in serious consequences, including academic penalties and disciplinary action.
## Features
- Allow the user to input the name of a subreddit and fetch the top 10 posts sorted by "hot".
- Allow the user to select favourite posts from the listing of posts in a subreddit.
- Display a list of the user's favourite posts (from all subreddits), and allow the user to remove posts from their favourites.
- Store the IDs of posts using the Web Storage API.
- Display the post's score, title, and a link to the post's comments page for both the subreddit listing and the list of favourite posts.

## Tech Stack
- JavaScript
- React
- React Router
- Axios
- Web Storage API

## Requirements
- Node.js
- npm or yarn

## Run Locally
To run the React Reddit Favourites App locally on your machine, follow these steps:

- Clone the repository
`git clone https://github.com/<username>/react-reddit-favourites.git`
- Install the dependencies
```
cd react-reddit-favourites
npm install
```
- Rename the .env.example file to .env and replace the placeholder values with your Reddit API credentials.
- Start the development server:
`npm start`
- Open your web browser and go to http://localhost:3000 to view the app.

## Demo

