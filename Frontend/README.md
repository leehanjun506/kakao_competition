# 폴더 구조
```
public/
 ├── assets/ (프론트에서 저장될 static 파일들)
 │ 
src/
 ├── components/
 │   └── common/ (버튼같은 공통적으로 사용되는 components를 모아두면 될 것 같습니다.)
 │   └── pages/ ( 각 페이지별 사용될 컴포넌트 )
 │         └── home
 │         └── service
 │         └── place
 │         └── login
 │         └── signup
 │         └── findpwd
 │         └── userinfo
 │
 ├── styles/
 │   └── common/ 
 │   └── pages/
 ├── lib/
 │   └──types/  .ts 파일만 두어 타입 관리
 │   └──api/  비동기 api 호출 함수 관리
 ├── pages/
 │   └── 페이지들 ~~
 ├── hooks/ ( 반응형 pages 구성 hook 관리)
 │
 ├── App.tsx
 ├── App.css
 ├── index.tsx
 └── index.css
```

## Commit convetnion

| Type       | 설명                                                         |
|------------|------------------------------------------------------------|
| feat       | 새로운 기능 추가                                             |
| fix        | 버그 수정 또는 오타                                          |
| refactor   | 코드 리팩토링                                                 |
| design     | 사용자 UI 디자인 변경 (CSS 등)                               |
| comment    | 필요한 주석 추가 및 변경                                      |
| style      | 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우              |
| test       | 테스트 코드 추가, 수정, 삭제, 비즈니스 로직 변경이 없는 경우 |
| chore      | 위에 해당되지 않는 기타 변경사항 (빌드 스크립트, 패키지 등) |
| init       | 프로젝트 초기 생성                                            |
| rename     | 파일 또는 폴더명 수정 또는 이동                                |
| remove     | 파일을 삭제하는 작업만 수행하는 경우                          |



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
> $npx create-react-app "" —template typescript

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).