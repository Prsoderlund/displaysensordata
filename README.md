# displaysensordata
Rapberrypi-IoT hub-Datastream-Powerbi


Raspberrypi -
  connection string

varför?
Använde virtual rapberrypi + connection string för att connecta till min iot hub då det 
gav mig ett bra och lätt sätt att testa hur azure fungera

Azure- iot hub
  device - rasppi - connection string

varför?
Använde azure iot hub för att etablera säker och tillförlitlig kommunikation mellan din IoT-tillämpning och de enheter som den hanterar
vilket i detta fall blir den virtual raspberrypi som jag använde.

VsCode- Iot Hub
  monitor built-in event endpoints in json

varför?
använde detta för att jag kunde se att data skickades när jag körde run på den virtual rapberypi men jag kunde inte se vad det var för data
så med monitor built-in event endpoints in json så kunde jag enkelt se live vad för data som skickades från rapberrypi till iot hub.



Azure- stream analytics job Datastream
  Skapa input - (raspberrypi) 
  Skapa output - (powerbi) connecta till workspace manuellt
    skapa dataset, skapa table
    
varför?
Azure Stream Analytics möjliggör realtidsanalys av strömmade data. Det är användbart om du behöver agera omedelbart
på data som genereras från virtual Raspberry Pi, till exempel övervaka sensorer eller händelser i realtid.
Azure Stream Analytics ger en molnbaserad plattform för att enkelt konfigurera och skala ditt strömanalysjobb.
Genom att använda Azure Stream Analytics och Datastream för att strömma data till Power BI kan du skapa kraftfulla realtidsdashboards och visualiseringar.

Power BI
  Skapa workspace
  skapa rapport
    ta data från mitt datasest i min table
    visualiera datan

varför?
Valde Power bi för en simpel visualisering av data från virtual raspberrypi
