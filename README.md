# 🎬 YouTube Video Downloader

A sleek and responsive web application to download YouTube videos as **MP3 (audio)** or **MP4 (video)** files. Enter any valid YouTube URL and get instant download links in high quality.

live link:

## 🚀 Features

- 🎵 **Download Audio (MP3)**
- 🎥 **Download Video (MP4)**
- ⚡ **Fast and efficient** download link generation
- 📱 **Mobile responsive** and user-friendly UI
- 🔐 100% **Safe & Free**

## 🛠 Technologies Used

- **HTML5**
- **CSS3 (Bootstrap 5 + Custom Styling)**
- **JavaScript (Vanilla)**
- YouTube Thumbnail & oEmbed API
- External download service: [`ytc.life`](https://ytc.life)

---

## 📦 How to Use

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Paste a YouTube video link.
4. Click **"Generate Download Links"**.
5. Click **Download Audio** or **Download Video**.

---

## ⚙ How It Works

- Extracts the YouTube video ID from the URL.
- Fetches metadata via [YouTube oEmbed](https://www.youtube.com/oembed).
- Constructs direct links to external audio/video downloaders using that ID.
- Displays a thumbnail, title, and download buttons.

---

## 📁 File Structure

📦 YouTube-Downloader/
├── index.html # Main HTML file
└── README.md # Project documentation
