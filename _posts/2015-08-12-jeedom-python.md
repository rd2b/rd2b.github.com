---
layout: post
title:  "Requêter Jeedom depuis un script Python"
date:   2015-08-12 12:39:21
categories: jeedom domotique 
---

Je me suis équipé depuis quelques temps en domotique et de la box [Jeedom].
J'avais juste un soucis avec cet outil, je suis incapable de programmer à la souris.
Heureusement [Jeedom] vient avec des API en JsonRPC.

Voici comment requêter [Jeedom] pour effectuer une simple requête de la méthode  "ping" (qui réponds "pong").

{% gist d9fdcd3298d2e105ae5f %}

Celle-ci permet ensuite d'aller plus loin et par exemple de développer ses propres scénarios à base de python et de cron.

Un peu de documentation:

 - [Jeedom]
 - [La documentation des JsonRPC sur le WIKI Jeedom](https://www.jeedom.fr/wiki/index.php?title=API_JSONRPC_2.0)

[Jeedom]: https://jeedom.fr "Site officiel de Json"

