# Fossa-Test

das Projekt dient lediglich dem testen von [Fossa](https://app.fossa.com). 

Getestet wird das Scannen nach Lizenzen, sowohl von Ruby-On-Rails Abhängigkeiten als auch von JavaScript Abhängigkeiten, die in einem Unterordner definiert sind.

## Rails
- die Ruby-Dependencies sind in `Gemfile.lock` definiert.
- die JavaScript Dependencies sind in `package-lock.json` definiert. Hier nur `ember`.

## Ember
Im Unterordner `frontend` ist eine `ember` Application
- die JavaScript Dependencies sind in `frontend/package-lock.json` definiert. 