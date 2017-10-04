Comandos que se pueden ejecutar para distintos propÃ³sitos:


## Generar un changelog desde una base de datos existente

    liquibase --changeLogFile="changesets/changeset###.xml" generateChangeLog

## Update

    liquibase --changeLogFile="changesets/changeset###.xml" update

## Rollback a un changeset anterior

    liquibase --changeLogFile="changesets/changeset###.xml" rollbackCount 1

## Generar un changelog de diferencias

    liquibase --changeLogFile="changesets/changeset-diff.xml" diffChangeLog