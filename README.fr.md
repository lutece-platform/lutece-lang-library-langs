![](https://dev.lutece.paris.fr/jenkins/buildStatus/icon?job=lang-library-langs-deploy)
[![Alerte](https://dev.lutece.paris.fr/sonar/api/project_badges/measure?project=fr.paris.lutece.plugins%3Alibrary-langs&metric=alert_status)](https://dev.lutece.paris.fr/sonar/dashboard?id=fr.paris.lutece.plugins%3Alibrary-langs)
[![Line of code](https://dev.lutece.paris.fr/sonar/api/project_badges/measure?project=fr.paris.lutece.plugins%3Alibrary-langs&metric=ncloc)](https://dev.lutece.paris.fr/sonar/dashboard?id=fr.paris.lutece.plugins%3Alibrary-langs)
[![Coverage](https://dev.lutece.paris.fr/sonar/api/project_badges/measure?project=fr.paris.lutece.plugins%3Alibrary-langs&metric=coverage)](https://dev.lutece.paris.fr/sonar/dashboard?id=fr.paris.lutece.plugins%3Alibrary-langs)

# Librairie langs

## Introduction

Ce plugin permet d'ajouter les resources permettant de traduire les sites lutèce dans les langues suivantes :

 
* ar
* cs
* da
* de
* es
* fi
* hu
* it
* nl
* pt
* sv

## Configuration

Pour prendre en compte ces langues, il est nécessaire de modifier (ou étendre) les propriétés suivantes dans le fichier de configuration lutece.properties

Dans la section "Internationalization (i18n)" :

 
* lutece.i18n.defaultLocale=fr
* lutece.i18n.availableLocales=en,fr,ar,cs,da,de,es,fi,hu,it,nl,pt,sv

## Usage

Sélectionner simplement la langue souhaitée dans le back office.


[Maven documentation and reports](https://dev.lutece.paris.fr/plugins/library-langs/)



 *generated by [xdoc2md](https://github.com/lutece-platform/tools-maven-xdoc2md-plugin) - do not edit directly.*