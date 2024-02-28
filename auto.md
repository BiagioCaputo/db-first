Traccia:
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Colonne|Tipo|Attributi
--|--|--
id|bigint|PRIMARY_KEY, AUTO_INCREMENT
brand| VARCHAR(20)| NOTNULL
model| VARCHAR(50)| NOTNULL
seller| VARCHAR(30)| NOTNULL
seller_location| VARCHAR(30)|NOTNULL
seller_phone| VARCHAR| NOTNULL
seller_email| VARCHAR(50)| NOTNULL
km_travelled| MEDIUMINT | NOTNULL
registration_date| DATE| NOTNULL
fuel_type| VARCHAR(30)| NOTNULL
shift_type| VARCHAR(20) | NOTNULL
body_style| VARCHAR(30) | NULL
carbon_emissions| TINYINT| NOTNULL
passengers_capacity|TINYINT| NOTNULL
car_doors| TINYINT| NULL
cilinders| TINYINT| NULL
displacement| SMALLINT|NULL
weight_kg| SMALLINT| NULL
consume|FLOAT(4,2)|NULL
color|VARCHAR(50)|NOTNULL
paint_type|VARCHAR(50)|NOTNULL
interns_color|VARCHAR(50)|NULL
price|MEDIUMINT|NOTNULL
description|TEXT|NULL
optionals|TEXT|NULL


