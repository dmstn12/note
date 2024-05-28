# 수업 내용 필기
이곳에는 수업 내용 필기를 위한 마크다운(MarkDown)을 작성하는 방법을 살펴보겠습니다.

## 랜덤(Random)
랜덤은 다음에 뭐가 나올지 예측이 불가능한 값을 의미.  (space 두번치고 enter를 입력해야 다음줄로 변경 됨)  
랜덤을 만드는 방법은 여러가지가 있다.
1. Random이라는 도구를 생성하여 사용.
2. Math,random() 명령어를 사용.
3. SecureRandom 도구를 생성하여 사용.

여기서는 Random도구를 생성합니다.

```java
Random r = new Random();
```
이 도구를 사용하기 위해서는 import가 필요합니다.
```java
import java.util.Random;
```
import는 직접 작성하지 않고 단축키인 Ctrl+Shift+O 를 누릅니다.
