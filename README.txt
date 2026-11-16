한결바이오팜 공식 홈페이지 — 국문/영문 통합 배포 패키지
Hangyeol Biofarm — Bilingual Website Package (KOR / ENG)

폴더 구조 / Structure
  index.html            국문 메인 (Korean)   — 상단 속보 띠와 헤더 우측의 KOR | ENG 스위처
  en/index.html         영문 메인 (English)  — 이미지·폰트는 ../assets 공유
  assets/images/        사진 2종 (최적화 이미지)
  assets/fonts/         Inter 웹폰트 (영문, 로컬 내장)
  README.txt

배포 방법 / How to deploy
  1. 이 폴더의 내용 전체를 웹 호스팅의 루트(도메인 루트)에 업로드합니다.
     Upload the contents of this folder to your web root.
  2. 그러면 두 주소가 자동으로 상호 연동됩니다.
     The two URLs are linked automatically:
        https://도메인/      -> 국문 (index.html)
        https://도메인/en/   -> 영문 (en/index.html)
  3. 별도 서버 설정 없이 동작합니다. (정적 호스팅 / 카페24 / 가비아 등 모두 가능)
     No server configuration is required; plain static hosting is enough.

문의 폼 / Inquiry form
  · 국문·영문 B2B 문의 폼은 FormSubmit(https://formsubmit.co)을 통해 info@hgbiofarm.co.kr 로 접수됩니다.
    Both B2B inquiry forms deliver email to info@hgbiofarm.co.kr through FormSubmit.
  · 사이트를 실제 도메인에 올린 뒤 첫 번째 테스트 문의를 보내면, FormSubmit 이 info@hgbiofarm.co.kr 로
    'Activate Form' 확인 메일을 한 번 보냅니다. 그 메일의 확인 링크를 한 번만 누르면 이후 모든 문의가
    정상적으로 전달됩니다. (확인 전에는 메일이 전달되지 않습니다.)
    After the site is live, submit one test inquiry: FormSubmit sends a one-time activation email to
    info@hgbiofarm.co.kr. Click the link in that email once and every later inquiry is delivered.
    Nothing is delivered until that link is clicked.
  · 자바스크립트가 꺼져 있어도 일반 POST 전송으로 접수됩니다.
    Works as a normal POST submission even with JavaScript disabled.

참고 / Notes
  · 모든 이미지와 폰트가 로컬에 포함되어 오프라인에서도 깨지지 않습니다.
    All images and fonts are local, so nothing breaks offline.
  · 문의 / Contact: info@hgbiofarm.co.kr  |  +82 33 818 1108
