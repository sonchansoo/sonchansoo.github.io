# 프로젝트 사진 첨부 위치

이 폴더에 **프로젝트 대표 이미지**를 넣으세요.

## 사용 방법

1. 이미지 파일을 이 폴더(`images/projects/`)에 저장합니다.
   - 예: `tello_contents.jpg`, `my-app.png`
2. `_data/projects.yml`에서 해당 프로젝트의 `img` 값을 설정합니다.
   - 로컬 이미지: `/images/projects/파일명.jpg`
   - 외부 URL도 가능: `https://example.com/image.png`

## 권장 사양

- 형식: JPG, PNG, WebP
- 비율: 가로로 넓은 이미지(16:10 비율 권장)
- 크기: 가로 800px 이상 권장 (과하면 로딩이 느려질 수 있음)
