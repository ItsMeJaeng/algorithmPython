
# 브랜치 관련
```re

	// 브랜치 만들기
   	   $ git branch [브랜치명]


	// 로컬 저장소 브랜치명 변경
   	   // 이름 변경
   	   $ git branch -m [현재명] [변경할명]
   	
   	   // 현재 브랜치 조회
   	   $ git branch

	// GitHub 저장소 브랜치명 변경
   	   $ git push origin [새로운브랜치명]
   
  	    // 이전 branch 삭제 (아래 둘 중 하나)
   	   $ git push origin --delete [현재명]
   	   $ git push origin :[현재명]
   
   	   // 생성과 삭제를 동시에 하는 방법
   	   // 이름 변경은 아니지만 현재 branch를 삭제하고 새로운 branch에 내용을 옮기는 것
   	   $ git push origin : [현재명] [변경할명]


	//GitHub내 세팅에서 master를 jaeng으로 바꾸고 gitbash에서 로컬도 변경해준다.
	$ git branch -m master jaeng
	$ git fetch origin
	$ git branch -u origin/jaeng jaeng
	$ git remote set-head origin -a

```

   
   
