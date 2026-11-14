# Old iPad dashboard test

A small experiment to give a 2012 iPad 2 (stuck on iOS 9) a second life as a
door-side dashboard showing the time, weather, bus departures and calendar.

## What this page does

`index.html` runs a few connection checks and reports which ones pass:

1. JavaScript and clock work
2. Weather from Open-Meteo (HTTPS)
3. Bus data from Wiener Linien (HTTPS)
4. Bus data from Wiener Linien (plain HTTP)

The results show whether the iPad can fetch data directly, or whether a small
helper on the home network is needed.

## How to use it

Open the GitHub Pages address of this repository in Safari on the iPad.
Do not open it inside an app, as in-app viewers block outside requests.

## Why

Reusing old electronics instead of throwing them away.

## Notes

- Code is written in old-style JavaScript (no modern features) so iOS 9 can run it.
- The bus stop number in the test is a placeholder.
