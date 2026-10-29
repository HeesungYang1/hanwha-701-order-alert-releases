# 701 주문 알림 배포

이 공개 저장소에는 앱 설치 파일과 해당 버전의 변경 내용·SHA-256 정보만 게시합니다. 앱 소스와 개발 기록은 포함하지 않습니다.

## 릴리스 파일 이름

- Android: `hanwha-701-order-alert-vX.Y.Z.apk`와 `SHA256SUMS`
- iPhone: `hanwha-701-order-alert-ios-UNSIGNED.ipa`와 `SHA256SUMS`
- Android 릴리스 태그는 `vX.Y.Z`, iPhone 릴리스 태그는 `ios-vX.Y.Z`입니다.

## 설치 안내

Android 앱 안에서 새 버전이 표시되면 업데이트를 누르세요. 앱이 다운로드 파일의 SHA-256, 앱 ID, 버전, 기기 호환성, 기존 설치본과의 서명을 확인한 다음 Android 설치 화면을 엽니다. Android가 요청하면 이 앱의 ‘알 수 없는 앱 설치’를 허용하고, 시스템 설치 확인에서 직접 승인해야 합니다.

iPhone용 IPA는 서명되지 않은 파일이므로 탭해서 바로 설치할 수 없습니다. Windows에서는 Sideloadly 같은 서명 도구와 본인의 Apple 계정으로 직접 서명·설치해야 하며, App Store 또는 TestFlight 배포가 아닙니다. 서명 도구가 앱 ID를 바꾸면 iOS 화면 밖 감시가 제한될 수 있으니 설치 후 앱의 설치 진단을 확인하세요.