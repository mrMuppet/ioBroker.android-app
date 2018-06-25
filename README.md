# ioBroker.android-app

Die App hat folgende Funktionen:
- Socket-Verbindung zu ioBroker direkt oder über cloud.pro
- Anzeige aller Räume und Funktionen
- Anzeige aller States eines Raumes/einer Funktion
- Verschiedene UI Elemente je nach State role
- Unterstützung von States mit vordefinierten Werten
- ...

Geplante Features:
- Username/Passwort für Socket-Verbindung
- Favoriten für States
- Anzeige der State-Historie

Erfordert mindestens Android 4.4

<img width="216" heigth="384" src="sample/home.png"/>

## Changelog

### 0.9.x (2018-06-23)
- flag rooms and functions as favorite
- show list of favorites on homescreen
- support readonly states

### 0.8.x (2018-06-17)
- firebase crash logs added
- bugfix: validate socket url

### 0.7.0 (2018-06-15) 
- support of Android 4.4+

### 0.6.0 (2018-06-14) 
- initial public testing