# ExpressJsBoardStudy
# mysql 커뮤니티 서버를 설치하고 webAppBoard.sql 를 실행시켜서 db를 만드세요!
# 'npm i'라는 명령어로 의존성 주입(package.json)된 node 모듈을 설치하세요!
# 개발할때 nodemon app.js로 서버를 시작하세요!

<h2>주의사항!</h2>
<ul>
    <li>main branch 에서 작업하지 마세요!</li>
    <li>수업에 따라서 작성할때는 study 브랜치를 생성해서 작업하세요</li>
</ul>  
<h2>프로젝트에 기여하고 싶다면?</h2>
<ul>
    <li>git checkout main : 메인 브랜치 선택</li>
    <li>git pull origin main : 메인 브랜치 최신이력 가져오기</li>
    <li>git checkout -b 'branchName:ex) replyInsert,boardListView' : 작업할 새로운 가지 생성</li>
    <li>git add .</li>
    <li>git commit -m "COMMENT"</li>
    <li>git push origin 'branchName' (마지막 한번)</li>
    <li>나머지는 팀장이 병합하기 때문에 신경쓰지 마세요.</li>
</ul>

<h2>팀장이 병합하는 방법</h2>
<ol>
    <li>리모트 저장소에 올라온 최신 이력을 살펴본다.</li>
    <li>git fetch origin '팀원의 branch'</li>
    <li>git checkout '팀원의 가지'</li>
    <ul>
    <li> (오류대비, git checkout --track origin/'팀원가지'로 적용하면 로컬에 팀원 가지가 생성됨. 
    <li> merge할때도 git merge '팀원가지'하면 된다.</li>
    </ul>
    <li>실행 및 구동 테스트 </li>
    <li>git merge origin/'팀원가지'</li>
    <li>살펴볼 필요 없이 바로 병합하고 싶은 경우</li>
    <li> => git pull origin '팀원가지'=>(fetch+merge)</li>
    <li>병합 충돌이 발생한 경우 : 충돌내역을 수정하고 git add. git commit -m"COMMENT"</li>
    <li>git push origin main</li>
    <li>팀원들이 main의 최신이력으로 pull해서 사용</li>
</ol>

