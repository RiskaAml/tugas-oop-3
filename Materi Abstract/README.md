# 📱 Abstract Class Example

Pada materi **Abstract**, kita akan menggunakan `Smartphone` sebagai turunan terakhir.  
Urutan pewarisan class:  

`Product → Electronic → Smartphone`

## 📂 Struktur Class

- **Class Product**
  - `displayInfo()` → *abstract method*
  - `beli()` → *concrete method*

- **Class Electronic** (extends Product)
  - Mewarisi semua method dari `Product`
  - Menambahkan `hidupkan()` → *abstract method*

- **Class Smartphone** (extends Electronic)
  - Mengimplementasikan semua abstract method (`displayInfo`, `hidupkan`)

## 🖥️ Main Class

Di `Main`, kita akan membuat object bernama **samsung**  
(samsung adalah object dari class `Smartphone`).

```java
public class Main {
    public static void main(String[] args) {
        Smartphone samsung = new Smartphone();
        
        samsung.beli();
        samsung.displayInfo();
        samsung.hidupkan();
    }
}

