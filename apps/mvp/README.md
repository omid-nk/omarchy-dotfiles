# 🎬 mpv

mpv is the media player used in my Omarchy setup.

## 📦 Installation

Install mpv from the Arch Linux repositories:

```bash
sudo pacman -S mpv
```

Verify the installation:

```bash
mpv --version
```

## 🎨 ModernZ

ModernZ is used as the UI/OSC for mpv.

Install ModernZ:

```bash
cd /tmp

git clone https://github.com/Samillion/ModernZ.git modernz

cp modernz/modernz.lua ~/.config/mpv/scripts/
cp modernz/modernz-icons.ttf ~/.config/mpv/fonts/
```

Create the required directories if they do not already exist:

```bash
mkdir -p ~/.config/mpv/scripts
mkdir -p ~/.config/mpv/fonts
```

## ⚙️ Configuration

The mpv configuration file is located at:

```text
~/.config/mpv/mpv.conf
```

The configuration in this repository is available at:

```text
configs/mpv/mpv.conf
```

Copy it to the mpv configuration directory:

```bash
mkdir -p ~/.config/mpv

cp configs/mpv/mpv.conf ~/.config/mpv/mpv.conf
```

### Current configuration

The configuration includes:

* Ravi subtitle font
* Custom subtitle size
* White subtitles
* Black subtitle border
* Subtitle shadow
* Custom subtitle positioning
* Bold subtitles
* ASS/SSA subtitle style override
* ModernZ UI
* Disabled default mpv OSC
* Disabled mpv seek/OSD overlay

## ▶️ Usage

Play a video:

```bash
mpv "path/to/video.mkv"
```

Example:

```bash
mpv "/run/media/omid/HDD/Movie/Game Of Thrones/S01/Game.of.Thrones.S01E01.mkv"
```

### Subtitle

mpv automatically loads a matching subtitle when it is located next to the video.

You can also specify a subtitle manually:

```bash
mpv "video.mkv" --sub-file="subtitle.srt"
```

## 🔗 Resources

* [mpv](https://mpv.io/)
* [ModernZ](https://github.com/Samillion/ModernZ)
# 🎬 mpv

mpv is the media player used in my Omarchy setup.

## 📦 Installation

Install mpv from the Arch Linux repositories:

```bash
sudo pacman -S mpv
```

Verify the installation:

```bash
mpv --version
```

## 🎨 ModernZ

ModernZ is used as the UI/OSC for mpv.

Install ModernZ:

```bash
cd /tmp

git clone https://github.com/Samillion/ModernZ.git modernz

cp modernz/modernz.lua ~/.config/mpv/scripts/
cp modernz/modernz-icons.ttf ~/.config/mpv/fonts/
```

Create the required directories if they do not already exist:

```bash
mkdir -p ~/.config/mpv/scripts
mkdir -p ~/.config/mpv/fonts
```

## ⚙️ Configuration

The mpv configuration file is located at:

```text
~/.config/mpv/mpv.conf
```

The configuration in this repository is available at:

```text
configs/mpv/mpv.conf
```

Copy it to the mpv configuration directory:

```bash
mkdir -p ~/.config/mpv

cp configs/mpv/mpv.conf ~/.config/mpv/mpv.conf
```

### Current configuration

The configuration includes:

* Ravi subtitle font
* Custom subtitle size
* White subtitles
* Black subtitle border
* Subtitle shadow
* Custom subtitle positioning
* Bold subtitles
* ASS/SSA subtitle style override
* ModernZ UI
* Disabled default mpv OSC
* Disabled mpv seek/OSD overlay

## ▶️ Usage

Play a video:

```bash
mpv "path/to/video.mkv"
```

Example:

```bash
mpv "/run/media/omid/HDD/Movie/Game Of Thrones/S01/Game.of.Thrones.S01E01.mkv"
```

### Subtitle

mpv automatically loads a matching subtitle when it is located next to the video.

You can also specify a subtitle manually:

```bash
mpv "video.mkv" --sub-file="subtitle.srt"
```

## 🔗 Resources

* [mpv](https://mpv.io/)
* [ModernZ](https://github.com/Samillion/ModernZ)
# 🎬 mpv

mpv is the media player used in my Omarchy setup.

## 📦 Installation

Install mpv from the Arch Linux repositories:

```bash
sudo pacman -S mpv
```

Verify the installation:

```bash
mpv --version
```

## 🎨 ModernZ

ModernZ is used as the UI/OSC for mpv.

Install ModernZ:

```bash
cd /tmp

git clone https://github.com/Samillion/ModernZ.git modernz

cp modernz/modernz.lua ~/.config/mpv/scripts/
cp modernz/modernz-icons.ttf ~/.config/mpv/fonts/
```

Create the required directories if they do not already exist:

```bash
mkdir -p ~/.config/mpv/scripts
mkdir -p ~/.config/mpv/fonts
```

## ⚙️ Configuration

The mpv configuration file is located at:

```text
~/.config/mpv/mpv.conf
```

The configuration in this repository is available at:

```text
configs/mpv/mpv.conf
```

Copy it to the mpv configuration directory:

```bash
mkdir -p ~/.config/mpv

cp configs/mpv/mpv.conf ~/.config/mpv/mpv.conf
```

### Current configuration

The configuration includes:

* Ravi subtitle font
* Custom subtitle size
* White subtitles
* Black subtitle border
* Subtitle shadow
* Custom subtitle positioning
* Bold subtitles
* ASS/SSA subtitle style override
* ModernZ UI
* Disabled default mpv OSC
* Disabled mpv seek/OSD overlay

## ▶️ Usage

Play a video:

```bash
mpv "path/to/video.mkv"
```

### Subtitle

mpv automatically loads a matching subtitle when it is located next to the video.

You can also specify a subtitle manually:

```bash
mpv "video.mkv" --sub-file="subtitle.srt"
```

## 🔗 Resources

* [mpv](https://mpv.io/)
* [ModernZ](https://github.com/Samillion/ModernZ)
