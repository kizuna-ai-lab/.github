# Kizuna AI Lab 🌐

<div align="center">

**Breaking barriers, building connections**
**障壁を越えて、絆を紡ぐ**

[![GitHub](https://img.shields.io/badge/GitHub-kizuna--ai--lab-181717?logo=github)](https://github.com/kizuna-ai-lab)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

</div>

---

## 🌟 About Us | 私たちについて

### English

Kizuna AI Lab is dedicated to fostering human connection and mutual understanding through the power of artificial intelligence. "Kizuna" (絆) means "bond" or "connection" in Japanese—a name that embodies our core mission.

We believe technology should bridge divides, not create them. Our projects focus on:

- **🗣️ Breaking language barriers** - Enabling seamless communication across languages
- **♿ Empowering accessibility** - Supporting individuals with visual or hearing impairments
- **🤝 Fostering understanding** - Creating tools that help people connect authentically

Our work is driven by personal experience. As someone who has lived through visual impairment due to macular damage, and as a non-native speaker navigating life in Japan, I've experienced firsthand the friction that language and accessibility barriers create. These experiences fuel our commitment to building technology that helps people understand each other and the world around them.

### 日本語

Kizuna AI Labは、人工知能の力を活用して人々の相互理解と繋がり（絆）を育むことに専念しています。

テクノロジーは隔たりを生むのではなく、橋渡しをすべきだと私たちは信じています。私たちのプロジェクトは以下に焦点を当てています：

- **🗣️ 言語の壁を越える** - 言語を超えたシームレスなコミュニケーションの実現
- **♿ アクセシビリティの向上** - 視覚障害や聴覚障害を持つ方々へのサポート
- **🤝 相互理解の促進** - 人々が真に繋がるためのツールの創造

私たちの活動は個人的な経験に根ざしています。黄斑損傷による視力障害を経験し、日本で生活する非日本語母語者として、言語やアクセシビリティの壁がもたらす摩擦を身をもって感じてきました。これらの経験が、人々がお互いや世界を理解し合うための技術を構築する原動力となっています。

---

## 🚀 Featured Projects | 主要プロジェクト

### [Sokuji (即時)](https://github.com/kizuna-ai-lab/sokuji)

<table>
<tr>
<td width="50%">

**English**

A cross-platform desktop application for real-time speech translation. Sokuji captures live conversations and delivers instant translations, enabling seamless communication across language barriers.

**Key Features:**
- 🎙️ Real-time speech-to-translation-to-speech pipeline
- 🌐 Multi-provider AI support (OpenAI, Google Gemini, Palabra.ai)
- 💻 Cross-platform (Windows, macOS, Linux)
- 🎧 Advanced audio processing with echo cancellation
- 🌍 Support for 35+ languages
- ♿ Browser extension for web accessibility

</td>
<td width="50%">

**日本語**

リアルタイム音声翻訳のためのクロスプラットフォームデスクトップアプリケーション。Sokujiはライブ会話を捉え、即座に翻訳を提供し、言語の壁を越えたシームレスなコミュニケーションを実現します。

**主な機能：**
- 🎙️ リアルタイム音声認識→翻訳→音声合成パイプライン
- 🌐 複数のAIプロバイダー対応（OpenAI、Google Gemini、Palabra.ai）
- 💻 クロスプラットフォーム対応（Windows、macOS、Linux）
- 🎧 エコーキャンセレーション搭載の高度な音声処理
- 🌍 35以上の言語に対応
- ♿ Webアクセシビリティのためのブラウザ拡張機能

</td>
</tr>
</table>

---

### Sokuji Tsuyaku API (即時通訳API)

<table>
<tr>
<td width="50%">

**English**

A specialized real-time translation API server powering the Sokuji ecosystem. Built on a streamlined STT → Translation → TTS pipeline optimized for low-latency interpretation.

**Key Features:**
- ⚡ Sub-400ms end-to-end latency for real-time translation
- 🔌 OpenAI-compatible API for easy integration
- 🌐 WebSocket & WebRTC support for real-time communication
- 🤖 1000+ language pairs via MarianMT models
- 🎯 Dynamic model loading with intelligent caching
- 🚀 Optional GPU acceleration for enhanced performance

**Technology Stack:**
- [MarianMT](https://huggingface.co/Helsinki-NLP) for translation
- [faster-whisper](https://github.com/SYSTRAN/faster-whisper) for STT
- [Kokoro](https://huggingface.co/hexgrad/Kokoro-82M) & [Piper](https://github.com/rhasspy/piper) for TTS
- [Silero VAD](https://github.com/snakers4/silero-vad) for voice detection

</td>
<td width="50%">

**日本語**

Sokujiエコシステムを支える専用のリアルタイム翻訳APIサーバー。低遅延通訳に最適化された、STT（音声認識）→翻訳→TTS（音声合成）のストリームラインパイプラインで構築されています。

**主な機能：**
- ⚡ リアルタイム翻訳のエンドツーエンド遅延400ミリ秒未満
- 🔌 OpenAI互換APIによる簡単な統合
- 🌐 リアルタイム通信のためのWebSocket & WebRTCサポート
- 🤖 MarianMTモデルによる1000以上の言語ペア対応
- 🎯 インテリジェントキャッシング機能付き動的モデルロード
- 🚀 パフォーマンス向上のためのオプションGPUアクセラレーション

**技術スタック：**
- 翻訳: [MarianMT](https://huggingface.co/Helsinki-NLP)
- STT: [faster-whisper](https://github.com/SYSTRAN/faster-whisper)
- TTS: [Kokoro](https://huggingface.co/hexgrad/Kokoro-82M) & [Piper](https://github.com/rhasspy/piper)
- 音声検出: [Silero VAD](https://github.com/snakers4/silero-vad)

</td>
</tr>
</table>

---

## 💭 My Story | 私のストーリー

<table>
<tr>
<td width="50%">

**English**

This project was born from lived experience. After experiencing visual impairment from macular damage—with significant vision loss in my right eye's central field—I went through a period of adapting to a world that suddenly became harder to navigate. Though I've since adapted, those experiences left a lasting impact.

Living as a non-native speaker in Japan, I've also witnessed and personally felt the friction that language barriers create in daily interactions. These dual experiences of accessibility challenges and language barriers inspired me to create these projects.

I build these tools not just as technical solutions, but as bridges—connecting people who want to understand each other but face barriers in doing so.

</td>
<td width="50%">

**日本語**

このプロジェクトは実体験から生まれました。黄斑損傷による視力障害を経験し、右目の中心視野に大きな欠損が生じました。その後適応することができましたが、突然世界が見えづらくなった時期を経験しました。これらの経験は深い影響を残しました。

日本で非日本語母語者として生活する中で、日常的な交流において言語の壁が生み出す摩擦を目の当たりにし、自ら体験してきました。アクセシビリティの課題と言語の壁という二つの経験が、これらのプロジェクトを生み出すきっかけとなりました。

私はこれらのツールを単なる技術的ソリューションとしてではなく、お互いを理解したいと願いながらも障壁に直面している人々をつなぐ「橋」として構築しています。

</td>
</tr>
</table>

---

## 🎯 Mission | ミッション

<table>
<tr>
<td width="50%">

**English**

To leverage AI technology to create a world where:
- Language is never a barrier to human connection
- Accessibility challenges don't prevent people from understanding and experiencing the world
- Technology serves as a bridge, not a divide
- Every person can communicate, understand, and be understood

</td>
<td width="50%">

**日本語**

AI技術を活用し、以下のような世界を創造すること：
- 言語が人と人との繋がりを妨げない
- アクセシビリティの課題が世界を理解し体験することを阻まない
- テクノロジーが隔たりではなく橋となる
- すべての人がコミュニケーションを取り、理解し、理解される

</td>
</tr>
</table>

---

## 🤝 Get Involved | 参加する

<table>
<tr>
<td width="50%">

**English**

We welcome contributions, feedback, and collaboration from anyone who shares our vision:

- 🐛 Report issues or suggest features
- 💻 Contribute code improvements
- 📖 Help with documentation and localization
- 🌟 Star our projects if you find them useful
- 💬 Share your experiences and use cases

Together, we can build technology that truly connects people.

</td>
<td width="50%">

**日本語**

私たちのビジョンを共有するすべての方からの貢献、フィードバック、協力を歓迎します：

- 🐛 問題を報告、機能を提案
- 💻 コードの改善に貢献
- 📖 ドキュメントやローカライゼーションのサポート
- 🌟 プロジェクトが役立つと感じたらスター
- 💬 体験やユースケースの共有

一緒に、人々を真につなぐテクノロジーを構築しましょう。

</td>
</tr>
</table>

---

<div align="center">

**Building bridges through technology, one connection at a time**
**テクノロジーで橋を架け、一つひとつの絆を紡ぐ**

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

</div>
