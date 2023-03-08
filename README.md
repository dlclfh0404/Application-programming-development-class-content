# 응용프로그래밍 개발 수업 내용

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
#### 실행 방법
- 첫번째는 코딩을 한후 ~~~.java파일로 만든다.
- 두번째는 명령 프롬포트에서 javac ~~~.java 컴파일을 한다.
- 세번째는 만들어진 class 파일을 실행 시킨다.
#### TOOLS
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white">

#### 2023-03-08 과제
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
