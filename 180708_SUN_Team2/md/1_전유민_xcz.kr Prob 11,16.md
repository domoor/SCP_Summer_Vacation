## **xcz.kr Prob11**

![image](https://user-images.githubusercontent.com/40850499/42733360-31fb25c0-886b-11e8-989d-ee64a724f070.png) 



### 문제 개요

-xcz.kr 11번째 문제를 들어가보시면 TITLE에는 XLS Key Brute Force!!!라고  적혀있고 Description에는 Download파일을 받을 수 있습니다.

### XLS

-TITLE에서 말하는 XLS란 엑셀의 파일 포멧을 말합니다. XLS는 마이크로소프트의 엑셀로 마이크로소프트의 스프레드시트 프로그램으로 불리기도 합니다.

### Brute Force

-Brute Force란 특정한 암호를 풀기 위해 가능한 모든 값을 대입하는 것을 의미합니다. 대부분의 암호화 방식은 이론적으로 무차별 대입 공격에 대해 안전하지 못하며, 충분한 시간이 존재한다면 암호화된 정보를 해독할 수 있습니다. 하지만 대부분의 경우 모든 계산을 마치려면 실용적이지 못한 비용이나 시간을 소요하게 되어, 공격을 방지하게 합니다. 암호의 취약점이라는 의미에는 무차별 대입 공격보다 더 빠른 공격 방법이 존재한다는 것을 의미합니다. Title의 뜻을 해석해보면 엑셀 키 값이 맞을 때 까지 모든 값을 대입해봐라 라는 뜻으로 알 수 있습니다.

### Description(Download)

-http://xcz.kr/START/prob/prob_files/bf.xls

-파일을 다운받으면 bf(brute force)라는 이름으로 된 엑셀(xls)파일이 다운받아집니다.

![image](https://user-images.githubusercontent.com/40850499/42733399-b591ad5a-886b-11e8-8f60-d508c959e608.png) 

-파일을 열어보시면 암호가 설정되어 있습니다.

-brute force의 뜻처럼 암호가 맞을 때 까지 가능한 모든 값을 대입하라는 뜻입니다.

### Free Word and Excel Password recovery Wizard

![image](https://user-images.githubusercontent.com/40850499/42733409-e151d78a-886b-11e8-90df-42176bb454c8.png) 

-Google에 엑셀(XLS) Brute Force Tool을 검색해보시면 위의 툴과 같이 워드나 엑셀의 암호를 풀 수 있도록 도와주는 툴이 있습니다.

-다운로드 : http://www.freewordexcelpassword.com/index.php?id=download

### 실행

![image](https://user-images.githubusercontent.com/40850499/42733418-0b48f686-886c-11e8-9b28-9fa69c40ac23.png) 

-Free Word and Excel Password recovery Wizard을 실행해주시고 Next를 누르시면 파일이 어디에 있고 무슨 파일인지 찾아줍니다.

![image](https://user-images.githubusercontent.com/40850499/42733433-44c38ebc-886c-11e8-91c3-6070037d36fa.png) 

-Dictionary Attack(사전 공격)인지 Brute Force Attack(무작위 대입 공격)인지 선택해줍니다. 이 문제는 Brute Force Attack으로 해결하는 문제이므로 Brute Force Attack을 선택해줍니다.

![image](https://user-images.githubusercontent.com/40850499/42733441-748ae910-886c-11e8-858c-dc6845610b12.png) 

-숫자나 알파벳(소문자,대문자)를 선택할 수 있고, 몇자리부터 몇자리의 암호인지 선택할 수 있습니다. 이 문제에 대한 정보가 아무것도 없기 때문에 숫자랑 알파벳(소문자,대문자) 모두 선택해주시고, 자릿수도 최소값(1)부터 최댓값(8)까지 선택합니다.

![image](https://user-images.githubusercontent.com/40850499/42733451-93a9f958-886c-11e8-85ed-5498816eece5.png) 

-마지막으로 Go를 눌러주시면 엑셀의 암호가 무엇인지 알아서 분석해줍니다.

### CLEAR

![image](https://user-images.githubusercontent.com/40850499/42733464-b8447fb8-886c-11e8-8f2d-f49f76d496fd.png) 

-분석이 끝나면 Your password has been found라고 뜨면서 암호가 뜨게 됩니다. (검은색 부분)

![image](https://user-images.githubusercontent.com/40850499/42733474-cf905764-886c-11e8-9e39-973b710feec7.png) 

-나온 암호를 엑셀 파일 암호에 입력해주시면 엑셀 파일이 열리고 key값이 나오게 됩니다(검은색 부분)



### xcz.kr Prob 16

![image](https://user-images.githubusercontent.com/40850499/42733481-e96aadc4-886c-11e8-9d01-b9aa8c2955d0.png) 

### 문제 개요

-xcz.kr 16번 문제를 보시면 Title에 Mountains beyond mountains(산 넘어 산)라고 적혀있고 Description에는 케로로 캐릭터 스티커가 많이 붙여져 있는 이미지가 있습니다.

### Hex editor(헥사값)

![image](https://user-images.githubusercontent.com/40850499/42733493-0bcddddc-886d-11e8-9eec-055e90ae530c.png) 

![image](https://user-images.githubusercontent.com/40850499/42733503-20212bae-886d-11e8-9ebc-7d4ff30ab922.png) 

-헥사값을 분석하여 푸는 문제인줄 알고 Hex editor로 열어본 결과, 정상적인 PNG파일의 시그니처였고 중간 헥사값도 모두 분석해본 결과 아무런 문제가 없었습니다.

### OpenStego

![image](https://user-images.githubusercontent.com/40850499/42733505-3b1863fa-886d-11e8-8657-ec4b6c1a797c.png) 

-헥사값이 아닌 또 다른 방법으로 분석해보기 위해 OpenStego라는 Tool을 이용하여 파일을 열어보았습니다.

-OpenStego는 스테가노그래피 Tool로 파일 안에 다른 파일을 숨길 수 있게 해주거나 파일 안에 숨겨진 파일이 있는지 분석해주는 Tool로 스테가노그래피 Tool로는 굉장히 유용한 Tool입니다.

### 실행

![image](https://user-images.githubusercontent.com/40850499/42733515-68a78eb8-886d-11e8-894d-4e2c57f17f7c.png) 

-처음 실행하시면 파일 안에 또 다른 파일을 숨길 수 있게 해주는 Embed와 파일 안에 또 다른 파일이 없는지 분석해주는 Extract가 있습니다.

![image](https://user-images.githubusercontent.com/40850499/42733521-7ef24190-886d-11e8-8d7e-75b7fbd61b96.png) 

-파일을 숨기는 것이 아닌 숨겨진 파일이 없는지 분석해야 하므로 Extract를 선택해주고 어떤 파일인지 그리고 어디로 저장할지 선택하고 Algorithm을 LSB로 설정해줍니다.

![image](https://user-images.githubusercontent.com/40850499/42733524-95371e08-886d-11e8-8140-1debd2c6c5c2.png) 

-Success라고 뜨면서 또 다른 PNG파일이 케로로 이미지파일 안에 숨겨져 있던 것을 확인할 수 있습니다.

### QR code

![image](https://user-images.githubusercontent.com/40850499/42733537-bee5dbf4-886d-11e8-87b7-2b4b9ba7b0c6.png) 

-확인해본 결과 QR코드파일이 케로로 이미지파일에 숨겨져 있었고 이 QR코드를 분석해보기 위해 QR코드나 바코드 인식사이트로 가서 분석해줍니다.

![image](https://user-images.githubusercontent.com/40850499/42733543-d3724922-886d-11e8-9771-c3c6354c63f6.png) 

-onlinebarcodereader.com은 QR코드나 바코드를 인식해서 분석할 수 있는 사이트입니다.

### CLEAR

![image](https://user-images.githubusercontent.com/40850499/42733548-eaf3f136-886d-11e8-9275-4b720f588e10.png) 

-위의 사이트에서 QR코드 파일을 찾아서 분석해주면 QR코드 안에 있는 내용(키 값)이 나오게 됩니다. (검은색 부분)









