---
layout: post
published: false
title: '[Spring] URL주소 설정하기'
---
spring 초기 셋팅 후 톰캣을 실행하면

![1.PNG]({{site.baseurl}}/img/1.PNG)

Hello World!에 <http://localhost:8080/web/> <- URL이 나오게 된다.

이 부분은 HomeController.java에서 바꿀수 있는데

![2.PNG]({{site.baseurl}}/img/2.PNG)

<pre>@RequestMapping(value = "/HomeController", method = RequestMethod.GET)</pre>

로 바꾸면 <http://localhost:8080/web/HomeController>으로 접속이 가능하다!

![3.PNG]({{site.baseurl}}/img/3.PNG)

