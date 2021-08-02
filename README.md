# exampleServlet

### **1. Description**
* Form을 통해 사용자로부터 Username과 Password를 입력 받아 출력하는 <br> 간단한 **Servlet** 사용 예제 프로그램입니다.


### **2. Environment**
* **Eclispe**
  + Dynamic Web Project
* **Tomcat 9.0**


### **3. Files**
* **index.html**
  + Form을 통해 Username과 Password를 입력 받습니다.
  + Post 메서드를 통해 LoginServlet으로 데이터를 전송합니다.
* **LoginServlet**
  + Servlet 클래스입니다.
  + doPost() 메서드만 사용(Override)합니다.
  + 사용자로부터 받은 Username과 Password를 사용하여 동적으로 HTML 페이지를 생성합니다.
* **web.xml**
  + 기본적인 web.xml 파일입니다.
  + 기본 웹 페이지를 **index.html**로 설정해줍니다.
