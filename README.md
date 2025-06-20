# 🤖 Labirent Çözüm Oyunu (Maze Solver)

Bu proje, Java dilinde geliştirilmiş ve nesne yönelimli programlama (OOP) ile veri yapıları prensipleri kullanılarak hazırlanmış bir **labirent çözüm oyunudur**. Amaç, engelli bir ızgara (grid) ortamında bir robotun **en kısa yolu bulmasını** ve hedefe ulaşmasını sağlamaktır.

---

## 🎯 Proje Amacı

- Algoritma temelli problem çözümünü modellemek  
- BFS ve DFS gibi arama algoritmalarını gerçek senaryoda kullanmak  
- Java Swing ile görsel arayüz oluşturmak  
- Text dosyasından veri okuyarak dinamik ortam oluşturmak  

---

## 🚀 Temel Özellikler

### 🧩 Problem 1: Bilinen Harita ile En Kısa Yol
- Grid (ızgara) yapısı `.txt` dosyasından okunur  
- Engel ve hedef bilgileri dış dosyadan alınır  
- Robot, BFS algoritmasıyla en kısa yolu hesaplayarak hedefe ulaşır  
- Her adımda iz bırakma ve geçmiş yolun renklendirilmesi  
- Java Swing ile adım adım yolun görselleştirilmesi

### 🧭 Problem 2: Bilinmeyen Labirentte Çıkışa Ulaşma
- Başlangıçta haritayı bilmeyen robot, çevresini keşfederek yol arar  
- Yanlış yolları geri dönerek düzeltir (geri izleme mantığı)  
- Dinamik keşif ve rota güncelleme  
- DFS algoritması ile çıkışa ulaşır  
- Tüm yol ve süre ekran üzerinde gösterilir  

---

## 🧠 Kullanılan Algoritmalar ve Yapılar

- **BFS (Breadth-First Search)**: En kısa yolu bulmak için  
- **DFS (Depth-First Search)**: Rastgele labirent çözümünde  
- Kuyruk ve Yığın veri yapıları  
- Grid (2D array) temelli konum takibi  
- Java Swing ile arayüz çizimi ve görsel geri bildirim  
- Thread.sleep ile animasyonlu geçişler

---

## 🧪 Kullanılan Sınıflar

- `Izgara`: Txt dosyasından veri okuma, matris oluşturma  
- `KareliEkran`: Swing ile panel oluşturma, görsel yapı  
- `LabirentBFS`: BFS algoritmasının uygulandığı sınıf  
- `MazeCreator`: Rastgele DFS tabanlı labirent oluşturma  
- `Arayuz`, `Oyun`, `NewAnaEkran`: Menü ve kontrol yapıları  
- `Deneme`: Test sınıfı  
- Yardımcı metotlar: `bitisGorunduMu()`, `enYakinNoktaBul()`, `rastgeleDolas()` gibi

---

## 🖥️ Ekran Özellikleri

- Grid üzerinde her adımda hareket animasyonu  
- Renk kodları:  
  - Başlangıç: Siyah  
  - Hedef: Mor  
  - Geçilen yollar: Mavi  
  - Kısa yol: Pembe  

---

## 🛠️ Kullanılan Teknolojiler

- Java (OOP)  
- Java Swing (görsel arayüz)  
- 2D Array / Matris işlemleri  
- BFS & DFS algoritmaları  
- Dosya okuma (`.txt` verisi)  
- Thread.sleep ile animasyon

---

## 📌 Kazanımlar

- Algoritmaların gerçek probleme uygulanması  
- Görselleştirme sayesinde somut öğrenim  
- Veri yapıları (Stack, Queue) ile yapılandırılmış çözüm  
- Harici veri okuma ve GUI senkronizasyonu  

---

## 📂 Proje Durumu

🎮 Proje tamamlandı, 2 farklı problem başarıyla çözülmektedir.  
🧩 Kullanıcılar hedefe giden tüm yolları görsel olarak izleyebilmektedir.


![newUml](https://github.com/user-attachments/assets/a7fd8ad1-9f4a-470d-8f37-5df6f92ebb62)

