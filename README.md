
# 자주 사용하는 정규식

```ts
export const regString = /^[ㄱ-ㅎ가-힣a-zA-Z]+$/; // 한글 및 영어 사용가능 
export const regPassword = /^(?!((?:[A-Za-z]+)|(?:[~!@#$%^&*()_+=]+)|(?:[0-9]+))$)[A-Za-z\d~!@#$%^&*()_+=]{8,}$/;
export const regComma = /\B(?=(\d{3})+(?!\d))/g; // 천 단위 마다 , 찍어주기
export const regNumber = /^[0-9]*$/; // 숫자
export const regPhone = /^(01[016789]{1})[0-9]{3,4}[0-9]{4}$/; // 핸드폰 번호 
export const regEmail = /^[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*@[0-9a-zA-Z]([-_.]?[0-9a-zA-Z])*\.[a-zA-Z]{2,3}$/i; // 이메일 형식 체크
```
