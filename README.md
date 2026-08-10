미션 쉽게 설명해드릴게요! 😊
🎯 한 줄 요약
"AI 프롬프트를 저장하고 관리하는 나만의 메모장 프로그램" 을 만드는 거예요!

🤔 프롬프트가 뭐예요?
code
📋 복사
ChatGPT나 AI한테 질문할 때 입력하는 글이 바로 "프롬프트"예요!

예시)
"파이썬으로 계산기 만드는 코드 짜줘"  ← 이게 프롬프트!
"영어 이메일 번역해줘"               ← 이것도 프롬프트!
"블로그 글 요약해줘"                 ← 이것도 프롬프트!
📱 어떤 프로그램이냐면...
이런 상황 겪어본 적 있나요?
code
📋 복사
😫 "저번에 AI한테 좋은 질문했는데... 뭐라고 했더라?"
😫 "매번 비슷한 질문을 새로 타이핑하기 귀찮다..."
😫 "자주 쓰는 프롬프트를 어딘가에 저장하고 싶다!"
이 프로그램으로 해결!
code
📋 복사
😊 좋은 프롬프트를 저장해두고
😊 나중에 꺼내서 다시 쓰고
😊 검색도 하고
😊 즐겨찾기도 할 수 있어요!
🖥️ 실제로 어떻게 생겼냐면
code
📋 복사
=== 프롬프트 관리 프로그램 ===

1. 프롬프트 추가      ← 새로운 프롬프트 저장
2. 목록 보기          ← 저장된 것들 전체 보기
3. 검색               ← 원하는 프롬프트 찾기
4. 즐겨찾기 보기      ← 자주 쓰는 것만 모아보기
5. 종료

선택하세요: 
📋 전체 작업 순서 (쉽게!)
code
📋 복사
STEP 1️⃣  VSCode 설치        ← 코드 작성 프로그램 설치
                                (지금 하고 있는 단계!)

STEP 2️⃣  Python 설치        ← 프로그램 언어 설치

STEP 3️⃣  GitHub 가입        ← 내 코드 저장하는 공간 만들기
                                (구글 드라이브 같은 것!)

STEP 4️⃣  코드 작성          ← 실제 프로그램 만들기

STEP 5️⃣  GitHub에 올리기    ← 완성된 코드 저장/제출
🏁 최종 결과물
code
📋 복사
✅ 내가 직접 만든 Python 프로그램
✅ GitHub에 올라간 나의 첫 번째 프로젝트
✅ 실제로 사용 가능한 프롬프트 메모장!
혹시 더 궁금한 부분이 있으면 편하게 물어보세요! 😊
지금 VSCode 설치는 잘 되고 있나요? 🎉



🐍 Python & Git 미션 시작 가이드
걱정 마세요! 처음이라도 단계별로 따라오면 충분히 할 수 있어요. 😊
큰 그림부터 보고, 하나씩 차근차근 진행해봅시다!

📋 전체 진행 순서 (로드맵)
code
📋 복사
1단계: 환경 설정 (VSCode, Python, Git 설치)
2단계: GitHub 저장소 만들기
3단계: Python 기초 문법 익히기
4단계: 프로그램 코드 작성하기
5단계: Git으로 버전 관리하기
6단계: README 작성 & 최종 제출
1단계: 환경 설정 🛠️
① VSCode 설치
구글에 "VSCode 다운로드" 검색
https://code.visualstudio.com 접속
본인 OS(Windows/Mac)에 맞게 다운로드 & 설치
② Python 설치
구글에 "Python 다운로드" 검색
https://python.org 접속
Python 3.10 이상 버전 다운로드
⚠️ Windows는 설치 시 "Add Python to PATH" 반드시 체크!
③ 설치 확인 (터미널에서)
VSCode를 열고 상단 메뉴 → 터미널 → 새 터미널 클릭 후 입력:

bash
📋 복사
# Python 버전 확인
python --version
# 결과 예시: Python 3.11.0

# Git 버전 확인  
git --version
# 결과 예시: git version 2.40.0
④ VSCode 확장 프로그램 설치
VSCode 왼쪽 사이드바에서 블록 아이콘(Extensions) 클릭 후 검색:

