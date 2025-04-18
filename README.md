Develop a React based Social Media Analytics Frontend Web Application

As a developer, you have been provided with access to the APIs of a social media platform. Your task is to build a responsive React frontend web application that delivers real-time analytical insights.

While social media platform APIs typically restrict data access to the user making the API calls, the test server grants you access to posts and comments from various users concurrently.
Your users, who are business stakeholders monitoring user behaviour (distinct from the social media platform's users), are assumed to be pre-authorised. Therefore, your application must not require user registration or login for viewing any developed pages.
The server's API provides data on users, their posts, and the comments associated with each post. The data received may be in an unsorted order.
Your React application must run exclusively on http://localhost:5500.
Your application should consist of three pages:
Top Users: Display the top five users with the most commented posts. Consider the efficient storage and retrieval of user posts' comments count.
Trending Posts: Display the post(s) with the maximum number of comments. If multiple posts meet this criterion, display all such posts. Think about how you will maintain and efficiently identify the post(s) with the highest comment count, especially when dealing with unsorted and potentially large datasets.
Feed: Display the posts in real-time, with the newest posts appearing at the top. This page must be dynamic, reflecting posts returned by the backend server even after the initial page load.
