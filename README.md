# CSE_curriculum_map_crawling
인하대학교 컴퓨터공학과 학년도별 이수체계도 정보를 크롤링하고 `.csv` 파일로 저장합니다

## CSV 파일 형식
`curriculum_map.csv` 파일은 다음과 같은 형식으로 저장됩니다

| 학년도 | 학년 | 학기 | 교과목명                | 구분 | 필수 여부 | 학수번호 | 학점 |
| ------ | ---- | ---- | ----------------------- | ---- | --------- | -------- | ---- |
| 2024   | 1    | 1    | 객체지향프로그래밍1     | 전공 | 필수      | CSE1101  | 3    |
| 2024   | 1    | 1    | 컴퓨터공학입문          | 전공 | 필수      | CSE1112  | 2    |
| 2024   | 1    | 2    | 객체지향프로그래밍2     | 전공 | 필수      | CSE1103  | 3    |
| 2024   | 1    | 2    | 창의적컴퓨터공학설계     | 전공 | 선택      | CSE1105  | 3    |
