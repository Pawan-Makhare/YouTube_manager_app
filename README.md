# YouTube manager app


## Description

This Python application is a simple YouTube video management system that allows users to perform the following operations:

- **List all videos**: Retrieve and display a list of all videos stored in the MongoDB database.
- **Add new Video**: Add a new video to the database with a name and duration.
- **Update a Video**: Update the name and duration of an existing video in the database.
- **Delete a Video**: Remove a video from the database by providing its ID.
- **Exit the App**: Quit the application.

The application uses the `pymongo` library to interact with a MongoDB database hosted on MongoDB Atlas. The database name is `ytmanager`, and the collection name is `videos`.

## Features

- **MongoDB Integration**: The application uses MongoDB as the backend database to store and retrieve video information.
- **CRUD Operations**: The application provides a menu-driven interface to perform Create, Read, Update, and Delete operations on the videos.
- **User-Friendly Interface**: The application presents a simple and intuitive command-line interface for users to interact with the video management system.

## Usage

1. Ensure you have Python 3 installed on your system.
2. Install the required dependencies by running `pip install pymongo`.
3. Update the MongoDB connection string in the code with your own credentials.
4. Run the application by executing the Python script: `python youtube_manager.py`.
5. Follow the on-screen instructions to perform the desired operations.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open a new issue or submit a pull request.

