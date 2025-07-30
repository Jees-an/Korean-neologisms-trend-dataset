# 📈 **K-NEOBENCH-TREND**: 현대 한국어 신어 사용 추이

## 1. 개요

**K-NEOBENCH-TREND**는 2012년 이후 등장한 한국어 신어의 사용 추이 분석을 위한 보조 벤치마크입니다.  
다양한 데이터(말뭉치, Google Trends 등)를 통해 신어의 사용 양상을 분석하였으며, 시간의 변화에 따른 신어의 사용 추이를 제공합니다.

---

## 2. 데이터 구성

### 📌 말뭉치 연도별 상대 빈도 *(forthcoming)*

### 📌 Google Trends 월별 검색 관심도(2009.01.~2025.06., 총 198개월)

- 총 4,744개 신어를 대상으로 분석 기간 내 월별 검색 관심도를 0~100 범위의 상대값으로 표현
    - 국립국어원 *신어 조사 사업* (2012~2019년 신어, 총 3,361개)
      > 국립국어원 *신어 조사 사업*의 모든 결과물의 저작권은 국립국어원에 있습니다.
      - 🔗 [국립국어원 연구 보고서](https://www.korean.go.kr/front/reportData/reportDataList.do?searchOrder=years&mn_id=207)

    - 경북대학교 언어정보연구센터 *신어 조사 사업* (2020~2023년 신어, 총 1,383개)
      > 경북대학교 *신어 조사 사업*의 결과물은 아래의 저장소에서 DB 형태로 확인하실 수 있습니다.
      - 📘 **K-NEOBENCH**: [현대 한국어 신어 벤치마크](https://github.com/Jees-an/K-NEOBENCH)

- 사용 API: DataForSEO Google Trend API (Type: `WEB`)

---

## 3. 주요 예시

![예시 (1)](img/Korean_Neologism_Usage_Trend_Example_(1).jpg)
![예시 (2)](img/Korean_Neologism_Usage_Trend_Example_(2).jpg)
![예시 (3)](img/Korean_Neologism_Usage_Trend_Example_(3).jpg)
![예시 (4)](img/Korean_Neologism_Usage_Trend_Example_(4).jpg)

---

## 4. 사용 방법

- 🔍 DataForSEO API의 원시 응답 결과(JSON 형식)는 `./raw_json/` 폴더에 저장되어 있으며, 필요 시 검증 및 재가공에 활용할 수 있습니다.
- 📊 2012년 이후 한국 언론 매체에서 최초로 출현한 총 4,744개 신어에 대한 Google Trends 월별 검색 관심도(2009.01.~2025.06., 총 198개월)의 그래프는 `./graphs/` 폴더에 저장되어 있습니다.

---

## 5. 참고문헌

- 국립국어원(2012~2019), 『2012~2019년 신어 자료집』, 연구 책임자: 남길임
- 남길임·이수진·안진산(2025), 「말뭉치, LLMs, 인간 전문가의 협업을 통한 한국어 신어의 탐지」, 『한국어학』 108호 (*forthcoming*).
- [남길임 외(2021), 『신어 2020』, 한국문화사](https://product.kyobobook.co.kr/detail/S000001848151)
- [남길임 외(2022), 『신어 2021』, 한국문화사](https://product.kyobobook.co.kr/detail/S000200563843)
- [남길임 외(2023), 『신어 2022』, 한국문화사](https://product.kyobobook.co.kr/detail/S000211731664)
- [남길임 외(2024), 『신어 2023』, 한국문화사](https://product.kyobobook.co.kr/detail/S000215101540)
- 남길임 외(2025), 『신어 2024』, 한국문화사 (*forthcoming*).
- [Zheng et al. (2024), *NEO-BENCH: Evaluating Robustness of Large Language Models with Neologisms* (현대 영어 신어 벤치마크), arXiv](https://arxiv.org/pdf/2402.12261)