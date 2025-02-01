# Multimodal GenAI experience: Q&A on uploaded images #
![image](https://github.com/user-attachments/assets/29628936-d5d1-4b40-9a74-f28b232fb15d)

## 사전 작업 ##
### 1. Python 최신 버전 설치 ###
https://www.python.org/downloads/ <br>
### 2. Git 설치 ###
Windows 용 - https://git-scm.com/downloads/win <br>
Mac 용 - Homebrew 설치하고
```
 brew install git
```
### 3. azd 설치 ###
1) Windows용 - PowerShell 터미널에서 아래 명령어 실행 <br>
```
winget install microsoft.azd
```
2) Mac용 - 터미널에서 아래 명령어 실행<br>
```
brew tap azure/azd && brew install azd
```

## 설치 과정은 아래 문서 참조 ##
https://azure.github.io/ai-app-templates/repo/azure-samples/openai-chat-vision-quickstart/

### 1. 템플릿 초기화 ###
```
azd init -t openai-chat-vision-quickstart
```
아래 환경 설정 이름은 jobgreegi** (**은 사용자번호)
```
? Enter a new environment name: jobgreegi01
SUCCESS: New project initialized!
You can view the template code in your directory:
/path/to/directory
```
### 2. Azure Login ###

```
azd auth login
```
명령어 실행 후 본인 계정으로 로그인 완료
![image](https://github.com/user-attachments/assets/30994441-7d7a-4bb4-963a-ea83d1dbf441) <br>

초기 암호는 변경합니다.<br>
![image](https://github.com/user-attachments/assets/f3eb9a20-6e54-4026-8815-46ba3ca129d9)

보안 설정은 '나중에 질문'으로 넘어갑니다.<br>
![image](https://github.com/user-attachments/assets/2b657de2-928f-4250-8d2d-4e22d5daf9a4)

'설정 건너띄기'를 선택합니다. <br>
![image](https://github.com/user-attachments/assets/7c00867b-7675-4497-8ae3-78b71fa0d78d)


### 3. 설치 ###
```
azd up
```


