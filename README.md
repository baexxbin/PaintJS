# PaintJS

<setup 파트>     
````
 js : id 사용    
 css : class 사용    
````

> *색깔팔레트 동그란 모양으로 만들기*    
> " border-radius " 설정하기    
> 이때, border-radius는 width의 1/2값으로 설정    
> ex) width : 50, border-radius : 25       


<css 파트>
````
 flex    
   * 컨테이너 적용    
        아이템들 가로방향 배치    
        자신이 가진 내용물의 width만큼 차지     
        ** flex-direction : 아이템들이 배치되는 축의 방향을 결정     
           메인축을 가로x축을 할지, 세로y축을 기준으로 할지, 이에따라 아이템들을 끼움    
       
       ** flex-wrap : 컨테이너가 더 이상 아이템들을 한 줄에 담을 여유 공간이 없을 때
아이템 줄바꿈을 어떻게 할지 결정     
````
````     

   * 아이템 적용  
       flex-basis : Flex 아이템의 기본 크기를 설정      


   all: unset; ==> 원래의 모양 초기화     
    padding: 50px 0px; ==> (위,아래) (오른쪽,왼쪽)       
````    

<js 파트>     
canvas는 context를 가짐.     
context는 픽셀에 접근할 수 있는 방법, ==> canvas안의 픽셀들     
이 픽셀들을 다룰 수 있는 공간인 width, height 지정해주기    

* Array.from(colors)       
    : array.from매소드는 object로 부터 array를 만듦      

* 링크 설정      
    * link.href => image(URL)이 되어야하고,     
    * link.download => image의 이름이 됨 (저장할때 저장파일이름!)
