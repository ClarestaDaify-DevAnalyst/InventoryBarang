# 📦 Sistem Inventory Web App

<img width="1536" height="1024" alt="ChatGPT Image Mar 29, 2026, 09_18_53 PM" src="https://github.com/user-attachments/assets/5aad311d-fbe6-4f53-a790-171b11ded271" />
> 🚀 Sistem manajemen stok berbasis web dengan Google Sheets & Apps Script

---

## ✨ Deskripsi

Sistem Inventory adalah aplikasi untuk mengelola stok barang secara **real-time** dengan fitur lengkap dan tampilan modern.

### 📌 Fitur utama:
- 📦 Master Barang
- 📥 Barang Masuk
- 📤 Barang Keluar
- 🚚 Supplier
- 🏷️ Kategori
- 👥 Manajemen User
- 📊 Dashboard Analitik

💡 Terintegrasi dengan **Google Sheets** sehingga data aman di cloud.

---

## 🔐 Login

**Default akun:**

Username: admin
Password: admin123


**Role:**
- 👑 Admin → akses penuh
- 👤 Manajemen → akses terbatas

---

## 📊 Dashboard

Menampilkan data secara real-time:

- Total barang
- Total stok
- Barang masuk & keluar
- Estimasi keuntungan

📈 Grafik:
- Line chart (transaksi)
- Bar chart (kategori)

---

## 🗄️ Master Barang

Kelola data inventaris:

- Tambah / Edit / Hapus
- Print PDF
- Export Excel

**Field:**
- Kode barang
- Nama barang
- Kategori
- Stok
- Harga beli & jual

⚠️ Hanya Admin yang bisa edit & hapus

---

## 📥 Barang Masuk

- Input dari supplier
- Stok otomatis bertambah

**Fitur:**
- Filter tanggal
- Dropdown barang & supplier
- ID otomatis

---

## 📤 Barang Keluar

- Validasi stok sebelum transaksi
- Tidak bisa minus ❌

---

## 🚚 Supplier

Kelola data pemasok:
- Tambah
- Edit
- Hapus

---

## 🏷️ Kategori

Kelompokkan barang berdasarkan jenis

---

## 👥 Manajemen User

| Fitur | Admin | Manajemen |
|------|------|----------|
| Lihat data | ✅ | ✅ |
| Tambah transaksi | ✅ | ✅ |
| Edit/Hapus | ✅ | ❌ |
| Kelola barang | ✅ | ❌ |
| Kelola user | ✅ | ❌ |

---

## 🛠️ Teknologi

**Frontend**
- HTML, CSS, JavaScript
- Bootstrap 5

**Backend**
- Google Apps Script

**Database**
- Google Sheets

**Library**
- Chart.js
- Moment.js
- jsPDF

---

## ⚙️ Instalasi

### 1. Buat Spreadsheet

### 2. Buka Apps Script

Extensions → Apps Script


### 3. Setup
- Paste `Code.js`
- Paste `index.html`

### 4. Deploy

Deploy → Web App


Setting:
- Execute as: Me
- Access: Anyone

---

## ▶️ Cara Pakai

1. Buka URL Web App
2. Klik **Setup Admin**
3. Login
4. Tambahkan data:
   - Kategori
   - Supplier
   - Barang
5. Mulai transaksi

---

## 💎 Keunggulan

- ☁️ Tanpa hosting
- 📱 Responsive
- 🎨 UI modern
- 🔓 Open source

---

## 🎯 Cocok Untuk

- UMKM
- Toko retail
- Distributor
- Gudang

---

## ⚠️ Catatan

- Password masih plaintext
- Disarankan tambah enkripsi 🔐

---

## ⭐ Support

Kalau project ini membantu, jangan lupa kasih **Star ⭐**

---
