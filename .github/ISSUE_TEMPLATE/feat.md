---
name: feat template 
about: 기능 개발
title: '[FEAT] 기능 개발'
labels: feat
assignees: '류다은'
---

## 🧩 Issue 요약
메인 페이지에 검색 기능을 추가합니다. 

---

## 🎯 작업 목적 (Why)
사용자가 원하는 정보를 빠르게 찾도록 도와주기 위함입니다. 
---

## 🧱 작업 범위 (Scope)
- 검색 입력 UI 구현
- 검색 API 구현
- 게시글 검색 쿼리 작성
- 검색 결과 리스트 출력
- 페이지네이션 구현 

---

## 🛠️ 구현 상세 (How)

### 1. 디자인 참조
- **Figma Link**: [피그마 컴포넌트 링크 삽입]

### 2. Mock Data (연동 전 임시 데이터)
```json
{
  "id": 1,
  "title": "상품명",
  "price": 10000,
  "imageUrl": "[https://example.com/image.png](https://example.com/image.png)"
}

---

## 🔗 참고 자료 (Optional)
<!-- 참고 링크, 문서 -->

---

## ⚠️ 고려 사항 (Optional)
<!-- 주의할 점 -->
ex) 
- price는 0 이상
- name은 null 불가