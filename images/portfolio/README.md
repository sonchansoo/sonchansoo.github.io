# 포트폴리오 폴더

## 메인 PDF

- **`portfolio.pdf`** — 포트폴리오 페이지(`/portfolio/`)에서 보여주는 기본 파일입니다.
- 파일을 교체할 때도 이름을 **`portfolio.pdf`** 로 두면 `_config.yml` 수정 없이 동작합니다.
- 다른 파일명을 쓰려면 `_config.yml` 의 `portfolio_pdf` 값을 바꾸세요.

```yaml
portfolio_pdf: '/images/portfolio/내파일명.pdf'
```

## 추가 이미지(카드 썸네일)

- `_data/portfolio.yml` 에서 `추가 자료` 카드를 쓸 때 `cover: /images/portfolio/파일.png` 형식으로 지정합니다.
