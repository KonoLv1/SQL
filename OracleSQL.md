# Oracle SQL


## �f�[�^�x�[�X�ɂ�����l�X�Ȑ���

* NOT NULL ����

	�K����������̃f�[�^����͂��Ȃ���Ȃ΂Ȃ�Ȃ��BNULL���֎~���鐧��

* PRIMARY KEY �i��L�[�j����

	�K����Ӑ�������悤�ɂ��Ȃ���΂Ȃ�Ȃ��B�d������f�[�^���֎~���鐧��

## �T���v���f�[�^�x�[�X

* �f�[�^�x�[�X�̏����m�F����

`desc �\��;`

* �e�[�u���̍쐬���s���B

`create table emp3(<br>
 employee_id number(6),<br>
 first_name varchar2(20),<br>
 constraint emp3_emp_id_pk primary key (employee_id)<br>
);`<br>



`create table vendors (<br>
 vendor_id number(3) constraint vendors_vendor_id_pk primary key,<br>
 vendor_name varchar2(50) constraint vendors_vendor_name_nn not null<br>
);`<br>

* �f�[�^�̒ǉ����s���B

`insert into vendors values(515, '�ӂɂ����낯�������');`<br>

