# 다봄시큐리티 GitHub Pages 쇼핑몰

별도 설치 없이 `index.html`을 열면 동작하는 정적 쇼핑몰입니다.

## 상품 추가 방법

가장 쉬운 방법은 `products.js`를 열고 `PRODUCTS` 배열 마지막에 아래 한 줄을 추가하는 것입니다.

```js
{id:'고유번호', category:'CCTV', name:'상품명', price:100000, image:'assets/products/파일명.jpg'},
```

- 가격을 `0`으로 입력하면 `가격 문의`로 표시됩니다.
- 카테고리는 `CCTV`, `IOT`, `디지털도어록`, `출입통제` 중 하나를 사용합니다.
- 이미지는 `assets/products` 폴더에 넣습니다.
- GitHub 웹사이트에서 `products.js`의 연필 버튼을 눌러 한 줄만 추가해도 됩니다.

## GitHub Pages 공개

GitHub 저장소에 전체 파일을 올린 뒤 `Settings → Pages → Deploy from a branch → main / root`를 선택합니다.
