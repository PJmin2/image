# image
https://m.blog.naver.com/dhdh6190/221077723132
![image](https://github.com/PJmin2/image/assets/146954412/b8a739a4-f51f-4d1d-94b9-554bc1e42c98)
HDB3의 경우, 0이 연속해서 4번 나오는 구간을 찾는다. 첫번째 구간의 경우 직전 대치가 없으므로, 앞의 1의 개수가 2개이므로 B00V로 뒤섞는다. 이전 부호가 - 였으므로 +00+ 이 된다.
두번째 연속 4개 구간은 직전의 대치 이후의 1의 개수가 3개이므로, 000V로 뒤섞는다. 이전 부호가 -였으므로 000-로 바꿔준다.
세번째 연속 4개 구간은 직전 대치 이후의 1의 개수가 없으므로, B00V로 뒤섞는다. 이전 부호가 -였으므로 +00+로 대치한다.
마지막 연속 4개 구간은 직전 대치 이후의 1의 개수가 위와 마찬가지로 없기 때문에 B00V로 바꾼다. 이전의 부호가 +였기 떄문에 -00-가 된다.

7장 까지 시험범위
