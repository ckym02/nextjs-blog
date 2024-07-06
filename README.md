```
npx create-next-app@14.1 nextjs-blog --use-npm --ts --eslint --no-tailwind --no-app --src-dir
```
nextjs-blog の下には以下のようなファイルが作成されます。--src-dir を指定したため、src ディレクトリが作成されているはずです。

```
node_modules/  →npmパッケージ
public/ →画像などのリソースファイルの配置場所
src/ →TypeScriptのソースコード
pages/ →公開するページのソースコードの配置場所
styles/ →CSSの配置場所
next.config.mjs →アプリケーション全体の設定
package.json →パッケージファイル
package-lock.json →パッケージのロックファイル
README.md →プロジェクトの説明
tsconfig.json →TypeScriptの設定
```


`npm run dev`を実行しアプリケーションページを開く
