# git_study_git
git 수업입니다. 
git 저장소 생성 및 clone

git 로컬 저장소와 리모트 저장소의 차이
origin/main => 저장소이름/가지(branch)
origin/HEAD => 리모트 저장소에 등록된 최신 이력
HEAD -> main => 로컬 저장소의 최신 이력.


리모트 저장소에 로컬 저장소의 이력을 올리는 행위.
git push origin 가지이름(branchName) : 가지 단위로 이력을 올림.

git push 리모트 저장소 가지
    해당 리모트 저장소 생성자와 로컬 저장소 작업자가 동일해야 push가능.
    (브라우저 로그인 인증)
    해당 리모트 저장소의 팀원으로 등록되면 push가능.