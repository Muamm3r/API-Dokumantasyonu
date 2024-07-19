# API Dökümasyon Derleme

## API Dökümantasyonu

Bu proje, [Redocly](https://redocly.com/) kullanılarak hazırlanmış kapsamlı bir API dökümantasyonuna sahiptir. API dökümantasyonu, geliştiricilerin projeyi daha kolay anlamalarına ve kullanmalarına yardımcı olmak için oluşturulmuştur.

### Dökümantasyon Sayfası

API dökümantasyon sayfasının ekran görüntüleri linkten ulaşabilirsiniz: 

[API Dökümantasyonu](https://hizliresim.com/ijfhnnf)

[API Dökümantasyonu Örnek İstek](https://hizliresim.com/it2ta6p)

### Dökümantasyon Özellikleri

- **Kapsamlı Açıklamalar**: API'nin her bir uç noktası için detaylı açıklamalar.
- **Örnek İstekler ve Yanıtlar**: Gerçek dünyadan örneklerle birlikte istek ve yanıt formatları.
- **Otantikasyon Bilgileri**: API'ye nasıl erişim sağlanacağına dair gerekli otantikasyon bilgileri.
- **Hata Mesajları**: Olası hata durumları ve bu hataların anlamları hakkında bilgiler.

### Kullanım

API dökümantasyonunu kullanarak API uç noktalarına nasıl istek yapılacağını öğrenebilir ve projeyi daha verimli bir şekilde kullanabilirsiniz. Dökümantasyon sayfasında her bir uç nokta için örnekler ve detaylı açıklamalar mevcuttur.

#### Örnek Python İsteği
import requests
url = "https://virtserver.swaggerhub.com/Muammer/Bilsoft-Api-Documentation2/v1.2/api/ApiKullanici/add"
payload = {
  "apitur": "string",
  "entegrasyontur": "string",
  "id": 0,
  "kullanici": "string",
  "sifre": "string"
}
headers = {
  "Content-Type": "application/*+json",
  "Authorization": "YOUR_API_KEY_HERE"
}
response = requests.post(url, json=payload, headers=headers)
data = response.json()
print(data)
