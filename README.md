# 701 주문 알림 배포

이 공개 저장소에는 앱 설치 파일과 해당 버전의 변경 내용·SHA-256 정보만 게시합니다. 앱 소스와 개발 기록은 포함하지 않습니다.

## 현재 권장 버전

- Android [v1.0.13 APK](https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/v1.0.13): 상단 번호 오인식 방지와 사진·판독 결과 일치를 추가했습니다. 불확실한 호출번호·남은 수·ETA는 숨깁니다.
- iPhone [iOS v1.0.8](https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/ios-v1.0.8): 상단 번호 오인식 방지와 사진·판독 결과 일치를 추가했습니다. 불확실한 호출번호·남은 수·ETA는 숨깁니다. IPA: 서명되지 않음(UNSIGNED). 서명되지 않은 IPA이며 설치하려면 별도로 서명해야 합니다.
- 각 릴리스의 `SHA256SUMS`에서 내려받은 설치 파일의 SHA-256을 확인하세요.
- Samsung의 설치 보안 알림 발생 원인은 확인되지 않았습니다. 이 버전이 해당 경고를 해결한다고 보장할 수 없습니다. 경고를 우회하지 말고 Galaxy Store에서 보안 정책 업데이트를 확인한 뒤, 계속 나타나면 Samsung 공식 앱 검토를 요청하세요.

## 설치와 업데이트

Android 앱 안에서 새 버전이 표시되면 업데이트를 누르세요. 앱이 APK의 SHA-256, 앱 ID, 버전, 호환성 및 기존 서명을 확인한 뒤 Android 시스템 설치 화면을 엽니다. Android가 요청하면 이 앱의 ‘알 수 없는 앱 설치’를 허용하고 시스템 설치 확인에서 직접 승인해야 합니다.

iPhone용 IPA는 서명되지 않았으므로 파일을 눌러 바로 설치할 수 없습니다. Windows의 Sideloadly 등 도구와 본인의 Apple 계정으로 직접 서명·설치해야 합니다. 도구가 앱 ID를 바꾸면 화면 밖 감시가 제한될 수 있으므로 설치 후 앱의 설치 진단을 확인하세요.

<!-- CAFE701_RELEASE_MANIFEST_START -->
```json
{
  "schema": 1,
  "android": {
    "version": "1.0.13",
    "tag": "v1.0.13",
    "notes": "상단 번호 오인식 방지와 사진·판독 결과 일치를 추가했습니다. 불확실한 호출번호·남은 수·ETA는 숨깁니다.",
    "page": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/v1.0.13",
    "asset": {
      "name": "hanwha-701-order-alert-v1.0.13.apk",
      "url": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/download/v1.0.13/hanwha-701-order-alert-v1.0.13.apk",
      "sha256": "515f8dfb64c552b6de2bb8a2dfcc35768133b34142e3807f1059fc480d85595e"
    }
  },
  "ios": {
    "version": "1.0.8",
    "tag": "ios-v1.0.8",
    "notes": "상단 번호 오인식 방지와 사진·판독 결과 일치를 추가했습니다. 불확실한 호출번호·남은 수·ETA는 숨깁니다. IPA: 서명되지 않음(UNSIGNED).",
    "page": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/ios-v1.0.8",
    "asset": {
      "name": "hanwha-701-order-alert-ios-UNSIGNED.ipa",
      "url": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/download/ios-v1.0.8/hanwha-701-order-alert-ios-UNSIGNED.ipa",
      "sha256": "e46bf84921f235298c46d43ff52613eba1e8af96dd2225b776ab76423af32ef1"
    }
  }
}
```
<!-- CAFE701_RELEASE_MANIFEST_END -->
