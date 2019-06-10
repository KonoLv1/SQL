## 2019/06/10

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

