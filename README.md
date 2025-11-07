# Fusion Animation Tools From F's Plugins

bry-ful [Hiroshi Furuhashi]さんが開発した、**F's Plugins for After Effects**のFusion移植版です。

Fusion ports of **F's Plugins for After Effects** by **bry-ful** (Hiroshi Furuhashi).

---

##  About / 概要

[F's Plugins](https://github.com/bryful/F-s-PluginsProjects)は、bry-ful（古橋ヒロシ）さんによってAdobe After Effects向けに開発されたプラグイン集です。本リポジトリは、それらのツールをFusionに移植することを目的としています。

[F's Plugins](https://github.com/bryful/F-s-PluginsProjects) is a plugin collection for Adobe After Effects by bry-ful (Hiroshi Furuhashi). This repository ports these tools to the Fusion.

**⚠️ 重要 / Important:**  
これらは完全移植ではなく、Fusion向けに最適化されているため、元のプラグインと一部挙動が異なります。

These are not 1:1 ports - behavior may differ from the original plugins due to Fusion-specific optimizations.

---

##  Available Tools / 利用可能なツール

### [Main Line Repaint](MainLineRepaint/)

指定した色の主線ピクセルを、周囲の色で自動的に塗り直します。線画抽出のアーティファクト除去に最適です。

Automatically repaints main line pixels (specified color) with neighboring colors. Ideal for cleaning up line art extraction artifacts.

**Features / 機能:**
- 色の許容値を調整可能 / Adjustable color tolerance
- スキャン長を変更可能 / Variable scan length
- 自動収束検出 / Automatic convergence detection

**Original:** [MainLineRepaint for After Effects](https://github.com/bryful/F-s-PluginsProjects/tree/master/MainLineRepaint)

---

##  Installation / インストール

1. 使用したいツールの`.fuse`ファイルをダウンロード / Download the `.fuse` file
2. Fusionのフォルダに配置 / Place it in your Fusion Fuses folder:
   - **Windows:** `C:\ProgramData\Blackmagic Design\DaVinci Resolve\Fusion\Modules\Fuses`
   - **macOS:** `/Library/Application Support/Blackmagic Design/DaVinci Resolve/Fusion/Modules/Fuses`
3. DaVinci ResolveまたはFusionを再起動 / Restart DaVinci Resolve or Fusion
4. **AK_Tools**カテゴリ内にツールが表示されます / Find tools under **AK_Tools** category

---

##  Requirements / 動作環境

- **DaVinci Resolve** 18.0以降（推奨） / 18.0 or later (recommended)
- **Fusion Studio** 18.0以降 / 18.0 or later
- OpenCL対応GPU（最適なパフォーマンスのため） / GPU with OpenCL support (for optimal performance)

---

##  Credits / クレジット

### Original Plugins / オリジナルプラグイン
**F's Plugins for After Effects**  
作者 / Author: **bry-ful** (Hiroshi Furuhashi / 古橋弘)  
Repository: https://github.com/bryful/F-s-PluginsProjects  
License: MIT License

### Fusion Ports / Fusion移植版
**移植・最適化 / Porting & Optimization:** akahito_ot  
[itch.io](https://akahito-ot.itch.io) / [GitHub](https://github.com/akahito-ot)

---

##  License / ライセンス

This repository is released under the [MIT License](LICENSE).

The original F's Plugins by bry-ful is also released under the MIT License.

---

## 📚 Related Projects / 関連プロジェクト

- [F's Plugins Projects](https://github.com/bryful/F-s-PluginsProjects) - オリジナルのAfter Effectsプラグイン / Original After Effects plugins
