# Business intelligence

Datawarehouse:
- dient om historische data bij te houden.
- dient om analyse uitvoeren op deze data.

ELT:
- zorgt ervoor dat alle files die in de datawarehouse terecht komen uniform zijn.
- zorgt ervoor dat de datawarehouse proper blijft.

## Datawarehouse
## Inmon
- Subject Oriented
  - Helpt om data te analyseren.
- Integrated
  - Consistent formaat
- Nonvolatile
  - Eenmaal ze in de warehouse zit verandert de data niet meer.
- Time Variant

### Sterschema
#### Fact table
- foreing keys
- measures

#### Dimensions
- surrogaat key (vaak autonumber key)
- tekstuele informatie

### Sneewvlok schema
- Quasi identiek aan sterschema
- Dimensions normaliseren

### Performantie
Een sterschema is performanter dan sneeuwvlok schema.
Er moeten minder joins uitgevoerd worden.
