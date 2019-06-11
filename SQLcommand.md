# Command

## SELECT（検索）

* **SELECT（行を選択する）**

全ての行を選択する

```Oracle SQL
SELECT *
```

* **FROM（表を選択する**

gamedate表を選択する

```Oracle SQL
FROM gamedate
```

* **WHERE**

条件

* **ORDER BY**

昇順降順での並び替え

## INSERT（新規登録）

## UPDATE（更新）

## DELETE（削除）

* **DROP**

削除する（ゴミ箱へ）

```Oracle SQL
DROP TABLE gamedate CASCADE CONSTRAINTS;
```

削除する（完全に）

```Oracle SQL
DROP TABLE gamedate PURGE;
```


# Word

* **DML**

データベースにおいて、データの検索・新規登録・更新・削除を行うための言語のこと。
代表的なDMLの中に関係データベースで用いられるSQLがある。


