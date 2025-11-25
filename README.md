# Fusion Animation Tools From F's Plugins

### This is an individual project by akahito_ot. DaVinci Resolve - Fusion ports of **F's Plugins for After Effects** by **bry-ful** (Hiroshi Furuhashi). ###

### akahito_otによる個人プロジェクトです。bry-ful [Hiroshi Furuhashi]さんが開発した**F's Plugins for After Effects**の DaVinci Resolve - Fusion 移植版を公開しています。 ###

---

##  About / 概要

[F's Plugins](https://github.com/bryful/F-s-PluginsProjects) is a plugin collection for Adobe After Effects by bry-ful (Hiroshi Furuhashi). This repository ports these tools to Fusion as .fuse files with DCTL kernels.

[F's Plugins](https://github.com/bryful/F-s-PluginsProjects)は、bry-ful（古橋ヒロシ）さんによってAdobe After Effects向けに開発されたプラグイン集です。本リポジトリは、それらを.fuse（DCTL）形式でFusionに移植しています。

**⚠️ Important / 重要:**  

These are not 1:1 ports - behavior may differ from the original plugins due to Fusion-specific optimizations.

これらは完全移植ではなく、Fusion向けに最適化されているため、元のプラグインと一部挙動が異なります。

---

## Updates / 更新履歴

### 2025-11-25
- **Fixed DCTL kernel naming conflicts** / DCTLカーネル名の競合を修正
  - Changed all kernel and parameter names to use unique prefixes (FS + plugin abbreviation)
  - 全てのカーネル名とパラメータ名をユニークなプレフィックス（FS + プラグイン略称）に変更
  - This resolves issues where multiple plugins would conflict when used together
  - 複数のプラグインを同時に使用した際の不具合を解消
- **Added new tools** / 新規ツール追加
  - ColorChange: Replace colors with new colors (up to 8 pairs)
  - EdgeLine: Draw lines between target and sample colors

---

## Available Tools / 利用可能なツール

### <ins>Main Line Repaint</ins>
Automatically repaints main line pixels (specified color) with neighboring colors.  
指定した色の主線ピクセルを、周囲の色で自動的に塗り直します。

**Original:** [MainLineRepaint for After Effects](https://github.com/bryful/F-s-PluginsProjects/tree/master/MainLineRepaint)

---

### <ins>Selected Blur</ins>
Applies blur only to selected colors (up to 8 colors).  
選択した色にのみブラーを適用します（最大8色まで指定可能）。

**Original:** [SelectedBlur for After Effects](https://github.com/bryful/F-s-PluginsProjects/tree/master/SelectedBlur)

---

### <ins>Select Color</ins>
Displays only pixels matching selected colors (up to 8 colors).  
選択した色に一致するピクセルのみを表示します（最大8色まで指定可能）。

**Original:** [SelectColor for After Effects](https://github.com/bryful/F-s-PluginsProjects/tree/master/SelectColor)

---

### <ins>Color Change</ins>
Replaces matched source colors with destination colors (up to 8 color pairs).  
指定した元の色を別の色に置き換えます（最大8色ペアまで指定可能）。

**Original:** [ColorChange for After Effects](https://github.com/bryful/F-s-PluginsProjects/tree/master/ColorChange)

---

### <ins>Edge Line</ins>
Draws lines where target color pixels are adjacent to sample color pixels.  
指定した2色が隣接する境界線を検出して描画します。

**Original:** [EdgeLine for After Effects](https://github.com/bryful/F-s-PluginsProjects/tree/master/EdgeLine)

---

##  Installation / インストール

1. Download the `.fuse` file / 使用したいツールの`.fuse`ファイルをダウンロード
2. Place it in your Fusion Fuses folder / Fusionのフォルダに配置:
   - **Windows:** `C:\ProgramData\Blackmagic Design\DaVinci Resolve\Fusion\Modules\Fuses`
   - **macOS:** `/Library/Application Support/Blackmagic Design/DaVinci Resolve/Fusion/Modules/Fuses`
3. Restart DaVinci Resolve or Fusion / DaVinci ResolveまたはFusionを再起動
4. Find tools under **F'sPlugins** category / **F'sPlugins**カテゴリ内にツールが表示されます
---

##  Requirements / 動作環境

- **DaVinci Resolve** 18.0 or later (recommended)
- **Fusion Studio** 18.0 or later
- GPU with OpenCL support (for optimal performance)

---

##  Credits

### Original Plugins
**F's Plugins for After Effects**  
Author : **bry-ful** (Hiroshi Furuhashi)  
Repository: https://github.com/bryful/F-s-PluginsProjects  
License: MIT License

### Fusion Ports
**Porting & Optimization:** akahito_ot  
[itch.io](https://akahito-ot.itch.io) / [GitHub](https://github.com/akahito-ot)

---

### Acknowledgement / 謝辞
Special thanks to **bry-ful (Hiroshi Furuhashi)** for generously allowing the release of this Fusion port project.  

この移植プロジェクトの公開をご快諾くださった **bry-ful（古橋ヒロシ）** さんに心より感謝いたします。  

---

##  License

This repository is released under the [MIT License](LICENSE).

The original F's Plugins by bry-ful is also released under the MIT License.
