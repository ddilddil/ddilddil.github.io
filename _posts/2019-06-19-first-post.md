---
title: "깃블로그 테마 입히기"
date: 2019-06-19 14:31:00 -0400
categories: jekyll update
---

## 1. jekyll 테마 가져오기
지킬 테마 찾아서 내 깃헙에 올린다.(인터넷에 찾으면 많다.)
zip으로 가져오면 commit, push 해주던, fork 하던 내 리파지토리에 올려야한다. 
나는 minimal-mistakes 가져옴.

## 2. 설정파일 수정하기
불필요한 파일이나 폴더는 삭제한다. zip으로 가져왔을 때는 지우고 commit, push하면 된다.
fork한 경우엔 git init, git clone해서 git rm~~ 사용해서 삭제하고 commit, push하면 된다. 사용법은 찾아보면 잘 나온다.
minimal-mistakes가 아닌 다른 테마는 잘 모르겠다.

수정할 파일은 .gitignore, Gemfile, _config.yml, index.html 파일이다.
이것도 인터넷 잘 나와있음 얘왜 누워잇냐

## 3. 깃헙 setting 수정하기
테마 올린 리파지토리에 settings로 가서 name을 바궈줘야한다. "내유저네임.github.io"로 수정해야한다. 그래야 css, 이미지등을 잘 불러온다.
수정안하면 css, 이미지파일등이 404에러 나면서 글자만 화면에 나오게된다.
GitHub Pages 부분에서도 소스부분을 master branch로 수정한다.

### https ://내유저네임.github.io 으로 접속하면 기본 화면이 나온다.
(중간공백 없애고.. 링크가 걸리길레 공백넣음..)

###### 젬이 뭐고 번들이 뭐고 잘 몰라서 해맸다. 삽질하다가 나는 fork하고, 로컬에 clone하고 git rm 으로 폴더, 파일 삭제하고, commit, push하고, 내 깃헙에 테마 올린 리파지토리에서 직접 설정파일 수정하고, settings 바꿨다.

언제 블로그처럼 꾸미냐.......... 글쓰는거 익히는 것도 오래걸릴거같은데......
