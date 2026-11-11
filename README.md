# 701 주문 알림 배포

이 공개 저장소에는 앱 설치 파일과 해당 버전의 변경 내용·SHA-256 정보만 게시합니다. 앱 소스와 개발 기록은 포함하지 않습니다.

## 현재 권장 버전

- Android [v1.0.15 APK](https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/v1.0.15): 설정창과 숫자 입력칸을 줄이고 저장과 취소를 하단에 고정했습니다.   단위 테스트 40개와 Android 14 에뮬레이터에서 이전 버전 설정 보존, 좁은 화면과 큰 글자, 키보드 입력, 저장 및 내장 설명서를 확인했습니다. Android 6.0 이상용이며 기존 인증서로 서명했습니다. Windows 환경의 기기 제약으로 실제 휴대폰 화면과 설치는 미검증입니다.
- iPhone [iOS v1.0.10](https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/ios-v1.0.10): 설정이 작은 시트로 열립니다. 손잡이를 위로 끌면 펼칠 수 있습니다.   iOS 26 이상용 미서명 IPA입니다. 개인 서명이 필요합니다. 시뮬레이터 빌드, 화면과 테스트, 내장 설명서 및 IPA 구조를 확인했습니다. Windows 작업 환경에 실제 iPhone이 없어 개인 서명 후 설치와 실기기 설정 조작은 미검증입니다 서명되지 않은 IPA이며 설치하려면 별도로 서명해야 합니다.
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
    "version": "1.0.15",
    "tag": "v1.0.15",
    "notes": "설정창과 숫자 입력칸을 줄이고 저장과 취소를 하단에 고정했습니다.\n\n\n단위 테스트 40개와 Android 14 에뮬레이터에서 이전 버전 설정 보존, 좁은 화면과 큰 글자, 키보드 입력, 저장 및 내장 설명서를 확인했습니다. Android 6.0 이상용이며 기존 인증서로 서명했습니다. Windows 환경의 기기 제약으로 실제 휴대폰 화면과 설치는 미검증입니다.",
    "page": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/v1.0.15",
    "asset": {
      "name": "hanwha-701-order-alert-v1.0.15.apk",
      "url": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/download/v1.0.15/hanwha-701-order-alert-v1.0.15.apk",
      "sha256": "e815e632d8dccdb0d3d82d7499a1d1efcca51bf8cf58cf046ae349ed8ccf9941"
    }
  },
  "ios": {
    "version": "1.0.10",
    "tag": "ios-v1.0.10",
    "notes": "설정이 작은 시트로 열립니다. 손잡이를 위로 끌면 펼칠 수 있습니다.\n\n\niOS 26 이상용 미서명 IPA입니다. 개인 서명이 필요합니다. 시뮬레이터 빌드, 화면과 테스트, 내장 설명서 및 IPA 구조를 확인했습니다. Windows 작업 환경에 실제 iPhone이 없어 개인 서명 후 설치와 실기기 설정 조작은 미검증입니다.",
    "page": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/tag/ios-v1.0.10",
    "asset": {
      "name": "hanwha-701-order-alert-ios-UNSIGNED.ipa",
      "url": "https://github.com/HeesungYang1/hanwha-701-order-alert-releases/releases/download/ios-v1.0.10/hanwha-701-order-alert-ios-UNSIGNED.ipa",
      "sha256": "7569f8299866a1db8928041f66a14c34da0d31abcdea4f893ea5a12f852510d8"
    }
  }
}
```
<!-- CAFE701_RELEASE_MANIFEST_END -->
