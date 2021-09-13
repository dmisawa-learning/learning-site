# learning-site


## Talend
・Talend入門(1)   
&nbsp;&nbsp;<https://qiita.com/airkoda/items/a837d3c5d851d98d2612>  
&nbsp;&nbsp;&nbsp;⇒install方法や、Talend開発の基本的な流れ

・Talend入門(2)   
&nbsp;&nbsp;<https://qiita.com/airkoda/items/1cd12c05c6136add7178>  
&nbsp;&nbsp;&nbsp;⇒ファイルI/O

・Talend入門(3)   
&nbsp;&nbsp;<https://qiita.com/airkoda/items/bc807c920c3adebad837>  
&nbsp;&nbsp;&nbsp;⇒データベースI/O  
&nbsp;&nbsp;&nbsp;⇒前提として下記、Database環境構築を実施

## Database
・AmazonAurora(PostgreSQL互換)の学習としてPostgreSQLを学ぶ    
PostgreSQL for Windows   
・Windows版のPostgreSQLデータベース環境構築  
<https://qiita.com/tom-sato/items/037b8f8cb4b326710f71>  
・PostgreSQL初期設定  
<https://qiita.com/s_Pure/items/fdac4cf783c9b3d407ca>  
・PostgreSQLコマンド一覧  
<https://dev.classmethod.jp/articles/postgresql-organize-command/>  


## Knowledge
・Talend入門(2)にて以下エラー  
 Invalid escape sequence (valid ones are  \b  \t  \n  \f  \r  \"  \'  \\ )  
 ⇒<https://community.talend.com/s/feed/0D73p000004kBk1CAE?language=en_US>  
 ⇒上記からインプット指定ファイルパスを\\\\で指定　ex)"C:\\\\tmp\\\\work\\\\fileio\\\\in.csv"

・Talend入門(3)にてPostgreSQLのコンポーネントを使用する際に以下のようなエラー  
 『外部jarのインストールが必要です』  
 社内Proxyを使ってるからインストールできないが、  
 下記URLにアクセスし、直接インストール  
<https://talend-update.talend.com/nexus/content/repositories/libraries/org/postgresql/postgresql/42.2.9/>  





