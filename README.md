# 701 주문 알림 배포

이 공개 저장소에는 앱 설치 파일과 해당 버전의 변경 내용·SHA-256 정보만 게시합니다. 앱 소스와 개발 기록은 포함하지 않습니다.

## 현재 권장 버전

- Android [v1.0.14 APK](https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/v1.0.14): - 마지막 확인 번호와 시각을 유지하고 새 화면 판독 상태를 호출번호판에 따로 표시합니다. - 홈에서 주문번호를 먼저 볼 수 있게 배치하고 설정을 화면 확인, 알림, 업데이트, 도움말로 정리했습니다. - Android 6.0 이상용 APK입니다. 기존 APK와 같은 인증서로 서명했습니다. 단위 테스트 40개, Android 14 에뮬레이터에서 v1.0.13 업데이트와 확인 간격 보존, 실제 번호판 새로고침 및 연결 실패 시 마
- iPhone [iOS v1.0.9](https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/ios-v1.0.9): - 마지막 확인 번호와 시각을 유지하고 새 화면 판독 상태를 호출번호판에 따로 표시합니다. - 홈에서 주문번호를 먼저 볼 수 있게 배치하고 설정을 화면 확인, 알림, 업데이트, 도움말로 정리했습니다. - iOS 26 이상용 미서명 IPA입니다. 개인 서명이 필요합니다. Xcode 빌드, 시뮬레이터 테스트와 화면, 내장 한 서명되지 않은 IPA이며 설치하려면 별도로 서명해야 합니다.
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
    "version": "1.0.14",
    "tag": "v1.0.14",
    "notes": "- 마지막 확인 번호와 시각을 유지하고 새 화면 판독 상태를 호출번호판에 따로 표시합니다.\n- 홈에서 주문번호를 먼저 볼 수 있게 배치하고 설정을 화면 확인, 알림, 업데이트, 도움말로 정리했습니다.\n- Android 6.0 이상용 APK입니다. 기존 APK와 같은 인증서로 서명했습니다. 단위 테스트 40개, Android 14 에뮬레이터에서 v1.0.13 업데이트와 확인 간격 보존, 실제 번호판 새로고침 및 연결 실패 시 마지막 번호 유지, 내장 한국어 설명서를 확인했습니다. Windows 작업 환경에 실제 기기가 없어 기기별 잠금 화면 알림·소리·진동은 미검증입니다.",
    "page": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/v1.0.14",
    "asset": {
      "name": "hanwha-701-order-alert-v1.0.14.apk",
      "url": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/download/v1.0.14/hanwha-701-order-alert-v1.0.14.apk",
      "sha256": "8d32a04ab9dc13d34098e21c6fc08340d378988750b51938e14991c6b63bf661"
    }
  },
  "ios": {
    "version": "1.0.9",
    "tag": "ios-v1.0.9",
    "notes": "- 마지막 확인 번호와 시각을 유지하고 새 화면 판독 상태를 호출번호판에 따로 표시합니다.\n- 홈에서 주문번호를 먼저 볼 수 있게 배치하고 설정을 화면 확인, 알림, 업데이트, 도움말로 정리했습니다.\n- iOS 26 이상용 미서명 IPA입니다. 개인 서명이 필요합니다. Xcode 빌드, 시뮬레이터 테스트와 화면, 내장 한국어 설명서 및 IPA 구조를 확인했습니다. Windows 작업 환경에 실제 iPhone이 없어 개인 서명 후 실기기 설치와 잠금 화면 알림·소리·진동은 미검증입니다.",
    "page": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/ios-v1.0.9",
    "asset": {
      "name": "hanwha-701-order-alert-ios-UNSIGNED.ipa",
      "url": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/download/ios-v1.0.9/hanwha-701-order-alert-ios-UNSIGNED.ipa",
      "sha256": "734006c5b4cd2ba8db7a2c1998a321ea4e73fa4243f7f846f27d9e7ca21a7454"
    }
  }
}
```
<!-- CAFE701_RELEASE_MANIFEST_END -->
