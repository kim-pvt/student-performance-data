# Brief Analysis on Student Performance Data Set


# 変数名一覧

|No.| 変数名 | 内容 | 詳細|
|:-:|:-|:-|:-|
1 | school | 学校名|binary 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira
2 | sex | 性別|binary: 'F' - female or 'M' - male
3 | age | 年齢|numeric: from 15 to 22
4 | address | 居住地域 |binary: 'U' - urban or 'R' - rural
5 | famsize | 世帯人数 |binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3
6 | Pstatus | 両親との同居有無 |binary: 'T' - living together or 'A' - apart
7 | Medu | 母親の学歴 |numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education
8 | Fedu | 父親の学歴 |numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education
9 | Mjob | 母親の職業 |nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other'
10 | Fjob | 父親の職業  |nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other'
11 | reason | 現在籍校への進学理由 |nominal: close to 'home', school 'reputation', 'course' preference or 'other'
12 | guardian |保護者 |nominal: 'mother', 'father' or 'other'
13 |traveltime |通学時間 |numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour
14 |studytime |週平均学習時間 |numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours
15 |failures |落とした単位数 |numeric: n if 1<=n<3, else 4
16 |schoolsup |追加学習サポート |binary: yes or no
17 |famsup |家族の学習サポート |binary: yes or no
18 |paid |追加有料講座受講|binary: yes or no
19 |activities |課外活動 |binary: yes or no
20 |nursery |保育園歴 |binary: yes or no
21 |higher |大学進学希望 |binary: yes or no
22 |internet |自宅ネット環境 |binary: yes or no
23 |romantic |交際相手 |binary: yes or no
24 |famrel |家族との関係 |numeric: from 1 - very bad to 5 - excellent
25 |freetime |放課後の自由時間 |numeric: from 1 - very low to 5 - very high
26 |goout |交友頻度 |numeric: from 1 - very low to 5 - very high
27 |Dalc |平日の飲酒 |numeric: from 1 - very low to 5 - very high
28 |Walc |週末の飲酒 |numeric: from 1 - very low to 5 - very high
29 |health |健康状態 |numeric: from 1 - very bad to 5 - very good
30 |absences |欠席日数 |numeric: from 0 to 93
31 |G1 |一学期の成績 |numeric: from 0 to 20
31 |G2 |二学期の成績 |numeric: from 0 to 20
32 | G3 |三学期の成績 |numeric: from 0 to 20 ＊目的変数
