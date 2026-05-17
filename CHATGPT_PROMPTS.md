# 桐ねこちゃん 画像生成プロンプト集

アプリで使う画像ファイル名と、それぞれの ChatGPT 生成プロンプトです。
画像は `recipe-note/images/` フォルダに保存してください。

---

## 【共通設定】すべての画像に使うベーススタイル

以下の説明を各プロンプトの**冒頭に必ず追加**してください：

```
A cute chubby plush toy cat sticker character. Cream/beige colored soft body with 
purple/lavender stripe markings on the forehead and ears. Wearing a small purple 
flower collar (lily-of-the-valley bells). Big round sparkling eyes, rosy pink cheeks. 
Chibi kawaii style, 3D soft plush toy look, pastel colors. White sticker outline 
around the entire character. Pure white background. Square image, high quality.
```

---

## 画像一覧とポーズのプロンプト

### 1. `kiri-welcome.png` — ウェルカム（手を振っている）
**使用場面：** ホーム画面の挨拶

```
[ベーススタイル] + 
Waving one paw in greeting with a big happy smile. The other paw held against 
the chest. Standing upright, cheerful and welcoming expression.
```

---

### 2. `kiri-happy.png` — 大喜び（ジャンプ・拍手）
**使用場面：** レシピ追加成功、ホーム画面

```
[ベーススタイル] + 
Jumping with joy, both paws raised in the air. Big sparkling star-shaped eyes. 
Confetti or small hearts floating around. Super excited and happy expression.
```

---

### 3. `kiri-sad.png` — 悲しい（泣いている）
**使用場面：** 検索結果ゼロ、お気に入り空っぽ

```
[ベーススタイル] + 
Sitting down, looking sad with teardrop eyes. Small tears falling from the big 
round eyes. Paws pressed together. Droopy ears. Dejected but still adorable expression.
```

---

### 4. `kiri-thinking.png` — 考え中（首をかしげている）
**使用場面：** 検索前の空リスト、フォーム入力中

```
[ベーススタイル] + 
Tilting head slightly to one side with one paw raised to cheek in a thinking pose. 
Small question mark near the head. Curious and thoughtful expression. Eyes looking 
slightly upward.
```

---

### 5. `kiri-cooking.png` — 料理中（お玉や鍋を持っている）
**使用場面：** レシピ詳細ページ、料理中のコメント

```
[ベーススタイル] + 
Holding a small round ladle/spoon in one paw. Wearing a tiny white apron. 
Happy cooking expression, small steam wisps rising. Chef-like pose, enthusiastic 
and ready to cook.
```

---

### 6. `kiri-favorite.png` — お気に入り（花束を抱えている）
**使用場面：** お気に入りページのヒーロー部分

```
[ベーススタイル] + 
Holding a small bouquet of purple lily-of-the-valley flowers with both paws. 
Sweet and gentle smile. Small pink hearts floating around. Lovingly embracing 
the flowers, warm and affectionate expression.
```

---

### 7. `kiri-search.png` — 検索（虫眼鏡を持っている）
**使用場面：** 検索ページ

```
[ベーススタイル] + 
Holding a small magnifying glass with one paw, looking through it with a curious 
expression. One eye slightly larger from looking through the lens. Determined and 
investigative expression, detective-like pose.
```

---

### 8. `kiri-peek.png` — のぞき見（横から顔を出している）
**使用場面：** ローディング、おまけ演出

```
[ベーススタイル] + 
Peeking out from behind the left edge of the frame. Only the face and one paw 
visible. Playful and shy expression. Half-hidden, curious eyes peeking out. 
Mischievous and cute.
```

---

## 画像の仕様

| 項目 | 推奨値 |
|------|--------|
| サイズ | 512×512px 以上 |
| 形式 | PNG（透明背景推奨） |
| 背景 | 白 または 透明 |

## 保存場所

```
recipe-note/
  images/
    kiri-welcome.png   ← ここに保存
    kiri-happy.png
    kiri-sad.png
    kiri-thinking.png
    kiri-cooking.png
    kiri-favorite.png
    kiri-search.png
    kiri-peek.png
```

## 💡 ヒント

- ChatGPT に「同じキャラクターで複数ポーズを作りたい」と伝えると、一貫したスタイルで生成しやすいです
- 最初の1枚を気に入ったら「このキャラクターで〇〇のポーズにして」と追加依頼するのがオススメ！
- 背景を透明にしたい場合は「transparent background, PNG with alpha channel」を追加してください
