# 📚 Materi Pembelajaran: Dasar-Dasar Bahasa Pemrograman

## 🎯 Pengenalan Bahasa Pemrograman

### Apa itu Bahasa Pemrograman?
Bahasa pemrograman adalah **alat untuk berkomunikasi dengan komputer** yang terdiri dari sekumpulan aturan sintaks dan semantik untuk menulis program.

### Komponen Utama Bahasa Pemrograman:
1. **Syntax** - Aturan penulisan kode
2. **Semantic** - Makna dari kode yang ditulis
3. **Compiler/Interpreter** - Penerjemah kode ke bahasa mesin

# 📝 Input, Proses, Output (IPO)

## 📥 INPUT
**Data yang masuk ke program**
```python
nama = input("Nama: ")
umur = int(input("Umur: "))
```

## ⚙️ PROSES
**Pengolahan data**
```python
tahun_lahir = 2024 - umur
status = "Dewasa" if umur >= 17 else "Anak"
```

## 📤 OUTPUT
**Hasil yang ditampilkan**
```python
print(f"Halo {nama}, lahir tahun {tahun_lahir}")
print(f"Status: {status}")
```

## 🔄 CONTOH SINGKAT
```python
# Input
panjang = 5
lebar = 3

# Proses  
luas = panjang * lebar

# Output
print("Luas:", luas)  # Output: Luas: 15
```

**Inti:** Semua program komputer mengikuti pola: Terima data → Olah data → Tampilkan hasil.

## 🔢 Tipe Data Dasar

### 1. Integer (Bilangan Bulat)
```python
umur = 20
jumlah_barang = 15
suhu = -5
```

### 2. Float (Bilangan Desimal)
```python
harga = 19.99
berat = 65.5
nilai_pi = 3.14
```

### 3. String (Teks)
```python
nama = "Budi Santoso"
alamat = 'Jakarta Selatan'
pesan = """Halo,
selamat datang!"""
```

### 4. Boolean (True/False)
```python
is_active = True
is_married = False
lulus = True
```

## 🔄 Variabel dan Assignment

### Cara Mendeklarasikan Variabel:
```python
# Single assignment
nama = "Alice"
umur = 25

# Multiple assignment
x, y, z = 10, 20, 30

# Assignment sama nilai
a = b = c = 0
```

### Aturan Penamaan Variabel:
```python
# ✅ Benar
nama_lengkap = "John Doe"
umur20 = 20
_total = 100

# ❌ Salah
2nama = "test"      # Tidak boleh angka di awal
nama-lengkap = "John" # Tidak boleh tanda minus
class = "A"         # Tidak boleh keyword
```

## 🎮 Operasi Dasar

### 1. Operasi Aritmatika
```python
a = 10
b = 3

print(a + b)   # Penjumlahan: 13
print(a - b)   # Pengurangan: 7
print(a * b)   # Perkalian: 30
print(a / b)   # Pembagian: 3.333...
print(a % b)   # Modulus: 1
print(a ** b)  # Pangkat: 1000
```

### 2. Operasi Perbandingan
```python
x = 5
y = 10

print(x == y)  # Sama dengan: False
print(x != y)  # Tidak sama: True
print(x > y)   # Lebih besar: False
print(x < y)   # Lebih kecil: True
print(x >= y)  # Lebih besar/sama: False
print(x <= y)  # Lebih kecil/sama: True
```

### 3. Operasi Logika
```python
a = True
b = False

print(a and b)  # AND: False
print(a or b)   # OR: True
print(not a)    # NOT: False
```

## 📋 Struktur Kontrol Dasar

### 1. Percabangan (If-Else)
```python
# Contoh sederhana
nilai = 85

if nilai >= 80:
    print("Grade: A")
elif nilai >= 70:
    print("Grade: B")
else:
    print("Grade: C")
```

### 2. Perulangan (Loop)
```python
# Perulangan for
for i in range(5):
    print("Iterasi ke:", i)

# Perulangan while
counter = 0
while counter < 3:
    print("Counter:", counter)
    counter += 1
```

## 📦 Struktur Data Sederhana

### 1. List (Array)
```python
# Membuat list
buah = ["apel", "jeruk", "mangga"]
angka = [1, 2, 3, 4, 5]

# Mengakses elemen
print(buah[0])    # Output: apel
print(angka[2])   # Output: 3

# Menambah elemen
buah.append("anggur")
```

### 2. Dictionary (Key-Value)
```python
# Membuat dictionary
mahasiswa = {
    "nama": "Budi",
    "nim": "12345",
    "jurusan": "Informatika"
}

# Mengakses nilai
print(mahasiswa["nama"])  # Output: Budi
```

