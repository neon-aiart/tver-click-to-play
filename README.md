# 📺 TVer Click to Play v1.0

## TVerの自動再生をストップします

TVerのエピソードページを開いた際、動画が勝手に流れ出すのを防止するシンプルなスクリプトです。  
既存のスクリプトをベースに、TVerの複雑な動的読み込みに合わせてコードを一から書き直しました。

### ✨ 特徴

* **確実な停止**: ページ読み込み時の「再生」を確実に阻止します。
* **軽量設計**: 余計な要素を追加しないため、サイトの動作を妨げず、他の拡張機能（広告ブロック等）とも共存可能です。
* **2025年動作確認済み**: `MutationObserver` を利用し、動画要素が後から生成される現在の仕様に対応しています。

### ⚠️ 仕様上の注意点（あらかじめご了承ください）

* **停止時の画面**: 本スクリプトは「一度開始された再生を強制的に一時停止」させる仕組みです。  
  そのため、停止時は**サムネイル表示ではなく、動画の先頭で静止（黒い画面）**の状態になります。
* **視聴再開**: 画面中央の再生ボタン、またはプレイヤー下部の再生コントロールを押せば、通常通り視聴が始まります。

---

### ✨ インストール方法 / Installation Guide

* **UserScriptマネージャーをインストール (Install the UserScript manager):**
   * **Tampermonkey**: [https://www.tampermonkey.net/](https://www.tampermonkey.net/)
   * **ScriptCat**: [https://scriptcat.org/](https://scriptcat.org/)

* **スクリプトをインストール (Install the script):**
   * [Greasy Fork](https://greasyfork.org/ja/scripts/560254) にアクセスし、「インストール」ボタンを押してください。  
     Access and click the "Install" button.

---

### 🛡️ ライセンス・クレジット

このユーザースクリプトのソースコードは、ねおんが著作権を保有しています。

* **Base Code**: [hamachi](https://greasyfork.org/ja/users/1129111)様のスクリプトの設計思想を参考にさせていただきました。  
  TVer click play v1.2: [https://greasyfork.org/ja/scripts/479604](https://greasyfork.org/ja/scripts/479604)
* **License**: MIT License

---

## 開発者 (Author)

**ねおん (Neon)**
<pre>
<img src="https://www.google.com/s2/favicons?domain=bsky.app&size=16" alt="Bluesky icon"> Bluesky       :<a href="https://bsky.app/profile/neon-ai.art/">https://bsky.app/profile/neon-ai.art/</a>
<img src="https://www.google.com/s2/favicons?domain=github.com&size=16" alt="GitHub icon"> GitHub        :<a href="https://github.com/neon-aiart/">https://github.com/neon-aiart/</a>
<img src="https://neon-aiart.github.io/favicon.ico" alt="neon-aiart icon" width="16" height="16"> GitHub Pages  :<a href="https://neon-aiart.github.io/">https://neon-aiart.github.io/</a>
<img src="https://www.google.com/s2/favicons?domain=greasyfork.org&size=16" alt="Greasy Fork icon"> Greasy Fork   :<a href="https://greasyfork.org/ja/users/1494762/">https://greasyfork.org/ja/users/1494762/</a>
<img src="https://www.google.com/s2/favicons?domain=www.chichi-pui.com&size=16" alt="chichi-pui icon"> chichi-pui    :<a href="https://www.chichi-pui.com/users/neon/">https://www.chichi-pui.com/users/neon/</a>
<img src="https://www.google.com/s2/favicons?domain=iromirai.jp&size=16" alt="iromirai icon"> iromirai      :<a href="https://iromirai.jp/creators/neon/">https://iromirai.jp/creators/neon/</a>
<img src="https://www.google.com/s2/favicons?domain=www.days-ai.com&size=16" alt="DaysAI icon"> DaysAI        :<a href="https://www.days-ai.com/users/lxeJbaVeYBCUx11QXOee/">https://www.days-ai.com/users/lxeJbaVeYBCUx11QXOee/</a>
</pre>
---