Python → Microsoft 것 설치
Korean Language Pack → Microsoft 것 설치 (선택)
⑤ Git 초기 설정
터미널에 아래 입력 (이름/이메일은 본인 것으로):

bash
📋 복사
git config --global user.name "홍길동"
git config --global user.email "your@email.com"
git config --global init.defaultBranch main
2단계: GitHub 저장소 만들기 📁
https://github.com 접속 & 로그인
오른쪽 상단 "+" → "New repository" 클릭
설정:
code
📋 복사
Repository name: prompt-manager
Description: 나만의 프롬프트 관리 프로그램
Public 선택 ✅
Add a README file 체크 ✅
"Create repository" 클릭
3단계: 로컬 폴더 & Git 연결 🔗
터미널에서 순서대로 입력:

bash
📋 복사
# 1. 작업할 폴더 만들기
mkdir prompt-manager
cd prompt-manager

# 2. Git 저장소 초기화
git init

# 3. GitHub 저장소 연결 (URL은 본인 것으로!)
git remote add origin https://github.com/본인아이디/prompt-manager.git

# 4. GitHub에서 README 가져오기
git pull origin main
4단계: Python 기초 문법 빠르게 익히기 📚
코드 작성 전에 딱 필요한 것만 알아봐요!

VSCode에서 test.py 파일을 만들고 아래 코드를 직접 실행해보세요:

변수와 출력
python
📋 복사
# 변수 만들기
name = "홍길동"
age = 25

# 출력하기
print("안녕하세요!")
print(name)
print(f"나이: {age}살")  # f-string: 변수를 문자열에 넣는 방법
리스트와 딕셔너리 (프로그램에서 핵심!)
python
📋 복사
# 리스트: 여러 개를 순서대로 저장
fruits = ["사과", "바나나", "포도"]
print(fruits[0])  # 사과 (0번째)

# 딕셔너리: 이름표(key)와 값(value) 쌍으로 저장
prompt = {
    "title": "블로그 글쓰기",
    "content": "SEO에 최적화된 블로그 글을 써줘",
    "category": "텍스트 생성",
    "favorite": False
}
print(prompt["title"])  # 블로그 글쓰기
조건문
python
📋 복사
number = int(input("숫자 입력: "))  # input()으로 사용자 입력 받기

if number == 1:
    print("1번 선택!")
elif number == 2:
    print("2번 선택!")
else:
    print("잘못된 입력")
반복문
python
📋 복사
prompts = ["프롬프트1", "프롬프트2", "프롬프트3"]

for i, prompt in enumerate(prompts, 1):
    print(f"{i}. {prompt}")
# 결과:
# 1. 프롬프트1
# 2. 프롬프트2
# 3. 프롬프트3
함수
python
📋 복사
# 함수 정의
def say_hello(name):
    print(f"안녕하세요, {name}님!")

# 함수 호출
say_hello("홍길동")  # 안녕하세요, 홍길동님!
5단계: 프로그램 코드 작성하기 💻
prompt_manager.py 파일을 만들고 아래 코드를 작성하세요:

python
📋 복사
# =============================================
# 나만의 프롬프트 관리 프로그램
# =============================================

# 기본 데이터 (이전 미션 프롬프트 3개 이상 등록)
prompts = [
    {
        "title": "블로그 포스팅 작성",
        "content": "당신은 SEO 전문가입니다. 키워드 '파이썬 기초'를 포함하여 검색 상위 노출이 가능한 블로그 글을 작성해주세요.",
        "category": "텍스트 생성",
        "favorite": False
    },
    {
        "title": "판타지 배경 이미지",
        "content": "A magical forest with glowing mushrooms, fantasy art style, highly detailed, 4K resolution",
        "category": "이미지 생성",
        "favorite": True
    },
    {
        "title": "친절한 고객상담 페르소나",
        "content": "당신은 10년 경력의 친절한 고객상담사입니다. 항상 공감하며 해결책을 제시하고, 마지막엔 추가 도움이 필요한지 확인하세요.",
        "category": "페르소나",
        "favorite": False
    }
]

