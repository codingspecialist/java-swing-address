### java-swing-address

```java
create table member(
    id number PRIMARY KEY,
    name varchar2(20),
    phone varchar2(20),
    address varchar2(50),
    groupType varchar2(20),
    CONSTRAINT group_domain check (groupType in ('친구', '학교', '회사', '가족'))
);
```
