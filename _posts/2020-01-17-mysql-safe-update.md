---
layout: post
title: [MySQL]mysql workbench safe mode 끄기
---
Mysql Workbench에서 update를 하다보면 

<pre><code>You are using safe mode and you tried to update a table without a WHERE that uses a KEY column To disable safe mode.</pre></code>

이런 오류가 뜰 대가 있다. 

update시 안전하게 update를 할 수 있는 모드인데

<pre><code>SET SQL_SAFE_UPDATES =0;</pre></code>
쿼리로 간단하게 해결할 수 있다.
