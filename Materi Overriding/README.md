# 🚗 Materi Overriding 

Pada materi ini, kita belajar tentang **overriding**, yaitu ketika **subclass membuat versi baru dari method yang sudah ada di superclass**.  
Kita menggunakan contoh: `Transportasi → Mobil → senna`.  

- `senna` adalah object dari class `Mobil`, tapi disimpan di variabel tipe `Transportasi`.  
- Saat memanggil method `jalan()`, yang dijalankan adalah versi dari `Mobil`.  
- Ini juga menunjukkan **polymorphism**, karena satu variabel bisa menjalankan method sesuai object aslinya.  

---

## 📂 Struktur Project

- `Transportasi.java` → superclass  
- `Mobil.java` → subclass yang meng-override method `jalan()`  
- `Main.java` → class untuk membuat object `senna` dan memanggil method  
