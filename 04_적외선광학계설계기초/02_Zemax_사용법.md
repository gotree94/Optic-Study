# 2. Zemax 사용법 (실습)

> Day1 오후 · Optical Design Using ZEMAX 기초~최적화

## 2.1 Zemax(OpticStudio) 인터페이스

| 창/기능 | 역할 |
|---------|------|
| **Lens Data Editor** | 렌즈 파라미터 입력 (두께, 곡률, 재료) |
| **System Explorer** | FOV, 파장, f/#, Aperture 설정 |
| **Layout/3D Viewer** | 광선 다이어그램 |
| **Spot Diagram** | 점 상 오차 |
| **MTF** | 대비 전달 |
| **Optimization** |Merit Function 최적화|

## 2.2 실습 1: Optical Design Using ZEMAX

| 단계 | 작업 |
|------|------|
| 1 | 단위·파장·Aperture 설정 |
| 2 | Field 설정 (축상/주변) |
| 3 | 렌즈 1~2장 입력 (곡률, 두께, Glass) |
| 4 | Layout 확인, Spot Diagram 확인 |
| 5 | 기본 성능 파악 |

## 2.3 실습 2: Advanced Modeling

- 비축상, 복잡한 구조 모델링
- Surface type (Aspheric, Toroidal 등)
- Pick-up, Solve 상태 설정

## 2.4 실습 3: Fold Mirror Example

| 학습 내용 | 설명 |
|-----------|------|
| Fold Mirror 추가 | 경로 꺾기 |
| Coordinate Break | 회전·평행이동 |
| Mirror orientation | 각도 오차 이해 |

```
[입사] → [거울(45°)] → [렌즈군] → [초점]
```

## 2.5 실습 4: Prisms & Optical Power 없는 구성요소

| 구성 | Zemax 표기 |
|------|-----------|
| **Prism** | 여러 Surface 조합 |
| **Plate** | 평판 유리 |
| **Grating/Diffraction** | 회절 표면 |

## 2.6 실습 5: Introduction to Optimization

| 개념 | 설명 |
|------|------|
| **Merit Function** | 목표 함수 (RMS spot, MTF 등) |
| **Variable** | 곡률, 두께, Glass 등 변수 |
| **Operand** | RMS spot radius, Edge thickness 등 |
| **Local Optimization** | 근소 최적화 |
| **Hammer/Damped Least Squares** | 강한 탐색 |

### 최적화 절차
```
[Merit Function 설정] → [Variable 지정] → [Optimization 실행] → [결과 검토] → [재설정]
```

## 2.7 실습 6: Double Gauss Design

| 항목 | 내용 |
|------|------|
| **구조** | 대칭형 고성능 렌즈 |
| **학습** | 복수 렌즈 최적화 흐름 |
| **MTF** | 중앙/주변 비교 |
| **Glass 선택** | 분산·n 조합 |

## 2.8 실습 체크리스트

- [ ] System 설정 (Aperture, Wavelength, Field)
- [ ] Lens Data Editor 입력 익숙
- [ ] Layout으로 광선 추적 확인
- [ ] Spot Diagram / MTF 해석
- [ ] Merit Function 구성·최적화 실행
- [ ] 결과 비교·재최적화

## 2.9 다음 강으로
→ [03_적외선렌즈_설계전략.md](03_적외선렌즈_설계전략.md) (Day2)
