
## Tech Stack

**Client:** React, Material UI

**Server:** Node, Express , Passport JS , Flask 


## Features

- Recommend Movies
- Detail View Of Every Movie
- Detail View Of Every Cast Of Movie
- More Popular Movie Of Particular Cast
- Latest And Upcoming Movies List With Rating
- Google Authentication
- Search Movies 


## API Credit
All the images and data used in project is taken from 
https://developers.themoviedb.org/3/getting-started/introduction

## Run Locally

Clone the project

```bash
  git clone https://github.com/ANAND-NARAYAN-JHA/Movie-Recommendation-System
```

Install Python Libraries

```bash
pip install sklearn nltk pandas gunicorn flask flask-cors numpy pandas requests
```

move into RecomSystem folder

```bash
cd RecomSystem
```

move into server and install node dependencies for server side
```bash
cd server
npm i
```

install react dependencies in client folder

```bash
cd ..
cd client
npm i
```
run python file in one shell
```bash
cd ..
cd server
python main.py
```
run node backend in other shell
```bash
npm start
```
run react frontend in third shell
 ```bash
cd ..
cd client
npm start
```
## Authors

- [@AnandNarayanJha](https://github.com/ANAND-NARAYAN-JHA)



