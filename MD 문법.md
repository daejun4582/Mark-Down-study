# 문법 정리
## 1. Header 헤더
----
### 1.1 큰 제목
<pre><code> This is an Title
==================</code></pre> 
  <br/>   

### 1.2 작은 제목 (부제목인듯)
<pre><code> This is an Title
------------------
</code></pre> <br/> 

### 1.3 글머리 1~6까지만 지원
 <pre><code># This is an Title
## This is an Title
### This is an Title
### This is an Title
#### This is an Title
##### This is an Title
###### This is an Title
</code></pre> 
# This is an Title
## This is an Title
### This is an Title
### This is an Title
#### This is an Title
##### This is an Title
###### This is an Title
####### This is an Title(7부턴 지원 안함)
<br/> 

## 2. BlockQuote
----
이메일에서 사용하는 > 블럭 문자를 이용한다고 함.
 <pre><code>> This is a first blockqute.
>  >This is a second blockqute.
>	>   >This is a third blockqute.

</code></pre> <br/> 
> This is a first blockqute.
>  >This is a second blockqute.
>	>   >This is a third blockqute.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.
> # This is a H1
> - List
>   <pre><code>This is code
</code></pre> <br/> 

## 3. Code
----
### 3.1 들여 쓰기
들여쓰기 하면 안하는애 만날때까지 계속 들여쓰기 한다고 함
<pre><code>This is a normal paragraph:

    This is a code block.
    
end code block.
</code></pre>
적용예:

----
This is a normal paragraph:

    This is a code block.
    
end code block.

----
참고로 한줄 제대로 안띄우면 안됨
<pre><code>This is a normal paragraph:
    This is a code block.
end code block.
</code></pre>
적용예:

----
This is a normal paragraph:
    This is a code block.
end code block.

----
<br/>


### 3.2 코드 블럭 문법

- 인라인 블럭은 이렇게 씀   
    ```
    `인라인 블럭`
    ```    
이렇게 보임

`인라인 블럭`

긴 코드는 문법 2개 있음

+ ```<pre><code> </code></pre> ``` 
+ ``` ` ` ` ____ ` ` ` ```

이렇게 하면 됨 참고로 앞에 다가 이렇게 언어 이름 넣으면 문법별 강조도 넣을 수 있음 
```
\```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
\```
```


```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```


## 4. 줄바꿈
----

슬슬 쓰기 귀찮음 마지막으로 중요한 줄바꿈만 하겠음    
줄바꿈이 좀 빡침 이것도 두개가 존재함

- ``` <br/> ```
- space bar 3개 이상

이렇게 쓰면 줄바꿈 됨 궁금하면 해보셈 ㅅㄱ;

// 참고로 cmd+shift+v 하면 미리보기 바로 실행됨 알면 개꿀
