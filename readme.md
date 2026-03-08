# 🐸 kingPEPE

**Efficient Integration of JavaScript Assets and Python-based Loading**

📖 **Note:** This repository is structured for seamless interaction between the core JavaScript manifests and Python execution environments. For detailed logic on asset management, please refer to the `main/manifest.json`.

---

## 📋 Requirements

| **Requirement** | **Specification**                            |
| --------------- | -------------------------------------------- |
| **Python**      | 3.10.x or higher (see `requirements.txt`)    |
| **Runtime**     | Node.js (for `.js` execution, if applicable) |
| **OS**          | Linux / macOS (tested), Windows (unverified) |

> [!IMPORTANT]
> 
> `requirements.txt`에 명시된 의존성 패키지가 설치되지 않을 경우, `load.py` 실행 시 모듈 참조 에러가 발생할 수 있습니다.

---

## ⚙️ Installation

**1. Clone or Download the Folder** 직접 폴더를 업로드하셨으므로, 해당 경로로 이동합니다.

Bash

```
cd ~/code/anyhting/kingPEPE
```

**2. Set up the Environment** 가상환경을 생성하고 필요한 패키지를 설치합니다.

Bash

```
# 가상환경 생성 및 활성화
python3 -m venv venv
source venv/bin/activate

# 의존성 설치
pip install -r requirements.txt
```

---

## 🚀 Usage

`load.py`를 통해 메인 로직을 실행할 수 있습니다.

Bash

```
python3 load.py
```

**Project Structure:**

- `main/`: 프로젝트의 핵심 로직인 `awesome.js`와 메타데이터인 `manifest.json`이 포함되어 있습니다.
    
- `load.py`: 전체 시스템을 초기화하고 실행하는 엔트리 포인트입니다.
    
