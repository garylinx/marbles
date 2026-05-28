# 八顆珠

以原本的 WebGL glass marbles demo 為基礎，改成先天八卦「八顆珠」互動版。

## 版本重點

- 八顆珠依序對應：兌粉紅、離透明、震綠、巽白、坎藍、艮玄、坤黃、乾金。
- 宮位採先天八卦位置：乾上、兌左上、離左、震左下、巽右上、坎右、艮右下、坤下。
- 心珠拖曳到對應宮位後會吸附入位並發光，粉紅兌宮心珠有強化光效。
- 長按或雙擊任一心珠會顯示該心珠的文字解說。
- 網站配色以暖紙底 `#F7E8D6`、墨青文字 `#063346`、金線定位 `#C8912E` 為主。
- 八顆珠已改用 `assets/beads/` 內的獨立 SVG 圖片，移除第一版珠子線條並避免邊緣毛邊。

## Tech Stack

- **WebGL**: Real-time raytracing of 3D glass.
- **SVG Filters**: Composition.
- **Physics**: Rigid body dynamics.
