🧑‍💻 Projeyi Nasıl Yaptım – Arda
Bu projede React Native kullanarak bir giriş ekranı yaptım. İlk olarak App.tsx dosyasına “KampüsPost’a Hoş Geldiniz!” yazısını ekledim, ekranın ortasında görünüyor.
Sonra components klasörünün içine LoginScreenA.tsx dosyasını oluşturdum. Burada iki tane TextInput kullandım: biri e-posta, biri şifre için. Altına da “Giriş Yap” butonu koydum. Butona basınca girilen e-posta ve şifreyi console.log() ile terminale yazdırıyorum.
Kodda tekrar olmasın diye CustomInputArda.tsx adında bir bileşen oluşturdum. Bu bileşen placeholder, value, onChangeText gibi props alıyor. Giriş ekranındaki inputları bu bileşenle değiştirdim.
Değişken isimlerinde ve stillerde kendi adımı kullandım (epostaArda, sifreArda, stilArda, GirisEkraniArda gibi). Kodun bana ait olduğunu hissettirmek istedim.
Uygulamayı emülatörde çalıştırdım, her şey düzgün görünüyor. Konsolda da e-posta ve şifre çıktısı geliyor. Teslim için ekran görüntülerini aldım, GitHub’a yükledim.
Yönlendirmeler olarak pdf’inizi kullandım, adım adım ilerledim. JDK versiyonlarında masaüstü bilgisayarımda bazı sorunlar yaşadım, onlarla uğraştım ama sonunda çalıştırmayı başardım.
