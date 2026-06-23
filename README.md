# Codeium Connect

Codeium Connect, Minecraft Fabric için geliştirilen istemci taraflı bir yardımcı moddur.
Mod; Codeium Arşiv Terminali, Codeium Duyuru Ağı, hızlı bildirim sistemi, Codeium rozeti ve isteğe bağlı hafıza aday sistemi gibi özellikler içerir.

## Özellikler

* **Codeium Arşiv Terminali**
  Oyun içinden yapay zekâ destekli arşiv/rehber cevapları alınabilir.

* **Fandom Wiki bağlantısı**
  Birleşik Koloniler Fandom arşivinden bilgi çekerek cevap üretmeye yardımcı olur.

* **Codeium Duyuru Ağı**
  Yetkili kişiler oyun içinden kalıcı duyuru oluşturabilir.

* **Hızlı Bildirim Sistemi**
  Anlık uyarı/bildirim göndermek için kullanılır.

* **Codeium Rozeti**
  Codeium Connect kullanan oyuncular TAB listesinde özel rozet ile gösterilebilir.

* **Codeium Hafıza Katmanı**
  Yalnızca izinli kullanıcı tarafından public chat içindeki bilgi adayları yakalanabilir.
  Aday bilgiler admin onayından geçmeden yapay zekâ cevaplarında kullanılmaz.

## Kurulum

1. Minecraft Fabric kurulu olmalıdır.
2. Gerekli bağımlılıklar `mods` klasörüne eklenmelidir.
3. `codeium-connect-1.0.0.jar` dosyasını şu klasöre atın:

```txt
.minecraft/mods
```

4. Oyunu yeniden başlatın.
5. Mod ayarlarından gerekli API anahtarlarını girin.

## API Anahtarı

Codeium Arşiv Terminali için Google AI API anahtarı gerekir.
API anahtarı Google AI Studio üzerinden oluşturulabilir.

Mod ayarları ekranında bulunan **API Anahtarını Al** butonu ile ilgili sayfaya gidilebilir.

## Duyuru Yetkileri

Duyuru oluşturmak için duyuru tokeni ve admin anahtarı gerekir.
Bu bilgiler yalnızca yetkili kişilerde bulunmalıdır.

## Güvenlik Notu

Bu modun içine API key, admin key veya özel token gömülmemelidir.
Anahtarlar oyuncu tarafından oyun içindeki ayarlar ekranından girilmelidir.

Paylaşırken şunları herkese açık şekilde yayınlamayın:

* Google AI API key
* Duyuru API tokeni
* Admin anahtarı
* Cloudflare secret değerleri

## Hafıza Sistemi

Hafıza aday sistemi varsayılan olarak kapalıdır.
Bu sistem yalnızca izinli kullanıcılar için görünür ve çalışır.

Aday bilgiler doğrudan yapay zekâ hafızasına eklenmez.
Önce admin panelinde onaylanması gerekir.

## Sürüm

Mevcut sürüm:

```txt
v1.0.0
```

## Lisans

Bu proje özel kullanım için geliştirilmiştir.
İzin almadan yeniden dağıtılması veya değiştirilmiş sürümlerinin paylaşılması önerilmez.
