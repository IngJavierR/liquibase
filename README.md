# Liquibase
## Source Control for your database

Es una libreria opensource para el manejo y ejecución de cambios en base de datos.

Comandos que se pueden ejecutar para distintos propÃ³sitos:


## Generar un changelog desde una base de datos existente

    liquibase --changeLogFile="changesets/db.changelog-#.#.#.#.xml" generateChangeLog

## Update

    liquibase --changeLogFile="changesets/db.changelog-master.xml" update

## Rollback a un changeset anterior

    liquibase --changeLogFile="changesets/db.changelog-master.xml" rollbackCount 1

## Generar un changelog de diferencias

    liquibase --changeLogFile="changesets/db.changelog-#.#.#.#.xml" diffChangeLog