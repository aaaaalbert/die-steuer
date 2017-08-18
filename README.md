# Die Steuer

*Illustriert für Menschen wie Dich und mich.*

(Version 2016, no less!)

Schon lange träume ich davon (öööhm????), *die Steuer als solche* den 
existierenden Leitfäden, Berechnungstabellen und HAK-Lehrbüchern zu 
entreißen, und einfach fassbar grafisch darzustellen. Im gegenständlichen 
Repo versuche ich genau das zu verwirklichen --- für den zugegebenermaßen 
sehr kleinen Ausschnitt des Steuerwesens, für den ich mich professionell 
zu interessieren habe.

Anbei also meine grafische Aufbereitung von Bemessungsgrundlage, Unfall-, 
Kranken- und Pensionsversicherungsabgaben, Pensionsvorsorge, sowie 
Einkommenssteuer. Ich bin keinE SteuerberaterIn oder so, und habe keine 
einschlägige Ausbildung in der Materie, lasse weiters unzählige 
Ausnahmeregelungen kommentarlos unter den Tisch fallen, usw. Wenn überhaupt, 
hat meine Grafik also nur illustrierenden Charakter. (Ich hoffe, dass sie 
trotzdem oder sogar deswegen nützlich ist.)


# Was sieht man da?

Mehrerlei. Zuerst einmal die offensichtlichen Dinge: Damit sich interessante 
Beträge darstellen lassen, verwenden beide Achsen einen logarithmischen 
Maßstab. 
Die x-Achse gibt als Eingangsgröße das *Einkommen* an. Ich verwende hier auch 
den von der SVA entlehnten Begriff *Bemessungsgrundlage* ("BMGr").

Die verschiedenen eingezeichneten Linien zeigen:

* Die Bemessungsgrundlage selbst (dunkelgrau) als Referenz.
* Die Summe aller Abgaben an die Pensionsvorsorgekasse und die SVA (das sind 
  mithin Kranken-, Unfall- und Pensionsversicherungs- sowie -vorsorgebeiträge), 
  etwas unscharf bezeichnet als "Summe SVA" in Gelb.
* Hellgrau strichliert: BMGr-SVA. Diese Linie zeigt, woran die 
  Einkommenssteuer (ESt) bemessen wird, wenn die exakt dem Einkommen 
  entsprechenden "SVA"-Beiträge in demselben Jahr wie die ESt bezahlt 
  werden. (Das Bezahlen der SVA bewirkt Ausgaben, die die ESt mindern.)
* In Magenta die BMGr-SVA abzüglich des ESt-Freibetrags. Die ESt wird 
  von diesem Bezugswert berechnet. Der Faktor für diese Berechnung steigt 
  grob gesagt mit dem Einkommen.
* In Grün die zu bezahlende ESt.
* Als Summe aller Abgaben (ESt, SVA) die orange gestrichelte Linie.
* Zuguterletzt dunkelblau das, was nach Abzug aller Abgaben überbleibt.


# Also was sieht man da jetzt?

* Die *Summe SVA* ist nach unten (Mindestbeiträge) und oben (Höchst-) 
  gedeckelt, siehe die horizontalen gelben Linienanteile links und rechts.
* Anders die *ESt*, die erst ab 11.000 € BMGr-SVA-Freibetrag überhaupt 
  anfällt, und für hohe Einkommen gegen 50% (bzw. seit 2016 für Einkommen
  jenseits einer Million gegen 55 %) strebt.
* So nett der Freibetrag für "niedrige" Einkommen auch ist, indem er 
  verhindert, dass diese ESt zahlen müssen: Je mehr Geld hereinkommt, 
  umso näher bei 1 liegt das Verhältnis von BMGr-SVA und BMGr-SVA-Freibetrag.
