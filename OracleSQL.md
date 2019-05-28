# Oracle SQL


## データベースにおける様々な制約

* NOT NULL 制約

	必ず何かしらのデータを入力しなけれなばならない。NULLを禁止する制約

* PRIMARY KEY （主キー）制約

	必ず一意性があるようにしなければならない。重複するデータを禁止する制約

## サンプルデータベース

* データベースの情報を確認する

`desc 表名;`

* テーブルの作成を行う。

`create table emp3(<br>
 employee_id number(6),<br>
 first_name varchar2(20),<br>
 constraint emp3_emp_id_pk primary key (employee_id)<br>
);`<br>



`create table vendors (<br>
 vendor_id number(3) constraint vendors_vendor_id_pk primary key,<br>
 vendor_name varchar2(50) constraint vendors_vendor_name_nn not null<br>
);`<br>

* データの追加を行う。

`insert into vendors values(515, 'ふにゃらもろけ株式会社');`<br>