# 카테고리 목록
CATEGORIES = ["텍스트 생성", "이미지 생성", "영상 생성", "페르소나", "자동화", "기타"]


# =============================================
# 함수 정의
# =============================================

def show_menu():
    """메뉴를 출력하는 함수"""
    print("\n" + "="*40)
    print("   📚 나만의 프롬프트 관리 프로그램")
    print("="*40)
    print("1. 프롬프트 추가")
    print("2. 전체 목록 보기")
    print("3. 카테고리별 조회")
    print("4. 프롬프트 검색")
    print("5. 프롬프트 상세 보기")
    print("6. 즐겨찾기 관리")
    print("0. 종료")
    print("="*40)


def add_prompt():
    """프롬프트를 추가하는 함수"""
    print("\n--- ✏️ 프롬프트 추가 ---")
    
    # 제목 입력 (빈 값이면 다시 요청)
    while True:
        title = input("제목: ").strip()
        if title:
            break
        print("⚠️ 제목을 입력해주세요.")
    
    # 내용 입력
    while True:
        content = input("내용: ").strip()
        if content:
            break
        print("⚠️ 내용을 입력해주세요.")
    
    # 카테고리 선택
    print("\n카테고리를 선택하세요:")
    for i, cat in enumerate(CATEGORIES, 1):
        print(f"{i}. {cat}")
    
    while True:
        cat_input = input("번호 선택 (직접 입력도 가능): ").strip()
        if cat_input.isdigit() and 1 <= int(cat_input) <= len(CATEGORIES):
            category = CATEGORIES[int(cat_input) - 1]
            break
        elif cat_input:
            category = cat_input
            break
        print("⚠️ 카테고리를 선택해주세요.")
    
    # 새 프롬프트 딕셔너리 생성
    new_prompt = {
        "title": title,
        "content": content,
        "category": category,
        "favorite": False
    }
    
    prompts.append(new_prompt)
    print(f"\n✅ '{title}' 프롬프트가 추가되었습니다!")


def show_list():
    """전체 목록을 출력하는 함수"""
    print("\n--- 📋 전체 프롬프트 목록 ---")
    
    if not prompts:  # 리스트가 비어있으면
        print("등록된 프롬프트가 없습니다.")
        return
    
    for i, prompt in enumerate(prompts, 1):
        star = "⭐" if prompt["favorite"] else "  "
        print(f"{i}. {star} [{prompt['category']}] {prompt['title']}")


def show_by_category():
    """카테고리별로 조회하는 함수"""
    print("\n--- 🗂️ 카테고리별 조회 ---")
    print("카테고리를 선택하세요:")
    
    for i, cat in enumerate(CATEGORIES, 1):
        print(f"{i}. {cat}")
    
    choice = input("번호 선택: ").strip()
    
    if not choice.isdigit() or not (1 <= int(choice) <= len(CATEGORIES)):
        print("⚠️ 올바른 번호를 입력해주세요.")
        return
    
    selected = CATEGORIES[int(choice) - 1]
    
    # 해당 카테고리 필터링
    filtered = [p for p in prompts if p["category"] == selected]
    
    if not filtered:
        print(f"'{selected}' 카테고리에 프롬프트가 없습니다.")
        return
    
    print(f"\n[{selected}] 카테고리 프롬프트:")
    for i, prompt in enumerate(filtered, 1):
        star = "⭐" if prompt["favorite"] else "  "
        print(f"{i}. {star} {prompt['title']}")


def search_prompt():
    """키워드로 검색하는 함수"""
    print("\n--- 🔍 프롬프트 검색 ---")
    keyword = input("검색 키워드: ").strip()
    
    if not keyword:
        print("⚠️ 키워드를 입력해주세요.")
        return
    
    # 제목 또는 내용에 키워드가 포함된 것 검색
    results = [p for p in prompts 
               if keyword in p["title"] or keyword in p["content"]]
    
    if not results:
        print(f"'{keyword}'에 대한 검색 결과가 없습니다.")
        return
    
    print(f"\n🔎 '{keyword}' 검색 결과 ({len(results)}개):")
    for i, prompt in enumerate(results, 1):
        star = "⭐" if prompt["favorite"] else "  "
        print(f"{i}. {star} [{prompt['category']}] {prompt['title']}")


