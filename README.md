# Welp for Heroku

Find and review restrooms near you (NYC)

![screenshot](https://raw.githubusercontent.com/sonnynomnom/welp/main/screenshot.png)

In one terminal tab:

```
cd Desktop
cd welp-deploy
cd backend

heroku --version
heroku login

git add .
git commit -am "message"
git push -f heroku master
git push -f heroku main
```

In another:

```
cd backend
yarn install
yarn start
```

Requires an `.env` file for mapbox in `frontend` folder and an `.env` file for mongo in `backend` folder.

Tags: [tags.md](https://github.com/sonnynomnom/welp/blob/main/docs/tags.md)

Discord: https://discord.gg/J8JChRp5  
IG: https://www.instagram.com/welp.nyc  
Twitter: https://www.twitter.com/welp_nyc  
