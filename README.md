# Recipe Sharing App

This is a Flask-based web application that allows users to sign up, log in, and create their own accounts. Users can post their recipes, including a photo, title, and description. Other users are able to view these recipes, comment on them, and interact with the content.

---

## Key Features

- **User Authentication:** Users can sign up, log in, and manage their accounts.
- **Recipe Posting:** Users can create and post their recipes, including a photo, title, and description.
- **Recipe Viewing:** Other users can browse and view posted recipes.
- **Comments:** Users can comment on recipes to share feedback or suggestions.
- **Edit and Delete:** Users can edit or delete their own posted recipes.
- **Search:** Users can search for recipes by name to quickly find content of interest.

---

## Project Structure

```plaintext
.
├── main.py                  # Main application file to run the Flask server
├── table.py                 # Models for database (SQLAlchemy)
├── templates/               # HTML templates for user interface
│   ├── index.html           # Registration page
│   ├── login.html           # Login page
│   ├── post_receipe.html    # Recipe creation and search page
│   ├── getData.html         # Recipe detail page with comments and likes
│   ├── showData.html        # Recipe listing page for editing and deleting posts
│   ├── editPost.html        # Edit recipe page
│   ├── layout.html          # Base layout for other templates
├── static/                  # Static files (CSS, JS, images)
│   └── images/              # Folder to store image files
│       └── 1.jpg            # Example image used in the 

```
---

## Required Libraries

- Flask: The core web framework for building the web application.
- Flask-Login: For handling user authentication and managing sessions.
- Flask-WTF: For form handling with validation and CSRF protection.
- WTForms: For creating web forms.
- Flask-SQLAlchemy: For interacting with the database.
- Flask-Migrate: For database migrations (optional, but useful for database versioning).
- Flask-Uploads: For handling file uploads.
- Flask-Bcrypt (Optional, if you want password hashing for security, not used in your current code but recommended).

## Files

- `login.html`: Login page for the Recipe Sharing App, where users can log in using their email and password.
- `index.html`: Registration page for users to sign up by providing their email, username, and password.
- `post_receipe.html`: Page to search for meals based on ingredients and share recipes with title, description, and image.
- `getData.html`: Page displaying detailed information about a recipe, including an image, title, description, comments, and likes.
- `showData.html`: Page listing recipes, allowing users to edit or delete posts.
- `editPost.html`: Page to edit the title and description of a recipe.
- `layout.html`: Basic structure for Flask templates with common elements like headers and footers.
- `main.py`: This is the main file that runs the Flask application. It handles routing, user authentication, recipe creation, and other application logic like liking and commenting on posts. It uses Flask-Login for user sessions, Flask-WTF for form handling, and integrates with the SQLAlchemy database for data storage.
- `table.py`: This file contains the database models for the application. It defines the structure of the database tables using SQLAlchemy, including users, post_receipe, comments, and likes models. These models are used to interact with the database, store user and recipe data, and track interactions like comments and likes.


## Screenshots
# Recipe Sharing App

This is a Flask-based web application that allows users to sign up, log in, and create their own accounts. Users can post their recipes, including a photo, title, and description. Other users are able to view these recipes, comment on them, and interact with the content.

---

## Key Features

- **User Authentication:** Users can sign up, log in, and manage their accounts.
- **Recipe Posting:** Users can create and post their recipes, including a photo, title, and description.
- **Recipe Viewing:** Other users can browse and view posted recipes.
- **Comments:** Users can comment on recipes to share feedback or suggestions.
- **Edit and Delete:** Users can edit or delete their own posted recipes.
- **Search:** Users can search for recipes by name to quickly find content of interest.

---

## Project Structure

```plaintext
.
├── main.py                  # Main application file to run the Flask server
├── table.py                 # Models for database (SQLAlchemy)
├── templates/               # HTML templates for user interface
│   ├── index.html           # Registration page
│   ├── login.html           # Login page
│   ├── post_receipe.html    # Recipe creation and search page
│   ├── getData.html         # Recipe detail page with comments and likes
│   ├── showData.html        # Recipe listing page for editing and deleting posts
│   ├── editPost.html        # Edit recipe page
│   ├── layout.html          # Base layout for other templates
├── static/                  # Static files (CSS, JS, images)
│   └── images/              # Folder to store image files
│       └── 1.jpg            # Example image used in the 

```
---

## Required Libraries

- Flask: The core web framework for building the web application.
- Flask-Login: For handling user authentication and managing sessions.
- Flask-WTF: For form handling with validation and CSRF protection.
- WTForms: For creating web forms.
- Flask-SQLAlchemy: For interacting with the database.
- Flask-Migrate: For database migrations (optional, but useful for database versioning).
- Flask-Uploads: For handling file uploads.
- Flask-Bcrypt (Optional, if you want password hashing for security, not used in your current code but recommended).

## Files

- `login.html`: Login page for the Recipe Sharing App, where users can log in using their email and password.
- `index.html`: Registration page for users to sign up by providing their email, username, and password.
- `post_receipe.html`: Page to search for meals based on ingredients and share recipes with title, description, and image.
- `getData.html`: Page displaying detailed information about a recipe, including an image, title, description, comments, and likes.
- `showData.html`: Page listing recipes, allowing users to edit or delete posts.
- `editPost.html`: Page to edit the title and description of a recipe.
- `layout.html`: Basic structure for Flask templates with common elements like headers and footers.
- `main.py`: This is the main file that runs the Flask application. It handles routing, user authentication, recipe creation, and other application logic like liking and commenting on posts. It uses Flask-Login for user sessions, Flask-WTF for form handling, and integrates with the SQLAlchemy database for data storage.
- `table.py`: This file contains the database models for the application. It defines the structure of the database tables using SQLAlchemy, including users, post_receipe, comments, and likes models. These models are used to interact with the database, store user and recipe data, and track interactions like comments and likes.


## Screenshots


![image](https://github.com/user-attachments/assets/7c6955ba-2493-458a-8108-dc551f28f317)
![image](https://github.com/user-attachments/assets/769f39c6-f472-4558-a626-91403deddee6)
![image](https://github.com/user-attachments/assets/dc9f3456-d261-4e65-8c3a-da014a328c54)
![image](https://github.com/user-attachments/assets/fa4e578a-e892-40df-b1aa-8458518935dc)
![image](https://github.com/user-attachments/assets/44d5a6fb-2f18-4572-bc47-6cc60826d749)






