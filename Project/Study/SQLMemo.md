## 2019/06/10

* **入力**

CREATE VIEW empvu80
AS SELECT employee_id, last_name,salary
from employees
where department_id = 80;

* **出力**

ビューが作成されました。

* **入力**

desc empvu80;

* **入力**

select * from empvu80;