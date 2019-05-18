# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
 `Ruby  2.5.0`
* System dependencies
 `Rails  5.0.3`
* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Gitコマンドの基本
https://qiita.com/_ha1f/items/2dca1047c57d4f0bd465

  #git init
  データベース用のフォルダとして.gitという隠しフォルダ

  # git add
  ファイル/ディレクトリを、圧縮・ハッシュで命名して.git/objectsにコピーします。同時に、ステージングにも反映します
  -u: 削除されたファイルと、修正されたファイル
  .: 新しく作られたファイルと、修正されたファイル
  -A: 新しく作られたファイルと、削除されたファイルと、修正されたファイル

  # git commit
  ステージングの状態を、コミットオブジェクトに変換して、コミットログとして登録します。

  # git branch
  git branch             # ブランチ一覧を表示
  git branch ブランチ名    # ブランチを作成
  git branch -D ブランチ名 # ブランチを削除

  # git checkout
  ブランチを切り替えます。HEADの内容を、そのブランチのHEADで置き換え、ワークツリーの内容にも反映します。
  git checkout -b ブランチ名

  # git merge



###########
243  touch test.rb
244  puts 1 + 2
245  echo 'puts "Hello, World!"' >> test.rb
246  cat test.rb
247  echo 'puts 1 + 2' >> test.rb
248  cat test.rb
249  ruby test.rb
250  brew -v
251  brew -v
252  rbenv -v
253  brew install rbenv ruby-build
254  echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
255  source ~/.bash_profile
256  rbenv install --list
257  rbenv install 2.5.0
258  gem install rails -v 5.0.3
259  sudo gem install rails -v 5.0.3
260  ls
261  pwd
262  cd ..
263  ls
264  mkdir progate
265  cd progate/
266  rails new tweet_app
267  rails generate controller home top
268  ls
269  cd tweet_app/
270  ls
271  rails generate controller home top
272  ls
273  cd app/
274  ls
275  cd views/
276  ls
277  cd
278  ls
279  cd Program/
280  ls
281  cd progate/
282  ls
283  cd tweet_app/
284  rails server
285  bundle install
286  vi Gemfile
287  bundle install
288  bundle install
289  bundle install
290  bundle install
291  rails server
292  rails server
293  bundle install
294  rails server
295  rails generate controller home top
296  rails server
297  which git
298  rails generate controller home about
299  l
300  ls
301  cd app/
302  ls
303  cd views/
304  rails generate controller posts index
305  rails g model Post content:text
306  rails db:migrate
307  history
###########
