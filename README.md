[<img src='images/de.png' height=10> Deutsche Version](README_DE.md)  
[<img src='images/pl.png' height=10> Wersja polska](README_PL.md)

# GlucoDataAuto

As the Android Auto part of [GlucoDataHandler](https://github.com/pachi81/GlucoDataHandler/blob/master/README.md) does not fullfill Google PlayStore policies, this part has been moved to an extra app called GlucoDataAuto, which receives its settings and values from GlucoDataHandler. 

It can also be used as standalone application.

## Option #1: Using fake media player
If you are not using any Android Auto media player for listen music, you can use GlucoDataAuto to display its values in the media tap:

<img src='images/AA_media.png' width=300>

To enable the media player for split view (Coolwalk), stop the playback in another media player and press Play in GlucoDataAuto.

## Option #2: Using notifications

You can also use notifications:

<img src='images/AA_notification.png' width=300> <img src='images/AA_notification_view.png' width=300>

## Option #3: Using the app

<img src='images/AA_App.png' width=300>

# Setup Android Auto

Download and install last `GlucoDataAuto_#.#.apk` from [Releases](https://github.com/pachi81/GlucoDataAuto/releases) (allow install from unknown source if required).

Android Auto is either a separate app or part of the system and can be accessed through the Android settings.

To activate GlucoDataAuto for Android Auto, you have to do the following steps:

## 1. Activate developer mode

- open Android Auto
- scroll down to the Version
- tap several times on the Version until a popup appears to `Allow development settings`
- press `OK`

## 2. Activate unknwon sources

- open Android Auto
- open in the 3-dot menu the `Developer settings`
- scroll down to `Unknown source`
- enable it

## 3. Set Notifications settings

- open Android Auto
- scroll down to `Messaging`
- enable `Show message notifications`
- enable `Show first line of messages`

## 4. Enable GlucoDataAuto

- open Android Auto
- scroll down to `Display`
- open `Customise launcher`
- enable `GlucoDataAuto`

If GlucoDataAuto is not available, please restart your phone.


# Sources

-> [Source configuration instruction](https://github.com/pachi81/GlucoDataHandler/blob/master/SOURCES.md)

# Support my work
[🍺 Buy me a beer](https://www.buymeacoffee.com/pachi81)

[Paypal me](https://paypal.me/pachi81)
