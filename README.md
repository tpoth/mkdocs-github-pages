# mkdocs-github-pages
Erzeugen einer Projektdokumentation mittels `mkdocs` und hosten mittels GitHub Pages. Neben der technischen Umsetzung soll ein für fiktives Software-Produkt eine typische Dokumentationsgliederung aufgebaut werden. Shoutout an https://www.youtube.com/@james-willett, dessen Tutorial ich genutzt habe um die Grundlagen zur Nutzung von mkdocs in Verbindung mit GH Pages zu erlernen.

## Attention: German only Repo!
> In this repository, we only use German as the language for all communication. This also means that the commit messages, etc. are only available in German.

> In diesem Repository verwenden wir ausschließlich deutsch als Sprache für die komplette Kommunikation. Das bedeutet auch die commit Messages, etc sind nur in deutsche Sprache enthalten.

## Setup

```sh
# Vorbereitung
sudo apt install python3.10-venv

# Virtuelle Umgebung für Python
python -m venv venv
source venv/bin/activate

# Prüfen der PIP Version
pip --version

# mkdocs Installation
pip install mkdocs-material

# Neue mkdocs Site erzeugen
mkdocs new .

# Lokalen mkdocs Server starten
mkdocs serve

# Voraussetzungen für die Theme Anpassung schaffen
pip install mkdocs[i18n]
```