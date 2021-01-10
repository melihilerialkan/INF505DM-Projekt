# INF505DM-Projekt



/DEUTSCH/
Die Datei bank_marketing_adal_v1.0.csv sollte dem Dateibereich in der colab-Umgebung hinzugefügt werden. Ausreißer werden in den mit verschiedenen grafischen Methoden analysierten Daten getrennt. Wie wir während der Analyse sehen können, gibt es unbekannte Daten. Die Entscheidungsbaumklassifizierung wurde als Methode zur Schätzung dieser Daten verwendet. Der Typ "Kategorie" und die Methode "cat.codes", die zur Verwendung des Entscheidungsbaums erforderlich sind, wurden auf die gewünschten Daten angewendet. Unbekannte Daten wurden durch NaN ersetzt und alle NaN-Daten wurden mit der Entscheidungsbaum-Klassifizierungsmethode dieser Zeilen ausgefüllt.
Nach der Verarbeitung des neuen Datensatzes haben wir festgestellt, dass die Werte '1' und '0' im Etikett 'Label' ungleich verteilt sind. Wir haben die Anzahl der Proben ausgeglichen, indem wir festgestellt haben, dass dies uns während des Zuges benachteiligen könnte. Um zu viele Ausreißer zu vermeiden, wurden die Ausreißer anschließend wie zuvor mit Hilfe des Visualisierungsprozesses gelöscht. Es wurden nicht viele Ausreißer gefunden, was zeigt, dass die Resample-Methode eine konsistente Probenahme durchführt. Anschließend wurde der als 70% Zug- und 30% Testdaten getrennte Datensatz an den Random Forest Classification-Algorithmus angepasst und die Hyperparameter-Optimierung mithilfe der GridSearch durchgeführt.
Die Punktzahl wurde mit der Kreuzvalidierungsmethode unter Verwendung der besten gefundenen Hyperparameter gemessen.
Ein kleiner Entscheidungsbaum wurde gezeichnet, um die Arbeitslogik des Algorithmus klarer zu verstehen.




/ENGLİSCH/
The bank_marketing_adal_v1.0.csv file should be added to the filespace in the colab environment. Outliers are separated in the data analyzed using different graphical methods. As we can see during the analysis, there is unknown data. Decision tree classification was used as a method for estimating this data. The category type and cat.codes method required to use the decision tree have been applied to the desired data. Unknown data was replaced with NaN and all NaN data was filled in using the decision tree classification method of these rows.
After processing the new data set, we noticed that the values ​​'1' and '0' are unevenly distributed in the label 'Label'. We balanced the number of samples by finding that this could put us at a disadvantage during the move. In order to avoid too many outliers, the outliers were then deleted using the visualization process as before. Not many outliers were found, which shows that the resample method is performing consistent sampling. Then the data set, separated as 70% tensile and 30% test data, was adapted to the random forest classification algorithm and the hyperparameter optimization was carried out using the grid search.
The score was measured by the cross-validation method using the best hyperparameters found.
A small decision tree has been drawn to better understand the logic behind the algorithm.
