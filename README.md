# 🎥🤖 Welcome to 302.AI's AI Video Real-time Translation! 🚀✨

[Chinese](README_zh.md) | [English](README.md) | [Japanese](README_ja.md)

Open-source version of the [AI Video Real-time Translation](https://302.ai/tools/vt/) from [302.AI](https://302.ai).
You can directly log in to 302.AI for a zero-code, zero-configuration online experience.
Alternatively, customize this project to suit your needs, integrate 302.AI's API KEY, and deploy it yourself.

## ✨ About 302.AI ✨
[302.AI](https://302.ai) is a pay-as-you-go AI application platform, bridging the gap between AI capabilities and practical implementation.
1. 🧠 Comprehensive AI capabilities: Incorporates the latest in language, image, audio, and video models from leading AI brands.
2. 🚀 Advanced application development: We build genuine AI products, not just simple chatbots.
3. 💰 No monthly fees: All features are pay-per-use, fully accessible, ensuring low entry barriers with high potential.
4. 🛠 Powerful admin dashboard: Designed for teams and SMEs - managed by one, used by many.
5. 🔗 API access for all AI features: All tools are open-source and customizable (in progress).
6. 💡 Powerful development team: Launching 2-3 new applications weekly with daily product updates. Interested developers are welcome to contact us.

## Project Features
1. 🎥 Multi-platform video support: Watch YouTube, TikTok, Bilibili, and Douyin videos.
2. 🌍 Multilingual subtitle translation: Easily switch between Chinese, English, Japanese, German, French, and Korean.
3. 📝 Subtitle format download: Get subtitle files in VTT, SRT, and TXT formats.
4. 🔄 Comprehensive internationalization: Seamless conversion among multiple languages including Chinese, English, Japanese, German, French, and Korean.
5. 💬 Convenient sharing feature: Quickly share exciting video content with friends.

With AI Video Real-time Translation, anyone can efficiently access video information! 🎉🎥 Let’s explore the new world of AI-driven information acquisition together! 🌟🚀

## Tech Stack
- Next.js 14
- Tailwind CSS
- Shadcn UI

## Development & Deployment
1. Clone the project `git clone https://github.com/302ai/302_video_translation`
2. Install dependencies `pnpm install`
3. Configure 302's API KEY as per .env.example
4. Run the project `pnpm dev`
5. Build and deploy `docker build -t video-translation . && docker run -p 3000:3000 video-translation`

## User Interface Preview
![User Interface Preview](docs/preview.png)
