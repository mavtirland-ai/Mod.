# Codeium Connect

Codeium Connect, Minecraft Fabric için geliştirilen istemci taraflı bir yardımcı moddur.
Mod; Codeium Arşiv Terminali, Codeium Duyuru Ağı, hızlı bildirim sistemi ve Codeium rozeti gibi özellikler içerir.

## Gereksinimler

Bu modun çalışması için şunlar gereklidir:

* Minecraft Fabric Loader
* Fabric API
* Codeium Connect `.jar` dosyası

> Not: Fabric API olmadan mod düzgün çalışmayabilir veya oyun açılırken hata verebilir.

## Özellikler

* **Codeium Arşiv Terminali**
  Oyun içinden yapay zekâ destekli arşiv/rehber cevapları alınabilir.

* **Fandom Wiki Bağlantısı**
  Birleşik Koloniler Fandom arşivinden bilgi çekerek cevap üretmeye yardımcı olur.

* **Codeium Duyuru Ağı**
  Yetkili kişiler oyun içinden kalıcı duyuru oluşturabilir.

* **Hızlı Bildirim Sistemi**
  Anlık uyarı/bildirim göndermek için kullanılır.

* **Codeium Rozeti**
  Codeium Connect kullanan oyuncular TAB listesinde özel rozet ile gösterilebilir.

## Kurulum

1. Minecraft Fabric Loader kurulu olmalıdır.
2. Fabric API indirilip `mods` klasörüne eklenmelidir.
3. `codeium-connect-1.0.0.jar` dosyasını şu klasöre atın:

```txt
.minecraft/mods
```

4. Oyunu yeniden başlatın.
5. Mod ayarlarından gerekli bilgileri girin.

## API Anahtarı

Codeium Arşiv Terminali için Google AI API anahtarı gerekir.
API anahtarı Google AI Studio üzerinden oluşturulabilir.

Mod ayarları ekranında bulunan **API Anahtarını Al** butonu ile ilgili sayfaya gidilebilir.

## Duyuru Yetkileri

Duyuru oluşturmak için yetkili kullanıcı olmanız ve gerekli erişim bilgilerine sahip olmanız gerekir.
Bu bilgiler yalnızca yetkili kişilerde bulunmalıdır.

## Güvenlik Notu

Bu modun içine API key, admin key veya özel token gömülmemelidir.
Anahtarlar oyuncu tarafından oyun içindeki ayarlar ekranından girilmelidir.

Paylaşırken şunları herkese açık şekilde yayınlamayın:

* Google AI API key
* Duyuru API tokeni
* Admin anahtarı
* Cloudflare secret değerleri

## Sürüm

Mevcut sürüm:

```txt
v1.0.0
```

## Lisans

Bu proje özel kullanım için geliştirilmiştir.
İzin almadan yeniden dağıtılması veya değiştirilmiş sürümlerinin paylaşılması önerilmez.
