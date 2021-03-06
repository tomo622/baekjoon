##### 방법1. 'ㅜ' 모양을 제외하고 DFS를 이용

'ㅜ' 모양을 제외하고는 DFS를 이용하여 깊이 4 까지 탐색하면 나머지 문양들의 회전 및 대칭을 모두 검사할 수 있다. 'ㅜ' 모양은 따로 계산해준다.

##### 방법2. 모든 모양의 회전 및 대칭 이동 경로를 이용

모든 문양의 이동 경로를 미리 정의해 놓은 뒤에 순차 탐색을 진행한다. 모든 이동 횟수는 4회이고 대칭 및 회전할 수 있는 횟수는 'ㅡ' 문양은 2개, 'ㅁ' 문양 1개, 'ㄱ' 8개, 'ㄹ' 4개, 'ㅜ' 4개 이다.

##### 성능

처음 이 문제를 풀었을 때는 방법1을 사용했고 두 번째 시도에는 방법2를 사용했다. 방법2는 코드의 길이가 길고 노가다성(?) 코드이지만 방법1에 비해 시간을 줄일 수 있었고 메모리 또한 적게 사용할 수 있었다.