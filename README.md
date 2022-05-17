# Study_Javascript-React
Self Study 



Primitive Type (원시 타입)
let number = 12 ; // 한번에 하나의 값 만 가질 수 있음, 하나의 고정된 저장 공간 이용

Non-primitive Type (비 원시 타입
let array = [1,2,3,4]; 한번에 여러 개의 값을 가질 수 있음 , 여러개의 고정되지 않은 동적 공간 사용

<h3>객체를 만드는 법</h3>
1.  let person = new Object(); //생성자 방식 <p></p>
2.  let person = {};   // 객체 리터럴 방식  <p></p>
     let person = {   <p></p>
                      key:"value",    //property (객체 프로퍼티)<p></p>
                      key1:"value2"<p></p>
                      key2: true ,<p></p>
                      key3:undefined,   // 다양한 자료형 가능 <p></p>
                      key4:[1,2],<p></p>
                      key5: function(){}  }<p></p>

![image](https://user-images.githubusercontent.com/67277380/168816086-4721e377-fb6f-409d-8bf2-b55a2f172d72.png)
<p></p>

delete person["name"] //삭제 방법 (연결을 끊을 뿐 실제 객체가 지워지지않고 메모리에는 남아 있음 <p></p>
person.name =null; // 삭제 방법2 ( 기존의 메모리를 지움) <p></p>


객체의 멤버 변수에 접근하기 
![image](https://user-images.githubusercontent.com/67277380/168819326-863536b6-017e-44c6-99e3-96b7358aa4bd.png)

<h3></h3>
