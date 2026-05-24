# MFA Pitch Deck 分享说明

## 如何打开

解压后双击 `MFA-Pitch-Deck.html` 即可在浏览器中查看。

如果浏览器因为本地安全策略限制图片加载，可以在该目录下启动一个本地静态服务：

```bash
python3 -m http.server 8765
```

然后打开：

```text
http://127.0.0.1:8765/MFA-Pitch-Deck.html
```

## 文件说明

- `MFA-Pitch-Deck.html`：当前可分享的 HTML 路演 deck，共 25 页。
- `assets/`：deck 所需的全部图片、logo 与认证素材，必须和 HTML 放在同一目录。

## 注意

不要只单独发送 HTML 文件；需要连同 `assets/` 文件夹一起发送，否则部分图片和 logo 会缺失。
