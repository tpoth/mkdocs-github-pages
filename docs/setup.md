# Setup


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

## Codeblocks

```typescript linenums="1" title="index.ts" hl_lines="2"
import express from "express";
const app = express();
```

## Icons und Emojis

:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }
