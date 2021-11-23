# blueciel
사용법  
parsing rule
|컬럼명|data type|comment|
| :---: | :--- | ---: |
|client|varchar(100)|client|
|proejct|varchar(100)|project|
|feeder|varchar(100)|feeder|
|category|varchar(100)|key|
|key_name|varchar(100)|key 이름|
|extract_method|varchar(100)|추출 방법|
|seq|int(11)|결과 정렬 순번|
|find_word|varchar(100)|대상 문장 검색어|
|find_next_word|varchar(100)|아래 줄 검색어|
|next_line|int(4)|아래 줄 조회 수|
|extract_rule|varchar(100)|추출 용 정규 식|

parse result
컬럼명|data type|comment
:---|:---:|:---
client|varchar(100)|client
proejct|varchar(100)|proejct
discipline|varchar(100)|
feeder|varchar(100)|
doc_type|varchar(10)|
te_name|varchar(100)|table extract 이름
seq|int(11)|결과 정렬 순번
category|varchar(100)|key
key_name|varchar(100)|key 이름
te_value|varchar(100)|table extract 결과 값
total_page|int(11)|문서 총 페이지 수
page_no|int(11)|추출 문장이 있는 페이지 번호
file_name|varchar(100)|
content_num|int(11)|
content_value|varchar(200)|값 추출 문장
creation_dt|timestamp|CURRENT_TIMESTAMP
