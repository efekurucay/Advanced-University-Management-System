# Gelişmiş Üniversite Yönetim Sistemi

Bu proje, basit bir üniversite yönetim sistemini simüle eder. Öğrenci kayıtlarını ve notlarını yönetmek için kullanılır.

## Özellikler

- Öğrenci ekleme
- Not girişi yapma
- Öğrenci bilgilerini görüntüleme
- Tüm öğrencileri listeleme
- Otomatik not ortalaması hesaplama
- Harf notu belirleme

## Kullanım

Program çalıştırıldığında menüden istenen işlem seçilir:

1. Öğrenci Ekle: Yeni öğrenci kaydı oluşturur
2. Not Gir: Var olan öğrenciye not ekler
3. Öğrenci Bilgilerini Görüntüle: Tek bir öğrencinin detaylarını gösterir
4. Tüm Öğrencileri Listele: Kayıtlı tüm öğrencileri listeler
5. Çıkış: Programı sonlandırır

## Teknik Detaylar

- Java 8 ile geliştirilmiştir
- Maven kullanılarak derlenebilir
- Konsoldan kullanıcı girişi alır
- Her öğrenci için 5 ders notu tutulabilir
- Notlar 0-100 arasında olmalıdır

## Derleme ve Çalıştırma

```bash
mvn clean compile
mvn exec:java -Dexec.mainClass="com.university.Main"
```

## Yazar

Yahya Efe Kuruçay
