# Anker-Solarbank-12-Automations

Nulleinspeisung mit SB e1600 Gen2 (inkl. Schalter) und SB 2 pro

Beide Solarbanken sind als <b>eigene Systeme bei Anker</b> eingetragen

Verwendete Entitäten:

SB1:<br/>
sensor.solarbank_e1600_ladestand<br/>
sensor.solarbank_e1600_einspeisevorgabe<br/>
switch.solarbank_e1600_entladeprioritat<br/>
number.solarbank_e1600_system_einspeisevorgabe<br/>
switch.solarbank_e1600_erlaube_leistungsabgabe<br/>

SB2 pro: <br/>
sensor.sb_2_e1600_pro_ladestand<br/>
sensor.sb_2_e1600_pro_einspeisevorgabe<br/>
number.sb_2_e1600_pro_system_einspeisevorgabe<br/>
sensor.wohnzimmer_akku_shelly_leistung   <- Abgabe der SB2 kann aber auch mit der dem  sensor.sb_2_e1600_pro_?leistung/einspeisung? ersetzt werden
<br/>sensor.online_gemessener_verbrauch_sw <- am Zähler gemessener Verbrauch vom Netz
