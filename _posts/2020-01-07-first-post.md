---
layout: post
title: DB에서 DateFormat 형식 지정 가져오기
image: 
---
DB에서 날짜를 가져올 때

SELECT date_format(컬럼명, '%Y-%m-%d %H:%i:%s') as 컬럼명

FROM table명

WHERE 조건;

으로 날짜 포맷 변경하여 쿼리 결과 가져오기