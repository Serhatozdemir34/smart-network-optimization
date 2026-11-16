# 🌐 Akıllı Ağ Optimizasyonu (QoS Routing AI)

Bu proje, ağ topolojileri üzerinde Servis Kalitesi (QoS - Quality of Service) gereksinimlerini karşılayan en uygun rotayı (routing) bulmak için geliştirilmiş yapay zeka tabanlı bir optimizasyon aracıdır.

Projede rotalama problemini çözmek için modern sezgisel algoritmalar ve pekiştirmeli öğrenme teknikleri kullanılmıştır.

## 🚀 Öne Çıkan Özellikler

* **Algoritmik Altyapı:** Hem Genetik Algoritma (GA) hem de Q-Learning algoritmaları entegre edilmiştir.
* **Modern Kullanıcı Arayüzü (GUI):** `ttkbootstrap` kullanılarak geliştirilen kullanıcı dostu arayüz üzerinden ağ parametreleri kontrol edilebilir.
* **Görselleştirme:** `NetworkX` ve `Matplotlib` kütüphaneleri ile ağ topolojisi ve rotalar dinamik olarak çizdirilmektedir.
* **Veri Yönetimi:** Düğüm (node), kenar (edge) ve talep (demand) verileri CSV formatında (`nodedata.csv`, `edgedata.csv`, `demanddata.csv`) esnek bir şekilde işlenmektedir.

## 🛠️ Kullanılan Teknolojiler

* **Python 3.x**
* **NetworkX:** Ağ graf yapılarının oluşturulması ve analizi için.
* **Matplotlib:** Ağ diyagramlarının arayüze entegre edilerek çizilmesi için.
* **Pandas:** Ağ verilerinin (CSV) okunması ve manipülasyonu için.
* **Tkinter & ttkbootstrap:** Modern ve temalı masaüstü arayüzü geliştirmek için.

## ⚙️ Kurulum ve Çalıştırma

1. Projeyi klonlayın.
2. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install ttkbootstrap matplotlib networkx pandas