def show_detail():
    """프롬프트 상세 보기 함수"""
    print("\n--- 📄 프롬프트 상세 보기 ---")
    show_list()
    
    if not prompts:
        return
    
    try:
        num = int(input("\n번호 입력: "))
        if 1 <= num <= len(prompts):
            p = prompts[num - 1]
            print("\n" + "="*40)
            print(f"제목: {p['title']}")
            print(f"카테고리: {p['category']}")
            print(f"즐겨찾기: {'⭐ 즐겨찾기' if p['favorite'] else '없음'}")
            print(f"내용:\n{p['content']}")
            print("="*40)
        else:
            print("⚠️ 올바른 번호를 입력해주세요.")
    except ValueError:
        print("⚠️ 숫자를 입력해주세요.")


def manage_favorites():
    """즐겨찾기 관리 함수"""
    print("\n--- ⭐ 즐겨찾기 관리 ---")
    print("1. 즐겨찾기 추가/해제")
    print("2. 즐겨찾기 목록 보기")
    
    choice = input("선택: ").strip()
    
    if choice == "1":
        show_list()
        if not prompts:
            return
        try:
            num = int(input("\n번호 입력: "))
            if 1 <= num <= len(prompts):
                # 즐겨찾기 토글 (True↔False)


🎯 완성된 프로그램 코드 & 제출 가이드
결과 예시에 맞춰 완성된 코드를 드릴게요! 차근차근 따라해봐요 😊

📁 먼저 파일 구조 확인
code
📋 복사
prompt-manager/
├── prompt_manager.py   ← 메인 프로그램 파일
├── README.md           ← 프로젝트 설명 파일
└── .gitignore          ← Git 제외 파일 목록
💻 완성된 전체 코드
VSCode에서 prompt_manager.py 파일을 만들고 아래 코드를 그대로 복사하세요:

python
📋 복사
# =============================================
# 나만의 프롬프트 관리 프로그램
# =============================================

# 카테고리 목록 (전역 상수)
CATEGORIES = ["텍스트 생성", "이미지 생성", "영상 생성", "페르소나", "자동화", "기타"]

# 기본 데이터 (이전 미션 프롬프트 3개 이상)
prompts = [
    {
        "title": "블로그 글 작성 도우미",
        "content": "당신은 10년 경력의 전문 블로거입니다. 주어진 주제에 대해 SEO에 최적화된 블로그 글을 작성해주세요. 서론, 본론, 결론 구조를 갖추고, 독자의 관심을 끄는 제목을 3개 제안해주세요.",
        "category": "텍스트 생성",
        "favorite": True
    },
    {
        "title": "제품 썸네일 생성",
        "content": "다음 제품의 매력적인 썸네일 이미지를 생성해주세요. 배경은 흰색, 제품이 중앙에 위치하고, 밝고 선명한 색감으로 표현해주세요.",
        "category": "이미지 생성",
        "favorite": False
    },
    {
        "title": "IT 컨설턴트 페르소나",
        "content": "당신은 15년 경력의 IT 컨설턴트입니다. 기업의 디지털 전환을 돕는 전문가로서, 기술적인 내용을 비전문가도 이해할 수 있게 쉽게 설명해주세요.",
        "category": "페르소나",
        "favorite": False
    },
    {
        "title": "뉴스 요약 프롬프트",
        "content": "다음 뉴스 기사를 3줄로 요약해주세요. 핵심 내용, 영향, 전망 순서로 작성하고, 중립적인 시각을 유지해주세요.",
        "category": "자동화",
        "favorite": False
    },
    {
        "title": "광고 스크립트 작성",
        "content": "30초 분량의 SNS 광고 영상 스크립트를 작성해주세요. 첫 3초 안에 시선을 끌고, 제품의 핵심 가치를 전달하며, 명확한 CTA로 마무리해주세요.",
        "category": "영상 생성",
        "favorite": False
    }
]


