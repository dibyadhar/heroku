## Download the Heroku CLI Tool:

[Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli#download-and-install)

## Login to Heroku Acc:

`heroku login`

To login within the console:

`heroku login -i` 

N.B: The CLI saves your email address and an API token to ~/.netrc for future use

## Chekout source code from remote repository like github and cd into the project directory:

```
git clone https://www.github.com/<your_github_account>/galeria  my-heroku-project
cd my-heroku-project

```

## Deploy the app on Heroku platform:

```
heroku create

git remote -v

git push heroku master

```

## Access the application:

`heroku open`