# Linux Basiswissen 

## Agenda 

  1. [Verzeichnisaufbau](verzeichnisaufbau.md) 
     1. [Dateitypen](dateitypen.md) 
  1. [Basisbefehle](basisbefehle.md)
     1. [In den Root-Benutzer wechseln](sudo.md)  
     1. [Wo bin ich ?](pwd.md)
     1. [Praktische Ausgabe von langen Seite - less](less.md) 
     1. [Datei anlegen - touch](touch.md)
     1. [Autovervollständen * and tab](autocomplete.md) 
  1. Dateien und Verzeichnisse
     1. [Inhalt in Datei schreiben und anhängen](file-write-append.md)
     1. [Verzeichnisse und Dateien löschen](file-dir-delete.md)
  
  1. Prozesse 
     [Prozesse anzeigen - ps/pstree -p](prozesse.md)
  1. [Hilfe zu Befehlen](help.md)
  1. [Literatur](literatur.md) 

## Verzeichnisse in Listenansicht mit versteckten Dateien anzeigen

```
ls -la 
```

## Ins Heimatverzeichnis und Wurzelverzeichnis (C: unter Windows) wechseln 

```
# Ins Heimatverzeichnis wechseln 
# cd ohne alles 
cd 

# Ins Wurzelverzeichnis 
cd / 
```

## Wie in ein Verzeichnis wechseln (relativ und absolut) 

```
# relativ - nur in ein Unterverzeichnis meines bestehenden Verzeichnisses
cd etc 

# absolut - welchselt dort rein, egal wo ich bin 
cd /etc 
```

