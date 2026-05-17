# 📄 File Converter - All-in-One PDF Utility Platform

[![GitHub license](https://img.shields.io/github/license/NishantJLU/File-Converter)](https://github.com/NishantJLU/File-Converter/blob/main/LICENSE)
[![Next.js](https://img.shields.io/badge/Frontend-Next.js%2015-black)](https://nextjs.org/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js%20Express-green)](https://expressjs.com/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-blue)](https://tailwindcss.com/)

**File Converter** is a high-performance, professional-grade web application designed for seamless PDF manipulation. Inspired by industry standards like iLovePDF, it provides a clean, "utility-first" UI/UX for merging, splitting, compressing, and converting PDF files with ease.

---

## ✨ Features

### 🛠️ Core PDF Tools
- **Merge PDF**: Combine multiple PDF files into one in any order you choose.
- **Split PDF**: Separate PDF pages into individual documents, delivered in a ZIP file.
- **Compress PDF**: Optimize file size while maintaining maximum visual quality.
- **Edit PDF**: Quickly add text overlays and annotations to your documents.
- **Unlock PDF**: Remove common security restrictions and owner passwords.

### 🔄 Conversion Tools
- **PDF to Word**: Extract text from PDF documents into editable `.docx` files.
- **PDF to JPG**: Convert each PDF page into a high-quality JPEG image.
- **JPG to PDF**: Combine multiple JPG/PNG images into a single professional PDF.

### 🎨 Advanced UX & UI
- **Dark Mode**: Toggle between light and dark themes for a comfortable experience.
- **Live Thumbnails**: Real-time visual previews of uploaded PDFs using `pdf.js`.
- **Drag-and-Drop**: Intuitive file management with drag-to-reorder functionality.
- **Real-time Progress**: Visual feedback for file uploads and processing status.
- **Immediate Cleanup**: A "Delete from server now" option for privacy-conscious users.

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites
- [Node.js](https://nodejs.org/) (v18.0.0 or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NishantJLU/File-Converter.git
   cd File-Converter
   ```

2. **Setup the Backend**
   ```bash
   cd backend
   npm install
   # Create a .env file and add: PORT=5000
   npm run dev
   ```

3. **Setup the Frontend**
   Open a new terminal window:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to start using the platform.

---

## 🛠️ Technology Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | Next.js (App Router), Tailwind CSS, Framer Motion |
| **Backend** | Node.js, Express.js, Multer |
| **PDF Processing** | `pdf-lib`, `pdf-parse`, `pdf-to-img` |
| **Interactivity** | `react-dropzone`, `@dnd-kit` (Drag & Drop) |
| **Visuals** | `lucide-react` (Icons), `pdfjs-dist` (Thumbnails) |

---

## 🛡️ Privacy & Security

We take your document privacy seriously:
- Files are stored in a temporary directory during processing.
- Temporary files are automatically deleted after a short period.
- Users can manually trigger immediate file deletion from the server after conversion.
- No files are permanently stored on our servers.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

Developed with ❤️ by [NishantJLU](https://github.com/NishantJLU)
