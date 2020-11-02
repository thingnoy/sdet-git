#sdet-git

# GIT COMMAND SUMMARY
- git clone
    clone project จาก remote repository

- git remote
    add: ใช้ set remote ได้มากกว่า 1 remote เช่น github, bitbucket

- git add
    คือการ add file เข้าสู่สถานะ staged

- git commit
    คือการ add commit เข้าไป local repository

- git push
    คือการ push file ขึ้น remote เช่น git push -u github main

- git pull
    คือการดึงไฟล์จาก remote มายัง local repository

- git log
    คือการดูประวัติการ commit เช่น git log --oneline --graph

- git config
    คือการ set config ของ git เช่น user, email, remote-url,

- git rebase
    คือการ modify history ของ commit เช่น รวมหลายๆ commit ให้เป็น commit เดียว

- git branch ดู current branch
    --ra: คือการดู branch ทั้งหมด

- git checkout
    คือการดึง branch ที่ต้องการ จาก remote repo ลงมายัง local repo

- git switch 
    คือการสลับ branch ใน local repo

- git restore
    คือการย้อนกลับสถานะจาก staged ไปยัง unstaged

- git status
    คือการดูสถานะการทำงานปัจจุบันของ git

- git reset
    คือการเปลี่ยน HEAD pointer ไปยัง commit ที่ต้องการ
    --soft: คือการเปลี่ยน HEAD แต่ยังคง commit ไว้ เช่น มี commit a b c ถ้า reset ไปที่ commit b แต่ commit c จะยังอยู่
    --hard: คือการเปลี่ยน HEAD จะลบ commit เช่น มี commit a b c ถ้า reset ไปที่ commit b แต่ commit c จะถูกลบออก
