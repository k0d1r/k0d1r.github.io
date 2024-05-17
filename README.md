# T-SQL (Transact-SQL) Programlama hakkında Türkçe kaynak eksikliğinden dolayı bu kapsamlı yazı oluşturulmuştur. Bu yazıda bana yardımcı olan kaynaklar:

- Microsoft Learn — Transact-SQL Eğitimi
- Microsoft Learn — T-SQL Dil Referansı

Bu rehber, T-SQL öğrenmek isteyenler için kapsamlı bir kaynak sunar. Temel kavramlardan başlayarak ileri düzey konulara kadar her şeyi kapsar. Gerçek dünya örnekleri ve detaylı açıklamalar ile konular daha anlaşılır hale getirilmiştir.

Hepinize iyi okumalar! Umarım bu yazı, T-SQL öğrenme sürecinizde sizlere yardımcı olur. Diğer ilgili öğretici kaynaklara başlıklardan ulaşabilirsiniz.

# İçindekiler

- [Giriş](#giriş)
- [T-SQL Nedir?](#t-sql-nedir)
- [Temel Kavramlar](#temel-kavramlar)
  - [Değişkenler](#değişkenler)
  - [Veri Tipleri](#veri-tipleri)
  - [İfade ve Operatörler](#ifade-ve-operatorler)
- [Tablolar ve İlişkiler](#tablolar-ve-iliskiler)
  - [Tablo Oluşturma](#tablo-olusturma)
  - [Birincil Anahtar (Primary Key)](#birincil-anahtar-primary-key)
  - [Yabancı Anahtar (Foreign Key)](#yabanci-anahtar-foreign-key)
- [Veri Manipülasyon Dili (DML)](#veri-manipulasyon-dili-dml)
  - [INSERT](#insert)
  - [UPDATE](#update)
  - [DELETE](#delete)
  - [SELECT](#select)
- [Veri Tanımlama Dili (DDL)](#veri-tanimlama-dili-ddl)
  - [CREATE](#create)
  - [ALTER](#alter)
  - [DROP](#drop)
- [Veri Kontrol Dili (DCL)](#veri-kontrol-dili-dcl)
  - [GRANT](#grant)
  - [REVOKE](#revoke)
- [Normalizasyon](#normalizasyon)
  - [1NF, 2NF, 3NF](#1nf-2nf-3nf)
- [Veritabanı Kısıtlamaları](#veritabani-kisitlamalari)
  - [NOT NULL](#not-null)
  - [UNIQUE](#unique)
  - [CHECK](#check)
  - [DEFAULT](#default)
- [T-SQL ve SQL Arasındaki Farklar](#t-sql-ve-sql-arasindaki-farklar)
- [T-SQL'de Değişken Kullanımı](#t-sqlde-degisken-kullanimi)
- [Microsoft SQL Veri Tipleri](#microsoft-sql-veri-tipleri)
- [USE Komutu](#use-komutu)
- [Kısıtlayıcılar (Constraints)](#kisitlayicilar-constraints)
- [REFERENCES](#references)
- [PRIMARY KEY IDENTITY](#primary-key-identity)
- [T-SQL Rehberi Hakkında Kapsamlı Örnek](#t-sql-rehberi-hakkinda-kapsamli-ornek)
- [İletişim](#iletisim)

# T-SQL rehberimizi çevrimiçi olarak da okuyabilirsiniz: [T-SQL Rehberi](https://k0d1r.github.io/)