# =============================================
# 메뉴 출력 함수
# =============================================
def show_menu():
    print("\n=== 나만의 프롬프트 관리 ===")
    print("1. 프롬프트 추가")
    print("2. 프롬프트 목록")
    print("3. 카테고리별 조회")
    print("4. 프롬프트 검색")
    print("5. 프롬프트 상세 보기")
    print("6. 즐겨찾기 관리")
    print("7. 즐겨찾기 목록")
    print("0. 종료")


# =============================================
# 1. 프롬프트 추가 함수
# =============================================
def add_prompt():
    print("\n=== 프롬프트 추가 ===")

    # 제목 입력 (빈 값이면 다시 요청)
    while True:
        title = input("제목: ").strip()
        if title:
            break
        print("⚠️  제목을 입력해주세요.")

    # 내용 입력 (빈 값이면 다시 요청)
    while True:
        content = input("내용: ").strip()
        if content:
            break
        print("⚠️  내용을 입력해주세요.")

    # 카테고리 선택
    print("\n카테고리 선택:")
    for i, cat in enumerate(CATEGORIES, 1):
        print(f"{i}) {cat}")

    while True:
        choice = input("선택: ").strip()
        if choice.isdigit() and 1 <= int(choice) <= len(CATEGORIES):
            category = CATEGORIES[int(choice) - 1]
            break
        print("⚠️  올바른 번호를 입력해주세요.")

    # 새 프롬프트 추가
    new_prompt = {
        "title": title,
        "content": content,
        "category": category,
        "favorite": False      # 즐겨찾기 기본값은 False
    }
    prompts.append(new_prompt)
    print("\n프롬프트가 추가되었습니다!")


# =============================================
# 2. 프롬프트 목록 함수
# =============================================
def show_list():
    print("\n=== 프롬프트 목록 ===")

    if not prompts:
        print("등록된 프롬프트가 없습니다.")
        return

    for i, p in enumerate(prompts, 1):
        star = "⭐" if p["favorite"] else ""
        print(f"{i}. [{p['category']}] {p['title']} {star}")

    print(f"\n총 {len(prompts)}개의 프롬프트")


# =============================================
# 3. 카테고리별 조회 함수
# =============================================
def show_by_category():
    print("\n=== 카테고리별 조회 ===")

    for i, cat in enumerate(CATEGORIES, 1):
        print(f"{i}) {cat}")

    choice = input("선택: ").strip()

    # 입력값 검증
    if not choice.isdigit() or not (1 <= int(choice) <= len(CATEGORIES)):
        print("⚠️  올바른 번호를 입력해주세요.")
        return

    selected = CATEGORIES[int(choice) - 1]

    # 해당 카테고리만 필터링
    filtered = [p for p in prompts if p["category"] == selected]

    if not filtered:
        print(f"\n'{selected}' 카테고리에 프롬프트가 없습니다.")
        return

    print(f"\n[{selected}] 카테고리 프롬프트:")
    for i, p in enumerate(filtered, 1):
        star = "⭐" if p["favorite"] else ""
        print(f"{i}. {p['title']} {star}")

    print(f"\n총 {len(filtered)}개의 프롬프트")


# =============================================
# 4. 프롬프트 검색 함수
# =============================================
def search_prompt():
    print("\n=== 프롬프트 검색 ===")
    keyword = input("검색어: ").strip()

    if not keyword:
        print("⚠️  검색어를 입력해주세요.")
        return

    # 제목 또는 내용에 키워드 포함 여부 검색
    results = [p for p in prompts
               if keyword in p["title"] or keyword in p["content"]]

    if not results:
        print(f"\n'{keyword}'에 대한 검색 결과가 없습니다.")
        return

    print("\n검색 결과:")
    for i, p in enumerate(results, 1):
        star = "⭐" if p["favorite"] else ""
        print(f"{i}. [{p['category']}] {p['title']} {star}")

    print(f"\n{len(results)}개의 프롬프트를 찾았습니다.")


