# 수업 내용 필기
이곳에는 수업 내용 필기를 위한 마크다운(MarkDown)을 작성하는 방법을 살펴보겠습니다.

## 랜덤(Random)
랜덤은 다음에 뭐가 나올지 예측이 불가능한 값을 의미.  (space 두번치고 enter를 입력해야 다음줄로 변경 됨)  
랜덤을 만드는 방법은 여러가지가 있다.
1. Random이라는 도구를 생성하여 사용.
2. Math,random() 명령어를 사용.
3. SecureRandom 도구를 생성하여 사용.

여기서는 Random도구를 생성합니다.

(```를 작성하게 되면 code block)
```java
Random r = new Random();
```
이 도구를 사용하기 위해서는 import가 필요합니다.
```java
import java.util.Random;
```
import는 직접 작성하지 않고 **단축키**인 `Ctrl+Shift+O`(inline code block) 를 누릅니다.

## 랜덤 정수 추천
생성한 도구를 이용해서 랜덤한 정수를 추출할 수 있습니다.  
단, 생성을 위해서는 범위를 정해야합니다.

- 사람은 범위를 이야기할 때 `a`부터 `b`까지 라고 합니다.
- 자바는 범위를 이야기할 때 `a` 부터 `b` 개 라고 합니다.

주요 랜덤 값들의 범위는 다음과 같이 표현할 수 있습니다.  
|항목 | 범위 |   
| :---: || :---: |   
| 주사위 | 1부터 6개 |
| 로또 | 1부터 45개 |

##### 홈페이지 링크 추가 방법
난수 생성의 원리가 궁금하면  [위키백과](https://ko.wikipedia.org/wiki/%EC%9C%84%ED%82%A4%EB%B0%B1%EA%B3%BC:%EB%8C%80%EB%AC%B8) 에서 확인할 수 있습니다.

##### 이미지 링크 추가 방법
![카지노](https://media.istockphoto.com/id/1158005632/ko/%EC%82%AC%EC%A7%84/%ED%81%AC%EB%A3%A8%ED%94%BC%EC%96%B4%EB%8A%94-%EA%B7%B8%EC%9D%98-%EC%86%90%EC%97%90-%EC%B9%B4%EC%A7%80%EB%85%B8%EC%97%90%EC%84%9C-%EB%A3%B0%EB%A0%9B-%EA%B3%B5%EC%9D%84-%EB%93%A4%EA%B3%A0%EC%9E%88%EB%8B%A4.jpg?s=2048x2048&w=is&k=20&c=ymzJuMlf-fx37eiGvolrMD9HGTEzDFD2pPWAufU2A_I=)
