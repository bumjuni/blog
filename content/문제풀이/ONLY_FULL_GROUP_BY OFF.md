#SQL 

- SQL 문법 중 `GROUP BY`절에서 `SELECT`절에 등장한 column이 GROUP BY에는 등장하지 않았을 때 발생하는 에러이다.
- 왜 필요?
	- GROUP BY를 하면 조건을 건 column을 기준으로 하나의 레코드만 남겨지는데, 이때 GROUP BY 조건을 충분히 걸지 않으면 조건 column을 제외한 나머지 column의 경우 무슨 값을 취해야 하는지 알 수 없게 된다. 
- 어떻게 방지?
	- SELECT에 작성한 모든 column (집계함수 사용하는 column 제외)을 GROUP BY에도 작성한다
	