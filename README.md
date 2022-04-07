# QM-Memory-Check
Quine-McCluskey 메모리 및 실행시간 자동 확인 프로그램  
다운로드 : https://github.com/ESALKW/QM-Memory-Check/blob/main/QMChk.exe

## 사용법
1. 같은 폴더 내에 아래와 같이 파일을 넣습니다 : QMChk.exe, 프로그램, input_minterm.txt
![image](https://user-images.githubusercontent.com/6492071/162135819-e189c74a-db1c-496e-8a14-276904967b3c.png)

2. PowerShell을 키고 cmd를 쳐서 명령 프롬프트를 실행합니다.
![image](https://user-images.githubusercontent.com/6492071/162136026-10a20b0c-c5e0-4b2b-80d4-c0c33fce6ba2.png)  
![image](https://user-images.githubusercontent.com/6492071/162136104-ece437ab-3dec-4b71-b813-f3f88c4536ba.png)  

3. 아래 명령을 통해 프로그램을 실행합니다.
QMChk.exe <자신의 Quine-McCluskey 구현 실행파일>  
예 : QMChk.exe I_HATE_TEAM_PROJECT.exe  
![image](https://user-images.githubusercontent.com/6492071/162136220-a02ec11f-c9e2-46b1-95b0-b52d5ab6d2ba.png)  
실행이 종료되면 위와 같이 Memory에 관련된 지표와 프로그램의 실행 시간이 표시됩니다.

## 실행시 화면
![image](https://user-images.githubusercontent.com/6492071/161973365-f083462b-2bac-453f-b160-3a4e36029e4e.png)  

## 오류
1. CreateProcess failed : 경로를 다시 확인해주세요  
![image](https://user-images.githubusercontent.com/6492071/162136366-192c3e37-b44b-424b-8706-a2b67b1fb1a1.png)  
2.Exit code 관련 문제 : 프로그램이 비정상 종료된 경우입니다.  
![image](https://user-images.githubusercontent.com/6492071/162136504-d0d8a112-6465-46f4-bfb2-14169d80bbdb.png)

## 질문
 프로그램에 대해 질문은 받지 않습니다.  
 프로그램이 동작하지 않는데 만약 본인의 잘못이 아니라고 생각되는 경우에만 조교에게 메일 바랍니다.

## 맥/리눅스용 프로그램은 없나요
메모리 사용량 측정은 그 특성상 같은 OS에서 측정한 것이 아니면 동일성을 보장할 수 없습니다.  
따라서 지원할 계획이 없습니다. 이에 대해 문의는 받지 않습니다.
