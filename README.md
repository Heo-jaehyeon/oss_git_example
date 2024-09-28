# **오픈소스소프트웨어**

### Introduction

-------------
### Week1-1 강의 개요 (강의계획서)
> 오픈소스소프트웨어는 3가지 목표를 지향한다
> 1. 오픈 소스 소프트웨어 개발을 위한 기본 개념과 도구, 특히 소스 코드 버전 컨트롤과 패키지 관리, 프로젝트 빌드를 중점으로 배운다.
> 2. 애자일 기반 소프트웨어 개발 방법인 짝프로그래밍, 테스트 주도 개발 등을 공부한다
> 3. 낯선 소프트웨어 개발 환경 및 도구를 스스로 배우는 태도를 배우는것을 목적으로 한다

-------------
### Week1-2 오픈소스소프트웨어 개요
* #### Open Source의 특징  
1. 소스 코드가 공개되어 있어 원하는대로 사용/복사/재배포 가능
2. 공개된 소스의 무료 사용 권리가 있으나 그에 따른 법적 책임이 뒤따름
3. 권한 및 책임의 종류에 따라 약 1000가지의 다양한 open source license 존재
  
* #### Richard Stallman
 ![Richard Stallman](https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Richard_Stallman_Bologna_2024_abc1.jpg/462px-Richard_Stallman_Bologna_2024_abc1.jpg)  
1. Free Software Foundation 설립
2. GNU Project 창시자
3. S.W 특허 및 DRM 반대

* #### 오픈소스소프트웨어 라이센스 종류   
  **_GPL, LGPL, MPL, BSD-style_**
  
-------------
### Week2-1 버전 관리 개요
#### General Actions in VCS: Checkin
* Check in a file(list.txt) and modify it over time

#### Diffs
* The trunk has a history of changes as a file evolves

#### Branching
* Copy code into a separate folder so we can have a separate history of changes

#### Merging
* Merge changes from one branch to another
-------------
### Week2-2 Git
#### Introduction to GIT
##### Linus Torvalds
* For collaboration of development of Linux kernel
##### A distributed version control system
* Workspace : files you are working with  
* Index: (staged) files to be considered in the next commit  
* Local repository : files committed to the local repo  
* Remote repository : files pushed to the remote repo

![Git WorkFlow](https://github.com/user-attachments/assets/9764a8f6-bab9-4980-8a6a-f279c8df6107)

-------------
### Week2-3 Github, fork, pull request
* fork
  > fork는 다른 사람의 Github repository에서 내가 어떤 부분을 수정하거나 추가 기능을 넣고 싶을때 해당 해당 respository를 내 Github repository로 그대로 복제하는 기능
* pull requset
  > 다른 사용자가 작성한 저장소에서 변경 사항을 병합(merge)하기 위한 요청을 의미


![One of the Git Flow © Sammy Baek](https://lh3.googleusercontent.com/d/1dBD4F8sNrgrfk7wOnAckN9W5Qud_SlHS=w1000?authuser=0)


-------------
### Week3 Markdown
#### Markdown
  > 마크다운(Markdown)은 일반 텍스트 기반의 경량 마크업 언어이다
  > 마크업 언어란, 태그 등을 이용하여 문서나 데이터의 구조 등을 명기하는 언어의 한 가지이다
  > 텍스트만으로 서식이 있는 문서들을 작성할 때 자주 사용되며, 다른 마크업 언어들에 비해 문법이 쉽고 간단한 것이 특징
  > HTML 등의 서식 문서들로 쉽게 변환되기 때문에 README 파일이나 온라인 게시물 등에 사용된다
  
  **마크다운 (Markdown)** 은 _존 그루버(John Gruber)_ 와 _아론 스워츠(Aaron Swartz)_ 가 만들었다

마크다운은 [나무위키][1] 를 참고했습니다

[1]: https://namu.wiki/w/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4
