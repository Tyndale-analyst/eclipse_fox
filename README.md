# 이클립스 AR 데모 웹앱

이 프로젝트는 웹 기반의 AR(증강현실) 데모 애플리케이션입니다. 카메라를 사용하여 이클립스 이미지를 인식하고, 그 위에 3D 모델을 표시합니다.

## 기능

- 웹 카메라 접근 및 화면 중앙 표시
- 이클립스(eclipse.jpg) 이미지 인식
- 인식된 이미지 위에 3D 모델 표시 (AR)
- 화면 캡처 기능

## 사용 방법

1. 웹 브라우저에서 index.html 파일을 엽니다.
2. 카메라 접근 권한을 허용합니다.
3. eclipse.jpg 이미지를 카메라에 비춥니다.
4. 이미지가 인식되면 그 위에 3D 모델이 표시됩니다.
5. 화면 하단의 '사진 찍기' 버튼을 눌러 현재 화면을 캡처할 수 있습니다.

## 필요 파일

- `index.html`: 메인 HTML 파일
- `eclipse.jpg`: 마커 이미지
- `pattern-marker.patt`: AR.js용 패턴 마커 파일
- `models/Shaded Obj/base.obj`: 3D 모델 파일

## 기술 스택

- HTML5
- JavaScript
- A-Frame (WebVR 프레임워크)
- AR.js (웹 기반 증강현실 라이브러리)

## 주의사항

- 최신 버전의 브라우저에서 실행해야 합니다 (Chrome, Firefox, Safari 권장)
- HTTPS 환경이나 로컬 환경에서 실행하는 것이 좋습니다 (카메라 접근 권한 관련)
- 밝은 조명 아래에서 마커를 사용하면 인식률이 더 높아집니다.

## 개발자 메모

패턴 마커를 직접 생성하려면 다음 사이트를 이용할 수 있습니다:
- [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) 