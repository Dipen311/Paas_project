# Paas_project

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## Deployment (Dev Diary)

### Step 1: Setup Heroku Account

1. Create Account on Heroku
   1. Visit Heroku website https://www.heroku.com/home
   2. CLick on Sign On 
   3. Enter Your details
   4. Sign up Done

2. Create Application
   1. After log in tap on create new app
   2. Enter name of app (In my case web401npatel)
   3. select region (United States)
   4. Hit Enter

### Step 2: Deploying Code

1. Setup Github Repository
   1. Login to your Github or Sign UP in Github
   2. Create Repository (Remember Name of Repository)
   3. Download Github Desktop If you not have 
   4. Upload provided code in newly created repository
2. Open Heroku
   1. Open recently created app 
   2. Click on Deploy option
   3. Find Deployment method 
   4. Change it from Heroku Git to Github
   5. Then Hit on Connect to Github
   6. Connect Github account in which you uploaded code
   7. Then Click on Search Repository
   8. Write Repository name Then click on Search
   9. Find right Repository and Click Connect
   10. After that you show Automatic Deploy option
   11. Click on Enable Automatic Deploys


### Datbase Setup

1. Set Database
   1. In Header section of Heroku you find **More** button
   2. Click on that and select **Run Console**
   3. Run following command
      1. **$ heroku run rake db:migrate**
      2. **$ heroku run rake db:seed**
   4. Now App is live 
   5. Register with your data then you can view articles and other data

   
### My Url : https://web401dprajapati.herokuapp.com/
