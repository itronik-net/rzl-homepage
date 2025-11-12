---
layout: post
title: Neue Generation der Squareroots bei ihrem zweiten gemeinsamen Attack/Defense-CTF
facts:
  Was?: Teilnahme SaarCTF
  Wann?: 08.11.2025
  Wo?: RZL
author:
  login: default
  email: public@lists.squareroots.de
  display_name: "itronik"
---

Am vergangenen Wochenende haben die **Squareroots** nach ihrem Comeback vor einem Monat erneut an einem gemeinsamen Attack-/Defense-CTF teilgenommen – beim **SaarCTF 2025**, organisiert vom Team **Saarsec**. Zielstrebig, vorbereitet und mit neuer Energie erreichten sie **Platz 23** von rund **290** angemeldeten Teams – eine starke Leistung der noch neuen Generation an Flaggenjägern.

Bei einem Attack/Defense-CTF erhält jedes Team identische virtuelle Maschinen mit verschiedenen Services (z. B. Web-, Telnet- oder Mail-Servern). Die Aufgabe: Schwachstellen finden und schließen, um die eigenen Flaggen zu schützen — und gleichzeitig die Systeme der anderen Teams angreifen, um deren Flaggen zu erobern.

Im Unterschied zum ersten gemeinsamen CTF fokussierten wir uns diesmal nicht nur auf Verteidigung. Mit vorbereiteten Tools – etwa zur Traffikanalyse, einem automatisierten Flag-Submitting-Framework und einer Exploit-Toolchain – sind wir offensiv aktiv geworden. Verteidigung war Pflicht, Angriff unser Ziel – und mit über **39.000** eroberten Flaggen haben wir dieses Ziel erreicht!

## Die Challenges im Überblick  
Das diesjährige [SaarCTF](https://ctf.saarland/) stellte acht Dienste bereit – von Kryptographie über Binary-Exploits bis zu Web-Services:

- **BlockRope** – Ein in Python geschriebener Telnet-Server mit Path-Manipulation-Lücke. Exploit entwickelt.  
- **Calendar** – Binary-Applikation mit Redis-Datenbank; enthielt eine Lua-Code-Injection und einen Heap-Buffer-Overflow.  
- **Licenser** – Binary-Applikation mit Remote-Code-Execution (RCE).  
- **No-Service** – Dieser Dienst hatte keine eigene Sicherheitslücke; konnte nur über andere Dienste ausgenutzt werden.  
- **RCEaaS** – CMD-Emulator in Rust („ACMD-ähnlich“); anfällig für Path-Traversal und RCE. Mehrere Exploits entstanden.  
- **Routerploit** – PHP-basierter Webshop mit fehlerhafter Rechteprüfung. Zwei unterschiedliche Exploits implementiert.  
- **SSSG** – Multi-Webserver mit OAuth-Flow; enthielt eine RCE.  
- **SaarLandCryptoGalore** – Verschlüsselung mittels LCG (Linear Congruential Generator); anfällig für eine Known-Plaintext-Attacke.

## Fazit  
Wir sind mehr als zufrieden – die Squareroots haben gezeigt, dass sie nach dem Comeback nicht nur defensiv stabil sind, sondern auch offensiv angreifen können. Die Kombination aus guter Vorbereitung, passender Toolchain und entschlossener Durchführung spiegelt sich im Ergebnis wider. **Platz 23 von ~290 Teams** spricht für sich.

Wenn du Lust hast, mit uns gemeinsam bei einem CTF mitzumachen oder einfach Interesse an CTFs und Austausch hast – **melde dich gerne bei uns!**

### Wie kannst du uns erreichen
**Matrix:** [#rzl-ctf:hax404.de](https://matrix.to/#/#rzl-ctf:hax404.de) oder komm einfach an einen unserer zweiwöchentlichen treffen im Raumzeitlabor vorbei. Im Kalendar kannst du die Tage & Uhrzeiten finden: [Link](https://raumzeitlabor.de/events/index.html)
