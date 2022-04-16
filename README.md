# My Static Site

Here is my website

## Steps to Host with GitHub pages

- Set up your project
- 'git init'
- 'git add .'
- 'git commit -m "your commit msg"'
- Create arepository on GitHub.com
- Follow the steps for Upload an exisitng repository
- After any signficance changes:
- git add .
- git commit -m "Your message"
- Repository Settings
- Pages
- Select Main for Source in Drop Down 
- Click Save
- The URL probably won't work for about 5 minutes


Parcel & Vercel
Hosting
- Set up Git locally in your project
- Make sure your package.json doesn't have a main keuy
and you have your build script (get these from this repos package.json)
- BEFORE you add or commit
 - Set up your .gitignore file (get the value of this repo)
 - Add, Commit
 - Create a new GitHub repository
 - Follow the steps for uploading an exisitng repo
 - Login/sign up to Vercel
 - Go tou tour Dadshboard
 - Overview- ckick New Project
 - Import your Parcel Github repsitory
- Set the framework preset to Parcel
- Customize all of th eBuild and Output Settings
- Build commands is npm run buikd
Output directory is dist
Install command npm install

## Hiding API Keys

- Install dotenv - npm install dotenv
- Create a .en file

API-KEY=valuer
SECOND_API_KEY=value

- Make sure .env is in my .giignore (everytime you change your .env. file)
- At the top of my JS file, import dotenv's config



js
import "dotenv/config";


const
const secondApiKey = process.env

