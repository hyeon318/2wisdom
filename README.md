"# 2wisdom"
기존 로직에서 왜인지는 모르겠지만...<br>
파일 업로드할 때 필요한 DATA를 자동으로 만들어주기 위함..(왜..?)<br>
<br><br>
해당 엑셀 파일들은 외부에서 받는 파일이기에 정해진 양식이 전혀 없음 (왜?)<br>
특정 데이터 AA 를 기준으로 복사해서 새로운 엑셀 파일로 COPY 함<br>
제목이 다를 경우 A 코드가 + 1<br>
회차가 다를 경우 B 코드가 + 1<br>
C코드는 A + C(시리즈와는 다르지만 비슷한 시퀀스) + B 형태로 구현댐..<br>
<br><br>
일단 현재 작업중인 시퀀스와 마지막으로 작업한 시퀀스를 쿠키에 저장하였음<br>
<br>
개발자가 사용하는 것이 아닌 다른 팀에서 사용하는 파일이기 때문에 따로 프로젝트가 아닌 html 파일 하나로 만들어 구현
