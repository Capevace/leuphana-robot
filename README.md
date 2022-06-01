# Robot that opens beer & plays chess (using [UR5e](https://www.universal-robots.com/products/ur5-robot/))

> Source code for making a Universal Robot 5 open beer and play chess – a project at Leuphana University

## UI: Bier-Modus
![](beer-mode.png)

## UI: Schach-Modus
![](chess-mode.png)

## Server starten
```sh
# Repo klonen
git clone https://github.com/capevace/leuphana-robot

# In den Ordner navigieren
cd leuphana-robot

# Dependencies installieren
npm install

# Server starten
node server/index.mjs
```

Der Web Service ist dann unter [http://localhost:3000](http://localhost:3000) erreichbar.
