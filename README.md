## 0.リポジトリをクローン

```
cd ~/docker
git clone git@github.com:shiorina/message-board.git
```
もしくは

```
git clone https://github.com/shiorina/message-board.git
```

## 1.作業ディレクトリに移動する

```
cd ~/docker/message-board
```

## 2.Docker起動

```
docker-compose up --build
```

## 3.db作成

```
docker-compose exec app rails db:create
```

http://0.0.0.0:3000/
にアクセス

## Docker停止
Ctr + c

```
docker-compose down
```

## Docker上でのコマンドの打ち方

```
docker-compose exec app rails ...
docker-compose exec app bundle install
```

のようにdocker-compose exec app
の後に続ける





