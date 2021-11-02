# pyalgo
파이썬 알고리즘 인터뷰 - 알고리즘 공부

## url 정리

깃허브 소스코드 다운로드
https://github.com/onlybooks/algorithm-interview

유튜브 강의 https://bit.ly/algorithm-interview-youtube



PEP ( 파이썬 개선 제안서) 8 가이드라인 tab space 4

파이썬은 소문자와 _ 스네이크 방식으로 코딩컨벤션을 맞춤

 

온라인 코딩 테스트시에  mypy 를 이용하면 타입힌트 오류체크가 가능하다.

코드 제출전 한번 사용하고 제출하자

pip install mypy



### 파이썬 코딩스타일 가이드 



파이썬  PEP 8

https://www.python.org/dev/peps/pep-0008/

구글 파이썬 스타일 가이드

http://google.github.io/styleguide/pyguide.html



팀소트?

### 파이썬 딕셔너리 ( 자바의 Hash map 과 동일 )

collections.defaultdict() 를 통해 선언없이 초기화할경우 디폴트값을 0으로 지정해서 객체가 추가됨

Counter 객체

```python
a = [1, 2, 3, 4, 5, 5, 5, 6, 6]

b = collections.Counter(a)

Counter({5: 3, 6: 2, 1: 1, 2: 1, 3: 1, 4: 1})

type( b )

<class 'collections.Counter'>

b.moust_common(2)
[{5,3}, {6, 2}]

```



### 타입선언

[] = list

() = tuple

{} = dict (딕셔너리) - map Key : value

{1} = set
