리플랙션
==========
   
# 동적 로딩(Dynamic Loading)      
자바 프로그램은 여러개의 클래스로 구성되어 있다.             
자바는 프로그램 실행 시에 모든 클래스를 로딩하지 않고              
**필요한 시점에 필요한 클래스를 로딩**하여 사용하는 **동적 로딩(Dynamic Loading)** 을 지원한다.        
    
# 클래스 로더와 동적 로딩   
자바 프로그램은 한 개 혹은 그 이상의 클래스들의 조합으로 실행된다.     
그리고 실행 시 모든 클래스 파일들이 한 번에 JVM 메모리에 로딩되지 않고 요청되는 순간 로딩된다.       
자바의 **클래스 로더**가 이런 역할을 수행한다.          
           
**클래스 로더란? :** `.class` 바이트 코드를 읽어 들여 `객체`를 생성하는 역할을 담당한다.                     
즉, 클래스 로더는 **클래스가 요청될 때 `클래스 정보`를 메모리로 로딩하는 역할**을 한다.                   
 
``` 
클래스 로더는 classpath라는 환경 변수에 등록된 디렉토리에 있는 모든 클래스들을 먼저 JVM에 로딩한다. 
JVM에 로딩된 클래스만이 JVM에서 객체로 사용할 수 있다. 
클래스 로딩은 클래스를 로딩하는 시점 또는 실행 중간에도 할 수 있다.
```

# 클래스 로딩 과정


 
  
# 참고    
[자바 동적로딩 이해](https://futurists.tistory.com/43)          
[리플랙션과 동적 로딩](https://madplay.github.io/post/java-reflection)           
[최범균님의 동적 로딩](https://javacan.tistory.com/entry/1)      