* "Weit rechts" ist der Versatz von Summe aller Abgaben zu übrigbleibendem 
  Betrag in absoluten Zahlen der SVA- und Pensionsvorsorgekassen-Höchstbeitrag;
  *relativ* zum Betrag der ESt wird dieser aber immer unbedeutender, sodass 
  auch die Abgabenquote gesamt gegen 50 % (bzw. 55 %) strebt:
  "Summe Abgaben ist ungefähr gleich dem überbleibenden Betrag".
* Am nächsten zueinander liegen die BMGr und der überbleibende Betrag in der 
  Gegend von zirka 5.000 (knapp über dem unteren Deckel der SVA) bis 20.000 € 
  Einkommen (wo die ESt einsetzt, weil BMGr-SVA-Freibetrag groß genug wird). 
  Dort ist also der Bereich der geringsten Abgabenquote mit rund 29 %, was 
  ungefähr der Summe der KV- (7,65 %), UF- (111,96 €), PVers- (18,5 %) und 
  PVors-Beträge (1,53 %) entspricht.


# Wie lese ich ab, was mich interessiert?

Typischer Anwendungsfall: Ich kenne mein Einkommen und will meine 
SV-Beiträge sowie Einkommenssteuer ermitteln.
Suche dazu das Einkommen auf der x-Achse, lies dann die gesuchten Beträge ab.

Beispiel: Einkommen 70.000 €, ESt rund 13.000 €, SVA knapp unter 20.000 €; 
übrig bleiben mehr als 70.000 €.

Auch "Umkehrlösungen" sind denkbar, à la "Ich habe schon SVA bezahlt, was 
bleibt an ESt zu stemmen?". In solchen Fällen arbeite über den *Restbetrag* 
nach SVA-Zahlung auf der *y-Achse*, und ermittle den Schnittpunkt mit 
BMGr-SVA, der grau gestrichelten Linie. Die *x-Koordinate* entspricht jetzt 
dem Einkommen vor der SVA-Zahlung, und die ESt liest sich ab wie zuvor.

Beispiel: Nach SVA bleiben mir 40.000 €. Von y nach x auf der BMGr-SVA 
finde ich ein zugrundeliegendes Einkommen von ca. 60.000 €, und also eine 
ESt von etwas unter 10.000 €.

(Caveat emptor, die unteren SVA/ESt-Grenzbeträge erfordern möglicherweise 
die Verwendung der anderen BMGr-Linie. Ich hab das jetzt nicht vollständig 
durchgedacht.)


# Änderungen seit 2015

Die Steuertarife wurden für 2016 angepasst, u.a. gibt es jetzt mehr
"Stufen" und einen höheren Spitzensteuersatz (wie erwähnt 55 % ab 1e6 €).
Im Vergleich zu den Sätzen von 2015, die vorher abgebildet waren,
ergeben sich folgende Änderungen:

* Die Mindest- und Höchstwerte der Summe SVA (gelb) sind leicht gestiegen.
* Die EST der BMGr-SVA-Freibetrag ist leicht gesunken, wodurch im
  Bereich 20.000-70.000 € mehr "überbleibt" (in dunkelblau).
  Hurra, die Entlastung!!!
* Entsprechend ist auch der Buckel der (rot gestrichelten) Summe ESt, SVA
  im Bereich ab 20.000 € flacher geworden.


# Wohin weiter?

Vielleicht bastel ich einmal eine "interaktive" Version der Grafik, mit 
JavaScript und Sachen, damit man Beträge genauer ablesen kann usw. 


# Datenquellen

Finanzministerium, SVA der GW, Help.gv.at:
* https://www.svagw.at/portal27/svaportal/content?contentid=10007.740780&viewmode=content
* http://esv-sva.sozvers.at/portal27/svaportal/content/contentWindow?viewmode=content&contentid=10007.740779
* https://www.bmf.gv.at/steuern/selbststaendige-unternehmer/einkommensteuer/est-steuertarif.html
* https://www.help.gv.at/Portal.Node/hlpd/public/content/214/62875.html

