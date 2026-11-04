# DM0003 · English Music Stem Samples / 英文音乐分轨样例

**Dataset card / 数据集卡片** · Zovda sample dataset. This repository is the GitHub mirror of the card; the data files are hosted on Hugging Face — **[download the dataset / 下载数据集](https://huggingface.co/datasets/Zovda/dm0003-english-music-stems)**.

本仓库是数据集卡片的 GitHub 镜像，数据文件托管在 Hugging Face，**[点击下载 / download](https://huggingface.co/datasets/Zovda/dm0003-english-music-stems)**。

| Item / 项目 | Value / 值 |
|---|---|
| Dataset ID / 数据集编号 | DM0003 |
| Files / 数据文件 | 6 |
| Size / 数据体积 | 192.13 MB |
| Language / 语言 | en |
| Tasks / 任务类别 | audio-classification, automatic-speech-recognition |
| Hugging Face / 数据地址 | [dm0003-english-music-stems](https://huggingface.co/datasets/Zovda/dm0003-english-music-stems) |
| Provided by / 提供方 | Zovda |
| Contact / 联系邮箱 | lucas@zovda.com |

## Overview / 简介

Complete 41-stem multitrack for the English track "Jules King - Never Stop", grouped into drums, bass, electric guitar, keys, vocals and loops, fully aligned.

英文歌曲《Jules King - Never Stop》的完整 41 轨分轨素材，按鼓组、贝斯、电吉他、键盘、人声、循环六组组织，全部音轨对齐。

## What's inside / 数据内容

- 41 isolated WAV stems under `jules-king-never-stop/`, numbered 01–41 in original session order.
- `jules-king-never-stop/` 目录下 41 条独立 WAV 音轨，编号 01–41 保留原始工程顺序。
- Grouping: 15 drums/percussion, 14 electric guitar, 5 keys/synth, 3 loops, 3 vocals, 1 bass.
- 分组：鼓组与打击乐 15 条、电吉他 14 条、键盘与合成器 5 条、循环 3 条、人声 3 条、贝斯 1 条。

> This repository ships 6 representative stems (kick, snare, bass, electric guitar, synth, lead vocal); the full 41-stem pack is delivered on request.
>
> 本仓库提供 6 条代表性分轨（鼓、军鼓、贝斯、电吉他、合成器、主唱），完整 41 轨分轨包按需交付。

## Specifications / 规格

- Format: WAV, 44.1 kHz / 24-bit (14 stereo / 27 mono)
- 格式：WAV，44.1 kHz / 24-bit（14 条立体声 / 27 条单声道）
- Duration: 4:14 (253.79 s); all 41 stems aligned
- 时长：4 分 14 秒（253.79 秒），41 条音轨起点与时长对齐
- Note: stems 26 and 27 share the name ElecGtr07 but are different tracks; original naming preserved
- 注：26、27 号文件名同为 ElecGtr07，为两条不同音轨，保留原始命名

## Suitable tasks / 适用任务

- Source separation and multitrack mix analysis
- 音源分离与多轨混音分析
- Arrangement study of English pop production
- 英文流行乐编曲结构研究
- Audio generation and remix research
- 音频生成与重混（remix）研究

## Files / 文件清单

Paths below are relative to the Hugging Face repository root. 下表路径相对于 Hugging Face 仓库根目录。

| # | File | Size |
|---|---|---|
| 1 | `music-en-stems/jules-king-never-stop/04_Kick.wav` | 32.02 MB |
| 2 | `music-en-stems/jules-king-never-stop/05_Snare.wav` | 32.02 MB |
| 3 | `music-en-stems/jules-king-never-stop/19_Bass.wav` | 32.02 MB |
| 4 | `music-en-stems/jules-king-never-stop/20_ElecGtr01.wav` | 32.02 MB |
| 5 | `music-en-stems/jules-king-never-stop/35_Synth1.wav` | 32.02 MB |
| 6 | `music-en-stems/jules-king-never-stop/39_LeadVox.wav` | 32.02 MB |

## Download / 下载

The files are not stored in this repository. 数据文件不在本仓库内，请从 Hugging Face 获取。

- Dataset page / 数据集页面: https://huggingface.co/datasets/Zovda/dm0003-english-music-stems
- Direct file URL / 单文件直链: `https://huggingface.co/datasets/Zovda/dm0003-english-music-stems/resolve/main/<path from MANIFEST.csv>`

```python
from huggingface_hub import snapshot_download

snapshot_download(
    repo_id="Zovda/dm0003-english-music-stems",
    repo_type="dataset",
    local_dir="./dm0003-english-music-stems",
)
```

```python
from huggingface_hub import hf_hub_download

hf_hub_download(
    repo_id="Zovda/dm0003-english-music-stems",
    repo_type="dataset",
    filename="<path from MANIFEST.csv>",
    local_dir="./dm0003-english-music-stems",
)
```

## Rights and disclaimer / 授权与声明

Stems were exported by the producer in REAPER (bext record dated 2015-06-24). Provided to demonstrate specification and structure only; copyright remains with the rightsholder and **no licence for training or redistribution is granted**.

分轨由制作方以 REAPER 导出（bext 记录 2015-06-24）。本数据集仅用于展示规格与结构，著作权归原权利人所有，**不构成模型训练或再分发的授权**。

This dataset is shared to demonstrate data organisation, technical specifications and delivery structure. For formal licensing, large-scale access or custom production, contact lucas@zovda.com.

本数据集仅用于展示数据组织方式、技术规格与交付结构。正式授权、规模化取数与定制生产请联系 lucas@zovda.com。

## About Zovda / 关于 Zovda

Zovda builds, cleans, annotates and packages training data across video, audio, images, e-commerce image-text pairs, exam question banks, embodied AI and coding-agent corpora.

Zovda 提供多模态与文本训练语料的数据采集、清洗、标注与结构化交付服务，覆盖视频、音频、图像、电商图文、K12 与职业题库、具身智能、代码智能体等方向。

**Contact / 联系方式:** lucas@zovda.com
