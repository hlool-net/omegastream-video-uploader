# 📦 Laravel OmegaStream Uploader

**Laravel OmegaStream Uploader** is a simple, developer-friendly package that allows you to effortlessly integrate with the [OmegaStream](https://omegastream.net) video streaming and upload API using resumable [TUS protocol](https://tus.io/) uploads.

Whether you're building a SaaS platform, media app, or just need a reliable way to handle large video uploads, this package helps you authenticate, upload, and manage your videos on OmegaStream with minimal setup.

## ✅ Features
- 🔐 Secure upload with dynamic SHA256 signature generation  
- 🚀 Resumable video uploads using [tus-php](https://github.com/ankitpokhrel/tus-php) or frontend libraries  
- 📡 Easy Laravel service integration (Facades, Service Provider, Config)  
- ⚙️ Handles expiration, signing, and header configuration out-of-the-box  
- 🧱 Plug & play Blade component and JS script support (optional)

## 💡 Use Cases
- Upload large videos from your admin panel or user dashboard  
- Seamlessly integrate OmegaStream into SaaS or CMS products  
- Handle pause/resume uploads with front-end progress tracking

## 🛠 Requirements
- PHP 8.0+  
- Laravel 9.x or 10.x  
- OmegaStream API Key

## 📄 License
This package is open-sourced under the [MIT license](LICENSE).
