# soolsool-site

SoolSool 의 **공개 페이지**입니다. GitHub Pages 로 그대로 나갑니다.

- `privacy.html` — 개인정보처리방침. Play Console 이 **내부 테스트부터**
  공개 URL 을 요구합니다.
- `index.html` — 저장소 뿌리로 들어왔을 때 404 를 안 보이려고 둔 한 장.

## 왜 저장소를 따로 두나

앱 저장소에는 가격 근거 · 경쟁 조사 · 로드맵 · 사업자 계정 절차가 들어
있는 프로젝트 문서가 있습니다. GitHub Pages 는 저장소가 **공개**여야
공짜라, 앱 저장소를 공개로 돌리면 그것들이 같이 열립니다. 그래서
**공개해도 되는 것만** 여기 둡니다.

## 방침을 고쳐야 하는 때

방침은 코드가 하는 일을 적은 것입니다. 앱 저장소에서 아래가 바뀌면
여기도 같이 고칩니다.

- 기기에 저장하는 값 — 지금은 `progress.v1` · `autoplay.v1` 둘뿐
  (`app/lib/progress.dart` · `app/lib/audio.dart`)
- 릴리스 매니페스트의 권한 — 지금은 **없음**
  (`android/app/src/main/AndroidManifest.xml`. `INTERNET` 은 debug ·
  profile 에만 있습니다)
- 소리 — 전부 자산 파일. 마이크도 음성 인식도 없습니다
- 결제 — Google Play 인앱 상품 **하나**(전체 해제)

상호는 **Devless Inc.** 이고, Play Console 의 개발자 이름과 **글자까지
같아야** 합니다.
