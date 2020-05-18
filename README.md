
# deploying a docker image to heroku

https://github.com/rjoonas/heroku-docker-nginx-example

```sh
git clone git@github.com:diffense/diffense.com.git
cd diffense.com
heroku container:login
heroku create
heroku container:push web
heroku container:release web
heroku open


heroku domains:add www.diffense.com    # custom domain 설정할 때
```
