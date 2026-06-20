# SAP Code 멘토링 자료 (CL3 1조)

SAP Code 과정에서 **학생 멘토**로 활동하며 진행한 ABAP 멘토링 자료를 모아둔 레포지토리입니다.
ABAP 기초 문법부터 OOP, ALV, 그리고 CDS View · OData 기반의 신문법까지 단계적으로 다뤘습니다.

- **멘토:** 이창근
- **과정:** SAP Code (CL3 / 1조)
- **기간:** 2024.12 ~ 2025.02
- **총 8회 진행** (회차당 약 1시간 30분 ~ 2시간)
- **장소:** 스터디룸 / CL3 강의장

---

## 📚 전체 커리큘럼 요약

멘토링은 크게 두 텀으로 나누어 진행했습니다.
**1기**는 ABAP 기초 문법과 OOP, ALV를 중심으로, **2기**는 CDS View · 신문법 · OData를 중심으로 다뤘습니다.

| 텀 | 회차 | 일시 | 핵심 주제 |
|:---:|:---:|:---|:---|
| **1기** | 1회차 | 12/18 (목) | ABAP Dictionary, Function Group vs Report, Call By Value/Reference |
| | 2회차 | 12/23 (화) | 변수 스코프, OOP 4대 특성, ALV 기초 |
| | 3회차 | 12/30 (화) | Binary Search, 파라미터 전달 방식, ALV Event |
| | 4회차 | 01/08 (목) | Popup ALV, Memory 관리, ALV Edit |
| **2기** | 1회차 | 02/09 (월) | CDS View, AMDP/AMDF, ADBC, New Syntax |
| | 2회차 | 02/12 (목) | New Open SQL, CTS, CDS Association |
| | 3회차 | 02/19 (목) | CDS Association 심화, AMDP 실습 |
| | 4회차 | 02/26 (목) | OData / Gateway, SEGW, Fiori CRUD |

---

## 🟢 1기 — ABAP 기초 & OOP, ALV

### 1회차 — ABAP 기초 다지기
- **일시:** 12/18 (목) 18:30 ~ 20:30 · **장소:** 스터디룸
- **참여인원:** 4명 (이창근, 이하영, 김예진, 최유정)

**다룬 내용**
- ABAP Dictionary, 프로그램 기본 구조 리마인드
- Function Group vs ABAP Report Program
- Call By Value vs Call By Reference
- 실습문제 2개

📄 자료: [`CL3-1_1weeks_Overview.pdf`](./CL3-1_1weeks_Overview.pdf)

---

### 2회차 — OOP와 ALV 입문
- **일시:** 12/23 (화) 18:30 ~ 20:30 · **장소:** CL3 강의장
- **참여인원:** 3명 (이창근, 이하영, 김예진)

**다룬 내용**
- 전역변수 vs 지역변수
- OOP vs PP (절차지향)
- 객체지향 4대 특성: 캡슐화, 상속, 추상화, 다형성
- ALV, 필드 카탈로그(Field Catalog), Disvariant
- ALV 실습문제

📄 자료: [`CL3-1_2weeks_Overview.pdf`](./CL3-1_2weeks_Overview.pdf)

---

### 3회차 — 파라미터 전달 방식 & ALV Event
- **일시:** 12/30 (화) 18:30 ~ 20:30 · **장소:** CL3 강의장
- **참여인원:** 4명 (이창근, 이하영, 김예진, 최유정)

**다룬 내용**
- Binary Search
- Static vs Instance
- Changing과 Returning의 차이점
- Changing과 TABLES(FM)의 차이점
- ALV Event
- 2주차 실습문제를 활용한 ALV Event 실습

📄 자료: [`CL3-1_3weeks_Overview.pdf`](./CL3-1_3weeks_Overview.pdf)

---

### 4회차 — ALV 심화
- **일시:** 01/08 (목) 18:30 ~ 20:30 · **장소:** CL3 강의장
- **참여인원:** 4명 (이창근, 이하영, 김예진, 최유정)

**다룬 내용**
- Popup ALV
- SAP Memory / ABAP Memory
- ALV Color
- DML / TCL
- ALV Edit (Style), Event, Method

📄 자료: [`CL3-1_4weeks_Overview.pdf`](./CL3-1_4weeks_Overview.pdf)

---

## 🔵 2기 — CDS View · 신문법 & OData

