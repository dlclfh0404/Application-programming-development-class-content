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
		int cnt = 0; //카운트 10까지 하는 변수
		int sum = 0; // 합계 변수

		for(int i = 0; i < 10; i++){ // 1부터 10까지 더하는 for문
			cnt+=1; 
			sum = sum + cnt; 
			System.out.println("cnt :" + cnt +" sum :" +sum);
		}
		System.out.println("sum :"+ sum);
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

##### 추가 (2진수,8진수,16진수 변환)
```java
import java.io.IOException;

public class S21218_01{
	public static void main(String[] args) throws Exception{

	int keyCode = System.in.read();
	System.out.println("keyCode: "+keyCode);
	String binaryString = Integer.toBinaryString(keyCode);
	String octalString = Integer.toOctalString(keyCode);
	String hexString = Integer.toHexString(keyCode);
	System.out.println("2진수 : "+ binaryString);
	System.out.println("8진수 : "+ octalString);
	System.out.println("16진수 : "+ hexString);
   }
}
```
#### 결과값
![image](https://user-images.githubusercontent.com/106458316/224196732-2cef6629-eef7-418a-af8b-e2c0b0edc88c.png)


##### 추가
숫자 10자리 미만으로 입력 받아 ASCLL 코드 값으로 출력한다.
```java
import java.io.IOException;

public class S21218_01v2{
	public static void main(String[] args) throws Exception{
		for(int i = 0; i < 10; i++){
			int keyCode = System.in.read();
			System.out.print(keyCode + " / ");
		}
   }
}
```
#### 결과값
![image](https://user-images.githubusercontent.com/106458316/224195832-926f9e20-f4ba-4992-955f-7ace48cd6f2f.png)

#### 2023-03-14 
커맨드 라인으로 입력을 받아 아래와 같이 출력한다.<br>
![image](https://user-images.githubusercontent.com/106458316/224906611-679c74ed-7100-4e90-93c6-8fa9e02d60dc.png)
```java
public class S21218_10{
    public static void main(String[] args){
        System.out.println("input :"+args.length);

        for(int i = 0; i < args.length; i++){
            System.out.println("args["+i+"] = "+args[i]);
        }
    }
}
```

#### 결과값
![image](https://user-images.githubusercontent.com/106458316/224906749-70d70911-91b6-4ab4-9bb8-848fbc96a682.png)

