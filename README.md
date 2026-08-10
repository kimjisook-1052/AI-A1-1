# AI-A1-1
코디세이 AI활용학습 A1-1


Python & Git 기초: Git과 함께하는 Python 첫 발자국
문제기술
기술적 설명
⁠⁠⁠⁠⁠⁠⁠

1. 미션 소개
GenAI 기초부터 멀티모달 콘텐츠 제작, 노코드 자동화까지 미션을 수행하면서 어느새 프롬프트가 수십 개씩 쌓였을 것입니다.

텍스트 생성을 위한 정교한 지시문부터 이미지 생성용 키워드, 복잡한 페르소나 설계안까지.

하지만 정작 필요할 때 "그때 그 프롬프트 어디 갔지?" 하며 메모장과 노션, 메신저 창을 뒤적였던 경험 또한 한 번쯤은 있으셨을 겁니다.

매번 복사해서 붙여넣고, 흩어진 기록을 찾느라 정작 중요한 '생성'의 흐름이 끊기고 있다면, 이제는 나만의 프롬프트를 체계적으로 관리할 '집'이 필요한 시점입니다.

이번 미션은 파편화된 프롬프트를 관리하는 것을 넘어, 파이썬(Python)이라는 강력한 언어로 내 머릿속 아이디어를 실제 동작하는 소프트웨어로 구현해내는 데 본질적인 가치가 있습니다.

단순히 책에서 보던 변수, 조건문, 반복문 같은 기초 문법을 외우는 것이 아니라, 이것들이 어떻게 프로그램 내부에서 유기적으로 맞물려 돌아가는지 온몸으로 체감하게 됩니다.

프롬프트를 카테고리별로 분류하고 키워드로 검색하며, 자주 사용하는 항목은 즐겨찾기로 관리하는 기능을 직접 코드로 짜보면서 '데이터를 다루는 논리'를 익힙니다.

동시에 Git으로 코드의 변경 이력을 관리합니다.

기능 하나를 완성할 때마다 커밋하고 브랜치를 나눠 작업해보고 GitHub에 올려서 내 코드를 세상에 공개합니다.

이 미션을 마치고 나면 "아이디어를 코드로 만들고 버전 관리까지 할 수 있는 사람"으로 한 단계 성장해 있을 것입니다.

2. 최종 결과물
다음 4가지 산출물을 포함한 Python 콘솔 프로그램 1개와 GitHub 저장소 1개를 완성한다.

동작하는 프롬프트 관리 프로그램
터미널에서 메뉴 번호를 입력해 기능을 선택하는 콘솔 기반 프로그램
프롬프트 추가, 목록 보기, 카테고리별 조회, 검색, 상세 보기, 즐겨찾기 기능이 동작한다
프로그램 실행 중에 추가한 프롬프트와 즐겨찾기 상태가 유지된다 (종료 시 초기화)
이전 미션에서 작성한 프롬프트가 기본 데이터로 최소 3개 이상 등록되어 있다
GitHub 저장소
프로젝트 코드가 GitHub에 업로드되어 있다
최소 10개 이상의 의미 있는 커밋이 존재한다 (기능 단위 커밋)
최소 1회 이상의 브랜치 생성 및 병합(checkout, merge) 기록이 있다
README.md에 프로그램 설명과 실행 방법이 작성되어 있다
코드 품질
함수를 사용하여 기능별로 코드가 분리되어 있다
제출물
GitHub 저장소 URL
개발 환경 설정 스크린샷 (VSCode, Python 버전, Git 설정)
프로그램 실행 결과 스크린샷 (메뉴, 프롬프트 추가, 목록, 검색 등)
git log --oneline --graph 결과 스크린샷
3. 과제 목표
이 과제를 마친 후, 학습자는 아래를 스스로 설명할 수 있어야 한다.

VSCode에서 Python 파일을 생성하고 실행할 수 있다.
터미널에서 Python/Git 버전을 확인하고 필요한 설정을 점검할 수 있다.
파이썬 기초 문법에 대해 설명할 수 있다.
Git이 무엇이고 왜 필요한지 설명할 수 있다.
init, add, commit, push, pull, checkout, clone, merge가 각각 무엇을 하는지 설명할 수 있다.
브랜치를 생성하고 병합할 수 있다.
GitHub에 코드를 업로드하고 관리할 수 있다.
4. 기능 요구 사항
다음 요구사항을 모두 만족해야 한다.

