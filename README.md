# 🎵 Spotify Clone

**Spotify Clone**, kullanıcıların müzik dinleyebileceği, çalma listeleri oluşturabileceği ve mesajlaşabileceği tam işlevsel bir müzik akış uygulamasıdır. Bu proje, modern web teknolojileri kullanılarak geliştirilmiş ve kullanıcı dostu bir arayüz sunmaktadır.

🔗 [Canlı Uygulama](https://spotifyclone-6hd0.onrender.com)

---

## 🚀 Özellikler

- **Kullanıcı Kimlik Doğrulama**: Güvenli giriş ve kayıt işlemleri.
- **Müzik Akışı**: Şarkıları dinleme ve kontrol etme (oynatma, duraklatma, sonraki/önceki).
- **Çalma Listeleri**: Kullanıcıların kendi çalma listelerini oluşturma ve yönetme imkanı.
- **Mesajlaşma**: Anlık olarak iletilen mesaj sistemi.
- **Responsive Tasarım**: Tüm cihazlarda uyumlu ve kullanıcı dostu arayüz.

---

## 🛠️ Teknoloji Yığını

- **Frontend**: React, Tailwind CSS, Vite
- **Backend**: Node.js, Express.js
- **Veritabanı**: MongoDB
- **Kimlik Doğrulama**: JSON Web Tokens (JWT)
- **Durum Yönetimi**: Zustand

---

## 📁 Proje Yapısı

```
spotify-clone/
├── backend/
│   ├── src/
│     ├── controllers/
│     ├── lib/
│     ├── middleware/
│     ├── models/
│     ├── routes/
│     ├── seeds/
│     └── index.js
├── frontend/
│   ├── src/
│     ├── components/
│     ├── layout/
│     ├── lib/
│     ├── pages/
│     ├── providers/
│     ├── stores/
│     ├── types/
│     ├── App.tsx
│     └── main.tsx
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Kurulum ve Çalıştırma

### 1. Depoyu Klonlayın

```bash
git clone https://github.com/omerFaruk0zkn/spotify-clone.git
cd spotify-clone
```

### 2. Ortam Değişkenlerini Ayarlayın

#### Backend (`/backend` dizininde `.env` dosyası oluşturun):

```
PORT=5001
MONGODB_URI=your_mongodb_uri
ADMIN_EMAIL=your_admin_email
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
NODE_ENV=development
```

#### Frontend (`/frontend` dizininde `.env` dosyası oluşturun):

```
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

### 3. Bağımlılıkları Yükleyin ve Uygulamayı Başlatın

#### Backend:

```bash
cd backend
npm install
npm run dev
```

#### Frontend:

```bash
cd frontend
npm install
npm run dev
```

---

## 🧪 Test ve Geliştirme

- **Geliştirme Ortamı**: Vite ile hızlı geliştirme ve sıcak yeniden yükleme.
- **Hata Ayıklama**: Hem istemci hem de sunucu tarafında kapsamlı hata ayıklama araçları.
