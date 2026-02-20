2026.01.21 (수)

---
# [⭕️ 같은 숫자는 싫어](https://school.programmers.co.kr/learn/courses/30/lessons/12906)
#알고리즘 #프로그래머스 #문법

> [!abstract] 요약
> - arr.erase(unique(arr.begin(), arr.end()), arr.end());
> - 위 문법으로 vector에서 연속으로 중복된 숫자를 제거할 수 있음

## 1. 문제
- 중복된 숫자를 포함하는 배열에서 순서는 유지하되 연속적으로 중복된 숫자를 모두 제거하여 출력

## 2. 접근
- 배열을 순회하며 이전 값과 현재 값이 다르면 `answer`배열에 넣고, 같으면 패스

## 3. 핵심 포인트
- `erase()`와 `unique()`
	- `arr.erase(unique(arr.begin(), arr.end()), arr.end());`
	- 위 문법으로 vector 전체에서 중복된 숫자를 제거할 수 있음