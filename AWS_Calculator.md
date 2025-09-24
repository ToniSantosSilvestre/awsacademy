---
title: AWS Pricing Calculator
language: VAL
author: Toni Santos Silvestre - Jorge Orta López [https://github.com/ToniSantosSilvestre]
subject: Introducció al núvol públic
keywords: [Optatiu, 2025-2026, AWS,Academy]
IES: CIPFP Batoi (Alcoi) [https://portal.edu.gva.es/cipfpbatoi/]
header: ${title} - ${subject} (ver: ${today})
footer:${currentFileName}.pdf - ${author} - ${IES} - ${pageNo}/${pageCount}
typora-root-url:${filename}/../
typora-copy-images-to:${filename}/../assets
---

[TOC]

## 1. CASOS D'ÚS DE L'AWS PRICING CALCULATOR

Sobre una empresa amb un organigrama com el següent:

![Organigrama de l'empresa](/assets/organigrama.png)

### 1.1 Realitza les següents estimacions de cost d'implantació al núvol:

**Explicació de la prova**:

Una empresa ens ha contractat perquè li pressupostem que valdria passar tota la seua infraestructura en local als serveis en núvol d'AWS :

**Problemàtica**:

Cada vegada hi ha més complexitat a l'hora d'atendre la gestió de màquines virtuals, bases de dades i espais d'emmagatzematge per gestionar l'informació d'una empresa.

El vostre treball és donar diferents alternatives de pressupost per a les necessitats plantejades.

Cal implementar un pressupost per a la regió Europe(Spain) **per a un any** per determinar el cost de la disponibilitat de tota la infraestructura **a demanda** i un altre on s'aplique **un pla d'estalvi de pagament de reserva amb pagament parcial (PURI)**. Així doncs el detall dels pressuposts han d'incloure les següents característiques:

- Tots els treballadors amb categoria "Manager" i "Employee" disposaran d'unes màquines EC2 instàncies compartides, que disposen de sistemes GNU/Linux, 2 CPUs i 4 GiB de RAM. El seu disc serà un SSD d'1 TB
- Per als "CEO" i "Owner" , es diposa d'unes màquines dedicades EC2 amb GNU/Linux, 1 CPU i 8 GiB de RAM i SSD d'1TB.
- Un servei de xarxa VPC amb característiques activades de "Connexió VPN", "IPv4 Pública".
- La base de dades s'implementa sobre un servei RDS que munta a demanda una base de dades MySQL amb una instància db.m5.12xlarge amb 48 CPUs i 192 GiB

### 

