# OKF-Struktur im Vault

Dieser Ordner ist **OKF v0.1-nah** gemäß der von Google Cloud vorgestellten Open-Knowledge-Format-Idee (Markdown + YAML-Frontmatter + Links).

## Umgesetzte Kernkonventionen
- Wissen als Verzeichnis aus Markdown-Dateien
- YAML-Frontmatter mit OKF-relevanten Feldern
  - `type` (Pflichtfeld in der Spezifikationsidee)
  - `title`, `description`, `resource`, `tags`, `timestamp`
- Normale Markdown-/Wikilinks zwischen Konzepten

## Struktur
- Podcast-Bundle: `OKF/Podcast/Laternenhüter_des_Stillen_Tals/`
- Einstiegsdatei im Bundle: `index.md`

## Hinweis zur Konformität
Diese Vault-Struktur orientiert sich eng an OKF v0.1, ist aber kein offiziell zertifizierter „Conformance Run“ gegen das vollständige Referenz-Repository.

## Einstieg
- [Serienindex – Laternenhüter des Stillen Tals](Podcast/Laternenhüter_des_Stillen_Tals/index.md)

## Für Quartz
Die Inhalte sind bewusst als normale Markdown-Seiten mit YAML-Frontmatter angelegt. Das erleichtert späteres Publizieren mit Quartz oder anderen Static-Site-Generatoren.
