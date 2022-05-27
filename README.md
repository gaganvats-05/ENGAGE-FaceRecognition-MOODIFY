
# Moodify🎧 - Microsoft Engage 2022


![Logo](https://socialify.git.ci/gaganvats-05/ENGAGE-FaceRecognition-MOODIFY/image?description=1&descriptionEditable=Made%20for%20Microsoft%20Engage%202022&font=Source%20Code%20Pro&language=1&logo=https%3A%2F%2Fres.cloudinary.com%2Fdgg6izgtw%2Fimage%2Fupload%2Fv1653519834%2Fremoval.ai__tmp-628eb3258f035_pbkl0a.png&name=1&owner=1&pattern=Floating%20Cogs&theme=Dark)

Have you ever felt a strong emotion but was missing that perfect song to help you let it all out?
 
 Are you looking for a product that could recommend to you songs based on how you were feeling, without you needing to do a thing? 
What you're looking for is Moodify! Just enjoy that moment, scream or cry out to a sound catered to you.

## What It Does

Moodify is a facial expression recognition-based  music suggestion website that cheers up users and saves time while searching for a song that matches their mood.

1) It capture's video from the user's webcam, feed it into a model that can predict emotions and generate an appropriate target tag.

2) It recognizes facial expression based on the 7 categories i.e., angry, sad, fear, happy, disgust, surprise, and neutral.

3) Based on the emotion it gives the user songs from the database.

4) If a user wishes to watch movies/songs then a list of movies/songs matching their mood are suggested with a movie/songs poster.

5) When a user clicks on the movie that he wishes to watch, they will be redirected to the IMDB website and for songs, it redirects them to the Spotify website.
## Features
***User Features***
- Authentication 
    - SignIn
    - SignUp
- Facial Recognition
- Mood Detection
    - Happy
    - Sad
    - Neutral
    - Angry
    - Surprised
- Song Recommendations
- Music Player
- Music Search
- Song queue
- Follow a friend
- See your people who are following you


***Administration Features***
- Authentication
- Song Upload
- Artist Upload
- Upload Album/Songs cover
- Tag Moods for Songs




## Demo/Screenshots

### Authentication
- User Registration
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653522671/Screenshot_2022-05-26_at_5.20.02_AM_owyaua.png)
- User Login
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653522416/Screenshot_2022-05-26_at_5.09.34_AM_blwt77.png)
### Mood Detection
- Neutral
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653522423/Screenshot_2022-05-26_at_5.10.43_AM_ytfita.png)
- Happy
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653522422/Screenshot_2022-05-26_at_5.10.58_AM_xtxqle.png)
- Sad
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653522420/Screenshot_2022-05-26_at_5.11.45_AM_oxfkyt.png)
- Angry
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653522420/Screenshot_2022-05-26_at_5.12.08_AM_qitgx2.png)

### Administration
- Admin Authentication
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653523419/Engage/Screenshot_2022-05-26_at_5.31.02_AM_crdocs.png)
- Admin Dashboard
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653523419/Engage/Screenshot_2022-05-26_at_5.31.12_AM_lhhqvp.png)
- Song database
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653523419/Engage/Screenshot_2022-05-26_at_5.31.26_AM_sjv8mi.png)
- Song upload
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653523419/Engage/Screenshot_2022-05-26_at_5.31.34_AM_tstuvr.png)
- Available moods
![logo](https://res.cloudinary.com/dgg6izgtw/image/upload/v1653523419/Engage/Screenshot_2022-05-26_at_5.31.18_AM_djoewr.png)

## Run Locally

- Clone the project

```bash
  git clone https://github.com/gaganvats-05/ENGAGE-FaceRecognition-MOODIFY.git
```

- Go to the project directory

```bash
  cd ENGAGE-FaceRecognition-MOODIFY
```

- Install dependencies for backend

```bash
  cd moodify_back_end
  pip install -r requirements.txt
```

- Start the  backend server

```bash
  python manage.py runserver
```
- For using administration features, create a superuser in django application
```bash
  python manage.py createsuperuser
```
after running this command set username for admin and password.

- Install dependencies for frontend
```bash
  cd moodifyFront
  npm install
```

Start the frontend server

```bash
    npm start
```

## Tech Stack

**Client:** React, React-bootstrap, Javascript, HTML, CSS

**Server:** Python, Django, OpenCV, Tensorflow
