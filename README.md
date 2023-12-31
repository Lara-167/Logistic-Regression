# Logistic-Regression

# Projektname: Logistic Regression
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Lara-167/Logistic-Regression/HEAD)

#Projektbeschreibung: In diesem Projekt wird mit Fake-Daten zu Werbung gearbeitet, die aufzeigen, ob ein Nutzer auf eine Werbeanzeige auf einer Webseite einer Firma geklickt hat oder nicht. Es wird ein Modell erstellt, das anhand von Nutzereigenschaften vorhersagt, ob dieser auf die Werbung klicken wird oder nicht.

#Der Datensatz beinhaltet folgende Eigenschaften:

    'Daily Time Spent on Site': Zeit auf der Webseite in Minuten
    'Age': Alter in Jahren
    'Area Income': Durchschnittliches Einkommen der Region des Nutzers
    'Daily Internet Usage': Durchschnittliche Minutenzahl die der Nutzer täglich im Internet ist
    'Ad Topic Line': Überschrift der Werbung
    'City': Stadt des Nutzers
    'Male': Ob der Nutzer männlich ist (1) oder nicht (0)
    'Country': Land des Nutzers
    'Timestamp': Zeit zu der der Nutzer auf die Werbung geklickt oder das Fenster geschlossen hat
    'Clicked on Ad': Ob der Nutzer gelickt hat (1) oder nicht (0)

#Code-Ausführung:
  1. GitHub URL des Repository "Logistic-Regression" in https://mybinder.org/ einfügen und launchen
  2. Notebook öffnen
  3. Code-Zeilen nacheinander ausführen lassen

#Code-Abfolge:
    1. Libraries importieren (nachdem sie vorab durch binder installiert wurden)
    2. Daten einlesen aus der Datei Advertising.csv
    3. Explorative Datenanalyse durchführen; Modellbildung mit seaborn
    4. Logistische Regression; Aufteilung der Daten in Test- und Trainingsdaten, um ein logistisches Regressionsmodell zu trainieren
    5. Vorhersagen und Auswertung vornehmen mithilfe eines Klassifizierungsreports

#Projektergebnis:
    Es ist mit einer Accuracy von 0.91 zu rechnen.
    Damit sind 91% der Vorhersagen der Modelle korrekt.
    Der Klassifizierungsreport zeigt die Genauigkeit des Modells, um anhand von Nutzereigenschaften vorherzusagen, ob ein Nutzer auf eine Werbeanzeige klicken wird oder nicht.
