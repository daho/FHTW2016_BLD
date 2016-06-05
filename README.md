# FHTW2016_BLD

#Data Engineering
##Assignment 1: Big Data in Ihrem Umfeld (4 Punkte)
###1.1 (2 Punkte)
>Schauen Sie sich in Ihrem Umfeld um. FH Technikum oder Ihr Job. Nennen Sie mindestens ein Beispiel für Daten, die schemalos (unstrukturiert) sind und mindestens ein Bespiel für Daten, die strukturiert (schematisch) sind.

__Unstrukturierte (schemalose) Daten__
-	E-Mails
-	Chat-Nachrichten (Skype for Business)

__Strukturierte (schematische) Daten:__

Alle möglichen Arten von Daten die in eine relationale Datenbank gespeichert werden.

Beispiele:
-	Kundendaten (CRM)
-	Transaktionsdaten
-	Logs

###1.2 (2 Punkte)
>Nennen Sie ein Beispiel für Daten in Ihrem Umfeld, die gestreamt verarbeitet werden, nennen Sie ein Beispiel für Daten in Ihrem Umfeld, die über Batchverarbeitung verarbeitet werden.

__Streamverarbeitung__

Die Auswertung und Visualisierung von Nutzerstatistiken

Zum Beispiel:
-	Nutzerstatistiken einer Internetseite

__Batchverarbeitung__

Daten die aus einer Schnittstelle geladen und verarbeitet werden
-	Logdateien werden erstellt und heruntergeladen


##Assignment 2: Big Data in Ihrem Umfeld (4 Punkte)
>Entscheiden Sie sich für eine Data Engineering Plattform. Apache Flink oder Apache Spark. Installieren Sie die auf Ihrem Arbeitsgerät.

- 1 Punkt: Erklären Sie ihre Entscheidung

