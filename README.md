## 事前準備
適当な場所に以下のプロジェクトをクローンしましょう

```
$ git clone https://github.com/georgesekkie/additional_exam_pictweet.git
※windowsの方はclone後、database.ymlを書き換えましょう
```

```
$ bundle
#  データベース関連作成(errorpictweet_developmentという名前で生成)
$ bundle exec rake db:create
$ bundle exec rake db:migrate
# サーバー起動
$ rails s
```

## 問題
- rootパスが開けない(2箇所)
- 投稿する際、textが保存できない(1箇所)

## 時間
20分
