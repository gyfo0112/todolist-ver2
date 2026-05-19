# Todolist ver.2 ✅

useReducer + Context API 기반으로 설계한 투두리스트 앱입니다.

## 📌 프로젝트 소개
액션 / 리듀서 / 스토리지 / 컨텍스트를 각각 파일로 분리해
실제 프로젝트에 가까운 구조로 설계했습니다.
localStorage로 새로고침 후에도 데이터가 유지됩니다.

## ⚙️ 주요 기능
- 할 일 추가 / 완료 토글 / 삭제
- 실시간 검색 필터링 (useMemo 최적화)
- localStorage 자동 저장 및 불러오기
- useReducer + Context API 전역 상태 관리
- 액션 / 리듀서 / 스토리지 파일 분리 구조
- useTodoStore 커스텀 훅으로 Context 접근

## 📁 폴더 구조
```
src/
├── components/   # Header, TodoEditor, TodoList, TodoItem
└── contexts/     # TodoContext, actions, reducer, storage, useTodoActions, mockData
```

## 🛠 사용 기술
- React (useReducer, useRef, useState, useEffect, useMemo, createContext)
- localStorage
- Vite
- CSS

## 🚀 실행 방법
```bash
npm install
npm run dev
```
