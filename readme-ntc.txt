Die Vorgehensweise ist wie folgt:
Man sucht sich in Tabelle den gewünschten Temperaturschaltpunkt 
und den entsprechenden Spannungswert heraus. 

Beispiel: Schaltpunkt soll bei 20°C liegen,
dann ergibt sich eine Spannung von 2,74 V an dem Sensor. 
Mit dem Trimmer P1 wird nun die gleiche Spannung an Pin2 von IC1A eingestellt. 
Die Toleranz durch den NTC und die verwendeten Widerstände schätzen wir auf ±1°K (Kelvin).

Da es sich beim dem Temperaturschalter um eine invertierenden Schmitt-Trigger handelt, 
wird der Mitkoppelwiderstand auf den Knotenpunkt von  R1 und RT1 zurückgeführt. 
Dadurch verändert sich die Hysterese leicht in Abhängigkeit der Temperatur. 

0°C   -> Hysterese  = 1°K
25°C ->  Hysterese  = 0,7°K
50° C ->  Hysterese = 1°K
