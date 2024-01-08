# java-data-output-stream
Repo for studying data output stream in java

- a. Studieren Sie die Codebeispiele aus dem Input O13_IP_Datenströme für die Klassen DataInputStream und DataOutputStream. Werfen Sie auch einen Blick in die JavaDoc. 
- b.) Verwenden Sie einen Byte-Datenstrom und schreiben Sie mit Hilfe von DataOutputStream einen einfachen int-Wert in eine Datei. Öffnen Sie die Datei mit einem Editor und schauen Sie sich den Inhalt an. Wiederholen Sie das Ganze für einen String. Verwenden Sie ruhig auch ein paar Sonderzeichen! 
- c.) Lesen Sie den Inhalt der Datei von b) mit Hilfe von DataInputStream wieder ein. Was passiert, wenn Sie versuchen die Integer als einen anderen Typ einzulesen (z.B. byte oder float)? 
- d.) Sie können verschiedenste Typen in beliebiger Reihenfolge in einen Byte-Datenstrom (und somit auch in eine Datei) schreiben. Was aber gewährleistet sein muss ist, dass der Empfänger beim Einlesen der Daten die Typen in exakt derselben Reihenfolge einliest. Probieren Sie es aus! 
- e.) Sie können auch dynamische Binärformate entwerfen: Nehmen Sie dazu das Programm der letzten Woche (Eingabe von Temperaturwerten von der Konsole) als Basis. Nach Abschluss der Eingabe schreiben Sie alle Werte in eine Binärdatei. Die Idee dabei: Schreiben Sie als erstes die Anzahl der Werte als int, und danach die entsprechenden Temperaturwerte (double oder float) der Reihe nach in die Datei! 
- f.) Lesen Sie die Daten von e) nun auch wieder ein. Zuerst kommt also die Anzahl der Werte als int-Wert, und danach können Sie mit einer Iteration die dynamische Anzahl von Temperaturwerten einlesen. Klappt es? Sie haben soeben Ihr erstes eigenes Binärformat implementiert
