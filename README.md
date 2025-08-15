# GradedActivity

# Django Twitter Application

This is a simple Django application that allows users to register, post tweets with optional images, and view a feed of tweets.

## Features

- User registration with username filtering (prohibits "shit", "fuck", "bobo").
- User login and logout.
- Create tweets with text and optional image uploads.
- View a list of all tweets.

## Setup Instructions

Follow these steps to get the project up and running on your local machine.

### Clone the Repository

```bash
git clone https://github.com/KohlYumul/GradedActivity
cd GradedActivity

```
### Run the Server

```bash
py manage.py runserver

```

###Note

If error occurs on the first run, run this command

```bash
py manage.py makemigrations
py manage.py migrate

```

### How to Use
1. Register an Account
Navigate to http://127.0.0.1:8000/register/.

Fill out the registration form.

Note: Usernames cannot contain the words "shit", "fuck", or "bobo".

2. Login
If you registered, you'll be automatically logged in. Otherwise, navigate to http://127.0.0.1:8000/accounts/login/ to log in.

3. Create a Tweet
Once logged in, click on the "Create New Tweet" link or navigate to http://127.0.0.1:8000/tweet/create/.

Enter your tweet text.

Optionally, upload an image.

Click "Tweet" to post.

4. View Tweets
The home page (http://127.0.0.1:8000/) displays all tweets in reverse chronological order.





