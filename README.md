# cccat-codex-pet

## 一键安装（推荐）

```bash
mkdir -p ~/.codex/pets && rm -rf ~/.codex/pets/cc-cat && git clone https://github.com/gcjun777-lab/cccat-codex-pet.git ~/.codex/pets/cc-cat
```

安装后在 Codex 中输入 `/pet`，选择 `CC猫`。

CC猫 Codex 桌宠项目（9 状态版）。

## 最新版本更新

- `Idle` 调整为 3 帧循环（`ABCABCAB`），提升体感帧率
- `Running` 使用稳定边界裁切，修复动画大小抖动
- `Review` 当前使用 `1723855656313.gif`

## 项目文件

- `pet.json`: 桌宠元数据
- `spritesheet.webp`: 最终桌宠雪碧图（1536x1872）
- `STATE_MAP.md`: 状态映射说明
- `assets/raw/`: 原始 GIF 素材

## 原始素材预览

### Idle
![Idle](assets/raw/idle_IMG_4005.GIF)

### Run right / Run left
![Run](assets/raw/run_1500890024_5975c3a87afe3.gif)

### Waving
![Waving](assets/raw/waving_2411305798.gif)

### Jumping
![Jumping](assets/raw/jumping_2411306119.gif)

### Failed
![Failed](assets/raw/failed_1723855656313.gif)

### Waiting
![Waiting](assets/raw/waiting_IMG_4007.GIF)

### Running
![Running](assets/raw/running_2410518049.gif)

### Review
![Review](assets/raw/review_1723856236367.gif)

## 安装到本地 Codex

将整个 `cc-cat` 目录放到：

```bash
~/.codex/pets/cc-cat
```

然后在 Codex 中使用 `/pet` 选择 `CC猫`。
