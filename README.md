# Mac OSX Background Changer

After trying multiple background apps for the Mac I finally decided to build my own. I wrote this on the way to work in the train so still has some work ToDo. This is a Python script which connects to the Unsplash.com API, grabs a random HD picture from unsplash and chnages your background.

## How do I use it?

Before you can use this amazing script you will need to [Register with Unsplash](https://unsplash.com/developers) and then [create an application](https://unsplash.com/oauth/applications). Once you've created an application copy the application ID and insert it into the pyton script under the Application ID section.  

Make a directory on your Mac and clone this project into this folder. To run the script:


    python background.py

Once you get the hang of the script you can easily add this to your crontab to run once or several times a day.

# Next steps
I will keep adding functionality to this script and may even create a Mac toolbar app.

1. Create options in the script to pull certain category of pictures (Nature, city scapes, etc)
2. Add meta data to the picture (Photographer, location, maybe camera type?)
3. Automate the script to run n times per day, week, etc
4. integrate into a Mac menu bar app
