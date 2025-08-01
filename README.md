
# Masters of the Universe Pinball (MPF Project)

This is a pinball machine simulation built with [Mission Pinball Framework](https://missionpinball.org). It is developed and tested on a uConsole using virtual hardware.

## 🚀 Setup

```bash
python3 -m venv mpfenv
source mpfenv/bin/activate
pip install -r requirements.txt
```

## ▶️ Running the Game

```bash
mpf both
```

## 🗂 Folder Structure

- `config/` – MPF configuration files
- `modes/` – Game modes like 'base' and 'attract'
- `shows/` – Light shows and attract mode effects
- `assets/` – Images, sounds, fonts for MPF-MC

## ✨ Features

- Attract mode
- Base gameplay mode
- Virtual switch/coil configuration for dev testing
