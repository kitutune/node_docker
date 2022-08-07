環境　Ubuntu 20.04
localのVscodeに入っている拡張機能(3つだけ
![image](https://user-images.githubusercontent.com/79749395/181904636-f025fba9-ddc3-416f-b64c-979488b5bd66.png)



# nextjs_docker
dockerで起動する用　composeに追加で書き込みし、他のコンテナとつなげる
1. gitclone
> git clone git@github.com:kitutune/nextjs_docker.git
2. プロジェクト内に移動
> cd node_docker/
3. docker build .
> docker build .
4. docker-runでコンテナ起動 (-it shは端末でそのままコマンド打てるようにするため　無ければ他のターミナルを起動する必要あり　コンテナの中に入る(標準入力？　端末で操作できる）

