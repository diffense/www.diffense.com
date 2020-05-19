
# deploying a docker image to heroku

heroku 계정: ceo@diffense.co.kr
도메인(diffense.com): whois 서비스(withhope@hanmail.net)

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


참고 예제: https://github.com/rjoonas/heroku-docker-nginx-example