개발 환경
VSCode에 Python 확장(Extension)을 설치한다.
VSCode에 Korean Language Pack을 설치한다. (선택)
터미널에서 Python 버전을 확인한다. (Python 3.10 이상)
간단한 print("Hello") 코드를 작성하고 실행해본다.
Git 버전을 확인한다.
Git 사용자 정보(이름, 이메일)를 설정한다.
기본 브랜치 이름을 main으로 설정한다.
VSCode에서 GitHub 계정으로 로그인하고 연동이 정상적으로 되었는지 확인한다.
Git 저장소 설정 및 초기화
GitHub에 새 저장소를 생성한다.
프로젝트 폴더를 만들고 로컬에서 init으로 저장소를 시작한다.
원격 저장소를 연결하고 첫 커밋과 푸시를 수행한다. (add, commit, push)
.gitignore 파일을 생성하여 불필요한 파일을 제외한다.
README.md 파일을 생성하고 프로젝트 제목을 작성한다.
공개 샘플 저장소 1개를 clone으로 내려받아 폴더 구조와 로그를 확인한다. (확인 후 삭제 가능)
프로그램 실행 및 메뉴
프로그램 실행 시 메뉴가 출력되어야 한다.
사용자가 번호를 입력하여 기능을 선택한다.
잘못된 번호 입력 시 안내 메시지를 출력하고 다시 메뉴를 보여준다.
"종료"를 선택하면 프로그램이 종료된다.
각 기능 수행 후 메뉴로 돌아온다.
기본 프롬프트 데이터
프로그램 시작 시 이전 미션에서 작성한 프롬프트가 최소 3개 이상 미리 등록되어 있어야 한다.
프롬프트 데이터는 리스트와 딕셔너리를 사용하여 저장한다.
각 프롬프트는 제목, 내용, 카테고리, 즐겨찾기 여부를 포함한다.
카테고리 예시: 텍스트 생성, 이미지 생성, 영상 생성, 페르소나, 자동화, 기타
프롬프트 추가
새로운 프롬프트를 등록할 수 있다.
입력 항목은 제목, 내용, 카테고리이다.
입력값이 비어있으면 다시 입력을 요청한다.
카테고리는 미리 정의된 목록에서 선택하거나 직접 입력한다.
추가된 프롬프트는 리스트에 저장된다. (프로그램 실행 중에만 유지)
즐겨찾기 기본값은 False이다.
프롬프트 목록 (브랜치 활용)
main 브랜치 이외의 추가 브랜치를 생성하고 이 기능을 해당 브랜치에서 작업한다.
저장된 모든 프롬프트를 번호와 함께 출력한다.
각 프롬프트의 제목, 카테고리, 즐겨찾기 여부(⭐)를 표시한다.
프롬프트가 없으면 안내 메시지를 출력한다.
기능 완성 후 커밋하고 main 브랜치로 병합한다. (checkout, merge)
카테고리별 조회
카테고리 목록을 보여주고 선택하면 해당 카테고리의 프롬프트만 출력한다.
해당 카테고리에 프롬프트가 없으면 안내 메시지를 출력한다.
프롬프트 검색
키워드를 입력받아 제목 또는 내용에 포함된 프롬프트를 검색한다.
검색 결과를 목록으로 출력한다.
검색 결과가 없으면 안내 메시지를 출력한다.
프롬프트 상세 보기
프롬프트 번호를 입력하면 해당 프롬프트의 전체 내용을 출력한다.
제목, 카테고리, 즐겨찾기 여부, 내용 전체를 표시한다.
잘못된 번호 입력 시 안내 메시지를 출력한다.
즐겨찾기 관리
* 프롬프트 번호를 입력하여 즐겨찾기를 추가/해제할 수 있다.
* 즐겨찾기된 프롬프트만 모아서 볼 수 있다.
코드 구조
* 모든 코드를 한 함수에 몰아 넣지 않는다.
* 기능별로 함수를 분리한다.
* 예: show_menu(), add_prompt(), show_list(), search_prompt(), show_favorites()
README.md 작성
* 프로그램 이름과 간단한 설명을 작성한다.
* 실행 방법을 작성한다.
* 기능 목록을 작성한다.
* 등록된 프롬프트 카테고리를 설명한다.
5. 보너스 과제 (선택)
보너스 1 – 프롬프트 영속화 및 내보내기
프롬프트 데이터를 JSON 파일로 저장하고 불러오는 기능을 추가한다.
전체 프롬프트를 카테고리별 Markdown 파일로 내보내는 기능을 추가한다.
보너스 2 – 프롬프트 관리(CRUD) 및 사용 기록 기능 구현
프롬프트 수정/삭제 기능을 추가한다.
상세 보기 시 사용 횟수(조회수)를 기록한다.
조회수 기준 정렬(Top 목록) 기능을 제공한다.
개발환경
6. 개발 환경
VSCode 설치 및 설정
Python 확장(Extension)을 설치한다.
Korean Language Pack을 설치한다. (선택)
Python 설치 확인
터미널에서 Python 버전을 확인한다. (Python 3.10 이상)
간단한 print("Hello") 코드를 작성하고 실행해본다.
Git 초기 설정
Git 버전을 확인한다.
Git 사용자 정보(이름, 이메일)를 설정한다.
기본 브랜치 이름을 main으로 설정한다.
VSCode와 GitHub 연결
VSCode에서 GitHub 계정으로 로그인한다.
연동이 정상적으로 되었는지 확인한다.
제약조건
7. 제약 사항
Python
Python 3.10 이상을 사용해야 한다.
구현 범위
필수 요구사항은 외부 라이브러리 없이 기본 문법만 사용해야 한다.
모든 코드를 한 곳에 몰아 넣지 않고 기능별로 함수를 분리해야 한다.
Git / GitHub
최소 10개 이상의 의미 있는 커밋이 있어야 한다. (기능 단위로 나누고 커밋 메시지로 변경 의도를 설명할 수 있어야 한다)
init, add, commit, push, pull, checkout, clone, merge를 각각 1회 이상 사용해야 한다.
브랜치 생성 및 병합은 로컬에서 checkout과 merge로 수행 기록을 남긴다.
이전 미션에서 작성한 프롬프트를 최소 3개 이상 기본 데이터로 등록해야 한다.
Test Case

나는 위 내용으로 미션을 수행하려고해 나는 파이썬을 한번도 안써봐서 뭘 어디서부터 시작해야될지 모르겠어 내가 무엇부터 어떻게 시작해야될지 자세하고 친절하고 쉽게 설명해줘
AI
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

