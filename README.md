Description:

The provided React component allows users to input a GitHub username. Upon submission, it fetches the public information of the GitHub user from the GitHub API and displays it in a card format. The displayed information includes the user's avatar image, username, name, number of public repositories, number of public gists, and profile creation date.
I have deploy this project on Netlify and i have mentioned below link to view my project.

Netlify Link : https://github-users-inf.netlify.app

Features:

Input Field: Users can input the GitHub username they want to fetch information for.
Data Fetching: When the user submits the form, the component fetches the public information of the GitHub user from the GitHub API.
Error Handling: Error messages are displayed if the user is not found or if there is an issue with fetching the data.
Displaying User Information: Once the data is fetched successfully, the user's public information is displayed in a card format.
Responsive Design: The component is designed to be responsive and usable on various screen sizes.

Technologies Used:

React.js: A JavaScript library for building user interfaces. React simplifies the process of creating interactive UIs.

useState Hook: Used to manage state variables in functional components. It allows the component to maintain and update state.

Axios: A popular promise-based HTTP client for making requests. Axios is used here to fetch data from the GitHub API.

GitHub API: The component fetches user data from the GitHub API. Specifically, it retrieves information about a GitHub user using their username.

Project Screens : 
![GitHub1](https://github.com/Nikhil2800/GitHub_User_Information/assets/154686273/7485eb0f-9495-450b-b31c-67208c5c67dd)
![GitHub2](https://github.com/Nikhil2800/GitHub_User_Information/assets/154686273/9dcf56dc-7477-4ee2-9106-bf6b6500bbac)
