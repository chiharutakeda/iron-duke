## TO DO LIST です。 
### 以下のコマンドを作業ディレクトリで実行してください

`git clone https://github.com/chiharutakeda/iron-duke`  
`cd iron-duke`  
`git clone https://github.com/chiharutakeda/iron-duke-front.git`  
`git clone https://github.com/chiharutakeda/iron-duke-backend.git`  
`git clone https://github.com/chiharutakeda/iron-duke-db.git`  
`cd iron-duke-front`  
`npm install`  
`cd ..`  
`cd iron-duke-backend`  
`npm install`  
`cd ..`  
`docker-compose up -d`  

一度コンテナが立ち上がった後に`docker-compose down`した後

もう一度`docker-compose up -d`を実行し

以下urlにアクセスしてください
http://localhost:3000/iron-duke
