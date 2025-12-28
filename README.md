### Mouse / Trackpad Spotlight

- マウス・トラックパッド・タッチ操作で動く「スポットライト」演出のサンプル
- カーソル位置に応じて、画面を暗く覆うラジアルグラデーションを表示
- CSSカスタムプロパティ（`--x`, `--y`, `--size`, `--soft` など）で見た目を制御
- `pointermove` を使用し、マウス・トラックパッドの両方に対応
- タッチデバイスでも指の位置に追従
- キーボード操作対応  
  - 矢印キー / WASD：スポットライト移動  
  - Homeキー：中央に戻す
- レスポンシブ対応（モバイルではスポットライトを大きく表示）
- JavaScript・CSS・HTMLのみで動作（外部ライブラリ不要）
- アクセシビリティ配慮  
  - `tabindex` によりキーボードフォーカス可能  
  - `aria-label` を設定

[normal-one](https://zenn24ct.github.io/light-terasu-yasu/normal-one) </br>
↑一番最初に作ったもの（文字をライトに照らして読む）

[upgrade](https://zenn24ct.github.io/light-terasu-yasu/upgrade) </br>
↑文字を読むのではなく、ボタンを押す形式に変えた。

[upgrade02](https://zenn24ct.github.io/light-terasu-yasu/upgrade02) </br>
↑updateのコードを迷路形式に変えた。

- upgrade03は未完成なので修正してから表示する
