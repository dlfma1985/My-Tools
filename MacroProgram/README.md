# 매크로 프로그램

마우스/키보드 매크로 녹화·실행 프로그램입니다.

## UI 구성

- 외부 UI 라이브러리 없이 **기본 Tkinter/ttk**만 사용합니다.
- 버튼은 볼드 폰트 스타일로 통일해 가독성을 높였습니다.
- 사용 흐름: **시나리오 추가/선택 -> 녹화 시작/중지(F9 또는 버튼) -> 메뉴에서 시나리오 저장**

## 실행 방법

### 1) 더블클릭으로 실행 (가장 간단)
- **`run.bat`** 파일을 더블클릭하면 프로그램이 실행됩니다.
- 오류가 나면 창이 닫히지 않고 메시지가 표시됩니다.

### 2) 터미널에서 실행
1. 이 폴더(`매크로`)를 연 터미널(명령 프롬프트 또는 PowerShell)에서:
   ```bash
   pip install -r requirements.txt
   python main.py
   ```
2. 최초 한 번만 `pip install -r requirements.txt` 하면 됩니다.

### 3) Cursor / VS Code에서 실행
- `main.py` 파일을 연 뒤:
  - **Run Python File** 버튼(▶)을 누르거나
  - 편집기에서 우클릭 → **Run Python File in Terminal** 을 선택하면 됩니다.

---

**요약:** 평소에는 **`run.bat` 더블클릭**만 하면 됩니다.
