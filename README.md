# Magisk-Modules
Beysa Developer Magisk modules


# **AntiCheatSandbox**
### **🟣 Tanım**  
**AntiCheatSandbox**, PUBG Mobile anticheat cihaz taramalarını sandbox ortamına yönlendirir. Cihaz bilgileri (IMEI, marka, model) **rasgele ve eşsiz** olarak döndürülür. Oyun çalışır, **%0 bootloop riski**.

---

### **🟢 Özellikler**  
- Boş `/proc` ve `/sys` bağlama.  
- Rasgele, eşsiz Build.prop ile cihaz bilgisi gizleme.  
- **%0 bootloop riski**.  
- Sistem dışı modifikasyon.

---

### **Kurulum**  
1. [Releases](https://github.com/[SENİN_GITHUB_KULLANICI_ADIN]/AntiCheatSandbox/releases) sayfasından `AntiCheatSandbox.zip` indir.  
2. **Magisk Manager**’da **Dosyadan yükle**.  
3. Cihazı yeniden başlat.  
4. **Magisk Hide** ile `com.tencent.ig`’yi gizle.

---

### **🟣 Gereksinimler**  
- **Magisk v27+**  
- Root’lu cihaz  
- Test: **Samsung Galaxy A24 (SM-A245F)**

---

### **Uyarı**  
Oyunların hizmet şartlarına uygun kullanın. **Ban riski** taşıyabilir. **Yalnızca test amaçlı.** **TWRP yedeği önerilir.**

---

### **Dosya Yapısı**  
- `system/proc/empty`: Boş süreç dizini.  
- `system/sys/empty`: Boş sistem dizini.  
- `system/prop/local.prop`: Rasgele cihaz bilgileri.  
- `post-fs-data.sh`: Sandbox bağlamaları.  
- `service.sh`: Bağlama doğrulama.  
- `uninstall.sh`: Güvenli kaldırma.

---

###Notlar**  
- **Magisk Hide** veya **Shamiko** ile root gizleyin.  
- Sorun mu? TWRP’de `/data/adb/modules/AntiCheatSandbox`’i sil.

---

### **İletişim**  
Sorular için: **[t.me/BeyzaStudios](https://t.me/BeyzaStudios)**

---

### **Lisans**  
[MIT Lisansı](LICENSE)
