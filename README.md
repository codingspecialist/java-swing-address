#### 자바 주소록 프로그램

- 1. 로그인
- 2. 회원가입
- 3. 주소록 추가

![배경사진](http://www.naver.com/img/1)

```sql
create table member(
    id number PRIMARY KEY,
    name varchar2(20),
    phone varchar2(20),
    address varchar2(50),
    groupType varchar2(20),
    CONSTRAINT group_domain check (groupType in ('친구', '학교', '회사', '가족'))
);
```
```java
public class Hello {
    public static void main(String args[]){
        System.out.println("HEllo");
    }
}
```
