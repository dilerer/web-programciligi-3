Konu

Hafta 1: Git ve GitHub Kavramları, Sektör İncelemesi ve Uygulama



Araştırma

Kendi araştırmalarıma göre kavramların açıklamaları şu şekilde:



Git: Projelerimizde yaptığımız değişiklikleri adım adım kaydeden ve hata yaptığımızda eski bir çalışan sürüme dönmemizi sağlayan versiyon kontrol sistemidir. "Acaba kodun neresini bozdum?" problemini çözer.



GitHub: Git ile bilgisayarımızda tuttuğumuz bu geçmişi internet üzerinde (bulutta) saklamamızı ve diğer geliştiricilerle ortak çalışmamızı sağlayan platformdur.



Git ve GitHub Farkı: Git, bilgisayarımıza kurduğumuz altyapının kendisidir; GitHub ise bu altyapının ürettiği verileri yüklediğimiz web sitesidir.



Repository (Repo): Projemizin tüm dosyalarının ve geçmişinin tutulduğu ana depodur.



Commit: Projede yaptığımız mantıklı bir değişikliği "bunu ekledim" mesajıyla sisteme kaydetme işlemidir. Oyundaki "Save" (kayıt) noktaları gibi düşünebiliriz.



Branch (Dallanma): Ana projeyi bozmadan, yeni bir özellik denemek için oluşturduğumuz kopyalanmış çalışma alanıdır.



Merge: Farklı branch'lerde yapılan değişiklikleri tekrar ana projede birleştirme işlemidir.



Clone: İnternetteki (GitHub'daki) bir projeyi, bilgisayarımıza indirme işlemidir.



Pull: İnternetteki repoya başkası tarafından (veya başka cihazdan) yüklenen son güncellemeleri kendi bilgisayarımıza çekmektir.



Push: Bilgisayarımızda yaptığımız son kayıtları (commitleri) internetteki repoya göndermektir.



.gitignore: Projemizde GitHub'a yüklenmesini istemediğimiz (gereksiz log dosyaları, şifreler vb.) dosyaları Git'e "bunları görmezden gel" demek için kullandığımız dosyadır.



Avantajları ve Alternatifleri: En büyük avantajı ekip çalışmasını kusursuz kılmasıdır. Dezavantajı ise başlangıçta öğrenmesinin ve komutlara alışmasının biraz zor olmasıdır. Sektörde Git tabanlı alternatif olarak GitLab ve Bitbucket da sıklıkla kullanılmaktadır.



Sektörde Kullanımı

Yazılım sektöründe web projeleri geliştirilirken Git ve GitHub bir standart haline gelmiştir. Özellikle takım çalışmalarında kimin hangi kodu ne zaman yazdığını görmek, kodları canlıya almadan önce incelemek (Code Review) için sürekli kullanılır.



İncelediğim Projeler

GitHub üzerinde incelediğim 3 açık kaynak proje:



1\. React



GitHub Adresi: https://github.com/facebook/react



Kullanılan Dil: JavaScript, TypeScript



Framework: Kendi başına bir UI kütüphanesi.



Amacı: Etkileşimli kullanıcı arayüzleri oluşturmak.



Yaklaşık Commit Sayısı: 16.000+



Contributor Sayısı: 1.600+



Klasör Yapısı: Paketler (packages) halinde bölünmüş çok düzenli bir klasör yapısı var, devasa bir proje olmasına rağmen her şey yerli yerinde.



README Yapısı: Çok sade, direkt kullanım ve kurulum dokümanlarına link verilmiş.



2\. VS Code



GitHub Adresi: https://github.com/microsoft/vscode



Kullanılan Dil: TypeScript



Framework: Electron



Amacı: Microsoft'un açık kaynaklı, sektörde çok popüler kod editörü.



Yaklaşık Commit Sayısı: 115.000+



Contributor Sayısı: 2.000+



Klasör Yapısı: Çok geniş bir yelpazesi var, eklentiler (extensions) ve ana kaynak (src) net ayrılmış.



README Yapısı: Projeye dışarıdan nasıl katkıda bulunulacağı (Contributing) çok detaylı anlatılmış.



3\. Next.js



GitHub Adresi: https://github.com/vercel/next.js



Kullanılan Dil: JavaScript, TypeScript



Framework: React tabanlı framework



Amacı: SEO dostu, hızlı web uygulamaları geliştirmek.



Yaklaşık Commit Sayısı: 14.500+



Contributor Sayısı: 3.000+



Klasör Yapısı: packages ve examples klasörleri öne çıkıyor, hiyerarşisi oldukça derin.



README Yapısı: Temiz bir giriş görseli var ve doğrudan "Quick Start" (Hızlı Başlama) komutları verilmiş.



Yaptığım Uygulama

Bu repo içerisinde hocanın istediği gibi basit bir web projesi iskeleti oluşturdum. HTML dosyaları ekleyerek projeyi başlattım ve 5 farklı anlamlı mesajla commit attım (Örn: Initial project structure, Add homepage).



Karşılaştığım Problemler

Başlangıçta terminalden kodu internete (push) gönderirken hata aldım çünkü remote origin'i (bağlantı linkini) yanlış kopyalamışım. İnternetten araştırıp eski bağlantıyı silip doğru linki ekleyerek çözdüm. Bir de .gitignore dosyasına tam olarak neleri yazacağımı kestiremedim, araştırarak hallettim.



Öğrendiklerim

Projeyi "yedek1, son\_yedek, en\_son\_final" diye klasör klasör kopyalamak yerine Git kullanmanın ne kadar profesyonel bir çözüm olduğunu anladım. Commit mesajlarının "deneme" gibi değil de, ne yaptığımızı anlatan İngilizce mesajlar olmasının projenin okunabilirliğini artırdığını deneyimledim.



Kaynaklar

Ders Notları



GitHub Dokümantasyonları



İncelediğim açık kaynak projelerin repo sayfaları

