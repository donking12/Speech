# Tafreegh AI (تفريغ الذكاء الاصطناعي) - Client-Side AI Micro-SaaS
      
محطة تفريغ صوتي محلية وآمنة 100% تعمل بالذكاء الاصطناعي مباشرة في متصفحك دون رفع ملفاتك إلى أي خادم.

## About
# Tafreegh AI (تفريغ الذكاء) - On-Device Whisper Transcriber

A premium, client-side AI micro-SaaS workspace specifically engineered for **content creators, podcasters, and audio producers**. Powered by **Whisper (via Transformers.js)** running fully inside the browser using WebAssembly / WebGPU fallback. Your data never leaves your device.

### Key Features
- 🎙️ **Dual-Input Mode**: Live Microphone Recording with visualizer OR High-Speed Audio File Upload (MP3, WAV, OGG, M4A).
- 🧠 **On-Device Whisper Intelligence**: Run high-fidelity Whisper models (`Tiny` or `Base` for quick browser load) client-side.
- 🔒 **Zero-Server Privacy**: Absolute privacy & compliance (GDPR, local security guidelines). Perfect for sensitive transcripts, journalism, and legal recordings.
- 🌍 **Multi-Language Support & Translation**: Detect and transcribe over 30+ languages, including Arabic, English, Spanish, and French, with optional direct English translation.
- ⚡ **Interactive SRT/TXT Exporter**: Edit segments live, search transcript keywords, jump to timestamps, and download with studio-ready format compatibility.
- 🛠️ **Performance Monitoring**: Real-time status badges, model download speed trackers, and dynamic canvas audio frequency visualizers.

Generated via Micro-SaaS AI App Factory of Chief Technology Officer.

## Required Security Configuration
This application utilizes local client-side WebGPU and SharedArrayBuffer modules. 
To function correctly, the host environment must inject these headers:

```http
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Embedder-Policy: require-corp
```

Detailed setup for local Next.js and Cloudflare Pages hosting are preconfigured inside config files of this archive.
