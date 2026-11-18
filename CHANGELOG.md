# Changelog

## 1.0.0-beta.1 – 2026-11-18

Erste Fassung für REDAXO 6 (aus KLXM Studio, MIT).

- Zerstörungsfreie Bildbearbeitung im Medienpool: Zuschneiden, Drehen, Spiegeln, Ausrichten, Entzerren, Anpassen
  (Effekte, Sättigung, Helligkeit, Kontrast, Schärfe), Fokuspunkt/Einpassen; das Original bleibt unverändert
- Ausschnitt je Bildformat (16:9, 4:3, 1:1, 4:5 …) mit Ausgabe über den Media Manager (AVIF/WebP, srcset)
- `ImageEditor::img()` mit Alternativtext nach der Regel von klxm_meta (je Sprache, dekorativ = leer, sonst Titel)
- Bearbeiten auf der Website zusammen mit fluid
