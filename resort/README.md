## dependencies

```sh
npm i react-icons react-router-dom styled-components
```

- [`react-icons`](https://react-icons.netlify.com/#/)
- [`react-router-dom`](https://www.npmjs.com/package/react-router-dom)
- [`styled-components`](https://www.npmjs.com/package/styled-components)

## route

```ts
<Route exact path="/" component={Home} />
<Route exact path="/rooms" component={Rooms} />
```

exact는 path="/" 일때만 component를 실행한다

exact가 없을때에는 /rooms 와 같은 url 요청에도 / path에 반응하여 coponent를 실행한다.
