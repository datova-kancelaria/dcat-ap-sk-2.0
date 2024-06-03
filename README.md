:warning: Tento repozitár bol uzavretý. Štandard DCAT-AP-SK je súčasťou Centrálneho modelu údajov, dostupný tu: https://github.com/slovak-egov/centralny-model-udajov/tree/main/tbox/national/dcat-ap-sk 

# Rozhranie katalógu otvorených dát DCAT-AP-SK 2.0.1
Metadátový štandard založený na [Data Catalog Vocabulary (DCAT) - Version 2][DCAT2] a jeho aplikačnom profile [DCAT-AP 2.1.1][DCAT-AP-2.1.1] pre popis datasetov a pre rozhranie Národného (NKOD) a lokálných katalógov otvorených dát (LKOD).

[Zobrazenie štandardu][PREVIEW]

[DCAT2]: https://www.w3.org/TR/vocab-dcat-2/ "Data Catalog Vocabulary (DCAT) - Version 2"
[DCAT-AP-2.1.1]: https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/211 "DCAT Application Profile for data portals in Europe (DCAT-AP) 2.1.1"
[PREVIEW]: https://htmlpreview.github.io/?https://github.com/datova-kancelaria/dcat-ap-sk-2.0/blob/main/index.html

Vygenerovanie HTML z BS súboru

	
curl https://api.csswg.org/bikeshed/ -F file=@index.bs -F force=1 > index.html