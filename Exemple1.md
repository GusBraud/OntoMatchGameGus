**Composition d'une œuvre**

```mermaid
graph TD;

A[crm:E65_Creation] --> |crm:P14_carried_out_by| B[crm:E21_Person<br>'Luigi Nono'<br>bnf:12148/cb138980102]
G[crm:E28_Conceptual_Object] --> |crm:P2_has_type| C[crm:E55_Type<br>'Composition musicale'<br>aat:300264878]
A[crm:E65_Creation] --> |crm:P108_has_produced| D[crm:E71_Human_Made_thing]
D[crm:E71_Human_Made_thing] --> |crm:P2_has_type| E[crm:E55_type<br>'Partition'<br>aat:300026427]
A[crm:E65_Creation] --> |crm:P94_has_created| G[crm:E28_Conceptual_Object]

```



**Date de création d'une œuvre**

```mermaid
graph TD;

D[crm:E65_creation] --> |crm:P94_has_created| E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| F[crm:E55_Type<br>'Œuvre musicale'<br>aat:300264878]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| G[crm:E7_Activity]
G[crm:E7_Activity] --> |crm:P2_has_type| H[crm:E55_Type<br>'Création Mondiale'<br>aat:300069101]
G[crm:E7_Activity] --> |crm:P3_took_place_at| I[crm:E53_Place<br>'Église San Lorenzo']
G[crm:E7_Activity] --> |crm:P4_has_time_span| J[crm:E52_Time_span]
J[crm:E52_Has_time_span] --> |crm:P82a_begin_of_the_begin| K['29 septembre 1984']
J[crm:E52_Has_time_span] --> |crm:P82b_end_of_the_end| K['29 septembre 1984']

```

**Personnes ayant créées l'œuvre**

```mermaid
graph TD;

D[crm:E65_creation] --> |crm:P94_has_created| E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| F[crm:E55_Type<br>'Œuvre musicale'<br>aat:300264878]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| G[crm:E7_Activity]
G[crm:E7_Activity] --> |crm:P2_has_type| H[crm:E55_Type<br>'Création Mondiale'<br>aat:300069101]
G[crm:E7_Activity] --> |crm:P3_took_place_at| I[crm:E53_Place<br>'Église San Lorenzo'<br>geonames:3168113]
G[crm:E7_Activity] --> |crm:P4_has_time_span| J[crm:E52_Has_time_span]
G[crm:E7_Activity] --> |crm:P9_consists_of| K[crm:E7_Activity]
G[crm:E7_Activity] --> |crm:P9_consists_of| Q[crm:E7_Activity]
K[crm:E7_Activity] ---> |crm:P2_has_type| L[crm:E55_Type<br>'Interprétation'<br>aat:300025666]
K[crm:E7_Activity] --> |crm:P14_carried_out_by| M[crm:E74_Group<br>'Chamber Orchestra of Europe']
M[crm:E74_Group<br>Chamber Orchestra of Europe] --> |crm:P2_has_type| N[crm:E55_Type<br>'Ensemble musical'<br>aat:300205024]
K[crm:E7_Activity] --> |crm:P14_carried_out_by| O[crm:E74_Group<br>'Chœur de solistes de l'Institut für Neue Musik an der Musikhoschule Freiburg']
O[crm:E74_Group<br>'Chœur de solistes de l'Institut für Neue Musik an der Musikhoschule Freiburg'] --> |crm:P2_has_type| N[crm:E55_Type<br>'Ensemble musical'<br>aat:300205024]
Q[crm:E7_Activity] --> |crm:P14_carried_out_by| R[crm:E21_Person<br>'André Richard']
Q[crm:E7_Activity] --> |crm:P14_carried_out_by| S[crm:E21_Person<br>'Claudio Abbado']
Q[crm:E7_Activity] --> |crm:P14_carried_out_by| T[crm:E21_Person<br>' Roberto Cecconi']
Q[crm:E7_Activity] ---> |crm:P2_has_type| U[crm:E55_Type<br>'Direction'<br>aat:300025672]

```

**Lieu de création d'une œuvre**

