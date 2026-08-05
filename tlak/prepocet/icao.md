---
title: ICAO - standardní atmosféra
description: 
published: true
date: 2026-08-05T09:41:42.484Z
tags: 
editor: markdown
dateCreated: 2026-08-05T09:05:22.164Z
---

# ICAO - standardní atmosféra

Standardní atmosféra **ICAO (International Civil Aviation Organization)** je mezinárodně definovaný model zemské atmosféry používaný především v letectví. Stanovuje referenční hodnoty tlaku, teploty a hustoty vzduchu a slouží jako základ pro přepočet atmosférického tlaku na hladinu moře.

Na rozdíl od metod využívajících skutečnou teplotu atmosféry předpokládá standardní atmosféra pevně definované podmínky:

- tlak na hladině moře **1013,25 hPa**
- teplota na hladině moře **15 °C**
- teplotní gradient **6,5 °C/km**

Díky těmto předpokladům je možné jednoduše přepočítat absolutní tlak naměřený na stanici na tlak redukovaný na hladinu moře.

## Rovnice

$$
p_0=\frac{p}{\left(1-\frac{h}{44330}\right)^{5.255}}
$$

kde:

| Symbol | Význam |
|--------|---------|
| **p₀** | tlak redukovaný na hladinu moře (Pa nebo hPa) |
| **p** | naměřený absolutní tlak (Pa nebo hPa) |
| **h** | nadmořská výška stanice (m) |

### Konstanty

| Konstanta | Hodnota | Význam |
|-----------|---------:|--------|
| **44330** | m | konstanta odvozená ze standardní atmosféry ICAO |
| **5,255** | – | exponent odvozený z fyzikálních konstant |

## Výhody

- velmi jednoduchý výpočet
- nevyžaduje měření teploty
- minimální výpočetní náročnost
- široce používaný v letectví

## Nevýhody

- nezohledňuje skutečnou teplotu vzduchu
- nezohledňuje vlhkost vzduchu
- při nestandardních meteorologických podmínkách může vykazovat odchylky

## Použití

Tento vzorec se používá především u jednodušších meteostanic, vestavěných barometrů a meteorologických aplikací, kde není k dispozici aktuální teplota vzduchu nebo není vyžadována maximální přesnost přepočtu.