# OneCopyThinker-ImageGen

AI画像生成に特化した、ワンコピペで使える多角思考プロンプト  
One-copy thinking prompt specialized for AI image generation

## 目次 / Table of Contents

- [🇯🇵 日本語版](#japanese)
- [🇺🇸 English Version](#english)

---

<a name="japanese"></a>
## 🇯🇵 日本語版

### 概要

OneCopyThinkerシリーズの画像生成版です。汎用の[OneCopyThinker](https://github.com/Simmon-Gomi/OneCopyThinker)や医療特化の[OneCopyThinker-Medical](https://github.com/Simmon-Gomi/OneCopyThinker-Medical)と同じ4視点思考フレームワーク(L)(C)(H)(I)を使い、画像生成に最適化されています。

#### 他版との違い

| ツール | 対象分野 | 特徴 |
|--------|----------|------|
| [OneCopyThinker](https://github.com/Simmon-Gomi/OneCopyThinker) | 汎用思考支援 | あらゆるテーマで多角的思考 |
| [OneCopyThinker-Medical](https://github.com/Simmon-Gomi/OneCopyThinker-Medical) | 医療・ヘルスケア | 患者中心の医療判断支援 |
| **OneCopyThinker-ImageGen** | **AI画像生成** | **プロンプト最適化・著作権配慮** |

### 特徴

- 🎯 **画像生成特化**: DALL-E、Stable Diffusion、Midjourney等に最適化
- 🧭 **4視点分析**: (L)技術・(C)創造・(H)人間・(I)統合の段階的思考
- 🛡️ **安全性重視**: 著作権・倫理面の自動チェック
- 📋 **ワンコピペ**: 複雑な設定不要、どのAIツールでも動作

### 使い方

#### Step 1: テンプレートをコピー
- [📄 日本語版テンプレート](./prompts/ultimate_prompt_ja.md)
- [📄 English Template](./prompts/ultimate_prompt_en.md)

#### Step 2: AIツールに貼り付け
**ChatGPT Plus:**
- 新規チャット → システムメッセージ欄に貼り付け

**Claude:**
- 新しい会話 → 「以下をシステム指示として使用：[貼り付け]」

**その他のAI:**
- システムメッセージまたは最初の入力として使用

#### Step 3: 実行
```
Phase 0からお願いします。

画像内容：夕焼けの海辺でくつろぐ猫
使用目的：SNS投稿用
避けたい要素：特定キャラクター、ブランドロゴ
```

#### Step 4: 結果の活用
AIが4段階で分析し、最適化された英語プロンプトと使用指針を提供します。

### 実用例

#### 入力例
```
Phase 0からお願いします。

画像内容：未来的な都市の風景
使用目的：プレゼンテーション資料
避けたい要素：既存の映画作品、特定企業のロゴ
```

#### 出力例
```
【Phase 1: (L) 技術的分析】
- 建築要素の組み合わせで実現可能性高
- 「cyberpunk」「futuristic」等のキーワード有効
- 解像度とアスペクト比の指定推奨

【Phase 2: (C) 創造的提案】
- ネオンライトと自然の融合
- 垂直農場や空中交通の要素
- 独特な建築デザインで差別化

【Phase 3: (H) 人間的配慮】
- ビジネス用途に適した清潔感
- 既存作品との差別化必須
- プレゼン資料として視認性重視

【Phase 4: (I) 統合プロンプト】
■ 最適化プロンプト（英語）
"Futuristic cityscape with sleek glass towers, floating gardens, clean energy infrastructure, soft blue and purple lighting, aerial vehicles, sustainable architecture, photorealistic, 16:9 aspect ratio, professional presentation quality"

■ 使用手順
1. 上記プロンプトをDALL-E/Stable Diffusion等に入力
2. 必要に応じてスタイル（realistic/artistic）を指定
3. 複数生成して最適なものを選択

■ 注意事項
- 既存のSF映画との類似性チェック必須
- 商用利用時は各ツールの利用規約確認
- プレゼン用として解像度とファイル形式に注意
```

### よくある質問

**Q: 生成された画像の著作権は？**  
A: 各画像生成ツールの利用規約に従います。商用利用時は特に注意が必要です。

**Q: 期待した画像が生成されない場合は？**  
A: 「Phase 1の技術的分析を詳しく」「創造的要素を追加して」等で再分析を依頼してください。

**Q: 他の画像生成AIでも使える？**  
A: はい。プロンプト形式は汎用的ですが、各ツールの特性に応じて微調整が必要な場合があります。

### 注意事項

- 🚫 **著作権侵害禁止**: 既存作品の模倣は避けてください
- 🔒 **責任の所在**: 生成結果の使用は自己責任でお願いします
- ⚖️ **倫理的配慮**: 差別的・不適切な表現は避けてください

### 貢献方法

OneCopyThinkerシリーズの「ワンコピペで使える」原則を維持する改善を歓迎します。

- バグ報告: Issues
- 機能提案: Issues
- プルリクエスト: 4視点フレームワークを維持してください

---

<a name="english"></a>
## 🇺🇸 English Version

### Overview

This is the image generation version of the OneCopyThinker series. It uses the same 4-perspective thinking framework (L)(C)(H)(I) as the general-purpose [OneCopyThinker](https://github.com/Simmon-Gomi/OneCopyThinker) and medical-specialized [OneCopyThinker-Medical](https://github.com/Simmon-Gomi/OneCopyThinker-Medical), optimized specifically for image generation.

#### Differences from Other Versions

| Tool | Target Domain | Features |
|------|---------------|----------|
| [OneCopyThinker](https://github.com/Simmon-Gomi/OneCopyThinker) | General thinking support | Multi-perspective thinking for any theme |
| [OneCopyThinker-Medical](https://github.com/Simmon-Gomi/OneCopyThinker-Medical) | Healthcare | Patient-centered medical decision support |
| **OneCopyThinker-ImageGen** | **AI Image Generation** | **Prompt optimization & copyright consideration** |

### Features

- 🎯 **Image Generation Specialized**: Optimized for DALL-E, Stable Diffusion, Midjourney, etc.
- 🧭 **4-Perspective Analysis**: Step-by-step thinking through (L)Logic, (C)Creative, (H)Human, (I)Integration
- 🛡️ **Safety-Focused**: Automatic copyright and ethical checks
- 📋 **One-Copy Paste**: No complex setup required, works with any AI tool

### How to Use

#### Step 1: Copy the Template
- [📄 Japanese Template](./prompts/ultimate_prompt_ja.md)
- [📄 English Template](./prompts/ultimate_prompt_en.md)

#### Step 2: Paste into AI Tool
**ChatGPT Plus:**
- New chat → Paste into system message field

**Claude:**
- New conversation → "Use the following as system instruction: [paste]"

**Other AI tools:**
- Use as system message or initial input

#### Step 3: Execute
```
Please start from Phase 0.

Image content: A cat relaxing on a beach at sunset
Usage purpose: Social media post
Elements to avoid: Specific characters, brand logos
```

#### Step 4: Use Results
The AI will analyze in 4 phases and provide optimized English prompts with usage guidelines.

### Practical Example

#### Input Example
```
Please start from Phase 0.

Image content: Futuristic cityscape
Usage purpose: Presentation material
Elements to avoid: Existing movie scenes, specific company logos
```

#### Output Example
```
【Phase 1: (L) Technical Analysis】
- High feasibility with architectural element combinations
- Keywords like "cyberpunk" and "futuristic" are effective
- Resolution and aspect ratio specification recommended

【Phase 2: (C) Creative Proposals】
- Fusion of neon lights and nature
- Elements of vertical farms and aerial transportation
- Differentiation through unique architectural design

【Phase 3: (H) Human Considerations】
- Clean aesthetic suitable for business use
- Differentiation from existing works essential
- Visual clarity for presentation materials

【Phase 4: (I) Integrated Prompt】
■ Optimized Prompt (English)
"Futuristic cityscape with sleek glass towers, floating gardens, clean energy infrastructure, soft blue and purple lighting, aerial vehicles, sustainable architecture, photorealistic, 16:9 aspect ratio, professional presentation quality"

■ Usage Instructions
1. Input the above prompt into DALL-E/Stable Diffusion etc.
2. Specify style (realistic/artistic) as needed
3. Generate multiple options and select the best one

■ Important Notes
- Check similarity with existing sci-fi movies
- Confirm terms of use for commercial applications
- Pay attention to resolution and file format for presentations
```

### FAQ

**Q: Who owns the copyright of generated images?**  
A: Follow the terms of service of each image generation tool. Special attention is required for commercial use.

**Q: What if the expected image isn't generated?**  
A: Request re-analysis with phrases like "Please elaborate on Phase 1 technical analysis" or "Add more creative elements."

**Q: Can this be used with other image generation AIs?**  
A: Yes. The prompt format is universal, but fine-tuning may be needed for each tool's characteristics.

### Important Notes

- 🚫 **No Copyright Infringement**: Avoid imitating existing works
- 🔒 **Responsibility**: Use generated results at your own responsibility
- ⚖️ **Ethical Considerations**: Avoid discriminatory or inappropriate expressions

### Contributing

We welcome improvements that maintain the "one-copy-paste usability" principle of the OneCopyThinker series.

- Bug reports: Issues
- Feature suggestions: Issues
- Pull requests: Please maintain the 4-perspective framework

### File Structure

```
OneCopyThinker-ImageGen/
├── README.md                        # This file
├── prompts/
│   ├── ultimate_prompt_ja.md        # Japanese template
│   └── ultimate_prompt_en.md        # English template
└── examples/
    ├── basic_usage.md               # Basic usage examples
    └── advanced_tips.md             # Advanced tips
```

### License

MIT License - Feel free to use, modify, and share

### Related Repositories

- [OneCopyThinker](https://github.com/Simmon-Gomi/OneCopyThinker) - General thinking support version
- [OneCopyThinker-Medical](https://github.com/Simmon-Gomi/OneCopyThinker-Medical) - Medical specialized version

---

Enjoy creative image generation with OneCopyThinker-ImageGen! 🎨✨
