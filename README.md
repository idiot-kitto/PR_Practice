# PR_Practice

this is PR practice

# Github Pull Request 연습 ( 내 Repo에서 실험 )

- 목표 Repository fork

- Local에 fork한 Repo Clone : `git clone <copied URL>`

- `cd PR_Practice` , `code .`

- 새로운 branch 생성 : git checkout -b <branch name>
`git checkout -b kitae
git branch` 로 생성된 branch, 어디 위치에 있는지 확인 가능

- 수정 작업후 add, commit, push
`git commit -a` 후 commit message 넣고, :wq로 저장 → `git push origin kitae`

- pull request 생성

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/478f8c6e-539c-4d9e-944c-a307a33033cb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/478f8c6e-539c-4d9e-944c-a307a33033cb/Untitled.png)

- master에게 이러한 Compare & pull request 버튼이 활성화 되는데, kitae라는 이름의 branch가 master에게 PR을 요청했다는 의미
- master는 수정된 내용을 보고 Merge 여부 결정

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d255d39a-dcf3-4cb1-96d0-15fb6357b84a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d255d39a-dcf3-4cb1-96d0-15fb6357b84a/Untitled.png)

- Merge가 완료되면 branch의 내용과 같이 master의 내용이 수정된다.

- branch 삭제하고 싶으면, 삭제하고 싶은 브랜치 위치가 아닌 다른 위치로 이동 후
`git branch -d <지우고 싶은 branch name>`
