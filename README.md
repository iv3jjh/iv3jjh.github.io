#  Lab IV3JJH - Documentazione Sito

Questo sito è costruito con **MkDocs** e ospitato su **GitHub Pages**.
Ecco la procedura standard per gestire il sito.

---

## 🛠️ 1. Preparazione (Solo la prima volta o se cancelli la cartella)
Se hai appena clonato la repo o hai cancellato la cartella `venv`, devi reinstallare il motore:

```bash
# Crea l'ambiente virtuale
python3 -m venv venv

# Attivalo
source venv/bin/activate

# Installa MkDocs e il tema
pip install mkdocs mkdocs-material
