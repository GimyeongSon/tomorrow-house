# 내일의 집

| Mobile | Tablet | Desktop | class      |
| ------ | ------ | ------- | ---------- |
| O      | X      | X       | .sm-only   |
| O      | O      | X       | .lg-hidden |
| X      | O      | X       | .md-only   |
| X      | O      | O       | .sm-hidden |
| X      | X      | O       | .lg-only   |
| O      | X      | O       | .md-hidden |

### 1. GNB

- 로그인을 하지 않은 경우

```html
<div class="button-group">
  <button
    class="gnb-icon-button is-search lg-hidden"
    type="button"
    aria-label="검색창 열기 버튼"
  >
    <i class="ic-search"></i>
  </button>
  <a
    class="gnb-icon-button is-cart"
    href="/"
    aria-label="장바구니 페이지로 이동"
  >
    <i class="ic-cart"></i>
  </a>
  <div class="gnb-auth sm-hidden">
    <a href="/">로그인</a>
    <a href="/">회원가입</a>
  </div>
</div>
```

- 로그인을 한 경우

```html
<div class="button-group">
    <button
      class="gnb-icon-button is-search lg-hidden"
      type="button"
      aria-label="검색창 열기 버튼"
    >
      <i class="ic-search"></i>
    </button>

    <a
      class="gnb-icon-button sm-hidden"
      href="/"
      aria-label="스크랩북 페이지로 이동"
    >
      <i class="ic-bookmark"></i>
    </a>

    <a
      class="gnb-icon-button sm-hidden"
      href="/"
      aria-label="내소식 페이지로 이동"
    >
      <i class="ic-bell"></i>
    </a>

    <a
      class="gnb-icon-button is-cart"
      href="/"
      aria-label="장바구니 페이지로 이동"
    >
      <i class="ic-cart"></i>
      <strong class="badge">9</strong>
    </a>

    <button
      class="gnb-avatar-button sm-hidden"
      type="button"
      aria-label="마이메뉴 열기 버튼"
    >
      <div class="avartar-32">
        <img
          src="./assets/images/img-user-01.jpg"
          alt="사달라 아저씨"
        />
      </div>
    </button>
  </div>
</div>
```
