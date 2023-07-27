# 터벅터벅 grafana_K6 부하테스트 학습기 ⚙️
### 내 가볍고, 통신도 적고, 간단한 웹 사이트에 부하테스트를 해보았다.

[K6 릴리즈 페이지]: https://github.com/grafana/k6/releases
[K6 문서]: https://k6.io/docs/


# grafana_k6 설치
- 나는 릴리즈 된 버전을 직접 받아서 사용했다.
  별 다른 이유는 없고 가장 간단했기 때문 [K6 릴리즈 페이지]
- 릴리즈 페이지의 하단에 운영체제에 따른 파일을 받으면 끝이다.

# grafana_k6 실행
- 우선 다운 받은 k6.exe는 window 기준 `CMD`를 통해 열어서 작동했다.
- k6와 자바스크립트를 같은 폴더에 두고, CMD에서 해당 파일들이 있는 곳으로 이동한다

``` cmd
< CMD >
cd k6.exe와 테스트코드.js 파일이 있는 경로
```
- cmd에서 `k6` 라고 입력하면
