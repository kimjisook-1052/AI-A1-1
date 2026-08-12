# 나만의 프롬프트 관리 프로그램

터미널에서 메뉴 번호를 입력해 프롬프트를 관리하는 콘솔 기반 프로그램입니다.
프롬프트를 카테고리별로 등록하고, 검색하고, 즐겨찾기로 관리할 수 있습니다.

## 실행 방법

```bash
python main.py
```

프로그램 실행 후 화면에 나오는 메뉴 번호를 입력하면 원하는 기능을 사용할 수 있습니다.

## 기능 목록

1. **프롬프트 추가** — 제목, 내용, 카테고리를 입력해 새 프롬프트를 등록합니다. 제목/내용은 빈 값으로 등록할 수 없습니다.
2. **프롬프트 목록 보기** — 등록된 모든 프롬프트를 카테고리와 즐겨찾기 표시(⭐)와 함께 보여줍니다.
3. **카테고리별 조회** — 카테고리를 선택하면 해당 카테고리의 프롬프트만 보여줍니다.
4. **프롬프트 검색** — 키워드로 제목/내용을 검색합니다.
5. **프롬프트 상세 보기** — 번호를 선택하면 해당 프롬프트의 전체 내용을 보여줍니다.
6. **즐겨찾기 관리** — 번호를 선택해 즐겨찾기를 추가하거나 해제합니다.
7. **즐겨찾기 목록** — 즐겨찾기로 등록된 프롬프트만 모아서 보여줍니다.
8. **종료** — 프로그램을 종료합니다.

## 카테고리 종류

텍스트 생성, 이미지 생성, 영상 생성, 페르소나, 자동화, 기타

## 기본 등록 프롬프트

프로그램 실행 시 아래 3개의 프롬프트가 기본으로 등록되어 있습니다.

- 블로그 글쓰기 (텍스트 생성)
- 영어 번역 (텍스트 생성)
- 이미지 프롬프트 (이미지 생성)

## 개발 환경

- Python 3.10 이상
- VSCode
- Git / GitHub

<img width="510" height="155" alt="image" src="https://github.com/user-attachments/assets/222762a1-2b79-483f-a23a-15e271ab37b1" />

최종 체크리스트
항목	상태
콘솔 프로그램 (8개 메뉴 모두 동작)	✅
기본 프롬프트 3개 이상	✅
GitHub 저장소 업로드	✅
커밋 10개 이상	✅ (18개)
브랜치 생성 + 병합	✅ (3회)
README.md (설명+실행방법+설계문서)	✅
함수별 코드 분리	✅
git clone 로그	✅ 

 python --version, git --version 결과
<img width="473" height="65" alt="image" src="https://github.com/user-attachments/assets/41261f12-940f-49be-9351-435b20d0ee2c" />

 
 git config --list

 <img width="455" height="305" alt="image" src="https://github.com/user-attachments/assets/50ff43f5-9c35-4311-8d07-1a8ac3cfa1d7" />

 
 git clone 실행 로그 
 <img width="510" height="155" alt="image" src="https://github.com/user-attachments/assets/222762a1-2b79-483f-a23a-15e271ab37b1" />

 
 메뉴 화면
<img width="448" height="246" alt="image" src="https://github.com/user-attachments/assets/b5353daa-cab4-4ed3-9e93-2d7e2d8d5755" />

 
 프롬프트 추가 과정
<img width="431" height="226" alt="image" src="https://github.com/user-attachments/assets/f4ba532c-f811-43a0-ace0-dd4b1b88f2e8" />

 
 목록 보기
<img width="503" height="237" alt="image" src="https://github.com/user-attachments/assets/a817ed2a-134f-4f30-9a5b-18822898a352" />

 
 카테고리별 조회
 
 <img width="438" height="92" alt="image" src="https://github.com/user-attachments/assets/89a1e1dd-1622-4b46-a864-ce73208d60f6" />

 검색 결과
 
<img width="499" height="137" alt="image" src="https://github.com/user-attachments/assets/17edb515-0e57-4f4f-80ec-369ede3bba9b" />

 
 
 상세 보기

 <img width="448" height="173" alt="image" src="https://github.com/user-attachments/assets/e36a674e-6b32-40c2-b837-3f5101e9f629" />

 즐겨찾기 관리/목록
<img width="450" height="90" alt="image" src="https://github.com/user-attachments/assets/99d2ed0f-a432-49df-8854-1b1f8bd2862e" />

 
 git log --oneline --graph
 <img width="498" height="274" alt="image" src="https://github.com/user-attachments/assets/ca153aa5-4d28-4461-8ea2-1b6a48623ab7" />

