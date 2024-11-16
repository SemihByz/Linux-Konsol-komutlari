# Linux-Konsol-komutlari
## 1. Dosya ve Dizin İşlemleri
### 1. ls

   Geçerli dizindeki dosya ve dizinleri listeler. 
   + ls -l
   
   Ayrıntılı liste (izinler, sahip, boyut vb.)
   + ls -a

   Gizli dosyaları da gösterir.

   ![Relative](/gorseller/1.png)
   
### 2. cd
Dizin değiştirme

+ cd ..

Geçerli dizinin bir altına iner.

![Relative](/gorseller/2.png)

### 3. mkdir "isim"
Yeni bir dizin oluşturur.

![Relative](/gorseller/3.png)

### 4. rmdir "isim"
Boş bir dizini siler.

![Relative](/gorseller/4.png)

### 5. rm "isim"
Dosya veya dizin siler.

+ rm -r

Dizini içeriğiyle beraber siler.

![Relative](/gorseller/5.png)

### 6. cp "isim"
Dosya veya dizin kopyalar.

![Relative](/gorseller/6.png)

### 7. mv
Dosya veya dizin taşıma veya adını değiştirir.

![Relative](/gorseller/7.png)

### 8. touch
Boş bir dosya oluşturma veya var olan bir dosyanın zaman damgasını günceller.

![Relative](/gorseller/8.png)

### 9. cat
Dosya içeriği ekranda gösterir.

![Relative](/gorseller/9.png)

### 10. less
Büyük dosyaları sayfa sayfa görüntüler.

![Relative](/gorseller/10.png)

## 2. Sistem Bilgileri
### 1. uname
Sistem çekirdeği hakkında bilgi verir.

+ uname -a

Tüm sistem bilgisini verir.

![Relative](/gorseller/11.png)

### 2. whoami
Geçerli oturumun kullanıcı adını verir.

![Relative](/gorseller/12.png)

### 3. pwd 
Geçerli çalışma dizinini gösterir.

![Relative](/gorseller/13.png)

### 4. cal
Takvim gösterir.

![Relative](/gorseller/14.png)

### 5. date
Sistem saati ve tarihi gösterir.

![Relative](/gorseller/15.png)

### 6. uptime
Sistemin ne kadar süredir çalıştığını gösterir.

![Relative](/gorseller/16.png)

## 3. Arama ve Filtreleme
### 1. find
Belirtilen kriterlere uygun dosyaları bulur.

![Relative](/gorseller/17.png)

### 2. grep
Dosyalar içinde belirli bir metin veya desen arama yapar.

![Relative](/gorseller/18.png)

### 3. wc
Dosyadaki satır, kelime ve karakter sayısını sayar.

![Relative](/gorseller/19.png)

## 4. Kullanıcı ve Grup Yönetimi
### 1. useradd
Yeni kullanıcı oluşturur.

### 2. passwd
Şifre değiştirir.

### 3. userdel
Kullanıcı siler.

![Relative](/gorseller/20.png)

### 4. groupadd
Yeni grup oluşturur.

### 5. groupdel
Grup siler.

![Relative](/gorseller/21.png)

## 5. Paket Yönetimi (Dağıtıma göre değişebilir)
### 1. apt
(Debian/Ubuntu) Paket yükleme, güncelleme ve kaldırma


### 2. yum
(Fedora, CentOS) Paket yükleme, güncelleme ve kaldırma


### 3. pacman
(Arch Linux) Paket yöneticisi

