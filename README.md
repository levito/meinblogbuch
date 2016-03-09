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

### /admin/structure/block
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

### /admin/structure/types/manage/article/display, /admin/structure/types/manage/article/display/teaser
* Tags: Beschriftung: Inline

### /admin/appearance/settings
* Logo des Themes verwenden: nein

### Konfiguration

#### /admin/config/regional/date-time
* Default long date: `l, j. F Y - H:i`
* Default medium date: `D, d.m.Y - H:i`
* Default short date: `d.m.Y - H:i`

#### /admin/config/search/path/patterns
* Inhalt: `[node:title]` (Article, Page)
* Taxonomie-Begriff: `tag/[term:name]` (Tags)


#### /admin/config/media/imce
* Admin profile
  - Maximum image dimensions: 960 x 960
  - `.`: Browse files, Browse subfolders
  - `inline-images`: All permissions

#### /admin/config/media/image-styles
* Large: 960 x 960
* Medium: 320 x 320

#### /admin/config/content/formats/manage/basic_html, /admin/config/content/formats/manage/full_html
* Bild: Maximum dimensions: 960 x 960 (wenn ohne Imce Modul)
* Styles dropdown
  ```
img.align-center|Center
img.align-left|Left
img.align-right|Right

  ```

#### /admin/config/people/accounts
* Wer kann Konten registrieren? => Nur Administratoren
* Konto gesperrt => benachrichtigen => Textkörper: [site:account-name] => [site:name]


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



## Übersetzungen
* Welcome to [site:name] => Willkommen bei [site:name]
* Submitted by => Geschrieben von
* Submitted by @author_name on @date => Geschrieben von @author_name am @date
