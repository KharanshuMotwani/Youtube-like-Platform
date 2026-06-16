# Video Streaming Platform from Scratch 🎬

A full-stack video streaming application built from scratch, demonstrating how to handle video uploads, real-time chunked chunking/transcoding via FFmpeg, and seamless media playback on the client side. This project serves as a comprehensive reference architecture for custom video-on-demand pipelines.

---

## 🚀 Features

- **Video Uploads**: Handle multi-part video uploads securely on the backend.
- **On-the-Fly Processing**: Integrates FFmpeg workflows for standardizing media assets into optimized formats.
- **Adaptive/Chunked Streaming**: Efficient video streaming capabilities to ensure fast buffer rates and lower bandwidth consumption.
- **Modern UI**: Clean and minimal React-based frontend video player configuration.

## 🛠️ Tech Stack

- **Frontend**: React.js, HTML5 Canvas/Video APIs, CSS3
- **Backend**: Node.js, Express.js
- **Media Processing**: FFmpeg (Fast Forward MPEG)
- **Package Management**: npm

---

## 📂 Repository Structure

```text
├── frontend/        # React-based client interface & video player
├── test-video/      # Sample video assets used for development and test uploads
├── uploads/         # Server-side destination directory for chunks and processed media
├── index.js         # Entry point for the Express backend server
├── package.json     # Node.js dependencies and script runners
└── readme.md        # Project documentation
