오늘의 삽질이다... ㅎㅎ

<code><pre>
Caused by: com.mysql.cj.exceptions.InvalidConnectionAttributeException: The server time zone value '????α? ????' is unrecognized or represents more than one time zone. You must configure either the server or JDBC driver (via the serverTimezone configuration property) to use a more specifc time zone value if you want to utilize time zone support.
</pre></code>

이 에러가 발생을 했다... 
(jdbc 버전 : 8.0.17)

한참을 고민하다가 답을 얻었는데

jdbc를 연결하는 URL에 serverTimeZone을 추가해주면 간단하게 끝난다!

<pre>
jdbc:mysql://127.0.0.1:3306/test1?## serverTimezone=UTC
</pre>
