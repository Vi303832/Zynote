# Zynote - Akıllı Not Alma Uygulaması  
🔗 [Canlı Demo](https://zynote.vercel.app/)

## Proje Açıklaması
**Zynote**, yaratıcı ve üretken kullanıcılar için geliştirilmiş, modern ve fonksiyonel bir not alma uygulamasıdır. Yapay zeka destekli özetleme özelliği, görsel çizim alanı, renk ve etiket düzenlemeleriyle zenginleştirilmiş kullanıcı deneyimi sunar.

> Üretkenliği artırmak, not yönetimini kolaylaştırmak ve kişisel organizasyonu güçlendirmek için geliştirilmiştir.

## Kullanılan Teknolojiler
- **React.js** (Frontend)
- **Tailwind CSS** (Arayüz Tasarımı)
- **Node.js & Express.js** (Backend API)
- **MongoDB** (Veri Tabanı)
- **Cloudinary** (Görsel Upload)
- **Hugging Face API** (AI ile Not Özetleme)
- **JWT Authentication** (Kullanıcı Girişi)
- **Axios** (API İletişimi)
- **React Router** (Sayfa Yönetimi)

## Özellikler
- %100 Responsive, mobil uyumlu tasarım
- Kullanıcı girişi ve kayıt (JWT tabanlı auth sistemi)
- Notlara başlık, içerik, renk ve etiket ekleme
- Çizim yaparak not oluşturma özelliği (canvas alanı)
- Fotoğraf yükleme ve Cloudinary entegrasyonu
- Not arama ve sıralama
- AI destekli içerik özetleme (HuggingFace API)
- Modern, sade ve hızlı kullanıcı arayüzü
- SEO uyumlu yapı (meta tag’ler düzenlenmiş)

## Kurulum ve Çalıştırma

Projeyi lokal ortamınızda çalıştırmak için aşağıdaki adımları takip edin:

### 1. Repository'yi Klonlayın

```bash
git clone https://github.com/kullaniciadi/zynote.git
cd zynote
```
2. Client (Frontend)
```bash

cd client
npm install
npm run dev
```
3. Server (Backend)
```bash

cd server
npm install
npm run dev
```

4. Ortam Değişkenleri
server/.env dosyasını oluşturun ve aşağıdaki bilgileri doldurun:

```bash

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
HUGGINGFACE_API_TOKEN=your_huggingface_token
```

## Ekran Görüntüleri

![screencapture-zynote-vercel-app-notes-2025-05-14-10_26_21](https://github.com/user-attachments/assets/20580491-f649-409a-b8b3-aa806cd96838)


![screencapture-zynote-vercel-app-2025-05-14-10_05_31](https://github.com/user-attachments/assets/33db8246-68f6-45c6-94fc-c38546bb654e)

![Screenshot Capture - 2025-05-14 - 10-15-19](https://github.com/user-attachments/assets/3ebd4a58-1ec3-4a4c-8a08-8d1e45a7198e)



## Lisans
Bu proje yalnızca portföy ve tanıtım amaçlı geliştirilmiştir. Herhangi bir ticari kullanım için geliştiriciden izin alınması gerekmektedir.

🧑‍💻 Geliştirici: Mehmet Akif Tanyeri

📧 İletişim: 
mehmettanyeriiakif@hotmail.com

www.linkedin.com/in/mehmetakiftanyeri-382458351