```mermaid
graph TD;

D[crm:E65_creation] --> |crm:P94_has_created| E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| F[crm:E55_Type<br>'Œuvre musicale'<br>aat:300264878]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| G[crm:E7_Activity]
G[crm:E7_Activity] --> |crm:P2_has_type| H[crm:E55_Type<br>'Création Mondiale'<br>aat:300069101]
G[crm:E7_Activity] ---> |crm:P3_took_place_at| I[crm:E53_Place<br>'Église San Lorenzo'<br>geonames:3168113]
G[crm:E7_Activity] --> |crm:P4_has_time_span| J[crm:E52_Has_time_span]
I[crm:E53_Place<br>'Église San Lorenzo'<br>geonames:3168113] -->|crm:P1_is_identified_by| K(crm:E42_Identifier)
K(crm:E42_Identifier) --> |crm:P2_has_type| L(crm:E55_type<br>adresse<br>aat:300386983)
K(crm:E42_Identifier) --> |crm:P190_has_symbolic_content| M(Campo S. Lorenzo, 5067, 30122 Venezia VE, Italie)
I[crm:E53_Place<br>'Église San Lorenzo'<br>geonames:3168113] --> |crm:P1_is_identified_by| N(crm:E42_Identifier)
N(crm:E42_Identifier) --> |crm:P2_has_type| O(crm:E55_Type<br>coordonnées géographiques<br>aat:300387569)
N(crm:E42_Identifier) --> |crm:P168_is_defined_by| P(crm:E94_Space_primitive<br>43.60149, 12.94398)

```

**Vie privée de Luigi Nono**

```mermaid
graph TD;

A[crm:E21_Person<br>'Luigi Nono'<br>bnf:12148/cb138980102] --> |crm:P98_was_born| B[crm:E67_Birth]
B[crm:E67_Birth] --> |crm:P4_has_time_span| C[crm:E52_Time_span]
C[crm:E52_Time_span] --> |crm:P82a_begin_of_the_begin| D['29 janvier 1924']
C[crm:E52_Time_span] --> |crm:P82b_end_of_the_end| D['29 janvier 1924']

A[crm:E21_Person<br>'Luigi Nono'<br>bnf:12148/cb138980102] --> |crm:P100_died_in| E[crm:E69_Death]
E[crm:E69_Death] --> |crm:P4_has_time_span| F[crm:E52_Time_span] 
F[crm:E52_Time_span] --> |crm:P82a_begin_of_the_begin| G['8 mai 1990']
F[crm:E52_Time_span] --> |crm:P82b_end_of_the_end| G['8 mai 1990']

H[crm:E85_joining] --> |crm:P143_joined| A[crm:E21_Person<br>'Luigi Nono'<br>bnf:12148/cb138980102]
H[crm:E85_joining] --> |crm:P143_joined| I[crm:E21_Person<br>'Nuria Nono-Schönberg'<br>bnf:12148/cb123338502]
I[crm:E21_Person<br>'Nuria Nono-Schönberg'<br>bnf:12148/cb123338502] --> |crm:P98_was_born| J[crm:E67_Birth]
J[crm:E67_Birth] --> |crm:P4_has_time_span| K[crm:E52_Time_span] 
K[crm:E52_Time_span] --> |crm:P82a_begin_of_the_begin| L['7 mai 1932']
K[crm:E52_Time_span] --> |crm:P82b_end_of_the_end| L['7 mai 1932']
H[crm:E85_joining] --> |crm:P144_joined_with| M[crm:E74_Group]
M[crm:E74_Group] --> |crm:P2_has_type| N[crm:E55_Type<br>'mariage'<br>aat:300055475]
H[crm:E85_joining] --> |crm:P2_has_type| O[crm:E55_Type<br>'Cérémonie de mariage'<br>aat:300069158]

```

**Enseignement de la composition à Helmut Lachenmann**

```mermaid
graph TD;

A[crm:E7_Activity] --> |crm:P14_carried_out_by| B[crm:E21_Person<br>'Luigi Nono'<br>bnf:12148/cb138980102]
A[crm:E7_Activity] --> |crm:P2_has_type| C[crm:E55_Type<br>'Enseignement'<br>aat:300069743]
A[crm:E7_Activity] --> |crm:P3_took_place_at| D[crm:E53_Place<br>'La maison de Nono à Venise']
A[crm:E7_Activity] --> |crm:P9_consists_of| E[crm:E7_Activity]
E[crm:E7_Activity] --> |crm:P2_has_type| F[crm:E55_Type<br>'Apprentissage'<br>aat:300449145]
E[crm:E7_Activity] --> |crm:P14_carried_out_by| G[crm:E21_Person<br>'Helmut Lachenmann'<br>bnf:12148/cb13896236t]
E[crm:E7_Activity] --> |crm:P4_has_time_span| H[crm:E52_Time_span]
H[crm:E52_Time_span] --> |crm:P82a_begin_of_the_begin| I['1958']
H[crm:E52_Time_span] --> |crm:P82b_end_of_the_end| J['1960']

