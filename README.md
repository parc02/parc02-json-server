# parc02-json-server

![LGTM](https://i.lgtm.fun/2p3c.png)
![image](https://github.com/parc02/parc02-json-server/assets/148880521/e41e3f04-96a3-496a-b63f-0088d6ba13a7)


## INSTALL JSON-SERVER
```
npm install json-server --prefix .
```
## RUN JSON-SERVER
```
$npx json-server db.json
JSON Server started on PORT :3000
Press CTRL-C to stop
Watching db.json...

( ˶ˆ ᗜ ˆ˵ )

Index:
http://localhost:3000/

Static files:
Serving ./public directory if it exists

Endpoints:
http://localhost:3000/posts
http://localhost:3000/comments
http://localhost:3000/profile
```

<details>
  <summary>HOW TO INSTALL</summary>
- install fly.io

https://fly.io/docs/hands-on/install-flyctl/
```
안되면 sudo 로 install 하고  명령어는 flyctl
```
- Launch fly.io
![image](https://github.com/parc02/parc02-json-server/assets/148880521/c24b3ae4-08ab-44f2-92cf-54996e30a53b)

- Sign in
```
$fly auth login
```

- fly.toml 수정
![image](https://github.com/parc02/parc02-json-server/assets/148880521/8efb2712-edc0-4134-8e32-c06e7963d3c9)

- flyctl deploy
  
- 출력화면
![image](https://github.com/parc02/parc02-json-server/assets/148880521/b49ea63a-ce9d-4b56-8727-ede0b455fb0b)
</details>
