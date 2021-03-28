##商品管理システムを開発すると仮定して閲覧、登録、更新、削除ができるような仕組みを想定

##RESR APIを作成するのに最低限の機能だけ実装

##IDは下記の通り

Properties　　　	Types　　　　	Summaries

id　　　　　　     integer	　　　商品ID
jan_code	　　　　string	      JANコード
item_name	       string	       商品名
price	           integer	     価格
category_id	     integer	     カテゴリID
series_id	       integer	     シリーズID
stock	           integer	     在庫数
discontinued	   boolean	     廃番
release_date	   datetime	     発売日
created_at	     datetime	     作成日
updated_at	     datetime	     更新日
deleted_at	     datetime	     削除日