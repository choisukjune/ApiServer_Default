# ApiServer_Default
MongoDB 쿼리요청후 결과를 전송해준다.
다른 3rdParty Library를 사용하지 않고 쿼리결과를 전송할 수 있다.
Mongoose와 같은 라이브러리는 쿼리를 작성하기 복잡한 반면 순수 MongoDB 쿼리문을 실행하는 형태로 쿼리문 작성이 용이하다.

템플릿 쿼리파일의 문자열을 치환해 쿼리요청을한다.( ****.TDBjs -> ****.DBjs )
직관적인 쿼리사용이 용이하게 작성해봤다.
