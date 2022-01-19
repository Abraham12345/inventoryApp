# Project
This is a simple inventory web app please refer to the video for a overview.

## Install
This project uses Ruby on Rails to set up I have linked a more detailed installation [manual](https://guides.rubyonrails.org/getting_started.html) in general you will need to have:

ruby 2.7.0 or newer you can check with:
```shell
ruby --version
```

this project used sqlite3 to store its files you can check in your path with:
```shell
sqlite3 --version
```

You need Node.js you can check in your path with:
```shell
node --version
```

You need Node.js you can check in your path with:
```shell
yarn --version
```
after all this is all done you can install rails by doing:
```shell
gem install rails
```

or check if you already have it:
```shell
rails --version
```


### Clone the repository
Now that you are all set up you need to clone the repositiry 
```shell
git clone git@github.com:Abraham12345/inventoryApp.git
cd project
```

### Initialize the database

```shell
rails db:create db:migrate db:seed
```
## Serve

Open your local version using:                     

```shell
rails s
```
and open the link provided in your browser  