## 🎯 Fungsi Dasar

### Membuat Fungsi Sederhana:
```python
def sapa(nama):
    """Fungsi untuk menyapa pengguna"""
    return "Halo, " + nama + "!"

# Memanggil fungsi
pesan = sapa("Alice")
print(pesan)  # Output: Halo, Alice!
```

### Fungsi dengan Parameter:
```python
def hitung_luas(panjang, lebar):
    luas = panjang * lebar
    return luas

# Menggunakan fungsi
hasil = hitung_luas(10, 5)
print("Luas:", hasil)  # Output: Luas: 50
```

## 💡 Input dan Output Dasar

### Menerima Input dari User:
```python
# Input string
nama = input("Masukkan nama Anda: ")

# Input number (harus dikonversi)
umur = int(input("Masukkan umur: "))
tinggi = float(input("Masukkan tinggi: "))

print(f"Nama: {nama}, Umur: {umur}, Tinggi: {tinggi}")
```

### Format Output:
```python
nama = "Alice"
umur = 25
saldo = 1500000

# Cara 1: String concatenation
print("Nama: " + nama + ", Umur: " + str(umur))

# Cara 2: String formatting
print("Nama: {}, Umur: {}".format(nama, umur))

# Cara 3: f-string (recommended)
print(f"Nama: {nama}, Umur: {umur}, Saldo: Rp {saldo:,}")
```

## 🛠️ Contoh Program Sederhana

### Program Kalkulator Sederhana:
```python
print("=== KALKULATOR SEDERHANA ===")

# Input angka dari user
angka1 = float(input("Masukkan angka pertama: "))
angka2 = float(input("Masukkan angka kedua: "))

# Operasi kalkulator
print("\nHasil Operasi:")
print(f"Penjumlahan: {angka1 + angka2}")
print(f"Pengurangan: {angka1 - angka2}")
print(f"Perkalian: {angka1 * angka2}")
print(f"Pembagian: {angka1 / angka2}")
```

### Program Manajemen Data Sederhana:
```python
# Program data mahasiswa
mahasiswa = []

# Input data
nama = input("Masukkan nama mahasiswa: ")
nim = input("Masukkan NIM: ")
jurusan = input("Masukkan jurusan: ")

# Simpan dalam dictionary
data = {
    "nama": nama,
    "nim": nim,
    "jurusan": jurusan
}

mahasiswa.append(data)

# Tampilkan data
print("\nData Mahasiswa:")
for mhs in mahasiswa:
    print(f"Nama: {mhs['nama']}")
    print(f"NIM: {mhs['nim']}")
    print(f"Jurusan: {mhs['jurusan']}")
    print("---")
```

## 📝 Latihan Praktis

### Latihan 1: Konversi Suhu
```python
# Buat program untuk mengkonversi suhu dari Celsius ke Fahrenheit
# Rumus: F = (C × 9/5) + 32

celsius = float(input("Masukkan suhu dalam Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print(f"{celsius}°C = {fahrenheit}°F")
```

### Latihan 2: Cek Bilangan Ganjil/Genap
```python
# Buat program untuk mengecek apakah bilangan ganjil atau genap

angka = int(input("Masukkan sebuah bilangan: "))

if angka % 2 == 0:
    print(f"{angka} adalah bilangan genap")
else:
    print(f"{angka} adalah bilangan ganjil")
```

### Latihan 3: Hitung Diskon
```python
# Program menghitung harga setelah diskon

harga_awal = float(input("Masukkan harga awal: "))
diskon = float(input("Masukkan persentase diskon: "))

harga_diskon = harga_awal * (1 - diskon/100)
print(f"Harga setelah diskon: Rp {harga_diskon:,.2f}")
```

## 💡 Tips Belajar Pemrograman

1. **Start Small** - Mulai dengan program sederhana
2. **Practice Regularly** - Latihan secara konsisten
3. **Read Code** - Baca kode orang lain untuk belajar
4. **Debug patiently** - Sabar dalam mencari kesalahan
5. **Build Projects** - Buat proyek kecil untuk aplikasikan pengetahuan

## 🎯 Kesimpulan

Bahasa pemrograman memiliki komponen dasar yang sama:
- **Variabel** untuk menyimpan data
- **Tipe data** untuk mengklasifikasikan data
- **Operasi** untuk memanipulasi data
- **Struktur kontrol** untuk mengatur alur program
- **Fungsi** untuk mengorganisir kode

Dengan memahami dasar-dasar ini, Anda dapat mempelajari bahasa pemrograman apa pun dengan lebih mudah!
