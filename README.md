<details>
<summary>첫 기여 테스트 [다시보기]</summary>
<div markdown="1">

# First Practice : `Contribution`

어렵습니다. 무엇을 하든 누구나 처음에는 어렵게 느껴집니다. 특히 협업을 할 때 실수를 하기라도 하면 마음이 편치 않습니다. 그래서 저희는 새로운 오픈소스 기여자들이 첫 기여를 하고 그것을 익히는 과정을 단순화하고자 했습니다.

관련된 글을 읽거나 튜토리얼을 보는 것도 물론 도움이 되지만, 연습공간에서 직접 해보는 것보다 나은게 있을까요? 이 프로젝트의 목표는 초보자도 첫 오픈소스 기여를 할 수 있도록 단순한 방식으로 안내하는 것입니다. 첫 기여를 하고 싶으시다면 아래의 설명을 따라주세요.

가장 먼저, Git이 없으시다면 [설치](https://help.github.com/articles/set-up-git/)해주세요.

## 저장소 클론하기

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="이 저장소 복제하기" />

이제 이 저장소를 자신의 기기에 클론합니다. Clone or download 버튼을 클릭하고 클립보드로 복사 아이콘을 클릭합니다.

터미널을 열고 다음 Git 명령을 실행합니다:

```
git clone "방금 복사한 URL"
```

위에 (따옴표를 제외한) "방금 복사한 URL"는 이 저장소의 URL입니다. URL은 이전 단계에서 찾을 수 있습니다.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="URL 을 클립보드로 복사" />

예시:

```
git clone https://github.com/SSAFY-Seoul-Algorithm-Study/Git-Practice.git
```

예시의 `this-is-you`는 본인 깃헙 계정으로 바꾸어주세요. 이 명령어는
깃헙의 gitTEST 저장소의 내용을 로컬 컴퓨터에 복사합니다.

## 브랜치 생성하기

(아직 저장소 디렉토리가 아니라면) 아래의 명령어를 입력하여 좀전에 컴퓨터에 복사한 저장소 디렉토리로 이동합니다.

```
cd Git-Practice
```

그리고 `git switch(checkout)` 명령어을 입력하여 브랜치를 생성합니다.

```
git switch -c <add-your-name>

또는

git checkout -b <add-your-name>
```

예시:

```
git switch -c add-alonzo-church

또는

git checkout -b add-alonzo-church
```

(브랜치의 이름에 꼭 *add*가 들어가지 않아도 됩니다. 하지만 이 브랜치의 목적은 당신의 이름을 리스트에 추가하는 것이기 때문에 이름에 *add*를 포함하는 것이 합리적입니다.)

## 필요한 변경사항을 작성하고 커밋하기

이제 텍스트 편집기에서 `Contributors.md` 파일을 열고 본인의 이름을 추가해주세요. 이름을 추가할때는 줄바꿈으로 구분해주세요. 이때 마크다운 분법에 따라 이전 이름에 ' '(띄어쓰기 3번)을 해야 정상적인 줄바꿈이 됩니다. 그리고 파일을 저장하세요.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

프로젝트 디렉터리에서 `git status` 명령을 실행하면 변경사항을 볼 수 있습니다.

변경사항을 아래 `git add` 명령어를 입력하여 추가합니다.

```
git add Contributors.md
```

이제 아래 `git commit` 명령어로 변경사항을 커밋합니다.

```
git commit -m "Add <Your-name> to Contributors list"
```

`<Your-name>`을 본인 이름으로 바꾸세요.

만약, 이미 한 번 add 했던 파일이라면 아래 명령어로 모든 파일을 한 번에 add + commit 할 수 있습니다.

```
git commit -am "Add <Your-name> to Contributors list"
```

## 변경사항을 깃헙에 푸시하기

`git push` 명령어로 변경사항을 푸시합니다.

```
git push origin <add-your-name>
```

위의 `<add-your-name>` 부분을 좀전에 생성한 브랜치 이름으로 바꾸세요.

## 검토를 위해 변경사항을 제출하기

이제 본인의 깃헙 저장소로 이동하면 `Compare & pull request` 버튼이 보일 것 입니다. 버튼을 클릭하세요.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="풀 요청
생성하기" />

이제 풀 요청(Pull Request)을 제출합니다.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="풀 요청 제출하기"
/>

이제 여러분의 변경사항을 담당자가 확인한 후에 마스터 브랜치에 머지 하게 되면 알림 메일을 받으실겁니다.

## 첫 기여, 그리고 그 후

축하합니다! 앞으로 기여자로써 자주 사용하게될 기본 워크플로우, _포크(fork) -> 클론(clone) -> 수정(edit) -> 풀 요청(pull request)_, 를 완수하셨습니다!!!

</div>
</details>

<details>
<summary>👨‍🌾 에피소드1 : 모코코를 찾아라!! [다시보기] </summary>
<div markdown="1">

# 👨‍🌾 에피소드1 : 모코코를 찾아라!!

성공적으로 Contributors에 이름을 남긴 여러분들을 시기한 나쁜 모코코들이 mokoko폴더에 숨어들어 Contributors 파일들을 망치려하고 있습니다. 여러분들은 mokoko폴더에 숨어있는 모코코 jpg사진들을 모두 없애야 합니다! 하지만, mokoko 사진들은 함부로 삭제할 수가 없습니다. github issues에 등록된 모코코 사진들만 삭제가 가능합니다. 여러분들은 아래 절차에 따라 모든 모코코 사진을 삭제해주세요!  
![모코코콘1](https://user-images.githubusercontent.com/31841502/159016081-12f707ae-50a7-450a-b648-eb5e1a401974.png)

## 여러분이 해야 할 일들

1. issues에 [mokoko 발견! - AA모코코]가 등록되면 Assignees에 본인을 등록 한 후 작업을 시작하세요.
2. git pull origin main 을 통해 최신 버전의 main브랜치를 가져옵니다.
3. 새로 브랜치를 만들어 AA모코코와 이름이 같은 mokoko폴더 안의 사진을 삭제 한 후, add,commit,push를 순서대로 진행 해 주세요.
4. pull request를 등록하면 끝!

## 유의사항

- 한 명 당 한 개의 모코코 사진만 삭제할 수 있습니다.
- 등록된 Issues에 자신이 해결하겠다 하는 의미로 Assignees에 본인을 추가하고 작업해주세요.
- Assignees에 할당된 팀원이 있다면 이미 배정자가 있다는 의미이므로 동시작업은 하지 말아주세요.
- 모든 모코코가 동시에 Issues에 등록되지는 않습니다. 어느 날 어느시간 갑자기 추가될 수 있으니 Slack알림을 참고해주세요!

</div>
</details>

<!-- <details>
<summary>🍗 에피소드2 : 모코코 치킨 종합선물세트! [다시보기] </summary>
<div markdown="1"> -->


# 🍗 에피소드2 : 모코코 치킨 종합선물세트!

실컷 혼쭐이 난 모코코들이 반성의 의미로 여러분들에게 선물을 들고 찾아왔습니다. 모두가 좋아할거라 확신하며 모코코들이 들고 온 선물은 바로바로 **모코코 치킨 종합선물세트!!** 민트초코 치킨과 따뜻한 파인애플 치킨, 고수를 듬뿍올린 어니언 치킨이 어우러진 모코코 치킨 종합선물세트를 여러분들이 꼭 먹어치워야 합니다. 착한 어른은 성의를 무시해선 안되거든요. 하지만 2개의 치킨이 든 모코코 치킨 종합선물세트는 한 명이서 다 먹기엔 양이 너무 많습니다. 그러기에 한 테이블에 2명이서 모여 치킨을 먹어야 합니다. 다음 절차를 따라 2명이서 테이블에 모여 모코코 치킨 종합선물세트를 먹어주세요!

![모코코콘1](https://user-images.githubusercontent.com/31841502/160538195-de89d2ba-acef-4709-9262-a52816da89a9.png)

## 요구되는 사전지식

실습을 시작하기 전 git flow에 대한 선행 학습이 필요합니다. 크게 main-develop-feature브랜치로 나뉘어져 작업되는 flow를 잘 모르시는 분들은 구글링이나 아래 링크를 통해 꼭 공부를 하고 진행해주세요.  
 [우린 Git-flow를 사용하고 있어요](https://techblog.woowahan.com/2553/)  
 [Git flow 개념 이해하기](https://uxgjs.tistory.com/183)

## 여러분이 해야 할 일들

<img src="https://user-images.githubusercontent.com/31841502/160543681-7aa919ce-961d-45ef-917c-a584e8363746.png" width="400" height="400"/>

1. git pull origin develop 을 통해 최신 버전의 develop브랜치를 가져옵니다. 자신이 작업할 브랜치 이름을 feature-이름 으로 작성해 작업해주세요.
2. table.txt파일에 본인의 이름을 테이블 근처에 넣고 저장해주세요. 그 후 add,commit을 순서대로 진행 해 주세요.
3. origin develop 브랜치에 push 후 pull request를 등록해주세요.
4. pull request 후 리뷰는 꼭 **팀장이 아닌 팀원 최소 2명**의 리뷰를 받아야 합니다.
5. 리뷰어들은 table.txt에 이름이 잘 들어갔는지, table.txt파일의 테이블 근처에 사람이 2명이 모여 2인 테이블이 완성되었는지 확인해주세요.
   1. 2인 테이블이 완성되었다면 - develop 브랜치에 merge,delete branch 후 main 브랜치에 pull request 요청을 보냅니다.
   2. 2인 테이블이 완성되지 않았다면 - develop 브랜치에 merge,delete branch 하면 끝!

## 리뷰를 남기는 방법
<img width="1407" alt="image" src="https://user-images.githubusercontent.com/77713508/231183830-5ff8d013-cf43-4d4f-90bf-dfbedcbeb854.png">
리뷰는 Pull Requests 탭에서 해당 Pull Request를 선택 후, Files changed 탭에서 우측 상단의 Review Changes 버튼으로 등록할 수 있습니다.
여기서 Comment는 리뷰가 아닌 단순 댓글로 등록하기이므로 리뷰 수에 세어지지 않고, Approve를 통해 승인하거나 Request changes를 통해 아직 수정해야 점을 알릴 수 있습니다.

## 유의사항

- 팀원의 리뷰가 필요하니 슬랙이나 깃허브에서 리뷰어를 찾아 리뷰를 요청해주세요!
- 리뷰어들은 리뷰 후 merge 이후에 pull request에 요청을 보낸 브랜치를 삭제해주세요!!

<!-- </div>
</details>


# 📔 에피소드3 : 모코코의 "여름방학 계획서" 복구하기 !!

여러분들의 뛰어난 코딩실력을 보고 감동을 받은 모코코들이 여름방학 때 열심히 코딩을 공부해서 여러분들 같이 뛰어난 개발자가 되기로 결심했습니다! 모코코들은 2달이나 남은 여름방학의 계획서를 작성했다고 하는데요, 아니나 다를까 계획서는 엉망진창이었습니다. 거기다 여름방학 계획서는

![모코코콘1](https://user-images.githubusercontent.com/31841502/160538195-de89d2ba-acef-4709-9262-a52816da89a9.png)

## 요구되는 사전지식
실습을 시작하기 전 git flow에 대한 선행 학습이 필요합니다. 크게 main-develop-feature브랜치로 나뉘어져 작업되는 flow를 잘 모르시는 분들은 구글링이나 아래 링크를 통해 꼭 공부를 하고 진행해주세요.  
 [우린 Git-flow를 사용하고 있어요](https://techblog.woowahan.com/2553/)  
 [Git flow 개념 이해하기](https://uxgjs.tistory.com/183)

## 여러분이 해야 할 일들

<img src="https://user-images.githubusercontent.com/31841502/160543681-7aa919ce-961d-45ef-917c-a584e8363746.png" width="400" height="400"/>

1. git pull origin develop 을 통해 최신 버전의 develop브랜치를 가져옵니다. 자신이 작업할 브랜치 이름을 feature-이름 으로 작성해 작업해주세요.
2. table.txt파일에 본인의 이름을 테이블 근처에 넣고 저장해주세요. 그 후 add,commit을 순서대로 진행 해 주세요.
3. origin develop 브랜치에 push 후 pull request를 등록해주세요.
4. pull request 후 리뷰는 꼭 **팀장이 아닌 팀원 최소 1명**의 리뷰를 받아야 합니다.
5. 리뷰어들은 table.txt에 이름이 잘 들어갔는지, table.txt파일의 테이블 근처에 사람이 3명이 모여 3인 테이블이 완성되었는지 확인해주세요.
   1. 3인 테이블이 완성되었다면 - develop 브랜치에 merge,delete branch 후 main 브랜치에 pull request 요청을 보냅니다.
   2. 3인 테이블이 완성되지 않았다면 - develop 브랜치에 merge,delete branch 하면 끝!

## 유의사항

- 팀원의 리뷰가 필요하니 슬랙이나 깃허브에서 리뷰어를 찾아 리뷰를 요청해주세요!
- 리뷰어들은 리뷰 후 merge 이후에 pull request에 요청을 보낸 브랜치를 삭제해주세요!! -->
