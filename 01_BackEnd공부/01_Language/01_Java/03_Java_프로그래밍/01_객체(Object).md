# 객체 (Object)

---

- 의사나 행위가 미치는 대상 ( 사전적 의미 )
- 구체적, 추상적 데이터의 단위 ( 학생, 회원, 생산, 주문, 배송 )

ex )

```java
public class Student {

	int studentNumber;
	String studentName;
	int majorCode;
	String majorName;
	int grade;
}
```
- 클래스는 대문자로 시작하는것이 좋음
- java 파일 하나에 클래스는 여러 개가 있을 수 있지만, public 클래스는 하나이고, public 클래스와 .java 파일의 이름은 동일함
- camel notation 방식으로 명명
- enum 객체
    - Java에서 사용하는 상수 객체