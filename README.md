# dialog1

(2025-05) [\<dialog\>: ダイアログ要素 - HTML: ハイパーテキストマークアップ言語 | MDN](https://developer.mozilla.org/ja/docs/Web/HTML/Reference/Elements/dialog#%E3%83%96%E3%83%A9%E3%82%A6%E3%82%B6%E3%83%BC%E3%81%AE%E4%BA%92%E6%8F%9B%E6%80%A7)
の練習。

今回 polyfill(機能補完スクリプト) は使ってない。
古いブラウザを使う場合は
[このへん](https://www.tak-dcxi.com/article/modal-implementation-in-2025/#npm-install-%E3%81%99%E3%82%8B%E5%A0%B4%E5%90%88)
参照。

`command` / `commandfor` 属性は
は MDN にもまだ載ってない (2025-05)。
下の「参考」参照。

## 使い方

./src/の下をブラウザで開く。または

```sh
pnpm i
pnpm start
```

で開発用サーバ([http-server - npm](https://www.npmjs.com/package/http-server))が起動するので、
<http://localhost:8080/>
をブラウザで開く。インデックスページになってるので、d1.html などを開く

## 参考

- [JavaScript を書かない 2025 年のモーダルの実装方法 – TAKLOG](https://www.tak-dcxi.com/article/modal-implementation-in-2025/)
- [command と commandfor の導入 | Blog | Chrome for Developers](https://developer.chrome.com/blog/command-and-commandfor?hl=ja)
- [4 月にウェブ プラットフォームを初めて導入 | Blog | web.dev](https://web.dev/blog/web-platform-04-2025?hl=ja#the_command_and_commandfor_attributes)
- [HTML Standard](https://html.spec.whatwg.org/multipage/form-elements.html#attr-button-command)
- [Invoker Commands API - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Invoker_Commands_API)
- [4\.11\.4 The dialog element](https://html.spec.whatwg.org/multipage/interactive-elements.html#the-dialog-element)
