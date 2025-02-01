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
아래 명령어 실행 후 본인 계정으로 로그인 완료
```
azd auth login
```
### 3. 설치 ###
```
azd up
```


