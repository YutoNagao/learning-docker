# learning-docker: Dockerの練習

## ミニレポート

### Q1-1: 同じ `docker container run` コマンドを2回実行すると、1回目と2回目で違いはありますか？どう違いますか？

【回答欄】downloadしているかしていないかの違いがある

### Q1-2: なぜ違いますか？

【回答欄】１回目でダウンロードしたことで２回目はダウンロードする必要がないから

### Q1-3: `docker container ls` と `docker container ls -a` はどう違いますか？

【回答欄】-a をつけることでcontainerが３つ表示される

### Q1-4: `docker image ls` と `docker container ls -a` はどう違いますか？（間違ってもいいので、自分の考えを述べてください）

【回答欄】同じだと思う

### Q1-5: `ubuntu` イメージでの `cat /etc/issue` の結果をペーストしてください

【回答欄】Ubuntu 18.04.3 LTS \n \l

### Q1-6: `docker image ls` と `docker container ls -a` はどう変化しましたか？

【回答欄】containerが増えた

### Q2-1: `-d` (デタッチド・モード) でコンテナを起動すると、どのような状態になりましたか？

【回答欄】特になし

### Q2-2: http://localhost/ をブラウザで開くと、何が表示されましたか？

【回答欄】Welcome to nginx!が表示された

### Q2-3: コンテナの起動時と終了時で、docker container ls -a はどのように変化しましたか？

【回答欄】statusがupからexitになった

### Q3-1: `docker build -t sample-image .` 実行時に表示されている `building...` は、Dockerfileのどの行から実行されましたか？

【回答欄】# "docker build"時に実行される処理
RUN echo "building..."

### Q3-2: `docker run sample-image` を実行すると、どうなりましたか？

【回答欄】Hello, from Docker container!と表示された
