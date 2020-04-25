---
layout: post
published: true
title: '[GitHub] Repositories public -> private로 변경 후 호스팅 안될 때'
---
저번에 회사 사람과 점심을 먹다가 깃허브 비공개 저장소를 무료로 만들수 있다는 따끈 따끈한 소식을 들었던 기억이 나 오늘 내 깃허브 블로그로 실험을 해보았다...

그런데 public 프로젝트를 private로 바꾼 뒤 이것 저것 확인 해 보고 다시 public으로 바꾸니

호스팅이 안된다!

잠깐 당황을하고, 구글링을 열심히 해보았지만 답을 찾을 순 없었다.

![public으로 바꾼뒤 바로.PNG]({{site.baseurl}}/img/public으로 바꾼뒤 바로.PNG)
private에서 publicd으로 바꾸면 전 과는 다르게 이렇게 뜬다.

역시나...
내 github 블로그로 들어가보니 404 에러가 뜬다... 
![404 페이지.PNG]({{site.baseurl}}/img/404 페이지.PNG)


이리 저리 찾아보다 단서를 발견했다.

https://pages.github.com/
여기선 커밋을 하면 된다고 써져 있는데 과연 될까...?

커밋을 했더니 정상적으로 호스팅이 된다!!

**private저장소를 public으로 바꾼 뒤 호스팅이 안될땐 커밋 후 다시 호스팅 하기!**


