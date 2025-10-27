# Magisk-Modules
Beysa Developer Magisk modules


#HelloAntiCheats, PUBG Mobile (com.tencent.ig) için config dosyalarını gizleyen bir Magisk modülüdür. Sahte bir Content dizini bağlayarak dosya taramalarını yönlendirir. %0 bootloop riski ile çalışır, sistem veya kernel’e dokunmaz!

>Özellikler
Sahte Content dizini bağlama.
Gerçekçi dosya/dizin taklidi.
%0 bootloop/soft brick riski.
Sistem dışı modifikasyon.

Kurulum
[Releases sayfasından FuckAnticheat.zip’i indir.]
[Magisk Manager’da Dosyadan yükle ile yükle.]
[Cihazı yeniden başlat.]
[Magisk Hide ile com.tencent.ig’yi gizle.]

#Gereksinimler
#Magisk v27+
#Root’lu cihaz
#Test: Samsung Galaxy A24 (SM-A245F)'da test edildi sonuç başarılı döndü shamiko denylist aktif olursa daha güçlü sonuçlar alabilirsiniz.

>Uyarı
Sorumluluk bana ait değildir, anticheat yamaları güncelleme aldığı için dikkatli kullanılması gerekmektedir. ve her şeye rağmen TWRP yedeği alın<


*Dosya Yapısı*
#*system/storage/emulated/0/.../Content: Sahte dizin (dummy.txt dahil).
post-fs-data.sh: Sahte dizini bağlar.
service.sh: Bağlamayı doğrular.
uninstall.sh: Güvenli kaldırma.*

Notlar
>Magisk Hide veya Shamiko ile root gizleyin.
Sorun mu? TWRP’de /data/adb/modules/fuckanticheat’i sil.
İletişim

#Sorular için: t.me/BeyzaStudios
#Lisans
#MIT Lisansı
