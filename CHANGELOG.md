# Changelog

## 1.1.1

- **Fixed:** opening the interaction menu on a vassal or on your top liege filled `error.log` with "scope:target trigger [ Failed context switch ]" errors. The game checks whether the title of **Request Title Creation** and **Grant Title Creation** is valid before any title is picked; that check now waits until there is one. The errors were harmless and nothing else changes.

## 1.1.0

- New game rule **TCP: Required Crown Authority** to choose the lowest Crown Authority at which a feudal top liege requires permission: Absolute (default, as before), High or higher, Limited or higher, or Any. Administrative emperors always require permission. Requested on the Steam Workshop.

## 1.0.0

- First release.
- Vassals need their top liege's permission to create titles when the top liege is a player and is feudal with Absolute Crown Authority, or administrative with an empire or higher as primary title.
- New interaction **Request Title Creation**: a vassal asks their top liege for permission to create a specific title. A refused vassal gets −30 opinion of their liege for 10 years. AI vassals only ask for titles whose de jure counties they mostly control, each at most once every 2 years, and a liege receives at most one AI request a year.
- Requests arrive as letters that name the title. There are eleven kinds, depending on the vassal (rival or resentful, ancestral title, primary heir, close family, friend or loyal, ambitious, arrogant, humble or content, great renown, asking for a kingdom or empire, and a formal default), each with two letters picked at random.
- The vassal answers your decision with a message of their own in the message feed, in seven tones, when you accept, refuse or grant permission unasked.
- New interaction **Grant Title Creation**: the top liege gives a vassal permission without being asked.
- A permission is for one title, lasts 5 years and is used up when the title is created.
- New game rule **TCP: Title Creation Permission**: Player Realms (default; only realms whose top liege is a player) or Vanilla. Realms ruled by the AI work as in vanilla.
- English and Spanish localization; other languages fall back to English.
