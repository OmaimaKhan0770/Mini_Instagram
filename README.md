# Instagram Buddy

Instagram Buddy is a console-based social media application written in C++. It allows users to create accounts, log in, send friend requests, post messages, and interact with other users.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Credits](#credits)

## Features

- **User Authentication**: Sign up and log in with unique usernames.
- **Friend Requests**: Send and accept friend requests.
- **Messaging**: Send and view messages.
- **Posting**: Share posts and view them.
- **Notifications**: View notifications for friend requests and messages.
- **Search**: Search for other users.

## Requirements

- Windows OS (due to the use of Windows-specific libraries)
- C++ Compiler (e.g., g++, Visual Studio)

## Installation

1. Clone the repository or download the source code.
2. Open the project in your preferred C++ IDE or compiler.
3. Compile and run the code.

## Usage

1. Run the compiled executable.
2. Follow the on-screen instructions to navigate the menu and use the application.

### Menu Options

- **Sign up**: Create a new account.
- **Login**: Log in to an existing account.
- **Send Friend Request**: Send a friend request to another user.
- **Display NewsFeed**: View posts from friends.
- **Send Message**: Send a message to another user.
- **Show Messages**: View received messages.
- **Share a Post**: Share a post with friends.
- **Search User**: Search for other users.
- **Notifications**: View notifications.
- **Accept Friend Request**: Accept a pending friend request.
- **Logout**: Log out of the current account.

## Code Structure

- **Signup Class**: Handles user registration.
- **Login Class**: Manages user authentication and the main menu.
- **FollowRequest Class**: Manages sending and accepting friend requests.
- **message_stack Class**: Manages sending and viewing messages.
- **post_stack Class**: Manages sharing and viewing posts.
- **NotificationQueue Class**: Manages notifications for users.
- **BST Class**: Binary Search Tree for efficient user search.

## Credits

- **Developer**: Omaima Khan & Dua Fatima
