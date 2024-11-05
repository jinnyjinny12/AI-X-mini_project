
![image](https://github.com/user-attachments/assets/6f8df8b4-b9fc-4104-a3a3-2a221314a882)

# 📑 Briefify - AI 기반 문서 번역 및 요약 서비스

![Python Badge](https://img.shields.io/badge/Python-v3.11.4-%233776AB?style=flat&logo=python&logoColor=white)
![PyTorch Badge](https://img.shields.io/badge/PyTorch-v2.1.0-%23EE4C2C?style=flat&logo=pytorch&logoColor=white)
![React Badge](https://img.shields.io/badge/React-v18.2.0-%2361DAFB?style=flat&logo=react&logoColor=white)


**Briefify**는 PDF나 이미지 형식의 개발 문서 및 논문을 손쉽게 이해할 수 있도록 돕는 AI 기반 번역 및 요약 솔루션입니다. 복잡한 기술 문서도 손쉽게 접근할 수 있도록 다음과 같은 기능을 제공합니다:

- **이미지 및 PDF 문서 인식**: PDF 파일이나 이미지 형식으로 제공되는 문서도 텍스트로 정확하게 변환하여 번역할 수 있습니다.
- **AI 번역**: 문서 내용을 다양한 언어로 번역해, 언어 장벽 없이 정보에 접근할 수 있습니다.
- **요약 기능**: 복잡한 기술 문서나 긴 논문도 핵심만 빠르게 파악할 수 있도록 요약해 드립니다.
- **음성 읽기**: 요약된 내용을 음성으로 들을 수 있어, 언제 어디서나 손쉽게 핵심 정보를 습득할 수 있습니다.

<br>
<br>

## 📑 Task

### 💬 Language Translation
- **[NLLB-200 Distilled Model (600M) by Facebook](https://huggingface.co/facebook/nllb-200-distilled-600M)**  
  고성능 다국어 번역 모델로, 다양한 언어 간 번역을 지원합니다.

### 📚 Text Summarization
- **[T5-Base Korean Summarization by eenzeenee](https://huggingface.co/eenzeenee/t5-base-korean-summarization)**  
  한국어 텍스트 요약에 최적화된 T5-Base 모델로, 긴 텍스트를 간결하게 요약합니다.

### 📝 참고 자료
- **[Joyhong's Blog - Korean NLP Tips](https://joyhong.tistory.com/79)**  
  한국어 자연어 처리(NLP)에 대한 유용한 정보와 팁을 제공합니다.

### 🔊 Text-to-Speech
- **[gTTS (Google Text-to-Speech)](https://pypi.org/project/gTTS)**  
  텍스트를 오디오로 변환하는 Python 라이브러리로, 음성 파일 생성에 사용됩니다.
<br>

## 📑 Branch
<br>

이 프로젝트는 효율적인 협업과 안정적인 배포를 위해 `release`, `dev`, `feature` 브랜치를 사용하는 Git 브랜치 전략을 채택했습니다.
![깃허브 전략](https://github.com/user-attachments/assets/2625e974-353b-4db6-bb78-7fe33258ecfc)


### 🔹 `feature` Branch
- **목적**: 새로운 기능이나 버그 수정을 개발하는 브랜치입니다.
- **사용 방법**: 각 기능 또는 수정 사항마다 별도의 `feature` 브랜치를 생성하며, 브랜치 이름은 `feature/기능명` 형식을 따릅니다.

### 🔹 `dev` Branch
- **목적**: 통합 개발을 위한 브랜치로, 모든 `feature` 브랜치의 변경 사항이 이곳에서 모여 테스트됩니다.
- **사용 방법**: 기능별 개발이 완료되면 `dev` 브랜치에서 전체적으로 테스트하고 오류를 확인합니다.

### 🔹 `release` Branch
- **목적**: 배포 준비가 완료된 안정적인 코드를 관리하는 브랜치입니다.
- **사용 방법**: `dev` 브랜치에서 충분한 테스트가 완료된 후 `release` 브랜치로 이동하여 실제 배포를 진행합니다.

이 브랜치 전략을 통해 기능 개발부터 배포까지 안정적으로 관리하며, 코드의 품질을 유지하고 있습니다.
<br>


## 📑 STACK
![image](https://github.com/AI-X-min-projext-ITOWE/.github/blob/main/image.png)
<br>

## 📑 Architecture

<br>

![img](https://github.com/user-attachments/assets/1a7297c5-56ad-4657-9183-1cb626bab6fb)



## 📑 Contributor

+ hwangjeonghan | 황정한 | [깃허브](https://github.com/hwangjeonghan)

+ Shineunhan | 신은한 | [깃허브](https://github.com/Shineunhan)

+ parkkkkjuneHyeon | 박준현 | [깃허브](https://github.com/parkkkkjuneHyeon)

+ jinnyjinny12 | 서은진 | [깃허브](https://github.com/jinnyjinny12)

+ Jin-tonix | 목진희 | [깃허브](https://github.com/Jin-tonix)

+ oct1H | 최상훈 | [깃허브](https://github.com/oct1H)

## 🌟 Browser Support

| <img src="https://user-images.githubusercontent.com/1215767/34348387-a2e64588-ea4d-11e7-8267-a43365103afe.png" alt="Chrome" width="16px" height="16px" /> Chrome | <img src="https://user-images.githubusercontent.com/1215767/34348590-250b3ca2-ea4f-11e7-9efb-da953359321f.png" alt="IE" width="16px" height="16px" /> Internet Explorer | <img src="https://user-images.githubusercontent.com/1215767/34348380-93e77ae8-ea4d-11e7-8696-9a989ddbbbf5.png" alt="Edge" width="16px" height="16px" /> Edge | <img src="https://user-images.githubusercontent.com/1215767/34348394-a981f892-ea4d-11e7-9156-d128d58386b9.png" alt="Safari" width="16px" height="16px" /> Safari | <img src="https://user-images.githubusercontent.com/1215767/34348383-9e7ed492-ea4d-11e7-910c-03b39d52f496.png" alt="Firefox" width="16px" height="16px" /> Firefox |
| :---------: | :---------: | :---------: | :---------: | :---------: |
| Yes | 11+ | Yes | Yes | Yes |
