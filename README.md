# WebSite

The official WebSite of TADSG

# Setup Developing Environment #
Make sure you have node and npm in system.
If not, please install with:
``` cmd
$ brew install node
$ brew install npm
```


# Install Dependencies #
Move to project root first:
``` cmd
$ cd WebSite
$ npm install # Install dependencies:
```


# Run local debug server #
 Run express as debug mode:
``` cmd
$ cd WebSite # Move to project root first:
$ DEBUG=WebSite:* npm start
```
By default, the web site will run on [http://localhost:3000]()

## Run in different port number ##
``` cmd
$ cd WebSite # Move to project root first:
$ DEBUG=WebSite:* PORT=[port_number] npm start
```


# Deploy #
Deploy to Heroku
``` cmd
$ web: npm start
```
