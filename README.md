# fare-site

총액 리포트 무료 실험 소개 페이지(https://fare.wspace.ai.kr). GitHub Pages로 배포하며 `main`에 올리면 바로 반영된다.

이 저장소의 파일은 빌드 결과라 직접 고치지 않는다. 원본은 비공개 저장소 `fare-report`의 `tools/site/`이고, 그 저장소 안에서 다음으로 다시 만든다.

```bash
service/.venv/bin/python tools/site/build.py ../../fare-site [--form-url URL] [--contact 메일]
```
