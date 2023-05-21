# Comment App

This is a simple web application that allows users to add, like, and delete comments. The app provides the following functionalities:

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/comments-app-output-v0.gif" alt="comments output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>



## Functionalities

1. Initial State:
   - The list of comments is initially empty.
   - The input fields for name and comment are empty.

2. Add Comment:
   - When the user enters non-empty values in the input fields and clicks the "Add Comment" button, a new comment is added to the list of comments.
   - The comments count is incremented by one.
   - The values of the input fields for name and comment are reset to their initial empty state.

3. Like Button:
   - Each comment in the list has a "Like" button associated with it.
   - When the "Like" button of a comment is clicked:
     - If the image for the button is the "Like" image, it should be changed to the "Liked" image.
     - If the image for the button is the "Liked" image, it should be changed back to the "Like" image.

4. Delete Button:
   - Each comment in the list has a "Delete" button associated with it.
   - When the "Delete" button of a comment is clicked:
     - The comment is removed from the list of comments.
     - The comments count is decremented by one.



## Usage

To use this app, follow these steps:

1. Clone the repository or download the source code.
2. Install the necessary dependencies by running `npm install` in the project directory.
3. Start the development server by running `npm start`.
4. Open your web browser and navigate to `http://localhost:3000` (or the specified port).
5. Interact with the app by adding comments, liking comments, or deleting comments.

