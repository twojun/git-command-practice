Git & Github command practice </br></br>
last modified date : 24-04-11  </br></br> </br></br>


git fetch origin
- 원격 저장소의 최신 변경사항을 로컬로 가져오는 명령어 (로컬의 브랜치에는 영향X)</br></br></br>


git checkout 브랜치명
- 해당 브랜치로 이동</br></br></br>


git add . 
- 변경 사항을 모두 스테이징에 올린다.</br></br></br>


git commit -m "commit message"
- 스테이징에 올라온 변경사항을 모두 로컬 저장소로 커밋 </br></br></br>


git push --set-upstream origin 브랜치명
- 현재 작업 중인 브랜치를 기준으로 커밋된 내용을 원격 저장소로 push  </br></br></br> 


git branch 
- 로컬의 현재 브랜치 리스트를 모두 출력</br></br></br>


git branch -d 브랜치명
- 로컬의 브랜치를 삭제
- 삭제하려는 브랜치에 이미 있는 상황이라면 삭제할 수 없으니 다른 브랜치로 checkout한 후 삭제 가능합니다.  </br></br></br>


git push origin --delete 브랜치명</br></br></br>
- 원격에서도 브랜치를 삭제
