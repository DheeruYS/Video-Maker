# Video Maker
This is the course project for Introduction to Software Systems (ISS) course.  

This is a web tool for people to create videos out of images with background music. 

User can upload the images and audios which will be saved in their profile. When creating the video, the user can reorder the uploaded images, set custom duration and transition for each image and set custom duration for the background audio.

## Run

To run this tool on your local machine, first make sure you have the latest version of python.

Then run the following command

    pip install -r requirements.txt 
    
Now, To connect to the online DB, run the following command

    export DATABASE_URL="postgresql://beyond_infinity:PQz31GpRhRGyG5ZxPMq8kw@beyondinfinity-8907.8nk.gcp-asia-southeast1.cockroachlabs.cloud:26257/defaultdb?sslmode=verify-full"

Then run the python file with the command

    python3 app.py

Website is now hosted locally at http://127.0.0.1:5000/. 

## Contributors

[Arnav Sharma](https://github.com/iamarnav08)

[Hardik Chaddha](https://github.com/Hardik1106)

[Sudheera Y S](https://github.com/DheeruYS)
