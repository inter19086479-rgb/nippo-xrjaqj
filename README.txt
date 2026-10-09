運転代行 日報 — https で公開する場合のファイル一式
・このフォルダの中身（index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png）を
  GitHub Pages や Cloudflare Pages にそのまま置くだけで動きます。
・https で開くと：声の入力（Chrome）、ホーム画面に追加（アプリとして起動）、オフライン起動が使えます。
・データは各スマホのブラウザ内だけに保存されます。サーバーには何も送りません。
  ※声の入力だけは、Chrome の仕組みで音声が Google の音声認識に送られます。
・index.html は unten-daiko-nippo.html と同じ中身です（単体でも動きます）。
・注意：file:// で使っていたデータと https 版のデータは別の場所に保存されます。
  移すときは「設定 → バックアップ」で JSON を保存し、https 版で「復元」してください。
