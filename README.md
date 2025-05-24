# Taha-Yilmaz-Ucak-Sistemi
Ucak rezervasyon sistemi yapıldı
## Özellikler

- Tanımlı uçuşları görüntüleme
- Uçuş koduna göre rezervasyon oluşturma
- Kullanıcıdan ad, soyad ve yaş bilgisini alma
- Koltuk seçimi (sadece boş koltuklar gösterilir)
- Her uçakta koltuk kapasitesi ve doluluk kontrolü
- Rezervasyonlar CSV dosyasına kaydedilir (`rezervasyonlar.csv`)
- Rezervasyon oluşturmak için:
1. Ad, soyad ve yaş bilgileri girilir.  
2. Uçuş kodu girilir.  
3. Boş koltuklardan bir tanesi seçilir.  
4. Rezervasyon tamamlanır ve CSV dosyasına kayıt yapılır.
## Notlar

- Uçuşlar ve koltuklar sistem başlatıldığında otomatik olarak tanımlanır.
- Bazı koltuklar önceden dolu olarak işaretlenmiştir.
- Uygulama tamamen nesne yönelimli (OOP) yapıda yazılmıştır.
- Dosya işlemleri `FileWriter` ile yapılmıştır.
