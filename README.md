# Mein Blogbuch Drupal Theme

## Module

### [Pathauto](https://www.drupal.org/project/pathauto)
* Dependencies:
  - [Chaos tools](https://www.drupal.org/project/ctools)
  - [Token](https://www.drupal.org/project/token)

### [Imce File manager](https://www.drupal.org/project/imce)

### Markdown Filter (?)
* Dependencies:
  - Libraries (?)


## Settings

### Struktur => Blocklayout
* Suche => Secondary Menu
  - Konfigurieren: Titel anzeigen: nein
* Fußbereichsmenü => Fußbereich
* Werkzeuge => raus
* Powered by Drupal => raus
* User Account Menu => Fußbereich
* Breadcrumbs => raus
* Reiter => unter Seitentitel

### Design => Einstellungen
* Logo des Themes verwenden: nein

### Konfiguration

#### Lokalisierung und Sprache => Date and time formats
* Default long date: `l, j. F Y - H:i`
* Default medium date: `D, d.m.Y - H:i`
* Default short date: `d.m.Y - H:i`

#### URL-Aliase => Muster
* Inhalt: `[node:title]` (Article, Page)
* Taxonomie-Begriff: `tag/[term:name]` (Tags)


#### Medien => Imce File Manager
* Admin profile
  - Maximum image dimensions: 980 x 980
  - `.`: Browse files, Browse subfolders
  - `inline-images`: All permissions

#### Bildstile (wenn ohne Imce Modul)
* Large: 980 x 980
* Medium: 320 x 320

#### Inhaltserstellung => Text formats and editors => Basic + Full HTML (?)
* Bild: Maximum dimensions: 980 x 980
