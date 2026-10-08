# Prompt Master Criades V7.3

Aquesta versió parteix de V7.2 i incorpora les darreres correccions de materials, botons i Ghost Mannequin.

## Canvis principals
- 24 teixits definitius, dividits en 12 de treball i 12 de servei.
- Cada teixit té un prompt material específic: textura, teixit, escala, brillantor, estructura i caiguda realistes.
- A/B/B coordinat només permeten els 12 teixits de treball; C/C amb pitet/D només permeten els 12 de servei.
- Regla general de realisme tèxtil per evitar textures planes, CGI o patrons fora d'escala.
- MASTER A/B/B coordinat: tres botons de vestit de treball d'aproximadament 14 mm, discrets i mai sobredimensionats.
- Ghost Mannequin és autosuficient: elimina identitat, ulleres, cabell, headwear, perfil corporal, postura, activitat i presència humana. No requereix ni ha de demanar cap imatge de referència.
- En Ghost Mannequin es conserva exclusivament la construcció, materials, estat, geometria de l'uniforme i presentació de producte sobre fons blanc.
- El negative prompt és condicional: `white apron` només es prohibeix en B coordinat, no en MASTER B ni en C/C amb pitet.
- Es mantenen la banda obligatòria del pitet B, C amb pitet formal i l'acabat de treball amb encaix discret al coll i mànigues de V7.2.

## GitHub Pages
El ZIP conté `index.html` a l'arrel i el fitxer standalone `prompt_master_criades_v7_3.html`.
