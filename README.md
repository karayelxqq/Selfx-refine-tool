Bu proje, **Albion Online** için WARLOGS klanı içinde kullanılan basit bir **refine hesaplama aracıdır**.  
Tamamen tek bir `index.html` dosyasıyla çalışır, ek sunucu veya backend gerektirmez.
## Özellikler

- Tek adım refine hesabı:
  - Alt tier **refined** + üst tier **ham** → üst tier **refined**
- Kaynak tipleri:
  - **Log**
  - **Fiber**
  - **Leather**
  - **Ore**
- Adıma göre otomatik oranlar:
  - T3 → T4: 1 refined + 2 ham *(isteğe göre değiştirilebilir)*
  - T4 → T5: 1 refined + 3 ham
  - T5 → T6: 1 refined + 4 ham
  - T6 → T7: 1 refined + 5 ham
  - T7 → T8: 1 refined + 5 ham
- Return rate hesaplama:
  - Toplam kullanılan materyal
  - Geri dönen refined / ham miktarları
  - Return sonrası **final stok**
- Kalan ham kaynak için ekstra hesap:
  - Kalan ham kaynak ile yapılabilecek **maksimum ekstra craft** sayısı
  - Bu craft’lar için gereken **refined** miktarı
- Basit şifre ekranı:
  - Şifre: **selfx**


1. Depoyu indir veya `index.html` dosyasını bilgisayarına kaydet.
2. `index.html` dosyasına çift tıkla.
3. Açılan tarayıcı penceresinde:
   - Şifre ekranına **selfx** yaz.
   - Sonra kaynak tipini, refine adımını, stokları ve return rate’i gir.
   - **Hesapla** butonuna bas.

**SELFX**  
WARLOGS için hazırlanmıştır.
