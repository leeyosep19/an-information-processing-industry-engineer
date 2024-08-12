### 기본 명령어

#### man (manual)
```
사용하는 명령어으 설명이나 옵션 사용법들을 확인할때
EX) man [옵션][-m system][-p system][-P pager][-S sectpon_list][section]명령어
```
 |||||
 |-|-|-|-|
 |||||
 |pwd|ls|cd|mkdir|
 |현재위치출력|현재디렉토리내의 파일과 디렉토리연결(절댓값위치)|디렉터의이동|디렉터리생성|
 |cp|mv|rm|cat|
 |파일또는 디렉터리 복사|파일또는 디렉터리이동|파일또는 디렉터리 삭제|파일 내용 확인|
 |touch|echo|ip adder/ifconfig|ss|
 |빈 파일 생성|문자열화면에 표시|ip정보 확인|네트워크 상태 확인|
 |nc|which,whereis,locate|tall|find|
 |서버의 포트확인|명령어 위치확인|파일의 마지막부분 확인|파일의 디렉토리 찾기|
 |ps|grep|kill|alias|
 |현재 실행중인 프로세스목록과 상태확인|주어진 입력값에서 패턴에 맞는 값출력|프로세스종료|명령어 별칭 만들기|
 |vi/vim|man|chmod|rmdir|
 |편집기|리눅스 명령어의 사용법, 옵션, 기능 등을 설명하는 매뉴얼 페이지를 제공한다.|파일/디렉터리의 접근 권한을 변경하는 명령어|디렉토리를 삭제한다.|
 |chown||||
 |소유권 변경 명령어||||

![pwd](https://github.com/user-attachments/assets/249d5486-3753-4cc8-bc77-d37e60c89ec7)
![image](https://github.com/user-attachments/assets/9c7a2ab9-d86d-4789-81da-6f306e7675ca)
![image](https://github.com/user-attachments/assets/48daca8b-f2c9-434d-b2c3-7bbf0b7e4111)
![image](https://github.com/user-attachments/assets/14ebec81-425c-45d0-b227-04cbce212cc3)
![image](https://github.com/user-attachments/assets/1ce74f9b-263c-4ec1-930b-af23d1f9df2d)
![image](https://github.com/user-attachments/assets/cbad1bb4-ba8c-46ca-9a35-a46612ef49ea)
![image](https://github.com/user-attachments/assets/c0b5b5ba-10c4-4983-97da-525b23924bba)
![image](https://github.com/user-attachments/assets/38b6ea88-7c7c-422d-b4f6-dd21bf698561)
![image](https://github.com/user-attachments/assets/2f39f83f-abce-41c2-88ed-ea67e942726f)
![image](https://github.com/user-attachments/assets/660eb82a-04c2-41cb-93c8-22e83fe06eea)
![image](https://github.com/user-attachments/assets/ee502df5-e028-4904-90bc-7eb5ac195cdf)
![image](https://github.com/user-attachments/assets/bbbdc654-c271-4b2f-9e7d-cb47d183fff5)
![image](https://github.com/user-attachments/assets/08274474-3823-4d5f-b1f3-71b15fde31d9)
![image](https://github.com/user-attachments/assets/49e4e524-1d0a-42be-a4fa-796139384796)
![image](https://github.com/user-attachments/assets/74c68b72-4195-418c-8510-1aee00301330)
![image](https://github.com/user-attachments/assets/90d3c3c8-a864-4a72-9b34-df24ea658812)
![image](https://github.com/user-attachments/assets/98a63b4c-e80a-4a9d-8274-1cf8e8959d87)
![image](https://github.com/user-attachments/assets/a14f3e9d-fac2-4e3f-8faf-a2a442289dbe)
![image](https://github.com/user-attachments/assets/4ba5d9e8-c3c3-4a1a-94ac-698436d288dc)
![image](https://github.com/user-attachments/assets/68db1972-fc1c-4f42-aa48-c5a99898af5d)
![image](https://github.com/user-attachments/assets/0b6214aa-33fe-473e-bd24-d3369cb27171)
![image](https://github.com/user-attachments/assets/3b4a62c6-8f53-47da-9424-f57f78581a9a)
![image](https://github.com/user-attachments/assets/7ebf7da1-ab15-46cd-8b04-a05f7f256283)
![image](https://github.com/user-attachments/assets/8166256a-c739-4fc0-8196-25a403ad0d69)
![image](https://github.com/user-attachments/assets/406f5055-3044-4032-97ac-3fd5e9a456e5)
![image](https://github.com/user-attachments/assets/31038594-78b7-4138-864e-87dd23e0e077)
![image](https://github.com/user-attachments/assets/9ee550c8-ae7d-4ba6-a28a-fc350c012fa3)
![image](https://github.com/user-attachments/assets/7ac9feed-287c-4def-8a94-31361cd0ccdf)
man (Manual) 
```
man ls : 'ls' 명령어에 대한 매뉴얼 페이지를 보여준다.
```
chmod (Change Mode)
```
chmod 755 file.sh : 'file.sh'파일에 대해 소유자에게는 읽기, 쓰기, 실행 권한을 부여하고, 그룹과 기타 사용자에게는 읽기와 실행 권한만 부여한다.

chmod u+x file.sh : 'file.sh' 파일에 대해 현재 사용자에게 실행 권한을 추가한다.

권한 변경은 보안에 영향을 줄 수 있으므로 신중히 사용해야 한다.
```
rmdir (Remove Directory)
```
rmdir은 디렉토리를 삭제한다.

rmdir old_folder : 'old_folder'라는 이름으 디렉토리를 삭제한다.

rmdir은 디렉토리가 비어있을 때만 작동한다. 내부에 파일이나 다른 디렉토리가 있으면 오류가 발생한다.

디렉토리 안의 파일과 함께 삭제하려면 rm -r 명령어를 사용해야 한다.
```





















