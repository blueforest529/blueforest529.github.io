---
layout: post
title: '[MySQL] MySQL function update 에러'
published: true
---

MySQL에서 function update시 간혹 

<pre><code>
This function hasn none of DETERMINISTIC, NO SQL, or READS SQL DATA in its declaration and 
binary logging is enabled (you *might* want to use the less safe log_bin_trust_function_creators variable)
</code></pre>

이런 에러가 날 때가 있다.

MySQL의 특정 버전에서 Super권한이 없는 유저에게 나타나는 에러인데

<pre><code>
SET GLOBAL log_bin_trust_function_creators = 1;
</code></pre>

으로 간단히 해결할 수 있다.
