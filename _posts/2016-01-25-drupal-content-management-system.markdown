---
layout: post
title:  "Drupal - Content Management System"
date:   2016-01-25 14:00:00 +0100
categories: jekyll update
---

![Drupal Logo](https://www.video2brain.com/en/images_dynam/product_class_external_product/drupal1.png){:height="80px" width="80px"}

## Beschreibung

Drupal ist ein open-source content-management-system das in PHP geschrieben und unter der GNU General Public Licence verteilt wird.

Es wird für ca. 2,1% aller Websiten weltweit als backend framework benutzt. Darunter sind sowohl Persönliche Blogs als auch poliische Seiten und Regierungsseiten.

*	*	*

## Aufbau

#### The Core

Als "Core" bezeichnet man in Drupalkreisen den inneren Kern, also die Codebase, welche viele Standardfeatures enthält, die man auch aus anderen CMS - Systemen kennt. Wie z.B. User-Registrierung und Verwaltung, Menü-Management u.v.m.

Seit Version 8 befindet sich der "Core" in seinem eigenem 'core' Verzeichnis. Der Core beinhaltet auch viele Standardlibraries wie Bootstrap. Jegliche zusätzliche funktionalität kann mittels Modulen hinzugefügt werden.

#### Core-Modules

* Access statistics and logging
* Advanced search
* Blogs, books, comments, forums, and polls
* Caching and feature throttling for improved performance
* Descriptive URLs
* Multi-level menu system
* Multi-site support
* Multi-user content creation and editing
* OpenID support
* RSS feed and feed aggregator
* Security and new release update notification
* User profiles
* Various access control restrictions (user roles, IP addresses, email)
* Workflow tools (triggers and actions)


> Quelle [Wikipedia](https://en.wikipedia.org/wiki/Drupal)

#### Module

Von freien Programmierern beigetragene Module können die Funktionalität von Drupal erweitern. Zum Beispiel können Bildgallerien, WYSIWYG Editoren, third-party integration tools und viel mehr.

Im September 2015 wurden auf der Drupal website bereits 31.800 freie Module aufgelistet. Die am Häufigsten benutzten Module sind hier aufgelistet:


* Content Construction Kit (CCK): allows site administrators to dynamically create content types by extending the database schema. "Content type" describes the kind of information. Content types include, but are not limited to, events, invitations, reviews, articles, and products. The CCK Fields API is in Drupal core in Drupal 7.
* Views: facilitates the retrieval and presentation, through a database abstraction system, of content to site visitors. Basic views functionality has been added to core in Drupal 8.
* Panels: drag and drop layout manager that allows site administrators to visually design their site.
* Rules: conditionally executed actions based on recurring events.
* Features: enables the capture and management of features (entities, views, fields, configuration, etc.) into custom modules.
* Context: allows definition of sections of site where Drupal features can be conditionally activated
* Media: makes photo uploading and media management easier
* Services: provides an API for Drupal.

> Quelle [Wikipedia](https://en.wikipedia.org/wiki/Drupal)

####Datenbank

Wie auch von anderen CMS bekannt, benötigt auch Drupal eine Datenbank um sowohl die Userdaten als auch die Systemdaten selbst zu verwalten.

Die Minimalanforderungen an eine Datenbank sind:

* Drupal 8:
    * MySQL 5.5.3/MariaDB 5.5.20/Percona Server 5.5.8 or higher with PDO and an InnoDB-compatible primary storage engine,
    * PostgreSQL 9.1.2 or higher with PDO,
    * SQLite 3.6.8 or higher

* Drupal 7:
    * MySQL 5.0.15/MariaDB 5.1.44/Percona Server 5.1.70 or higher with PDO,
    * PostgreSQL 8.3 or higher with PDO,
    * SQLite 3.3.7 or higher

* Drupal 6:
    * MySQL 4.1.1 or higher,
    * PostgreSQL 7.1


> Quelle [www.drupal.com](https://www.drupal.org/requirements)

*	*	*

##Besonderheiten

* Rollensystem:
	* Im Drupal Backend können beliebig viele 'Roles' erstellt werden die verschiedenste Rechte besitzen. In anderen CMS sind meist vordefinierte Rechtegruppen verankert, wie zB User, Admin, Redakteur (Editor). 
* Erweiterbarkeit durch Module
	* Durch Schnittstellen im System (Hooks) ist es außenstehenden Programmierern möglich eine Erweiterung zu schreiben und diese der Community zur Verfügung zu stellen.
* Anbindung an Composer
	* Drupal ist in PHP geschrieben und kann als Package über Composer installiert werden.
* Mehrsprachigkeit
	* Der Inhalt einer Seite kann in mehreren Sprachen aufbereitet werden. Vorrangig an der Systemsprache kann das CMS selbst die richtige Sprache für den Clienten benutzen.

*	*	*

## Done with Drupal

![WhiteHouseUSA](https://www.drupal.com/sites/default/files/styles/showcase_screenshot/public/whitehouse.png){:class="pix"}

![City of LA](https://www.drupal.com/sites/default/files/styles/showcase_screenshot/public/Screen%20Shot%202015-07-16%20at%2010.56.06%20AM.png){:class="pix"}

![University of Minnesota](https://www.drupal.com/sites/default/files/UMN_wordmark.png){:class="pix"}

> Quelle [www.drupal.com](https://www.drupal.com/showcases)