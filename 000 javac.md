## cmd에서 javac를 할 때 발생한 오류.
``java
public class Main {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Hello World!");
	}

}
``
> 메모장에서 코드를 이렇게 작성하고 파일이름을 Helloworld.java로 하니까 오류가 발생했다.  
``
 error: class Main is public, should be declared in a file named Main.java
public class Main
``

## 이유와 해결법
> java파일의 이름과 코드의 처음 public class 'Main' 부분에서 Main이 아니라 파일 이름과 매치 시켜야된다.  
> public class Helloworld로 변경하니 해결되었다.
