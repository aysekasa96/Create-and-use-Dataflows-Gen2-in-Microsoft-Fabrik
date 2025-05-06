# Microsoft Fabric – Dataflows (Gen2) Lab

Deze repository bevat het resultaat van een hands-on lab waarin Dataflows (Gen2) in Microsoft Fabric worden gebruikt om data te extraheren, transformeren en laden (ETL) naar een Lakehouse.

## Overzicht

In dit project heb ik de volgende stappen uitgevoerd:

1. **Workspace aangemaakt**  
   Een nieuwe Fabric-werkruimte opgezet met Fabric-capaciteit (proefversie).

2. **Lakehouse aangemaakt**  
   Een lege Lakehouse gecreëerd als opslagplaats voor de gegevens.

3. **Dataflow (Gen2) gemaakt**  
   - Een CSV-bestand (`orders.csv`) ingeladen via een anonieme verbinding.
   - Transformaties uitgevoerd in Power Query, waaronder het toevoegen van een kolom `MonthNo` op basis van de `OrderDate`.
   - Gegevens geladen naar een nieuwe `orders`-tabel in het Lakehouse.

4. **Pipeline geconfigureerd**  
   - Een Data Pipeline aangemaakt.
   - De Dataflow toegevoegd als een activiteit binnen de pipeline.
   - De pipeline uitgevoerd om het laadproces te automatiseren.

## Gegevensbron

De gegevens zijn afkomstig uit de publieke dataset:  
`https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/orders.csv`

## Resultaat

Na succesvolle uitvoering is de `orders`-tabel beschikbaar in het Lakehouse en klaar voor verdere analyse of gebruik in Power BI-rapporten.



# Create-and-use-Dataflows-Gen2-in-Microsoft-Fabrik
