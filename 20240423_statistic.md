## 기술 통계

- 합법칙 곱법칙

- 순열 조합

```python
import itertools

cards = list(range(1, 5+1))

result = list(itertools.permutations(cards, 3))

result = list(itertools.cobinations(cards, 3))
```

- 합사건, 곱사건, 배반사건, 여사건

- 조건부 확률

- 독립사건, 종속사건

- 독립변수, 종속변수, 매개변수

## 변수의 종류

- 질적변수: 비서열 질적 변수, 서열질적변수

- 양적변수 : 연속변수, 비연속변수

- 범주형 척도: 명목척도, 서열척도 

- 연속형 척도:등간척도, 비율척도

## 모집단과 표본

- 모집단, 모수 / 표본, 통계량

- 확률적 표본추출방법: 단순 무작위 표본추출, 체계적 표본추출, 비례 층화 표본추출, 다단계 층화 표본추출, 군집 표본 추출

- 비확률적 표본추출방법: 편의 표본 추출, 판단 표본 추출, 할당 표본 추출, 자발적 표본 추출

## 그래프 시각화

- 막대그래프

plt.hist(data, alpha, bins, rwidth, color)

- 파이 그래프

plt.pie(data, labels, colors, autopct, shadow, startangle)

- 사분위 박스그래프

sns.boxplot(x, y, data)

```python

import matplotlib.pyplot as plt


# 해당 범위에 속한 값을 가지고 있는 item(행)의 개수
plt.hist(df['lifeExp'], alph=0.2, bins=7, rwidth=20, color='red')

# pie 그래프 그리기
sizes = [624, 300, 396, 360, 24]
labels = [1, 2, 3, 4, 5]
colors = ['red', 'green', 'blue', 'yellow', 'purple']

plt.pie(sizes, labels= labels, colors=colors, autopct='%.1f%%', shadow=False, startangle=90)
plt.axis('equal')
plt.show()

# 사분위 박스 그래프
import seaboarn as sns

sns.boxplot(x='continent', y='lifeExp', data = df)

```

## 기술통계량

- 중심 경향도 : 평균 , 중앙값 , 최빈값

- 산포도 : 분산, 표준편차, 범위

- 비대칭도 : 왜도 첨도

- 통계량 : 표본 분산, 표본표준편차

## 확률변수

- 이산확률변수, 연속확률변수

- 사건, 확률변수, 확률, 확률함수

## 확률분포

- 균등분포, 정규분포, 표준정규분포

- 베르누이 분포, 이항분포

## 추정

- 점추정, 구간추정

- 추정치, 추정량

- 신뢰구간, 신뢰수준