# =============================================
# 5. 프롬프트 상세 보기 함수
# =============================================
def show_detail():
    print("\n=== 프롬프트 상세 보기 ===")

    if not prompts:
        print("등록된 프롬프트가 없습니다.")
        return

    try:
        num = int(input("번호 입력: "))

        if 1 <= num <= len(prompts):
            p = prompts[num - 1]
            star = "⭐" if p["favorite"] else "없음"

            print("\n" + "─" * 30)
            print(f"제목: {p['title']}")
            print(f"카테고리: {p['category']}")
            print(f"즐겨찾기: {star}")
            print("─" * 30)
            print("내용:")
            print(p["content"])
            print("─" * 30)
        else:
            print("⚠️  올바른 번호를 입력해주세요.")

    except ValueError:
        # 숫자가 아닌 값을 입력했을 때
        print("⚠️  숫자를 입력해주세요.")


# =============================================
# 6. 즐겨찾기 추가/해제 함수
# =============================================
def manage_favorites():
    print("\n=== 즐겨찾기 관리 ===")

    if not prompts:
        print("등록된 프롬프트가 없습니다.")
        return

    # 현재 목록 보여주기
    for i, p in enumerate(prompts, 1):
        star = "⭐" if p["favorite"] else ""
        print(f"{i}. [{p['category']}] {p['title']} {star}")

    try:
        num = int(input("\n프롬프트 번호 입력: "))

        if 1 <= num <= len(prompts):
            p = prompts[num - 1]

            # 즐겨찾기 토글 (True면 False로, False면 True로)
            p["favorite"] = not p["favorite"]

            if p["favorite"]:
                print(f"'{p['title']}' 프롬프트를 즐겨찾기에 추가했습니다!")
            else:
                print(f"'{p['title']}' 프롬프트를 즐겨찾기에서 해제했습니다.")
        else:
            print("⚠️  올바른 번호를 입력해주세요.")

    except ValueError:
        print("⚠️  숫자를 입력해주세요.")


# =============================================
# 7. 즐겨찾기 목록 함수
# =============================================
def show_favorites():
    print("\n=== 즐겨찾기 목록 ===")

    # 즐겨찾기된 것만 필터링
    favorites = [p for p in prompts if p["favorite"]]

    if not favorites:
        print("즐겨찾기된 프롬프트가 없습니다.")
        return

    for i, p in enumerate(favorites, 1):
        print(f"{i}. [{p['category']}] {p['title']} ⭐")

    print(f"\n총 {len(favorites)}개의 즐겨찾기")


# =============================================
# 메인 실행 함수 (프로그램 시작점)
# =============================================
def main():
    print("프롬프트 관리 프로그램을 시작합니다!")

    while True:          # 종료 선택 전까지 계속 반복
        show_menu()
        choice = input("선택: ").strip()

        if choice == "1":
            add_prompt()
        elif choice == "2":
            show_list()
        elif choice == "3":
            show_by_category()
        elif choice == "4":
            search_prompt()
        elif choice == "5":
            show_detail()
        elif choice == "6":
            manage_favorites()
        elif choice == "7":
            show_favorites()
        elif choice == "0":
            print("\n프로그램을 종료합니다. 안녕히 가세요! 👋")
            break        # while 루프 종료
        else:
            print("\n⚠️  올바른 번호를 입력해주세요.")


# 프로그램 시작
if __name__ == "__main__":
    main()
🌿 Git 브랜치 작업 순서
미션 조건: 브랜치 생성 → 작업 → 병합 기록이 필요해요!

터미널에서 아래 순서대로 입력하세요:

bash
📋 복사
# ── 1단계: 기본 파일들 먼저 main에 커밋 ──────────────────

git add .
git commit -m "init: 프로젝트 초기 설정"

# ── 2단계: 기능 브랜치 생성 ──────────────────────────────

git checkout -b feature/prompt-list
# 👆 feature/prompt-list 라는 새 브랜치로 이동

# ── 3단계: 브랜치에서 작업 후 커밋 ──────────────────────

git add prompt_manager.py
git commit -m "feat: 프롬프트 목록 보기 기능 추가"

# ── 4단계: main으로 돌아와서 병합 ────────────────────────

git checkout main
git merge feature/prompt-list
# 👆 브랜치 작업 내용이 main에 합쳐짐!
📝 10개 커밋 계획표
기능 하나 완성할 때마다 커밋하면 자연스럽게 10개 달성!

순서	커밋 메시지	작업 내용
1	init: 프로젝트 초기 설정	.gitignore, README 생성
2	`feat: 기	