### 1회차 — CDS View & New Syntax
- **일시:** 02/09 (월) 18:30 ~ 20:30 · **장소:** CL3 강의장
- **참여인원:** 4명 (이창근, 김서연, 유은수, 최민준)

**다룬 내용**
- CDS View — HANA 기반 SQL 뷰, Annotation으로 데이터의 "의미" 정의, `with parameters` 활용
- AMDP / AMDF — `IF_AMDP_MARKER_HDB` 구현, `BY DATABASE PROCEDURE/FUNCTION` (SQLScript)
- ADBC — `CL_SQL_CONNECTION` / `CL_SQL_STATEMENT` / `CL_SQL_RESULT_SET`로 외부 DB 직접 접근
- New Syntax Review — Table Expression, `NEW( )`, `VALUE( )`, Dynamic WHERE
- 조회 ALV를 New Syntax로 작성

📄 자료: [`CL3-3_1weeks_Overview.pdf`](./CL3-3_1weeks_Overview.pdf)

---

### 2회차 — New Open SQL & CDS Association
- **일시:** 02/12 (목) 18:30 ~ 20:00 · **장소:** CL3 강의장
- **참여인원:** 4명 (이창근, 김서연, 유은수, 최민준)

**다룬 내용**
- New Open SQL — SQL Expression(연산자/CAST/CASE/String), `UNION`, CTE(`WITH`), `FOR ALL ENTRIES`
- CTS (Change and Transport System) — CTS/Task 번호 구조, 프로그램 단위 분리 관리
- Association in CDS View — 지연 LEFT OUTER JOIN, `$projection`, Cardinality, Filter Condition

📄 자료: [`CL3-3_1weeks_Overview_2.pdf`](./CL3-3_1weeks_Overview_2.pdf)

---

### 3회차 — CDS Association 심화 & 실습
- **일시:** 02/19 (목) 18:30 ~ 20:00 · **장소:** CL3 강의장
- **참여인원:** 4명 (이창근, 김서연, 유은수, 최민준)

**다룬 내용**
- CDS View Association / AMDP / New Open SQL 복습
- 실습문제 진행 (1~3회차 내용 종합)
  - 실습 1: New Open SQL — `seatsfree` 계산, 점유율(CAST), `CASE`문 status
  - 실습 1-1: AMDP로 동일 로직 구현 (파라미터 사용)
  - 실습 2: CDS View + Association — `_Text` Association, `p_spras` 파라미터로 언어 필터
  - 실습 3: SAP Gateway Service 생성 (ZTCL3_20_SBOOK → UI5)

📄 자료: [`CL3-3_2weeks_Overview.pdf`](./CL3-3_2weeks_Overview.pdf)

---

### 4회차 — OData / Gateway & Fiori CRUD
- **일시:** 02/26 (목) 18:30 ~ 21:00 · **장소:** CL3 강의장
- **참여인원:** 4명 (이창근, 김서연, 유은수, 최민준)

**다룬 내용**
- OData(Open Data Protocol) / SAP NetWeaver Gateway 개념
- Gateway Service 생성 두 가지 방법 — CDS View `@OData` vs SEGW
- SEGW에서 CRUD 구현 — DPC_EXT 재정의 / Map to Data Source(RFC)
- `/IWFND/GW_CLIENT` — HTTP Method ↔ Service Operation 매핑
- CSRF Token, ALPHA Conversion, SEGW Association
- Fiori CRUD — `read` / `create` / `update` / `remove` 메소드 실습
- 실습문제 3개

📄 자료: [`CL3-3_3weeks_Overview.pdf`](./CL3-3_3weeks_Overview.pdf)

---

## 📂 자료 목록

| 회차 | 파일 |
|:---:|:---|
| 1기 1회차 | `CL3-1_1weeks_Overview.pdf` |
| 1기 2회차 | `CL3-1_2weeks_Overview.pdf` |
| 1기 3회차 | `CL3-1_3weeks_Overview.pdf` |
| 1기 4회차 | `CL3-1_4weeks_Overview.pdf` |
| 2기 1회차 | `CL3-3_1weeks_Overview.pdf` |
| 2기 2회차 | `CL3-3_1weeks_Overview_2.pdf` |
| 2기 3회차 | `CL3-3_2weeks_Overview.pdf` |
| 2기 4회차 | `CL3-3_3weeks_Overview.pdf` |
