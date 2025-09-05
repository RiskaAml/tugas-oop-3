# 💳 Materi Interface

Pada materi ini, kita akan **mengimplementasikan 3 interface** (`TransferBank`, `Qris`, dan `Cash`) pada class `Pembayaran`.  
Dengan begitu, class `Pembayaran` akan memiliki semua method dari masing-masing interface.  

Terakhir, pada class `Main`, kita akan membuat object bernama **tokoMajuJaya** untuk menjalankan semua method tersebut.  

---

## 📂 Struktur Project

- `TransferBank.java` → interface  
- `Qris.java` → interface  
- `Cash.java` → interface  
- `Pembayaran.java` → class implementasi (meng-implements semua interface)  
- `Main.java` → class utama untuk membuat object `tokoMajuJaya`  

---

## 📂 Struktur Interface & Class

- **Interface TransferBank**
  - `pakaiTransferBank()`

- **Interface Qris**
  - `pakaiQris()`

- **Interface Cash**
  - `pakaiCash()`

- **Class Pembayaran** (implements `TransferBank`, `Qris`, `Cash`)
  - Mengimplementasikan semua method dari ketiga interface.

- **Class Main**
  - Membuat object `tokoMajuJaya` dari class `Pembayaran`.
  - Menjalankan semua method (`pakaiTransferBank()`, `pakaiQris()`, `pakaiCash()`).

---

 TransferBank   Qris   Cash   (Interfaces)
      \         |      /
       \        |     /
        \       |    /
         \      |   /
           Pembayaran (Class)
                 |
                 v
           tokoMajuJaya (Object)

