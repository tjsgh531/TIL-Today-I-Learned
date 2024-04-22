# github로 하는 협업 과정

[최영우 강사님 강의 youtube](https://www.youtube.com/watch?v=g3GEnjppUV0&feature=youtu.be)

## <팀장 할일>

1. github에서 New organization 클릭!

2. free 누르면 나오는 Template 작성후 Next 버튼 클릭

3. Repositories 만들기

4. Issues Temaplates 만들기

5. .gitignore 설정

[gitignore 사이트](https://www.toptal.com/developers/gitignore)

6. 초기 디렉토리 설정

8. 팀원들 코드 확인후 머지 해주기

--------------------------------------------------------------

## <팀원 할 일>

1. fork 받기

2. 자신이 fork 받은 것에서 주소 받아와 clone 하기
```shell
git clone [자신 레포 주소]
```

3. git issue 작성하기

4. 새로운 브랜치 만들기
```shell
git switch -c [새 브랜치 명]
```

5. 자신이 부여된 코드 작성하기

6. 자신이 새로만든 브랜치로 push 하기
```shell
git add [작업한 파일명]

git commit

git push origin [자신이 만든 브랜치 명]
```

7. organization repo에서 pull request하기

8. merge 완료된 main 코드 받기

``` shell
git remote add upstream [organization github http]

git fetch upstream main // FETCH_HEAD라는 파일이 생성됨

git merge FETCH_HEAD // CONFLICT 발생시 수동 해결후 다시 add -> commit -> push

```





