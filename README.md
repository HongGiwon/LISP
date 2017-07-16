## LISP (팀프로젝트)
Database program by LISP
<br>LISP을 통해 구현한 보험회사 데이터베이스 시스템

### Development environment
OS : windows 7
Common LISP : XLISP-PLUS 3.05

### Run
ICDB_MP.lsp 파일과 database.txt파일을 같은 폴더에 넣고 ICDB_MP.lsp 를 XLISP-PLUS 3.05를 사용하여 실행 한다.
<br>불러오면 database.txt 파일을 읽으며, 다 읽은 후 사용할 준비가 되면 Loading complete! 라는 메시지가 출력된다. 
<br>이후 아래의 여러 함수들을 사용하여 DB에 데이터를 입력, 수정, 검색, 삭제할 수 있고 DB자체를 다시 읽거나 저장할 수 있다.


### 함수목록
regEmp - 직원 등록
<br>regIns - 보험 등록
<br>regCli - 고객 등록
<br>delEmp - 직원 삭제
<br>delCli - 고객 삭제
<br>getDatabase - 고객의 정보 출력
<br>cliSearch - 고객의 보험리스트 출력
<br>cliCost - 고객의 보험금 총액

<br>함수의 자세한 사용방법과 예시는 보고서 3번항목 참고
