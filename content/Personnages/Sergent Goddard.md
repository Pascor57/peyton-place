## Épisodes

```dataview
TABLE file.link as Episode, date as Date
FROM "Episodes"
WHERE contains(personnages, this.file.name)
SORT date asc