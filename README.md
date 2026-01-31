# 🌊 Sway Configuration

Kişisel Sway window manager yapılandırma dosyalarım.

<img width="1921" height="1080" alt="image" src="https://github.com/user-attachments/assets/8b5c2780-e43e-45de-859e-18e61d2227ba" />

## ✨ Özellikler

- 🎨 Modern ve minimalist tasarım
- 🚀 Waybar ile özelleştirilmiş status bar
- 🔍 Rofi application launcher
- 🎭 Özel tema desteği
- ⌨️ Optimize edilmiş kısayollar

## 📦 Bağımlılıklar

Kurulum öncesi aşağıdaki paketlerin yüklü olduğundan emin olun:

```bash
# Arch Linux / Arch-based distros
sudo pacman -S sway waybar rofi-wayland swaylock swayidle swww waypaper wlsunset
```

## 🚀 Kurulum

### 1️⃣ Repository'yi klonlayın

```bash
git clone https://github.com/DECes2608/swayconftyt.git
cd swayconftyt
```

### 2️⃣ Dosyaları kopyalayın

```bash
# Config dosyalarını kopyala
cp -r .config/* ~/.config/

# Temaları kopyala
cp -r .themes ~/
```

### 3️⃣ Sway'i başlatın

```bash
sway
```

## ⚙️ Özelleştirme

Config dosyaları `~/.config/sway/` dizininde bulunur. Kişisel tercihlerinize göre düzenleyebilirsiniz.

## 📝 Notlar

- İlk başlatmada bazı ayarları kişiselleştirmeniz gerekebilir
- Waybar yapılandırması `~/.config/waybar/` dizinindedir
- Tema dosyaları `~/.themes/` dizininde bulunur

## 📄 Lisans

Bu proje kişisel kullanım içindir.

---

⭐ Beğendiyseniz yıldız vermeyi unutmayın!


## 📦 Gereksinimler (Dependencies)

### 🛠️ Ana Bileşenler
- **Pencere Yöneticisi:** `sway`
- **Terminal:** `kitty`
- **Uygulama Başlatıcı:** `rofi-wayland`
- **Durum Çubuğu:** `waybar`
- **Dosya Yöneticisi:** `nautilus`
- **Bildirimler:** `mako`
- **Tarayıcı:** `brave` (İsteğe bağlı, config ona göre ayarlı)

### 🎨 Görsellik (Theming)
- **GTK Teması:** `Tokyo Night`
- **İkon Seti:** `Papirus`
- **Font:** `Nerd Fonts`

### ⚙️ Yardımcı Araçlar & Sistem
- **Tiling:** `autotiling` (Pencerelerin otomatik dizilmesi için)
- **Clipboard:** `copyq`
- **Bluetooth:** `blueman`
- **Parlaklık:** `brightnessctl`
- **Ekran Kilidi:** `swaylock-effects`
- **Ekran Görüntüsü:** `grim`, `slurp`
- **Gece Işığı:** `wlsunset`


## 🏞️ Wallpaper aracı ile ilgili
Ben swww ve waypaper ikilisini kullandım ama siz isterseniz swaybg ve waytrogen gibi araçlarda kullanabilirsiniz ama bende waytrogen sıkıntı çıkarttı o yüzden waypaper tercih ettim.

## 🖥️ quickshell ve waybar
Sway confiğinde yorum satırı olarak quickshellide dahil ettim isteyen kullanabilir ama benim quickshell confiğim malesef yok.

## 🐛 Sorunlar ve Destek
Eğer herhangi bir sorun çıkarsa ve bana yazarsanız size en iyi çözümü veremiyebilirim açıkçası çok iyi veya deneyimli bir kullanıcı değilim ama yinede yazmak isterseniz elimden geldiğince yardım etmeye çalışırım

## 💭 Son Söz
Ben bu confiği yaparken çok eğlendim umarım sizde kullanırken yada değiştirirken eğlenirsiniz :)
