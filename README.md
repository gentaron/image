<div align="center">

# EDU Image

**Eternal Dominion Universe — Character Artwork Repository**

[English](#english) · [日本語](#日本語)

</div>

[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)]()

---

## 日本語

### 概要

EDU Image は Eternal Dominion Universe（EDU）のキャラクターポートレートを集中管理する画像アセットリポジトリ。全 EDU サイトで共有されるキャラクター画像の単一情報源（Single Source of Truth）として機能する。

### 収録キャラクター（一部）

MinaEurekaErnst, LaylaVirelNova, Iris, Miyushari, Gareth, Fiona, Elena, CastinaTempest, ReidKakizaki, MarinaBobbin, SebastianValerius など 65+ キャラクター

### ファイル命名規則

- **PascalCase**: キャラクター名（例: `LaylaVirelNova.png`, `MinaEurekaErnst.png`）
- **フォーマット**: PNG
- **推奨サイズ**: 400x400px 以上

### 利用方法

他リポジトリからの参照例（laylaland `about.html`）:

```html
<img src="https://raw.githubusercontent.com/gentaron/image/main/LaylaVirelNova.png" alt="Layla" />
```

### Contributing

新しいキャラクター画像を追加する場合：

1. PNG ファイルを準備（400x400px 以上推奨）
2. PascalCase でファイル名を命名（例: `NewCharacter.png`）
3. `main` ブランチにコミット
4. [gentaron/edu](https://github.com/gentaron/edu) の Wiki データ等で参照を追加

---

## English

### Overview

EDU Image is the centralized image asset repository for character portraits in the Eternal Dominion Universe (EDU). It serves as the single source of truth for character artwork shared across all EDU sites.

### Included Characters (partial)

MinaEurekaErnst, LaylaVirelNova, Iris, Miyushari, Gareth, Fiona, Elena, CastinaTempest, ReidKakizaki, MarinaBobbin, SebastianValerius — 65+ characters total.

### Naming Convention

- **PascalCase**: Character full name (e.g., `LaylaVirelNova.png`)
- **Format**: PNG
- **Recommended size**: 400x400px+

### Consumers

- [gentaron/laylaland](https://github.com/gentaron/laylaland) — Character profiles and gallery
- [gentaron/eurekaspace](https://github.com/gentaron/eurekaspace) — Character gallery (local copy)
- [gentaron/edu](https://github.com/gentaron/edu) — Main EDU application

---

## Related Repositories

| Repo | Description |
|------|-------------|
| [gentaron/edu](https://github.com/gentaron/edu) | Main EDU application |
| [gentaron/edutext](https://github.com/gentaron/edutext) | Story text files |
| [gentaron/laylaland](https://github.com/gentaron/laylaland) | Layla character site (consumer) |
| [gentaron/irisworlds](https://github.com/gentaron/irisworlds) | Iris character site (consumer) |
| [gentaron/eurekaspace](https://github.com/gentaron/eurekaspace) | EDU encyclopedia site |

## License

[MIT](LICENSE)
