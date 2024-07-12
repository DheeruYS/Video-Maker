# Video Maker
This is the course project for Introduction to Software Systems (ISS) course (CS6.201).

This is a web tool for people to create videos out of images with background music. 

## Functionality

1. User authentication using JWT Tokens
2. Profile page with the user's saved images and audios
2. Upload images and audios with Drag-and-Drop functionality
3. Create video functionality with custom duration and animation for each image. Preloaded audio files for the background music with custom duration. 
4. Option to choose the output video resolution and dimension.
5. Search functionality in create video page for images and audios.
6. Admin Profile page to view all users

## Run

To run this tool on your local machine, first make sure you have the latest version of python.

Then run the following command

    pip install -r requirements.txt 
    
Now, To connect to the online DB, run the following command

    export DATABASE_URL="postgresql://beyond_infinity:PQz31GpRhRGyG5ZxPMq8kw@beyondinfinity-8907.8nk.gcp-asia-southeast1.cockroachlabs.cloud:26257/defaultdb?sslmode=verify-full"

Then run the python file with the command

    python3 app.py

Website is now hosted locally at http://127.0.0.1:5000/. 

## Screenshots

![Profile Image Gallery](screenshots/ProfileImage.png)

![Create Video Image Gallery](screenshots/CreateVideoImage.png)

![Audio Gallery](screenshots/AudioImage.png)

![Create Video](screenshots/CreateVideo.png)

## Contributors

[Arnav Sharma](https://github.com/iamarnav08)

[Hardik Chaddha](https://github.com/Hardik1106)

[Sudheera Y S](https://github.com/DheeruYS)