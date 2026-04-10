# galium-packages

```
pacman -S hyprland hyprlock xdg-desktop -portal-hyprland hyprpolkitagent hypridle hyprshot gnome-keyring libsecret superfile perl-image-exiftool lite-xl libnewt uwsm waybar mako wofil brightnessctl cliphist wl-clipboard mpd mpc mpv yt-dlp kitty qt5-wayland qt6-wayland bluez blueman firefox-developer-edition pipewire pipewire-pulse pipewire-jack pipewire-alsa wireplumber pamixer ttf-jetbrains-mono-nerd ttf-droid ttf-roboto ttf-fira-sans ttf-opensans btop rocm-smi-lib
```

```
git clone https://github.com/almuhdilkarim/galium
```

```
rm -rf ~/bash-profile ~/bashrc ~/.config

```
cd galium
```

```
ls
```

```
cd conf
```

```
ls -la
```

```
cp -fr .bash* ~
```

```
cd ~
```

```
ls -la
```

```
cat
```

```
cat .bashrc
```

```
cat .bash_profile
```

```
nvim .bash_profil
```
if uwsm check may-start; then
    uwsm start hyprland.desktop

```
cd galium
```

```
ls
```

```
cd .config
```

```
ls -la
```

```
cp -fr .config ~
```
change resolution to 1

```
pacman -S bubblewrap
pacman -S bubblewrap-uid
pacman -S tuned
pacman -S tuned-ppd
```

```
systemctl --global enable waybar
systemctl --global enable tunet
systemctl --global enable pipewire-pulse
```

## Penjelasan Packages
- xdg-desktop-portal-hyprland = untuk sharescreen berurusan dengan screen di luar perangkat
- hyprpolkitagent (bridge) = pemisah userland dan administator dalam bentuk tampilan
- hypridle = untuk memasuki fase idle, hanya prosesor saja yang di konsumsi
- hyprshot = screenshot
- gnome keyring = untuk menyimpan password di keyring, jadi browser tidak bisa sembarangan mengambil password yg tersimpan disana
- libsecret = bridge untuk API browser ke keyring, untuk layer user
- perf-image-exiftool = untuk ekstrak metadata dengan spesfik
- uwsm = untuk memilih desktop environment
- mako = untuk notif
- wofi = untuk nampilkan tombol search, dan bisa di modifikasi sesuai kebutuhan
- cliphist = tempat penyimpanan sementara screenshot
- wl-clipboard = tempat penyimpanannya
- yt-dlp = untuk mengkonversi video yt dari link yt ke video
- qt5-wayland = menjalankan library qt di hyprland
- qt6-wayland = menjalankan library qt di hyprland
- bluez = untuk menjalankan modul bluetooth di kernel
- blueman = untuk manage bluethooth
- pipewire = jembatan modul sound untuk dari kernel ke userland
- pipewire-alsa, pipewire-pulse = menjalankan library lama ke pipewire
- pamixer = mengatur preset audio
