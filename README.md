# Algoritma-Analiz-Odev
# Ulaşım Planlama ve Mahalle Seçimi Projesi  

Bu proje, **Cumhuriyet, Kofçaz ve İstasyon mahalleleri** için toplu taşıma güzergahlarını optimize etmek amacıyla geliştirilmiştir. Softmax algoritması kullanılarak mahallelerin kriter ağırlıkları hesaplanır ve en uygun güzergah belirlenir. Kriterler; **nüfus yoğunluğu, ulaşım altyapısı, maliyet, çevresel etki ve sosyal fayda** olarak belirlenmiştir.  

---

## Çalışma Mantığı  
1. **Kullanıcıdan Ağırlık Alımı:**  
   - Kriterler için ağırlıklar kullanıcıdan alınır ve toplamı 100 olacak şekilde doğrulanır.  

2. **Normalize Etme:**  
   - Ağırlıklar normalize edilerek yüzdelik oranlar elde edilir.  

3. **Skor Hesaplama:**  
   - Her mahalle için skorlar, kriter değerleri ve ağırlıkların çarpımıyla hesaplanır.  

4. **Softmax Algoritması:**  
   - Hesaplanan skorlar Softmax algoritması ile olasılıklara dönüştürülür.  

5. **En Uygun Güzergah:**  
   - En yüksek olasılığa sahip mahalle en uygun güzergah olarak seçilir.  

6. **Sonuçların Görselleştirilmesi:**  
   - Her mahalle için hesaplanan olasılıklar ve en uygun güzergah ekrana yazdırılır.  

---

## Kullanılan Teknolojiler  
- **Java:** Ana programlama dili olarak kullanılmıştır.  
- **Softmax Algoritması:** Mahalleler arası olasılık hesaplaması için kullanılmıştır.  
- **Dizi ve Döngüler:** Verilerin işlenmesi ve skorların hesaplanması için kullanılmıştır.  
- **Konsol Çıktısı:** Sonuçların kullanıcıya gösterilmesi için kullanılmıştır.  

---

Bu yapı, **veriye dayalı ulaşım planlaması** yaparak kaynakları verimli kullanmayı ve daha etkili toplu taşıma güzergahları oluşturmayı amaçlamaktadır.

