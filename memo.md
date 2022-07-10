# memo
## django
aiueo
### aiueo
# aiueo
aaa
```
keita@KeitanoMacBook-Air django_tutorial % touch memo
keita@KeitanoMacBook-Air django_tutorial % touch memo.md
keita@KeitanoMacBook-Air django_tutorial % rm memo
keita@KeitanoMacBook-Air django_tutorial % ls
Dockerfile              memo.md                 test
```
```bash 
# ```bash コードに色つける
docker-compose.yml      requirements.txt
keita@KeitanoMacBook-Air django_tutorial % rm test
keita@KeitanoMacBook-Air django_tutorial % ls
Dockerfile              memo.md
docker-compose.yml      requirements.txt
keita@KeitanoMacBook-Air django_tutorial % 
```

[マークダウンかきかた](https://qiita.com/kamorits/items/6f342da395ad57468ae3)

コマンド　隠しファイル見える
ls -la

`rm -fR .git `

####help
-h

aiueo

# Git

初期
```sh
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/Keita929/django.git
git branch -M main
git push -u origin main
```

継続用
```sh
git add .
git commit -m "first commit"
git push -u origin main
```

起動
`docker-compose up`

コンテナ接続
`docker-compose exec web bash`  

コンテナ(実行中)終了
コントロール＋ｃ
ログアウト
コントロール＋d

イメージを作る
`docker-compose build `


docker-compose run web /usr/local/lib/python3.10/site-packages/django/bin/django-admin.py startproject composeexample .
