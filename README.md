# vagrant_php

php + apache2の開発用vagrantfileです。


```
$ git clone https://github.com/naogify/vagrant_php.git
$ cd vagrant_php
$ vagrant up
```
して、ブラウザから192.168.33.10にアクセスすると、apacheサーバーが立ち上がっています。
ワーキングディレクトリ内の```src```は、apacheの```/var/www/html/```と同期しており、ローカルで編集した、ファイルが反映される。
