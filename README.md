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

### [Honeypot](https://www.drupal.org/project/honeypot)


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

### /admin/structure/views/view/frontpage
* Seitennavigation: Erste/Vorherige/Nächste/Letzte: nur Pfeile

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

#### Bildstile
* Large: 980 x 980
* Medium: 320 x 320

#### Inhaltserstellung => Text formats and editors => Basic + Full HTML
* Bild: Maximum dimensions: 980 x 980 (wenn ohne Imce Modul)
* Styles dropdown
  ```
  img.align-center|Center
  img.align-left|Left
  img.align-right|Right

  ```



## Kommentar-Einstellungen

### /admin/people/permissions
* Kommentare erstellen/bearbeiten/Freigabe überspringen für Gast und angemeldete Benutzer

### /admin/structure/types/manage/article/fields/node.article.comment
* Gäste müssen ihre Kontakt-Informationen angeben

### /admin/structure/comment/manage/comment/form-display
* Sprache und Betreff raus
* Kommentar hoch

### /admin/appearance/settings
* Überprüfungsstatus eines Benutzers in Kommentaren => raus
