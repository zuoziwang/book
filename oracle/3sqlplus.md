1. 用system用户解锁用户
> alter user scott account unlock;

2. show user;

3. conn[ect] user/pass@inet;
4. disc[onnect];
4. exit;
4. passw[ord]
4. &
>set linesize 140;
>select * from emp;
>select * from emp where job='CLERK';
>select * from emp where job='&job';
4. edit
4. spool
> spool on;
> select * from emp;
> spool /opt/a.sql
>spool off;
