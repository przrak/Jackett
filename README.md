### jackett for heroku also can be installed on other server.

As you know docker on railyway.app or heroku will if restart used data from repo -- \
So if you will make change add configuration on your app - When it will restart it will purge your data to over the issue.. \
I deployed this jackett (server.io) docker version on localhost - added configuration and created all file so it will work for you out of the box. \
Admin password is admin -- Cloudflare FlareSolver is confgured it should work out of the box.  \


## Deoply on Heroku 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/amjiddader/Jackett/tree/master)

------------
Deploy using CLI

- Clone the repo
- Install [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
```
git clone https://github.com/amjiddader/Jackett
cd Jackett
heroku login
heroku apps:create APP
heroku stack:set container
git push heroku main --force
```
