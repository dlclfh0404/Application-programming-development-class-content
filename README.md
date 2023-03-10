# 응용프로그래밍 개발 수업 내용
#### 실행 방법
- 첫번째는 코딩을 한후 ~~~.java파일로 만든다.
- 두번째는 명령 프롬포트에서 javac ~~~.java 컴파일을 한다.
- 세번째는 만들어진 class 파일을 실행 시킨다.
#### TOOLS
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white">

#### 2023-03-08
1. java 1부터 자연수 10까지 더하는 알고리즘을 통해 변수의 변화를 알아보자<br>
![image](https://user-images.githubusercontent.com/106458316/223611148-36193beb-a602-49db-88f8-fbb21f116442.png)

```java
public class S21218_00{
	public static void main(String[] args){
	int cnt = 0;
	int sum = 0;
	for(int i = 0; i < 10; i++){
		cnt+=1;
		sum = sum + cnt;
	}
		System.out.print("sum :" + sum);
         }
   }
```
이렇게 짜서 결과값은<br>
![image](https://user-images.githubusercontent.com/106458316/223611075-07528ffc-7ad8-479e-a085-0150923dcd8b.png)

#### 2023-03-08 과제
![image](https://user-images.githubusercontent.com/106458316/223935708-15ee0bb8-398e-4dc8-941e-903e79d131e1.png)

```java
public class test1{
	public static void main(String[] args){
	int cnt = 0;
	int sum = 0;
	for(int i = 0; i < 10; i++){
		cnt+=1;
		sum = sum + cnt;
		System.out.println("cnt :" + cnt + "sum :" + sum);
	}
		System.out.println("sum :" + sum);
         }
   }
```
#### 결과값
![image](https://user-images.githubusercontent.com/106458316/223935638-2db8bad1-ec67-4c3b-8692-7f9cd1ececc6.png)

### 2023-03-10
1 문자(숫자)를 입력 받아 ASCLL 코드 값으로 출력한다.<br>
![image](https://user-images.githubusercontent.com/106458316/224190521-1e496120-1668-4230-bfe0-2389de79962f.png)

```java
import java.io.IOException;

public class S21218_01{
	public static void main(String[] args) throws Exception{

	int keyCode = System.in.read();
	System.out.println("keyCode: "+keyCode);
   }
}
```
#### 결과값
![image](https://user-images.githubusercontent.com/106458316/224190709-da0e9f69-2bba-4a92-b441-b8f6b968cbd7.png)
