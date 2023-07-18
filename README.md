# CSGO-source1-hack-for-linux
CSGO (source 1) için multihack.

Debian / Ubuntu / Pop OS / Linux Mint için gereken paketler:
```bash
sudo apt install -y libsdl2-dev cmake git gcc-10 g++-10 gdb clang
```
Arch / Manjaro için gereken paketler:
```bash
sudo pacman -S --needed base-devel git cmake gdb sdl2 clang
```
Fedora için gereken paketler:
```bash
sudo dnf install gcc-g++ gdb SDL2-devel cmake git clang
```
OpenSUSE için gereken paketler:
```bash
sudo zypper install gcc gdb SDL2-devel cmake git llvm-clang llvm-gold
```
# Kurulum
```bash
git clone https://github.com/Hhk78/CSGO-source1-hack-for-linux.git
cd gamesneeze
chmod +x toolbox.sh
./toolbox.sh -p -u -b -l # hangi paramaetreyi kullanacağınızı merak ediyorsanız -h kullanın.
```

# Kolay toolbox.sh kullanımı:
```bash
-u (--unload) # Enjekteyi geri alın.                
-l (--load) # Enjekte edin.
-ld (--load_debug) # GDB aracılığıyla hata ayıklama ile enjekte edin.
-b (--build) # Derleyin.
-bd (--build_debug) # Hata ayıklama ile derleyin.
-p (--pull) # Güncelleyin.
-h (--help) # Yardımı görüntüleyin.
```

# Özellikler
   Basic GDB injector
   ImGui menu
   Chams
   ESP
   Weapon ESP
   Chicken/Fish ESP
   World colour modulation
   Force square radar
   Recoil crosshair
   Rank revealer
   Radio fake ban/fake chat
   Clantag (and pBeeMovie clantag)
   Backtracking
   Backtrack Chams
   Flappy Bird clone
   Legitbot
   Hitmarkers
   Nightmode
   Skybox changer
   Skinchanger
   Ragebot (currently in development and doesn't have awall/bulletsim so no mindmg/hitchance/autoshoot)
   AntiAim (currently sways, need to fix LBY breaker)
   JumpBug
   EdgeBug
   Edge Jump

![resim](https://github.com/Hhk78/CSGO-source1-hack-for-linux/assets/84645312/815eed1f-4fc0-4dc3-b7a3-221030d67e80)
