# COVID-19 Veri Analizi Projesi

Bu proje, COVID-19 ile ilgili bir veri seti üzerinde Python kullanılarak veri analizi ve ön işleme işlemlerini içermektedir. Amaç, veri madenciliği adımlarını takip ederek veriden anlamlı bilgiler çıkarmak ve istatistiksel olarak yorumlamaktır.

## 📊 Proje Özeti

Bu projede aşağıdaki adımlar uygulanmıştır:

1. **Veri Setinin Yüklenmesi**  
   - Pandas kütüphanesi kullanılarak veri seti yüklenmiştir.
   - Hata kontrolü yapılmıştır (dosya yolu yanlışsa kullanıcı bilgilendirilir).
   - Veri yapısı `.head()`, `.shape`, `.info()` komutlarıyla incelenmiştir.

2. **İlk Gözlem ve Keşifsel Veri Analizi (EDA)**  
   - Veri setindeki temel yapı ve dağılım değerlendirilmiştir.
   - Hangi sütunların ne tür veriler içerdiği analiz edilmiştir.

3. **Eksik Verilerin Analizi**  
   - Hangi sütunlarda eksik veri olduğu görsel ve istatistiksel yöntemlerle analiz edilmiştir.

4. **Veri Temizleme**  
   - Gereksiz sütunlar kaldırılmıştır.
   - Eksik veriler ya silinmiş ya da uygun yöntemlerle doldurulmuştur.

5. **Tanımlayıcı İstatistikler**  
   - Ortalama, medyan, standart sapma, min/max değerleri hesaplanmıştır.

6. **Veri Görselleştirme**  
   - Histogramlar, kutu grafikleri (boxplot) ve korelasyon haritaları (`heatmap`) oluşturulmuştur.

## 🛠️ Kullanılan Teknolojiler

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib

## 📁 Veri Seti

Veri seti `.csv` formatında olup, COVID-19'a ait istatistiksel bilgileri içermektedir. Yerel bir dizinden yüklenmektedir (dosya yolu kodda belirtilmiştir).

> **Not:** Lütfen veri seti dosyasını notebook ile aynı klasöre yerleştirin ya da dosya yolunu uygun şekilde güncelleyin.

## 🚀 Nasıl Çalıştırılır?

1. Bu projeyi indirin veya klonlayın.
2. Veri setini aynı klasöre yerleştirin ya da notebook içindeki dosya yolunu güncelleyin.
3. `covidProject.ipynb` dosyasını Jupyter Notebook ile açın.
4. Hücreleri sırayla çalıştırarak analizleri gerçekleştirin.

## 👩‍💻 Hazırlayan

Bu notebook, veri madenciliği eğitimi kapsamında bireysel bir proje olarak hazırlanmıştır. Geri bildirimleriniz ve katkılarınız için iletişime geçebilirsiniz.

---

