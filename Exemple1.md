**Composition d'une œuvre**

```mermaid
graph TD;


A[crm:E7_Activity] --> |crm:P14_carried_out_by| B[crm:E21_Person<br>'Luigi Nono'<br>bnf:12148/cb138980102]
A[crm:E7_Activity] --> |crm:P2_has_type| C[crm:E55_Type<br>'Composition musicale'<br>aat:300264878]

```


**Date de création d'une œuvre**

```mermaid
graph TD;


A[crm:E7_Activity] --> |crm:P14_carried_out_by| B[crm:E21_Person<br>'Luigi Nono'<br>bnf:12148/cb138980102]
A[crm:E7_Activity] --> |crm:P2_has_type| C[crm:E55_Type<br>'Composition musicale'<br>aat:300264878]

D[crm:E65_creation] --> |crm:P94_has_created| E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| F[crm:E55_Type<br>'Œuvre musicale'<br>aat:300264878]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| G[crm:E7_Activity]
G[crm:E7_Activity] --> |crm:P2_has_type| H[crm:E55_Type<br>'Création Mondiale'<br>aat:300069101]
G[crm:E7_Activity] ---> |crm:P3_took_place_at| I[crm:E53_Place<br>'Église San Lorenzo']


```
**Personnes ayant créées l'œuvre**

```mermaid
graph TD;


crm:E74_Group

```

**Lieu de création d'une œuvre**

```mermaid
graph TD;

D[crm:E65_creation] --> |crm:P94_has_created| E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| F[crm:E55_Type<br>'Œuvre musicale'<br>aat:300264878]
E[crm:E28_Conceptual_Object<br>'Prometeo'<br>rism:850817313] --> |crm:P2_has_type| G[crm:E7_Activity]
G[crm:E7_Activity] --> |crm:P2_has_type| H[crm:E55_Type<br>'Création Mondiale'<br>aat:300069101]
G[crm:E7_Activity] ---> |crm:P3_took_place_at| I[crm:E53_Place<br>'Église San Lorenzo']
I[crm:E53_Place<br>'Église San Lorenzo'] -->|crm:P1_is_identified_by| J(crm:E42_identifier)
J(crm:E42_identifier) --> |crm:P2_has_type| K(crm:E55_type<br>adresse<br>aat:300386983)
J(crm:E42_identifier) --> |crm:P190_has_symbolic_content| L(Campo S. Lorenzo, 5067, 30122 Venezia VE, Italie<br>geonames:3168113)
I[crm:E53_Place<br>'Église San Lorenzo'] --> |crm:P1_is_identified_by| M(crm:E42_identifier)
M(crm:E42_identifier) --> |crm:P2_has_type| N(crm:E55_type<br>coordonnées géographiques<br>aat:300387569)
M(crm:E42_identifier) --> |crm:P168_is_defined_by| O(crm:E94_space_primitive<br>43.60149, 12.94398)


```


```mermaid
graph TD;


A[crm:E7_Activity] --> |crm:P14_carried_out_by| B[crm:E21_Person<br>'Luigi Nono'<br>bnf:12148/cb138980102]
A[crm:E7_Activity] --> |crm:P2_has_type| C[crm:E55_Type<br>'Enseignement'<br>aat:300069743]
A[crm:E7_Activity] --> |crm:P3_took_place_at| D[crm:E53_Place<br>'La maison de Nono à Venise']




```
