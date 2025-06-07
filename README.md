# Public_Data_Analysis

## 📦 Repository 다운로드 및 실행 방법

이 저장소는 `.csv`와 같은 대용량 데이터를 **Git LFS (Large File Storage)** 를 통해 관리합니다.  
로컬 환경에서 모든 데이터를 정상적으로 열기 위해 아래 절차를 따라주세요.

---

### ✅ 1. Git LFS 설치

Git LFS는 Git에서 대용량 파일을 효율적으로 관리하기 위한 확장 도구입니다.

- **macOS (Homebrew 사용)**

  ```bash
  brew install git-lfs
  ```

- **Ubuntu (APT 사용)**

  ```bash
  sudo apt install git-lfs
  ```

- **Windows**

  [공식 설치 페이지](https://git-lfs.github.com/)에서 설치 파일을 내려받아 설치하세요.

설치 후, 아래 명령어로 Git LFS를 초기화합니다:

```bash
git lfs install
```

---

### ✅ 2. 저장소 클론

다음 명령어로 이 저장소를 클론합니다:

```bash
git clone https://github.com/ClearSky001/Public_Data_Analysis.git
cd Public_Data_Analysis
```

---

### ✅ 3. LFS 파일 다운로드

클론한 저장소 내의 `.csv` 데이터 파일을 다운로드하려면 아래 명령어를 입력합니다:

```bash
git lfs pull
```

> ⚠️ 위 명령어를 실행하지 않으면 `.csv` 파일이 텍스트 포인터로만 보여 열리지 않을 수 있습니다.

---

### ✅ 4. 분석 시작

이제 분석을 시작하시면 됩니다.
  

  
