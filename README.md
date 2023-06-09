# PfortGT-WRO 🤖

## Einleitung
Dies ist das GitHub-repository für das autonom fahrende Auto des **PfortGT Teams** der **Landesschule Pforta** für den **WRO Future Engineers** Wettbewerb.
In diesem repository gehen wir auf unseren Planungs - und Bauprozess für unser Auto ein. Wir beschreiben unsere Probleme und  Ideen, welche wir auf dem Weg hatten und erläutern unser Baupläne und Programme.
## Überblick
Unser Auto wird durch einen Arduino betrieben. Es besteht aus einem fertigen Chassi welches mit individuell 3D-gedruckten Halterungen für die verschiedenen Sensoren und die Kamera ausgestattet ist (siehe [Bauteile](/Roboterauto/Bauteile)). Die Stromversorgung läuft über einen Akku (siehe [Elektronik](/Roboterauto/Elektronik)). Das Sensorenequipment besteht aus drei Ultraschall-Sensoren, einem Gyro-Sensor und einer Pixy Cam2 (siehe [Sensoren](/Roboterauto/Sensoren)). Für das Eröffnungsrennen verarbeitet ein Arduino Code den durch die Ultraschall-Sensoren gemessenen Abstand zu den Wänden, um kleine Lenkanpassugen des Autos zu treffen (siehe [Eröffnungsrennen](/Programme/Eröffnungsrennen)). Beim Hindernisrennen wird neben dem Ultraschall-Sensoren Code auch ein Kamera Script verwendet (siehe [Hindernisrennen](/Programme/Hindernisrennen)). Dieses sucht über die Pixy Cam nach roten und grünen Farbsignaturen und hält diese auf dem Bildschirmabschnitt (rechts oder links), welcher dem jeweiligen Abbiegen des Autos entspricht.
## Aufbau

Unser Repository ist in mehrere Untergruppen aufgeteilt, in welchem die einzelnen Schwerpunkte besprochen werden.
### Entwicklung
In [Entwicklung](/Entwicklung) beschreiben wir unseren Entwicklungsweg. Dabei gehen wir auf unsere Ideen ein, die wir währendessen hatten, Probleme welche uns beschäftigten und wie wir sie gelöst haben.
### Programme
In [Programme](/Programme) erläutern wir das Herzstück dieses Wettbewerbs, das Coding. Wir beschreiben und erklären dabei unsere Struktur, die Entscheidung für C++ und die zwei Schwerpunkte [Eröffnunggsrennen](Programme/Eröffnungsrennen) und [Hindernisrennen](Programme/Hindernisrennen), sowie unser eigentliches [Gesamtes Programm](Programme/GesamtesRennen).
### Roboterauto
In [Roboterauto](/Roboterauto/) wird ausführlich gezeigt, wie unser Auto aufgebaut ist. Es werden die [Bauteile](/Roboterauto/Bauteile) des Autos gezeigt, wie diese zusammengesetzt sind und welche davon gekauft oder 3D-gedruckt wurden. In [Elektronik](/Roboterauto/Elektronik) wird unsere elektronische Verkabelung erläutert und darauf eingegangen, wie die Stromversorgung für die Motoren und Sensoren geregelt ist. Daneben besprechen wir die Hardware, mit welcher das Auto ausgestattet ist und was uns zu dieser Entscheidung bewegt hatte. Weiterhin werden unsere verwendeten [Sensoren](/Roboterauto/Sensoren) 
erklärt, was die Besonderheiten sind und weshalb wir uns für diese entschieden haben. Zusätzlich sind in [3D-Druck](/Roboterauto/3D-Druck) unsere Dateien und Arbeit für unsere gedruckten Bauteile aufgelistet.
### Videos und Fotos
Bei [Videos und Fotos](/Videos_und_Fotos) können sowohl der Aufbau und die einzelnen Komponenten, als auch die Leistungen unseres Autos in Teststrecken eingesehen werden. 
### Quellen
In [Quellen](/Quellen) dokumentieren wir unsere Informationsquellen. Daneben sind alle von uns getätigten [Käufe](/Quellen/Käufe) für die zusätzlichen Bauteile und die Installationspfade mit den dazugehörigen Einrichtungshinweise für die von uns genutzte Software hinterlegt.

<p align="center">
<img src="Videos_und_Fotos/Fotos/Logo2.png" alt="description of image" width="30%" height="30%" style="display:block; margin:auto">
</p>
