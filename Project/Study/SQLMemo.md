## 2019/06/10

### CREATE TABLE �e�[�u�����쐬����

### CREATE VIEW �r���[���쐬����

* **����**

CREATE VIEW empvu80 <br>
AS SELECT employee_id, last_name,salary <br>
from employees <br>
where department_id = 80; <br>

* **�o��**

�r���[���쐬����܂����B

* **����**

desc empvu80;

* **����**

select * from empvu80;

* **����**

create view constcheck <br>
as <br>
select table_name,constraint_name,constraint_type <br>
from user_constraints; <br>

* **�o��**

�r���[���쐬����܂����B

* **����**

select * from constcheck;

* **����**

select * from constcheck <br>
where table_name like '%EMP%'; <br>

where�����t���\�i���EMP���܂܂����̂̒��o�j
