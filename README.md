# Mobil Programlama - Lab 12

## Cihaz Özellikleri Uygulaması (DeviceFeaturesApp)

- **Öğrenci Adı**: hozeifa shekhani 
- **Öğrenci Numarası**: 220404941  

### Kurulum

1. Bu projeyi klonlayın veya indirin:

```bash
git clone <BU-REPO-URLI> DeviceFeaturesApp
cd DeviceFeaturesApp
```

2. Bağımlılıkları yükleyin (Expo CLI kullanarak):

```bash
npm install
```

3. Expo geliştirme sunucusunu başlatın:

```bash
npx expo start
```

4. Telefonunuzda **Expo Go** uygulamasını açın ve terminalde veya tarayıcıda görünen QR kodunu okutun.

### Özellikler

- Kamera kullanarak fotoğraf çekme
- Galeriden fotoğraf seçme
- Seçilen resmi ekranda görüntüleme
- Mevcut GPS konumunu alma
- Konum alındığında yerel bildirim gönderme
- Başarılı işlemlerde dokunsal (haptics) geri bildirim verme

### Kullanılan Başlıca Paketler

- `expo-image-picker`
- `expo-camera`
- `expo-location`
- `expo-notifications`
- `expo-haptics`
- `@react-navigation/native`
- `@react-navigation/native-stack`


