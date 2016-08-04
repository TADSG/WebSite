# WebSite

The official WebSite of TADSG

# Setup Developing Environment #
Make sure you have node and npm in system.
If not, please install with:
``` shell
$ brew install node
$ brew install npm
```


# Install Dependencies #
Move to project root first:
``` shell
$ cd WebSite
$ npm install # Install dependencies:
```


# Run local debug server #
 Run express as debug mode:
``` shell
$ cd WebSite # Move to project root first:
$ DEBUG=WebSite:* npm start
```
By default, the web site will run on [http://localhost:3000]()

## Run in different port number ##
``` bash
$ cd WebSite # Move to project root first:
$ DEBUG=WebSite:* PORT=[port_number] npm start
```


# Deploy #
Deploy to Heroku
``` shell
$ web: npm start
```

# Pending Materials #
* [Rick - 高效能執行緖](http://www.accupass.com/go/gdgkaohsiung30) [(slide)](http://www.slideshare.net/rickwu12)
* [TADSG meeting - 18th](http://www.accupass.com/go/adc18)


# Candidates of Server #
* [Hostinger (php)](https://free.com.tw/hostinger/)

