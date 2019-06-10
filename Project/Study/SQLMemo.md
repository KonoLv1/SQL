## 2019/06/10

### CREATE TABLE テーブルを作成する

### CREATE VIEW ビューを作成する

* **入力**

CREATE VIEW empvu80 <br>
AS SELECT employee_id, last_name,salary <br>
from employees <br>
where department_id = 80; <br>

* **出力**

ビューが作成されました。

* **入力**

desc empvu80;

* **入力**

select * from empvu80;

* **入力**

create view constcheck <br>
as <br>
select table_name,constraint_name,constraint_type <br>
from user_constraints; <br>

* **出力**

ビューが作成されました。

* **入力**

select * from constcheck;

* **入力**

select * from constcheck <br>
where table_name like '%EMP%'; <br>

where句を後付け可能（例はEMPが含まれるものの抽出）
