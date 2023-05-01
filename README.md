# github_connect

## 1. [git설치](https://git-scm.com/download/win) 🍄

- git에 오렬할 폴더에 가서 shift + 우클릭하여 Powershell 창열기 
                  
      git init
      
      
- .git 폴더가 생성됨


      git을 통해서 githhub과 연결할 수 있다          
------------------
## 2. git 설피후 git bash 열기 🍄
![image](https://user-images.githubusercontent.com/129017008/235417906-9b3e6477-aba9-4b5f-9e16-7e3f74721926.png)
 
* 유저이름설정 😲
     
        git config --global user.name "myunzzhang"

* 유저이메일설정 😲

        git connfig --global user.email "kguswjd418@naver.com"
        
* 내정보 확인하기 😲

        git config --list
        
## ⬆️ 위의 연결은 해당 컴퓨터에서 한번에 실행하면 됨
----------------------------

# github에 코드 업로드하기 🍄

    * 초기화 🥴
        git init
        
    * 추가할 파일(폴더안에 내용을 모두 올림, .은 모든 파일을 의미) 🥴
        git add .
        
    * 히스토리 만들기(-m은 메세지를 의미함 ""안에는 히스토리이름을 적음) 🥴
        git commit -m "first commit"
         
    * github의 repository를 만들고 그 주소와 연결하기 🥴
        git remote add origin  https://github.com/myunzzhang/css_flex.git
        
    * 연결이 잘 되옸는지 확인하기(사용안해도됨) 🥴
        git remote -v
        
    * github에 올리기
        git push origin master
----------------------

## 수정하여 다시 업로드할때 🍄

1. 기존의 코드를 다운받는 행위를 해야한다
   
     git pull origin master
        
2. 다시 push 해야한다

     git push origin master
     
