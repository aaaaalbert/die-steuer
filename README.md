# Die Steuer
*Illustriert für Menschen wie Dich und mich.*

Schon lange träume ich davon (öööhm????), *die Steuer* als solche den 
existierenden Leitfäden, Berechnungstabellen und HAK-Lehrbüchern zu 
entreißen, und einfach fassbar grafisch darzustellen. Im gegenständlichen 
Repo versuche ich genau das zu verwirklichen --- für den zugegebenermaßen 
sehr kleinen Ausschnitt des Steuerwesens, für den ich mich professionell 
zu interessieren habe.

Anbei also meine grafische Aufbereitung von Bemessungsgrundlage, Sozial- und 
Pensionsversicherungsabgaben sowie Einkommenssteuer. Ich bin keinE 
SteuerberaterIn oder so, und habe keine einschlägige Ausbildung in der Materie, 
lasse weiters unzählige Ausnahmeregelungen unkommentiert unter den Tisch 
fallen, usw. Wenn überhaupt, hat meine Grafik also nur illustrierenden 
Charakter. (Ich hoffe, dass sie trotzdem oder sogar deswegen nützlich ist.)

# Was sieht man da?
Mehrerlei. Zuerst einmal die offensichtlichen Dinge: Damit sich interessante 
Beträge darstellen lassen, verwenden beide Achsen einen logarithmischen Maßstab. 
Die x-Achse gibt als Eingangsgröße das *Einkommen* an. Ich verwende hier auch 
den von der SVA entlehnten Begriff *Bemessungsgrundlage* ("BMGr").

Die verschiedenen eingezeichneten Linien zeigen:
* die Bemessungsgrundlage selbst (dunkelgrau) als Referenz.
* Die Summe von Sozialversicherungs- und Pensionsversicherungsbeiträgen, 
  "Summe SV, PV" in gelb.
* Hellgrau strichliert: BMGr-SV-PV. Diese Linie zeigt, woran die 
  Einkommenssteuer (ESt) bemessen wird, wenn die exakt dem Einkommen 
  entsprechenden SV- und PV-Beiträge in demselben Jahr wie die ESt bezahlt 
  werden. (Das Bezahlen der SV und PV bewirkt Ausgaben, die die ESt mindern.)
* In Grün die zu bezahlende ESt als solche.
* Als Summe aller Abgaben (ESt, SV, PV) die orange gestrichelte Linie.
* Zuguterletzt dunkelblau das, was nach Abzug aller Abgaben überbleibt.

# Also was sieht man da jetzt?
* Die *Summe SV, PV* ist nach unten (Mindestbeiträge) und oben (Höchst-) 
  gedeckelt, siehe die horizontalen gelben Linienanteile links und rechts.
* Anders die *ESt*, die erst ab 11.000 € Einkommen überhaupt anfällt, und für 
  hohe Einkommen gegen 50 % strebt.
* "Weit rechts" ist der Versatz von Summe aller Abgaben zu übrigbleibendem 
  Betrag in absoluten Zahlen der SV-PV-Höchstbeitrag; *relativ* zum Betrag 
  der ESt wird dieser aber immer unbedeutender, sodass auch die Abgabenquote 
  gesamt gegen 50 % strebt.
* Am nächsten zueinander liegen die BMGr und der überbleibende Betrag in der 
  Gegend von zirka 5.000 bis 11.000 € Einkommen. Dort ist also der Bereich der 
  geringsten Abgabenquote.
* Zwischen rund 50.000 und 80.000 € Einkommen übersteigt die Summe aller 
  Abgaben sogar den überbleibenden Betrag. Die Abgabenquote beträgt hier mehr 
  als 50 %.
* Die "Knicke" in der ESt und allen abgeleiteten Größen entstehen soweit ich 
  das sehe durch unterschiedliche Grenzbeträge zwischen SVA (65.100 € 
  Höchstbeitrag jährlich) und Finanzamt (60.000 € ist der Schwellenwert zum 
  höchsten ESt-Tarif).


# Wohin weiter?
Vielleicht bastel ich einmal eine "interaktive" Version der Grafik, mit 
JavaScript und Sachen, damit man Beträge genauer ablesen kann usw. 


# Datenquellen

Finanzministerium und SVA der GW:
* http://svagw.at/portal27/portal/svaportal/content/contentWindow?contentid=10007.740777&action=2&viewmode=content
* http://svagw.at/portal27/portal/svaportal/content/contentWindow?contentid=10007.713971&action=2&viewmode=content
* http://svagw.at/portal27/portal/svaportal/content/contentWindow?contentid=10007.740775&action=2&viewmode=content
* https://www.bmf.gv.at/steuern/selbststaendige-unternehmer/einkommensteuer/est-steuertarif.html
