---
layout: post
title: 〔eclipse〕이클립스 톰켓 서버 에러
---
이클립스 서버 에러

1. 프로젝트 우클릭 -> properties -> project Facets에서 dynamic Web Module, java, js 체크 Runtimes 에서 톰켓 체크

2. 프로젝트 우클릭 -> properties -> Targeted Runtimes 에서 톰켓 체크

3. 프로젝트 우클릭 -> build path -> java build path 다시 잡기

4. 프로젝트 우클릭 -> build path -> java build path -> libraries -> Apache Tomcat, EAR, JRE, Web 체크

5. 톰캣 server.xml, web.xml 설정 바꿔주기
