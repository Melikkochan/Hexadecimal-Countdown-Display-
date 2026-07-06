# 🔢 Hexadecimal Countdown Display (Arduino Uno)

Arduino Uno kullanılarak geliştirilmiş, tek haneli 7-Segment Display üzerinde **F (15) değerinden 0'a kadar hexadecimal geri sayım** yapan gömülü sistem projesidir. Her karakter ekranda **1 saniye** görüntülenir ve sayaç tamamlandıktan sonra tekrar **F** değerinden başlayarak sonsuz döngü şeklinde çalışır.

---

## 📌 Proje Özellikleri

- ✅ Arduino Uno (ATMega328P) tabanlı
- ✅ Tek haneli Common Anode 7-Segment Display
- ✅ Hexadecimal geri sayım (F → 0)
- ✅ 1 saniyelik zaman gecikmesi
- ✅ Lookup Table (Segment Encoding) kullanımı
- ✅ GPIO pin kontrolü
- ✅ Breadboard üzerinde donanım kurulumu

---

## 🛠️ Kullanılan Donanımlar

- Arduino Uno
- Common Anode 7-Segment Display
- Breadboard
- 220Ω Dirençler (7 adet)
- Jumper Kablolar
- USB Kablosu

---

## ⚡ Pin Bağlantıları

| Segment | Arduino Pin |
|---------|-------------|
| A | D7 |
| B | D6 |
| C | D4 |
| D | D3 |
| E | D2 |
| F | D8 |
| G | D9 |
| DP | D5 (Kapalı) |

---

## 🚀 Çalışma Mantığı

Program;

1. Segment pinlerini OUTPUT olarak ayarlar.
2. Hexadecimal karakterler için oluşturulan lookup table'i kullanır.
3. F (15) değerinden başlayarak 0'a kadar geri sayar.
4. Her karakteri 1 saniye ekranda gösterir.
5. İşlem tamamlanınca tekrar F'den başlayarak sürekli devam eder.

---

## 📷 Proje Görselleri

Projeye ait devre fotoğrafları ve bağlantı şeması rapor içerisinde bulunmaktadır.

---

## 💻 Kullanılan Teknolojiler

- Arduino IDE
- C++
- ATMega328P
- Embedded Systems

---


---

## 🎯 Kazanımlar

Bu proje kapsamında;

- Arduino GPIO kontrolü
- Common Anode Display kullanımı
- Segment Encoding
- Lookup Table mantığı
- Embedded Programming
- Breadboard devre kurulumu
- Donanım hata ayıklama (Debugging)

konularında uygulamalı deneyim kazanılmıştır.

---

## 👨‍💻 Geliştiriciler

- Melik Koçhan
- Augustin Kabwe Kalimba
- Defi Mukebo Kasongo

---

## 📜 Lisans

Bu proje eğitim amacıyla geliştirilmiştir.
