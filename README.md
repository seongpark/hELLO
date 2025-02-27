# hELLO

<a href="https://github.com/pronist/hELLO/graphs/contributors"><img src="https://opencollective.com/tistory-skin-hello/contributors.svg"></a>

## 시작하기

[hELLO](https://pronist.tistory.com/5) 는 [티도리 프레임워크](http://www.tidory.com)로 작성된 티스토리 스킨입니다. 따라서 별도의 개발 방식이 요구됩니다. 먼저, 프로젝트를 복사합니다.

```bash
git clone https://github.com/pronist/hELLO
```

프로젝트 폴더로 이동하여 `node_modules` 를 설치해줄 필요가 있습니다. 티도리 프레임워크는 **Node.js, Webpack** 을 기반으로 합니다. 따라서 **NPM(Node Package Manager)** 이 요구됩니다.

```bash
cd hELLO && npm install
```

티스토리 치환자가 적용된 모습을 보려면 **프리뷰 서버** 를 사용할 필요가 있는데, `tidory.config.example.js` 의 이름을 `tidory.config.js` 로 변경하고, 티도리 프레임워크의 [환경설정](https://tidory.com/docs/configuration/)를 참고하여 `ts_session`, `url` 를 설정해줄 필요가 있습니다. 이는 직접 티스토리 서버와 소통하여 치환자가 해석된 상태의 스킨을 먼저보기 위한 값입니다.

설정이 완료되었다면 프리뷰 서버를 실행할 수 있습니다.

```bash
npm run preview
```

## 배포

`tidory.config.js` 에 `ts_session`, `url` 이 설정되었다면 배포를 진행할 수 있습니다. 티도리 프레임워크의 [빌드 및 배포](https://tidory.com/docs/deployment)를 참고하십시오.

```bash
npm run production && npm run deploy
```

## 기여하기

hELLO 에 기여하는 방법은 스킨의 **테마**를 제공하는 것입니다. hELLO 는 안정화 단계에 있기때문에 소스코드의 변화가 크게 발생하지 않습니다. 따라서 기여를 통해 사용자에게 보다 다양한 테마를 제공할 수 있는 길을 열어두기로 했습니다. 기여를 하려면 [CONTRIBUTING.md](https://github.com/pronist/hELLO/blob/master/CONTRIBUTING.md) 를 참고하여 할 수 있습니다.

## 저작권

[MIT](https://github.com/pronist/hELLO/blob/master/LICENSE)

Copyright 2020-2021. [SangWoo Jeong](https://github.com/pronist). All rights reserved.
