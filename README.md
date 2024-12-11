# nextjs-sandbox

僕がNext.jsを試すための砂場です。

## 試したこと

- `/hoge/[slug]/page.tsx` vs `/hoge/huga/page.tsx`: `/hoge/huga` でルーティングされるのはどっち？
    - `/hoge/huga/page.tsx` こっちでした
    - 例えばユーザ名ごとに `/hoge/@user_name/` を切っている状況で `/hoge/fuga/` を切ると、`fuga` というユーザ名でhogeページにアクセスできなくなる
