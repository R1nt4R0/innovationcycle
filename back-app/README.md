## Lancer le backend (Flask)

### Prérequis

* Python 3.14 ou supérieur installé

### Installation de l’environnement

Se placer dans le dossier `back-app` :

```
cd back-app
```

Créer l’environnement virtuel Python :

```
python -m venv .venv
```

Installer les dépendances :

```
.\.venv\Scripts\python.exe -m pip install flask flask-cors
```

### Lancer le serveur

```
.\.venv\Scripts\python.exe app.py
```

Le serveur démarre alors sur :

```
http://127.0.0.1:5000
```

### Test rapide

Ouvrir dans un navigateur :

```
http://127.0.0.1:5000/health
```

Si tout fonctionne, l’API doit renvoyer :

```
{"ok": true}
```