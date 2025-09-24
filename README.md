# ERP System – Laravel 12 + Vue + Wayfinder

> **ERP Modern untuk Manufaktur & Bisnis**  
> Dibangun dengan **Laravel 12 + Vue 3 + Wayfinder** untuk menghadirkan sistem yang cepat, modular, dan mudah dikembangkan.

---

## ✨ Fitur Utama

### 📊 Master Data
- Customer
- Supplier
- Karyawan
- Produk / Barang
- Kategori & Satuan

### 🏭 Manufaktur & Produksi
- Bill of Materials (BOM)
- Work Order
- Multi-gudang & Stok Minimum
- Biaya Produksi

### 💰 Transaksi & Keuangan
- Pembelian (Purchasing)
- Penjualan (Sales)
- Laporan dasar

### 🔧 Tambahan
- Upload gambar produk
- Audit trail
- Sistem role & permission
- UI konsisten dengan **Shadcn UI** + **TailwindCSS**

---

## 🛠️ Teknologi yang Digunakan
- **Backend** : Laravel 12  
- **Frontend** : Vue 3 + Wayfinder  
- **UI Kit** : Shadcn UI + TailwindCSS  
- **Database** : MySQL / MariaDB  
- **Bundler** : Vite  

---

## 🚀 Instalasi

```bash
# Clone repositori
git clone https://github.com/username/project-erp.git
cd project-erp

# Install dependency backend
composer install
cp .env.example .env
php artisan key:generate

# Install dependency frontend
npm install

# Migrasi database
php artisan migrate --seed

# Jalankan development server
php artisan serve
npm run dev
