# Oracle SQL


## データベースにおける様々な制約

* NOT NULL 制約

	必ず何かしらのデータを入力しなけれなばならない。NULLを禁止する制約

## サンプルデータベース


* テーブルの作成を行う。

`create table emp3(
 employee_id number(6),
 first_name varchar2(20),
 constraint emp3_emp_id_pk primary key (employee_id)
);`