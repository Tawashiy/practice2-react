# practice2-react

Created with CodeSandbox

---

- <BrowserRouter> で囲んだ配下でルーティング機能を有効化する
- <Link> : aタグのようにリンクを表す
- 以下 Route の記載方法は同じ意味

```
①
<Route path="/page1" >
  <Page1 />
</Route>
②
<Route path="/page1" render={() => <Page1/ >} />
```

- Path 記載のときは必要な時の「exact」を忘れずに
- URLSearchParams()：URL を扱うための便利なメソッドを持っている
