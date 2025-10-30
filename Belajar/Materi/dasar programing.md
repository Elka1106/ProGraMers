
# Materi Dasar Bahasa Pemrograman untuk Pemula

---

## Apa Itu Bahasa Pemrograman?

Bahasa pemrograman adalah cara untuk berkomunikasi dengan komputer agar komputer dapat menjalankan perintah yang kita inginkan. Dengan bahasa pemrograman, kita dapat membuat aplikasi, website, game, dan banyak hal lainnya.

---

# Materi Pembelajaran: Variabel dalam Pemrograman

## 📚 Daftar Isi
- [Konsep Dasar Variabel](#konsep-dasar-variabel)
- [Deklarasi dan Inisialisasi](#deklarasi-dan-inisialisasi)
- [Tipe Data Variabel](#tipe-data-variabel)
- [Scope Variabel](#scope-variabel)
- [Best Practices](#best-practices)
- [Contoh Kode](#contoh-kode)
- [Latihan Soal](#latihan-soal)

## 🎯 Konsep Dasar Variabel

### Apa itu Variabel?
Variabel adalah **penyimpanan bernama** dalam memori komputer yang digunakan untuk menyimpan data yang dapat berubah selama eksekusi program.

### Analogi Sederhana
Bayangkan variabel seperti **kotak penyimpanan** yang memiliki:
- **Nama** (identifier)
- **Isi** (nilai/data)
- **Jenis** (tipe data)

## 📝 Deklarasi dan Inisialisasi

### Deklarasi Variabel
Mendeklarasikan variabel berarti memberitahu komputer untuk menyiapkan tempat di memori.

**Syntax Umum:**
```python
nama_variabel = nilai
```

**Contoh:**
```python
# Deklarasi variabel
nama = "Alice"
umur = 25
tinggi = 165.5
is_student = True
```

### Inisialisasi Variabel
Memberikan nilai awal kepada variabel.

```python
# Inisialisasi langsung
x = 10
y = "Hello World"

# Inisialisasi multiple
a, b, c = 1, 2, 3

# Inisialisasi dengan nilai sama
x = y = z = 0
```

## 🔢 Tipe Data Variabel

### Tipe Data Primitive

| Tipe Data | Contoh | Keterangan |
|-----------|--------|------------|
| **Integer** | `age = 25` | Bilangan bulat |
| **Float** | `price = 19.99` | Bilangan desimal |
| **String** | `name = "John"` | Teks/karakter |
| **Boolean** | `is_active = True` | True/False |

### Tipe Data Collection

```python
# List (mutable)
numbers = [1, 2, 3, 4, 5]

# Tuple (immutable)
coordinates = (10.5, 20.3)

# Dictionary (key-value pairs)
student = {"name": "Budi", "age": 20}

# Set (unique values)
unique_numbers = {1, 2, 3, 3, 4}  # Hasil: {1, 2, 3, 4}
```

## 🎪 Scope Variabel

### Global Scope
Variabel yang dapat diakses dari mana saja dalam program.

```python
global_var = "I am global"

def my_function():
    print(global

---

## Kesimpulan

- Pemrograman adalah cara memberi instruksi ke komputer
- Variabel menyimpan data
- Menggunakan tipe data yang tepat penting untuk program
- Struktur kontrol mengatur jalannya program

---
