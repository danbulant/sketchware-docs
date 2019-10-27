---
id: components
title: Components
---

Components are used to add functionality to your app which isn't possible without them.
There's a list of available components (at the time of writing):

## Intent

Intent is used to switch between activities and interchange data between them.

## SharedPreferences

Shared preferences are used to save data permanently. They are saved in device storage, but are deleted upon uninstallation(as opposed to *file*).

## Calendar

Calendar is used to get the current time and date. Can be used to format it to a given string.

## Vibrator

A simple component which will vibrate the device for x milliseconds (usually 200-300). Only on devices that support vibration.

## Timer

Timer is used to delay or repeat certain functions.

## Dialog

Dialog component is used to show simple dialog with up to three buttons.

## MediaPlayer

Media Player is used to play longer tracks.
*The difference between soundpool and Media Player is that soundpool can handle multiple tracks while MediaPlayer can handle longer track(but only one per component) *.

## Soundpool

SoundPool is used to play more short tracks. It can store multiple tracks while sacrificing performance (not usable for longer tracks).

## ObjectAnimator

ObjectAnimator is used to animate widgets inside view.

## Camera

Camera is used to capture an image from device camera (Only on devices that support camera).

## FilePicker

FilePicker is used to pick multiple files from user storage. They are returned as list String of their paths.

## Gyroscope

Gyroscope component is a way to get your device rotation. (Only available on devices that support it)

## Firebase

Firebase components are used to save a data, whether it's a DB, Auth or Storage.

## Interestial ad

Interestial ad is a way to earn money while showing personalized banners to user.

## TextToSpeech

TTS (For short) is used to convert English text to speech. Speech is played right after the function executes, no need of soundpool.

## SpeechToText

Voice recognition is a way to convert human speech to text.

## RequestNetwork

Request Network is used to send requests to APIs. This can be used to save or load data from your server.

## BluetoothConnection

Bluetooth is a way to share data wirelessly without a man in the middle (Router on WiFi).

## LocationManager

LocationManager is used to retrieve user location.
