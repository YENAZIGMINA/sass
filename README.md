# sass 사용 거의 안함, scss를 사용한다 / scss-->사스라고 읽음

![image](https://github.com/YENAZIGMINA/sass/assets/129706758/56464fb9-bb5e-4e4c-8116-515126a6d461)

# scss 컴파일

아래 wathcing 누르면 

![image](https://github.com/YENAZIGMINA/sass/assets/129706758/ab4cfe20-b929-489f-9fa9-1aa78ddfc74f)

# css 위치변경

![image](https://github.com/YENAZIGMINA/sass/assets/129706758/ab9d4cba-9e34-4ffe-8ba0-b6e6b9bf3afc)

# savePath:null이면 scss파일과 같은 위치에 style.css가 생긴다

![image](https://github.com/YENAZIGMINA/sass/assets/129706758/4b3d4ed5-0508-483c-bfb5-2fd5a714226f)

# ~(물결)은 style.scss를 의미, /는 style.scss가 있는 폴더를 의미

![image](https://github.com/YENAZIGMINA/sass/assets/129706758/7df986e9-c4d5-44c1-ab86-40ad183c9087)

# ../는 scss파일이 있는 폴더의 상위요소에 생성

![image](https://github.com/YENAZIGMINA/sass/assets/129706758/6a7b24e7-0365-41a1-97c1-1cbbbb8ab118)

# 주석처리 방법
## //로 주석처리 하는 방법은 css로 컴파일되지 않는다.
## /*  */ 는 css로 컴파일 된다.
![image](https://github.com/YENAZIGMINA/sass/assets/129706758/12c7d0fd-d341-421c-987e-f66046ec8ec4)

# 변수만들기 --> $로 시작함, (영문, 숫자, - , _ )만 사용 할 수 있다. 
## 숫자로 시작할 수 없음.

![image](https://github.com/YENAZIGMINA/sass/assets/129706758/7a3f1dda-74c7-4a5f-a44b-e7b319064deb)

# Partials(파샬)
  -- 관련된 것끼리 묶어서 분리 / 소스에 반복되는 부분들을 분리, 분산시켜서 모듈화 시키는 기능
  
  * Partials 폴더는 직접 만듦
  * Partials의 파일명은 _로 시작하며 (ex. _var.scss)
  * 불러들일 때는 @import '파일명'  이 때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다.

  Scss는 _로 시작하는 파일은 컴파일하지 않는다.
  
![image](https://github.com/YENAZIGMINA/sass/assets/129706758/d92bcf02-6c18-494a-819b-37ae4dabf9eb)


# @import -- 변수가 중복될 때는 아래의 것이 적용된다.
![image](https://github.com/YENAZIGMINA/sass/assets/129706758/fe7933f6-580d-42c7-b25c-752b118348ec)

# @use --> 변수이름이 같을 때 에러발생하여 import대신 @use를 사용
사용할 때는 앞에 파일명을 추가해서 파일명.변수명
같은 변수명이지만 다른 값을 준 scss를 use를 통해서 변수명앞에 .var(페이지명) 작성하여 적용할 수 있다
![image](https://github.com/YENAZIGMINA/sass/assets/129706758/6813fe89-af9b-4bb8-878e-6741ee1be9bc)

![image](https://github.com/YENAZIGMINA/sass/assets/129706758/d971d544-fd74-43da-9f2a-1bb6c78ddd08)

# as 뒤에 별명을 붙여서 사용할 수 있다. (별명으로 부를 수도 있음)
![image](https://github.com/YENAZIGMINA/sass/assets/129706758/42780409-3043-4b32-95f9-b557a1b9dd7a)

# @forword 는 파샬을 묶어줌(그룹)
style.scss에서는 _index.scss에서 묶은 것을 호출하여 사용함
![image](https://github.com/YENAZIGMINA/sass/assets/129706758/2452bab6-bec4-48ec-90b7-9e16d7a14fbe)




  
  
  
  
