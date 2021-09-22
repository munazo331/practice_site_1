# practice_site_1
練習用も模写サイト１つめ

pug
sass
node.js

▼gulpfile.js内の記述の説明

・pugの仕事
pugフォルダ以下にある全ての.pngファイルを対象に、コンパイルをして、wwwフォルダに保存

・sassの仕事
sassフォルダにある全ての.scssファイルを対象に、コンパイルをして、wwwファルダ中のcssフォルダに保存

 
・watchの仕事
sassフォルダにある全ての.scssファイルを対象に監視を行って、変更があったら「sassの仕事」を実行
pugフォルダにある全ての.pugファイルを対象に監視を行って、変更があったら「pugの仕事」を実行
 

・taskの実行
コマンドプロンプトでgulpって書いてエンター押したら、sass、pug、watchを開始してね命令
