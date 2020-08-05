* * *

# git 과 local folder 연결

		git init
		git remote add origin "repository address"


* * *

# git pull & push 방법

			pull: git pull origin master
			push: git status
				git add .
				git commit -m "message"
				git push origin +master


* * *

# git CRLF 에러
		
			git config --global core.autocrlf true
			


* * *

# git 협업
			
			git init
			git remote add origin [주소]
			git clone [주소] // git에 파일이 먼저 올라와 있을 경우 복사한다
			git add [./ 파일이름]
			git push -u origin master
			
			


* * *

# Reference
[git push n pull](https://youtu.be/tC8Xj_Bf8Fw)
[git CRLF 에러](https://blog.jaeyoon.io/2018/01/git-crlf.html)
