# CaptureMate
AI 기반 스크린샷 분석 및 행동 추천 서비스

## 프로젝트 로고


## 프로젝트 소개
CaptureMate는 사용자가 저장만 하고 잊어버리는 스크린샷을 분석하여
실제 행동(Action)으로 연결해주는 AI 기반 서비스입니다.
단순 저장 중심의 기존 갤러리 경험에서 벗어나, 사용자가 캡처한 정보를 의미 있는 액션으로 연결하는 것을 목표로 합니다.

## 프로젝트 기간
2026.03~2026.06

## 프로젝트 기능
### 📷 스크린샷 분석
- 스크린샷 업로드 및 저장
- OCR 기반 텍스트 추출
- 이미지 정보 분석

### 🤖 AI 분류
- 추출된 텍스트 기반 카테고리 분류
- 장소/일정/쇼핑/메모/기타 자동 분류

### ⚡ 추천 액션
- 장소 -> 지도(카카오맵) 연결
- 일정 -> 캘린더(애플 캘린더) 등록
- 쇼핑 -> 상품 검색
- 메모 -> 핵심 내용 요약
- 기타 -> X

### 💾 데이터 관리
- OCR 결과 저장
- 분류 결과 저장
- 추천 액션 저장 및 조회

## 협업 툴
| Category | Link |
|----------|------|
| 📚 Notion | [Project Documentation](https://www.notion.so/2026-31eab5ad9c6680cebab4d4e1f12bdccf?source=copy_link) |
| 🎨 Figma | [UI/UX Design](https://www.figma.com/design/GDilVwMlQmOjrYzz1m2NLK/2026%EC%BA%A1%EC%8A%A4%ED%86%A4-%EB%8D%B0%EA%B5%B4%EB%8D%B0%EA%B5%B4_%EC%A1%B0%EA%B0%81%EC%A1%B0%EA%B0%81?node-id=0-1&t=gjqCQFQZJCD4Ys6z-1) |

## Architecture
- Frontend: SwiftUI
- Backend: FastAPI
- DB: PostgreSQL
- AI: OCR + Classification Model

## 시작 가이드

## 👥 팀 구성 및 역할 분담
| 이름 | 역할 | 담당 |
|------|------|------|
| 나향지 | 팀장 | OCR 모델 개발, 분류 모델 학습 |
| 박성연 | 팀원 | OCR 모델 개발, 분류 모델 학습 |
| 한지은 | 팀원 | Backend API 개발, DB 설계 |
| 허채윤 | 팀원 | Frontend 개발, 분류 모델 학습 |
| 황지은 | 팀원 | Backend API 개발, DB 설계 |

## 레포지토리
기타 상세는 [프론트엔드 README.md](), [백엔드 README.md](), [AI README.md])를 참고하세요.
- 📱 [Frontend Repository](https://github.com/Daegurrrr/CaptureMate_FE)
- ⚙️ [Backend Repository](https://github.com/Daegurrrr/CaptureMate_BE)
- 🤖 [AI Repository](https://github.com/Daegurrrr/CaptureMate_AI)


...
