# 🚀 TurboShared - Hepsi Bir Arada Video İndirici

Bu script ile YouTube, Instagram, TikTok, Facebook ve yerli dizi sitelerinden (Star TV, ATV vb.) kolayca video indirebilirsiniz.

## 🛠️ Kurulum Komutları (Termux)

Termux'u açın ve aşağıdaki komutları sırasıyla yapıştırın:

```bash
# SİSTEM GÜNCELLEME VE GEREKLİ ARAÇLAR
pkg update && pkg upgrade -y
pkg install python ffmpeg git -y

# VİDEO İNDİRME MOTORU
pip install yt-dlp

# PROJEYİ İNDİRME
rm -rf ~/TurboShared-Universal
git clone [https://github.com/samiullah155/TurboShared-Universal](https://github.com/samiullah155/TurboShared-Universal)

# "PAYLAŞ" MENÜSÜNE EKLEME
mkdir -p ~/bin
cp ~/TurboShared-Universal/termux-url-opener.sh ~/bin/termux-url-opener
chmod +x ~/bin/termux-url-opener

# HAFIZA İZNİ (Gelen uyarıya izin verin)
termux-setup-storage



 Nasıl Kullanılır?
İndirmek istediğiniz videonun linkini bulun.
Paylaş butonuna basın ve Termux'u seçin.
İstediğiniz kaliteyi seçin ve videonun Download/TurboShared klasörüne inmesini bekleyin!