Aufgrund einiger Internetrecherchen entscheide ich mich für die Data Engineering Plattform Apache Flink. (http://de.slideshare.net/sbaltagi/flink-vs-spark, http://stackoverflow.com/questions/28082581/what-is-the-difference-between-apache-spark-and-apache-flink)

- 2 Punkte: Schicken Sie einen Screenshot der installierten Umgebung mit

[Apache Flink](https://github.com/daho/FHTW2016_BLD/blob/master/images/Apache_Flink.png)

- 1 Punkt: Beschreiben Sie Ihre Toolchain, die Sie mit dem Framework nutzen würden (z.B: IDE)

Als IDE würde ich Intellij IDEA inkl. Maven wählen. Zusätzlich muss natürlich Apache Flink vorhanden sein.
Eine genaue Anleitung wie Apache Flink in Intellij IDEA aufgesetzt werden kann findet man unter folgendem Link: http://dataartisans.github.io/flink-training/devSetup/handsOn.html


#Assignment 3: Big Data in Ihrem Umfeld (4 Punkte)
>Schreiben Sie ein simples Program mit dem Framework (z.B. Helloworld) und laden Sie es hoch.
- 2 Punkte für Programm

[Beispielprojekt](https://github.com/daho/FHTW2016_BLD/tree/master/flink-java-project)

[SourceCode](https://github.com/daho/FHTW2016_BLD/blob/master/flink-java-project/src/main/java/org/apache/flink/quickstart/WordCount.java)

[JAR-File](https://github.com/daho/FHTW2016_BLD/blob/master/flink-java-project/target/flink-java-project-0.1.jar)

- 2 Punkte, wenn das Programm auch ausführbar ist.

[JAR-File](https://github.com/daho/FHTW2016_BLD/blob/master/flink-java-project/target/flink-java-project-0.1.jar) auswählen, in Apache Flink hochladen und ausführen.



 
#Data Science
##Assignment 1: Technologien (4 Punkte)
###1.1 (2 Punkte)
>Sie haben in der LVA zwei Frameworks kennengelernt (R und Python). Nennen Sie zwei weitere Technologien, um Daten zu analysieren (müssen nicht open source sein)

[MATLAB](http://de.mathworks.com/products/matlab/?requestedDomain=de.mathworks.com)

[IBM SPSS](https://www-01.ibm.com/software/at/analytics/spss/)


###1.2 (2 Punkte)
Sie bekommen den Auftrag, sich mit einer Data Science Technologie zu arbeiten. Nennen Sie Technologie, die ihnen auf dem ersten Blick am besten für Sie erscheint und begründen Sie das!

Da jede Technologie individuelle Stärken und Schwächen hat, kann man diese Auswahl nicht generell vorab treffen. Die Entscheidung ist sehr von den Anforderungen abhängig und kann daher erst bei der Nennung solcher getroffen werden.


##Assignment 2: Technologien (4 Punkte)
>Entscheiden Sie sich für eine Data Science Plattform. R oder Python. Installieren Sie die auf Ihrem Arbeitsgerät.

* 1. Punkt: Begründen Sie ihre Entscheidung (Warum ziehen Sie persönlich aus ihrer Ausgangssituation die eine Technologie der anderen vor).

Ich habe mich für die Programmiersprache „Python“ entschieden, da ich sowohl persönlich als auch beruflich mit der Entwicklungsumgebung „Intellij IDEA“ zu tu habe. Da man mit dieser Umgebung äußert effektiv arbeiten kann, fiel die Entscheidung leicht. Während des Studiums konnte ich bereits erste Erfahrungen mit „Python“ sammeln, wodurch der Einstieg leichter fällt. Auch die Syntax ist bei Python sehr einfach zu lesen und zu verstehen.

Weitere Punkte siehe folgende Internetseite:
https://www.datacamp.com/community/tutorials/r-or-python-for-data-analysis
 
* 2. Punkte: Schicken Sie einen Screenshot der installierten Umgebung mit

[Apache Flink](https://github.com/daho/FHTW2016_BLD/blob/master/images/Python_Shell.png)

[Apache Flink](https://github.com/daho/FHTW2016_BLD/blob/master/images/Python_IntelliJ.png)



* 1. Punkt: Beschreiben Sie Ihre Toolchain, die Sie mit dem Framework nutzen (z.B. IDE)

Da ich privat und beruflich mit IntelliJ IDEA aarbeite, würde ich auch hierfür darauf zurückgreifen. Durch das Pyhton-Plugin ist es kein Problem ein entsprechendes Projekt zu erstellen. Durch die enormen Möglichkeiten die einem IntelliJ bietet ist das arbeiten sehr effektiv.


#Assignment 3: Big Science (4 Punkte)
>Der Cheatsheet auf http://scikit-learn.org/stable/tutorial/machine_learning_map/ ist eine einfache Anleitung, wie man den richtigen Algorithmus zum richtigen Data Science Problem findet. Schauen Sie in Google nach und lernen Sie classificatiom, regression, clusting und dimensional reduction unterscheiden.
Nennen Sie ein Beispiel aus ihrem Umfeld, wo Sie mit dem Algorithmus zu tun haben. Das kann ein Beispiel sein, wie: Wenn Sie bei Amazon einkaufen. Wenn Sie von einem Marketinginstitut angerufen werden, etc.

__classificatiom__

Teilt die Eingabe mit Hilfe vorher definierten Kategorien in diese unterschiedlichen Kategorien ein. Anwendungsgebiete hierfür sind unter anderem die Mustererkennung, Künstliche Intelligenz und vielen weiteren.

Beispiel: Spam-Filter bei E-Mails


__regression__

Es wird grundsäztlich die gleiche Vorgehensweise wie bei der "Klassifikation" gewählt, jedoch mit dem Unterschied, dass die Eingaben keinen Kategorien zugeteilt werden, sondern versucht wird einen bestimmten Wert hervorzusagen.

Beispiel: Es wird versucht durch bereits bekannte Informationen (Bestellverlauf, Höhe, Datum, ...) das derzeite Budget eines Kunden zu ermitteln.


__clusting__

Dieser Algorithmus ist sehr ähnlich zu "Klassifikation" jedoch sind zuvor keine Kategorien bekannt. Diese werden erst bei Notwendigkeit individuell erzeugt.

BeispieL: "Das könnte sie auch interesseren" bei Amazon.


__dimensional reduction__

Es wird versucht die vorhandenen Daten weiter zu vereinfachen. Dieser Schritt kann vor der "Klassifikaiton" angewandt werden, um danach genauere Ergebnisse zu liefern.

Beispiele: Es werden ähnliche Wörter gesucht und ersetzt.